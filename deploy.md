## [Деплой приложения на Django](#Деплой_приложения_на_Django)
- [Начало работы с Linux](#Начало_работы_с_Linux)
- [Доступ к серверу по SSH ключу](#Доступ_к_серверу_по_SSH_ключу)
- [Ошибки](#Ошибки)



<a name="Деплой_приложения_на_Django"></a>
# Деплой приложения на Django
https://github.com/s6ptember/for-deploy-guide/tree/main  
https://youtu.be/MORz2S5Bm0A?si=s93OfhzuoILLfmI3

### Структура проекта
**site dir**:
- .env
- requirements.txt
- nginx.conf
- Dockerfile
- compose.yml

**.env**:
```
DJANGO_SECRET_KEY=django-insecure-abc123

DB_NAME=my_db
DB_USER=postgres
DB_PASSWORD=123
DB_HOST=db
DB_PORT=5432
```

**requirements**:
```
asgiref==3.11.1
Django==6.0.6
django-debug-toolbar==6.3.0
gevent==24.11.1
gunicorn==26.2.0
pillow==12.2.0
psycopg2-binary==2.9.12
python-dotenv==1.2.3
sqlparse==0.5.5
tzdata==2026.2
```

**settings.py** (изменённая часть):
```
import os
from os import environ
from dotenv import load_dotenv

SECRET_KEY = environ.get('DJANGO_SECRET_KEY')
DEBUG = False

ALLOWED_HOSTS = ["MY_SITE.ru", "www.MY_SITE.ru"]

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': environ.get('DB_NAME'),
        'USER': environ.get('DB_USER'),
        'PASSWORD': environ.get('DB_PASSWORD'),
        'HOST': environ.get('DB_HOST'),
        'PORT': environ.get('DB_PORT'),

    }
}

LANGUAGE_CODE = 'ru-RU'

MEDIA_URL = '/media/'
MEDIA_ROOT = BASE_DIR / 'media'
STATIC_URL = 'static/'
STATIC_ROOT = os.path.join(BASE_DIR, 'static/')

# можно добавить if not DEBUG
SECURE_PROXY_SSL_HEADER = ('HTTP_X_FORWARDED_PROTO', 'https')
SECURE_SSL_REDIRECT = True
SESSION_COOKIE_SECURE = True
CSRF_COOKIE_SECURE = True

CSRF_TRUSTED_ORIGINS = ["MY_SITE.ru", "www.MY_SITE.ru"]
```

**compose.yml**:  
_в fsite было **ports** вместо **expose**_
```
services:
  fsite:
    build: .
    restart: always
    expose:
      - "8000"
    env_file:
      - .env
    networks:
      - db_net
    volumes:
      - .:/app
      - static:/app/static
      - media:/app/media
    environment:
      - TZ=Europe/Moscow
    depends_on:
      - db

  db:
    image: postgres:17-alpine
    restart: always
    environment:
      - POSTGRES_DB=${DB_NAME}
      - POSTGRES_USER=${DB_USER}
      - POSTGRES_PASSWORD=${DB_PASSWORD}
    volumes:
      - postgres_data:/var/lib/postgresql/data/
    networks:
      - db_net

  nginx:
    image: nginx:latest
    restart: always
    ports:
      - "80:80"
      - "443:443"
    volumes:
      - ./nginx.conf:/etc/nginx/nginx.conf
      - /etc/letsencrypt/:/etc/letsencrypt/
      - static:/app/static
      - media:/app/media
    depends_on:
      - fsite
    environment:
      - TZ=Europe/Moscow
    networks:
      - db_net

networks:
  db_net:
    driver: bridge

volumes:
  postgres_data:
  static:
  media:
```

**Dockerfile**:
```
FROM python:3.12-slim
# RUN groupadd -r groupdjango && useradd -r -g groupdjango userdjango
# RUN useradd -m -r -u 1000 userdjango

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

RUN pip install --upgrade pip
# USER userdjango
WORKDIR /app
# RUN chmod -R 755 /app/www/django_site
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

CMD ["sh", "-c", "gunicorn furniture.wsgi:application --bind 0.0.0.0:8000"]

# USER userdjango
# RUN chown -R userdjango:userdjango /app/www/django_site
```

**nginx first.conf** (для получения сертификата):
```
events {}

http {
    server {
        listen 80;
        server_name MY_SITE.ru www.MY_SITE.ru;

        location / {
            proxy_pass http://web:8000;
            proxy_set_header Host $host;
            proxy_set_header X-Real-IP $remote_addr;
            proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
            proxy_set_header X-Forwarded-Proto $scheme;
        }

        location /static/ {
            alias /app/static/;
        }

        location /media/ {
            alias /app/media/;
        }
    }
}
```
**nginx.conf**:
```
events {}

http {
    include /etc/nginx/mime.types;
    server_tokens off;
    client_max_body_size 10M;

    upstream f_site_ups {
        server fsite:8000;
    }

    server {
        listen 80;
        server_name MY_SITE.ru www.MY_SITE.ru;
        return 301 https://$host$request_uri;
    }

    server {
        listen 443 ssl;
        server_name MY_SITE.ru www.MY_SITE.ru;

        ssl_certificate /etc/letsencrypt/live/MY_SITE.ru/fullchain.pem;
        ssl_certificate_key /etc/letsencrypt/live/MY_SITE.ru/privkey.pem;

        location /admin/ {
            allow 1.2.3.4;
            allow 5.6.7.8;
            deny all;

            proxy_pass http://f_site_ups;
            proxy_set_header Host $host;
            proxy_set_header X-Real-IP $remote_addr;
            proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
            proxy_set_header X-Forwarded-Proto $scheme;
        }

        location / {
            proxy_pass http://f_site_ups;
            proxy_set_header Host $host;
            proxy_set_header X-Real-IP $remote_addr;
            proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
            proxy_set_header X-Forwarded-Proto $scheme;
        }

        location /static/ {
            alias /app/static/;
        }

        location /media/ {
            alias /app/media/;
        }
    }
}
```
`location /admin/ {...}` - доступ к админке с определённых IP


SSL должны выдаваться по-новой, можно проверить службу:  
`sudo systemctl status certbot.timer`


<a name="Начало_работы_с_Linux"></a>
## Начало работы с Linux
### Установка Docker, Nginx, Cerbot
```
sudo apt-get update
sudo apt-get install ca-certificates curl

sudo install -m 0755 -d /etc/apt/keyrings
sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
sudo chmod a+r /etc/apt/keyrings/docker.asc
echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu $(. /etc/os-release && echo "$VERSION_CODENAME") stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update

sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

sudo usermod -aG docker $USER
newgrp docker

sudo curl -L "https://github.com/docker/compose/releases/download/v2.24.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose

sudo apt update
sudo apt install nginx certbot python3-certbot-nginx
```

### SSL-сертификат
Далее поставить **первую конфигурацию** nginx.conf и получить SSL-сертификаты:  
```
sudo certbot --nginx -d MY_SITE.ru -d www.MY_SITE.ru

docker-compose stop nginx
sudo systemctl stop nginx
```
Установить второй конфиг nginx

### Деплой проекта
Запуск в фоне:  
`docker-compose up --build -d`

`docker-compose exec web python manage.py collectstatic --noinput`  
`docker-compose exec web python manage.py createsuperuser`

Для **остановки** контейнера _ctrl+C_ или `docker compose down`

Проверить **логи** и далее отслеживать их в реальном времени:  
`docker compose logs -f --tail 500` (_последние 500 строк_)


<a name="Доступ_к_серверу_по_SSH_ключу"></a>
## Доступ к серверу по SSH ключу
`ssh-keygen` можно ничего не заполнять  
Ключи сохраняться в `/root/.ssh/` (приватник id_ed25519 и публичный id_ed25519.pub)

Включить доступ по ключу: `ssh-copy-id root@1.2.3.4` (_пользователь@ip_сервера_)

Чтобы **отключить вход по логину и паролю**:  
в `/etc/ssh/sshd_config` и `/etc/ssh/sshd_config.d/50-cloud-init.conf` меняется:  
`PasswordAuthentication no`


## Ограниченный доступ к админке по IP
**МОЖЕТ НЕ РАБОТАТЬ** с CloudFlame
```
location /admin-url/ { 
    allow 1.2.3.4;
    allow 5.6.7.8;
    deny all;
    ...
    }
```


<a name="Ошибки"></a>
## Ошибки
1. Переход по ссылкам `MY_SITE.ru/catalog` (без слеша в конце) выдаёт страницу 404.
В функции представления со страницой 404 необходимо явно указать **status=404**, 
иначе джанго может посчитать, что корректно будет вернуть шаблон not_found.html с кодом 200
```
def page_not_found(request, exception):
    return render(request, 'main_app/not_found.html', status=404)
```