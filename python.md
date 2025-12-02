# Python
### [Основы ](#Основы)
<details>
<summary>...</summary>

- [**Работа с текстом**](#Работа_с_текстом)
  - [Методы строк](#Методы_строк)
  - [Поиск в строке find](#Поиск_в_строке_find)
  - [Разделение текста split](#Разделение_текста_split)
  - [Соединение строк join](#Соединение_строк_join)
  - [Дополнительные пробелы rjust и ljust](#Дополнительные_пробелы_rjust_и_ljust)
  - [Форматирование](#Форматирование)
  - [Цветной текст в консоли](#Цветной_текст_в_консоли)
  - [Регулярные выражения re](#Регулярные_выражения_re)
- [Арифметические и логические операции](#Арифметические_и_логические_операции)
- [Пример с шифрованием](#Пример_с_шифрованием)
- [Цикл for с двумя элементами, функция zip](#Цикл_for_с_двумя_элементами_функция_zip)
- [Аргументы в функции](#Аргументы_в_функции)
- [Функция как параметр функции](#Функция_как_параметр_функции)
- [Функция как результат функции](#Функция_как_результат_функции)
- [lambda](#lambda)
- [Область видимости переменных. Global и nonlocal](#Область_видимости_переменных_Global_и_nonlocal)
- [Декораторы](#Декораторы)
- [Проверка типа объекта isinstance](#Проверка_типа_объекта_isinstance)
- [Requirements.txt](#Requirements)
- [assert](#assert)
- [Обработка ошибок и исключения](#Обработка_ошибок_и_исключения)
- [Списки list](#Списки_list)
- [Кортежи tuple](#Кортежи_tuple)
- [Словари dict](#Словари_dict)
- [Множества set](#Множества_set)
- [List comprehension. Получение определённых элементов из списка](#List_comprehension)
- [Упаковка и распаковка](#Упаковка_и_распаковка)
- [Модули](#Модули)
- [Randome](#Randome)
- [Math](#Math)
- [locale](#locale)
- [decimal. Округление](#decimal)
- [dataclass. Сокращение шаблонов классов](#dataclass)
- [match](#match)
- [Контекстные менеджеры](#Контекстные_менеджеры)
- [Метаклассы](#Метаклассы)
- ☐ [**Работа с файлами**](#Работа_с_файлами)
  - [Открытие и закрытие файлов](#Открытие_и_закрытие_файлов)
  - [Запись в текстовый файл](#Запись_в_текстовый_файл)
  - [Чтение файла](#Чтение_файла)
  - [Кодировка](#Кодировка)
  - [Чтение и запись w+](#Чтение_и_запись_w)
  - [**CSV**](#CSV)
    - [Запись](#CSV_Запись)
    - [Чтение файла](#CSV_Чтение_файла)
    - [Запись словаря](#CSV_Запись_словаря)
    - [Чтение словаря](#CSV_Чтение_словаря)
  - [Бинарные файлы](#Бинарные_файлы)
  - [pickle. Запись информации в бинарный файл .dat](#pickle)
  - [shelve. Хранение данных в файле по типу словаря](#shelve)
  - [Json](#Json)
- ☐ [**OS**](#OS)
  - [Создание и удаление папки](#Создание_и_удаление_папки)
  - [Запуск и закрытие приложений](#Запуск_закрытие_приложений)
  - [Просмотр списка файлов в папки](#Просмотр_списка_файлов_в_папки)
- ☐ [**Работа с zip файлами. zipfile**](#Работа_с_zip_файлами_zipfile)
  - [Запись файлов в zip архив](#Запись_файлов_в_zip_архив)
  - [Получение информации о файлах в архиве](#Получение_информации_о_файлах_в_архиве)
  - [Извлечение файлов из архива](#Извлечение_файлов_из_архива)
- ☐ [**datetime**](#datetime)
  - [Преобразование строки в дату. strptime](#Преобразование_строки_в_дату_strptime)
  - [Форматирование даты и времени](#Форматирование_даты_и_времени)
  - [Операции со временем. timedelta](#Операции_со_временем_timedelta)
- [multiprocessing Pool](#multiprocessing_Pool)
- [Итераторы и генераторы](#Итераторы_и_генераторы)
- [Тесты doctest](#Тесты_doctest)
- [Логирование logging](#Логирование_logging)
- [Логирование при multiprocessing, свой уровень логирования](#Логирование_при_multiprocessing_свой_уровень_логирования_logging)
</details>

### [ООП ](#ООП)
<details>
<summary>...</summary>

- [Конструктор](#Конструктор)
- [Деструктор](#Деструктор)
- [Приватные атрибуты](#Приватные_атрибуты)
- [Аннотации свойств. Геттеры и сеттеры](#Аннотации_свойств_Геттеры_и_сеттеры)
- [Наследование](#Наследование)
- [Переопределение методов](#Переопределение_методов)
- [Статические методы](#Статические_методы)
- [Строковое представление объекта](#Строковое_представление_объекта)
- [Перегрузка операторов](#Перегрузка_операторов)
- [Абстрактные классы](#Абстрактные_классы)
- [Методы классов](#Методы_классов)
</details>

### [NumPy ](#NumPy)
<details>
<summary>...</summary>

- [Создание массива](#np_Создание_массива)
- [Удаление элементов из массива](#np_Удаление_элементов_из_массива) 
- [Представление массивов](#np_Представление_массивов) 
- [Объединение / разделение массивов](#np_Объединение_разделение_массивов) 
- [Срезы массивов](#np_Срезы_массивов) 
- [Математические операции над массивами](#np_Математические_операции_над_массивами) 
- [Генерация случайных чисел](#np_Генерация_случайных_чисел) 
- [Матричное умножение](#np_Матричное_умножение)
</details>

### [Pandas ](#Pandas)
<details>
<summary>...</summary>

- [read / to](#Pandas_read_to)
- [Общая информация](#Pandas_Общая_информация)
- [Создание графиков](#Pandas_Создание_графиков)
</details>

### [matplotlib ](#matplotlib)
<details>
<summary>...</summary>

- [Отображение графика](#matplotlib_Отображение_графика)
- [Разделение_окна_вывод_нескольких_графиков](#matplotlib_Разделение_окна_вывод_нескольких_графиков)
- [Изменение осей](#matplotlib_Изменение_осей)
- [Фигуры, разные типы графиков](#matplotlib_Фигуры_разные_типы_графиков)
- [Трехмерные графики](#matplotlib_Трехмерные_графики)
- [Анимация графиков](#matplotlib_Анимация_графиков)
</details>

### [Многопоточность и тд](#Многопоточность)
<details>
<summary>...</summary>

- [Многопоточность](#Многопоточность)
- [multiprocessing](#multiprocessing)
- [Asyncio](#Asyncio)
</details>

---
### [Другое ](#Другое)
- [Работа с почтой (imaplib, smtplib)](#Работа_с_почтой_(imaplib_smtplib))
- [Определение кодировки chardet](#Определение_кодировки_chardet)
- [Jinja2](#Jinja2)
- [Dadata](#Dadata)

### [Базы Данных](#Базы_Данных)
- [**SQLite**](#SQLite)
- [**MS SQL Server**](#MS_SQL_Server)
- [**PostgreSQL**](#PostgreSQL)
  <details>
  <summary>...</summary>

  - [Последовательности SEQUENCE](#PostgreSQL_Последовательности_SEQUENCE)
  - [DISTINCT, ORDER BY, LIMIT, OFFSET](#PostgreSQL_DISTINCT_ORDER_BY_LIMIT_OFFSET)
  - [Перечисления enum](#PostgreSQL_Перечисления_enum)
  - [JOIN](#PostgreSQL_JOIN)
  - [UNION, EXCEPT, INTERSECT](#PostgreSQL_UNION_EXCEPT_INTERSECT)
  - [Оконные функции (OVER)](#PostgreSQL_Оконные_функции)
  - [Пример в python (psycopg2)](#PostgreSQL_пример_psycopg2)
  - [Оптимизация, INDEX](#PostgreSQL_Оптимизация_INDEX)
  - [Удалённое подключение к БД](#PostgreSQL_Удалённое_подключение_к_БД)
  - [Ошибки](#PostgreSQL_Ошибки)
  </details>

### [SQLAlchemy ](#SQLAlchemy)
<details>
<summary>...</summary>

- [Cинхронные / асинхронные запросы](#SQLAlchemy_синхронные_асинхронные_запросы)
- [Создание таблиц](#SQLAlchemy_Создание_таблиц)
- [Insert](#SQLAlchemy_Insert)
- [Работа с сессиями](#SQLAlchemy_Работа_с_сессиями)
- [insert in ORM](#SQLAlchemy_insert_in_ORM)
- [Создание таблиц через классы](#SQLAlchemy_Создание_таблиц_через_классы)
- [Select / Update](#SQLAlchemy_select_update)
- [Тип полей](#SQLAlchemy_Тип_полей)
- [func](#SQLAlchemy_func)
- [Select / Update через ORM](#SQLAlchemy_select_update_через_ORM)
- [JOIN OVER WITH](#SQLAlchemy_JOIN_OVER_WITH)
- [Relationship](#SQLAlchemy_Relationship)
- [Вывод информации о моделях в консоль](#SQLAlchemy_Вывод_информации_о_моделях_в_консоль)
- [LIMIT](#SQLAlchemy_LIMIT)
- [INDEX CHECK](#SQLAlchemy_INDEX_CHECK)
- [Конвертация моделей в pydantic](#SQLAlchemy_Конвертация_моделей_в_pydantic)
- [Связь Many to Many](#SQLAlchemy_Связь_Many_to_Many)
</details>

### [PyQt ](#PyQt)
### [PySide ](#PySide)

[//]: # (### [HTML]&#40;#HTML&#41;)
[//]: # (### [CSS]&#40;#CSS&#41;)

### [Django ](#Django)
<details>
<summary>...</summary>

- [Установка Django](#Django_Установка_Django)
- [Представления](#Django_Представления)
- [Конверторы](#Django_Конверторы)
- [Отладка проекта](#Django_Отладка_проекта)
- [Page not found 404](#Django_Page_not_found)
- [redirect](#Django_redirect)
- [Шаблоны](#Django_Шаблоны)
- [Включение других элементов страницы include](#Django_Включение_других_элементов_страницы_include)
- [Подключение статических файлов](#Django_Подключение_статических_файлов)
- [Пользовательские теги шаблонов](#Django_Пользовательские_теги_шаблонов)
- [БД](#Django_БД)
- [get_absolute_url](#Django_get_absolute_url)
- [Пользовательский менеджер модели](#Django_Пользовательский_менеджер_модели)
- [Связи моделей](#Django_Связи_моделей)
- [Класс Q](#Django_Класс_Q)
- [Класс F](#Django_Класс_F)
- [Добавление новых временных полей](#Django_Добавление_новых_временных_полей)
- [Агрегирующие функции](#Django_Агрегирующие_функции)
- [GROUP BY](#Django_GROUP_BY)
- [Django Debug Toolbar](#Django_Django_Debug_Toolbar)
- [Оптимизация запросов](#Django_Оптимизация_запросов)
- [Админ панель](#Django_Админ_панель)
- [Метод save в models](#Django_Метод_save_в_models_py)
- [forms](#Django_forms)
- [Загрузка файла на сервер](#Django_Загрузка_файла_на_сервер)
- [Отображение картинок на сайте](#Django_Отображение_картинок_на_сайте)
- [Class Based Views (CBV). Классы View и TemplateView](#Django_Class_Based_Views)
- [ListView](#Django_ListView)
- [DetailView](#Django_DetailView)
- [FormView](#Django_FormView)
- [CreateView](#Django_CreateView)
- [UpdateView](#Django_UpdateView)
- [DeleteView](#Django_DeleteView)
- [Mixins](#Django_Mixins)
- [Авторизация](#Django_Авторизация)
- [Шаблонные контекстные процессоры](#Django_Шаблонные_контекстные_процессоры)
- [LoginView, AuthenticationForm, LogoutView](#Django_LoginView_AuthenticationForm_LogoutView)
- [Login Required](#Django_Login_Required)
- [Регистрация пользователя](#Django_Регистрация_пользователя)
- [UserCreationForm](#Django_UserCreationForm)
- [Авторизация через email](#Django_Авторизация_через_email)
- [Профиль пользователя](#Django_Профиль_пользователя)
- [PasswordChangeView](#Django_PasswordChangeView)
- [Почтовый сервис](#Django_Почтовый_сервис)
- [Восстановление пароля](#Django_Восстановление_пароля)
- [AbstractUser](#Django_AbstractUser)
- [Permissions Groups](#Django_Permissions_Groups)
- [Логирование](#Django_Логирование)
- [Обработка ошибок](#Django_Обработка_ошибок)
</details>

### [Selenium ](#Selenium)
<details>
<summary>...</summary>

- [Запуск страницы в браузере](#Запуск_страницы_в_браузере)
- [Изменение user agent](#Изменение_user_agent)
- [Поиск элемента](#Поиск_элемента)
- [Ввод данных в input](#Ввод_данных_в_input)
- [cookies](#Selenium_cookies)
- [Фоновый режим](#Фоновый_режим)
- [Перемещение между вкладками](#Перемещение_между_вкладками)
- [Добавление скриптов JS](#Добавление_скриптов)
- [Получение содержимого страницы](#Selenium_Получение_содержимого_страницы)
- [Перемещение к элементу ActionChains](#ActionChains)
</details>

### [OpenCV ](#OpenCV)
- [Поиск изображений](#Поиск_изображений)

### [Beautifulsoup ](#Beautifulsoup)
<details>
<summary>...</summary>

- [Получение данных о странице](#Beautifulsoup_Получение_данных_о_странице)
- [Сохранение страницы](#Сохранение_страницы)
- [Поиск элемента на странице](#Поиск_элемента_на_странице)
- [Парстинг атрибутов](#Парстинг_атрибутов)
- [Поиск элемента в тексте](#Поиск_элемента_в_тексте)
- [Антибот система](#Антибот_система)
</details>


### [Telegram](#Telegram)
<details>
<summary>...</summary>

- [pyTelegramBotAPI](#pyTelegramBotAPI)
- [asyncio](#asyncio)
- [pyrogram](#pyrogram)
</details>

### [WhatsApp](#WhatsApp)

### [Other ](#Other)
- [Практика](#Other_Практика)
- [Парсинг](#Other_Парсинг)
- [UserWarning](#Other_UserWarning)

### [Exe](#Exe_файл)
### [Git ](#Git)
### [Установка программы на сервер](#Установка_программы_на_сервер)


<a name="Основы"></a>
# Основы

<a name="Работа_с_текстом"></a>
### Работа с текстом

#### Многострочный текст
```
text = '''qwe
asd
123
'''
print(text) # qwe/n asd/n 123

text = ("qwe"
        "asd")
print(text)  # qweasd
```
#### Получение подстроки
```
    text = 'https://forum.com'
    print(text[:2])     # ht
    print(text[2:7])    # tps:/
    print(text[2:10:2]) # ts/f
```
#### Приведение к одному регистру
```
    text = 'Asd1'
    print(text.lower()) # asd1
    print(text.upper()) # ASD1
```
#### ord
Для получения значения из таблицы Unicode: `print(ord('a')) # 97`
#### Поиск в строке
```
    text = 'Asd1'
    s = 'd' in text
    print(s) # True
```
<a name="Методы_строк"></a>
### Методы строк
- **isalpha()** - возвращает True, если строка состоит из алфавитных символов
- **islower()** - возвращает True, если строка состоит из символов нижнего регистра
- **isupper()** - возвращает True, если строка состоит из символов верхнего регистра
- **isdigit()** - возвращает True, если строка состоит из цифр
- **isnumeric()** - возвращает True, если строка представляет из себя число
- **startswith(str)** - возвращает True, если строка начинается с подстроки str
- **endswith()** - возвращает True, если строка кончается на подстроку str
- **lower()** - переводит строку в нижний регистр
- **upper()** - переводит строку в верхний регистр
- **title()** - первые символы в словах переводятся в верхний регистр
- **capitalize()** - переводит в верхний регистр первую букву первого слова строки
- **lstrip()** - удаляет начальные пробелы из строки
- **rstrip()** - удаляет конечные пробелсы из строки
- **strip()** - удаляет начальные и конечные пробелы из строки
- **ljust(width)** - если длина строки меньшн width, то справа добавляются пробелы и строка выравнимается по левому краю
- **rjust(width)** - если длина строки меньшн width, то слева добавляются пробелы и строка выравнимается по правому краю
- **center(width)** - если длина строки меньшн width, то слева и справа добавляются пробелы и строка выравнимается по центру
- **find(str, start, end)** - возвращает индекс подстроки в строке, иначе возвращает -1
- **replace(old, new, num)** - заменяет в строке одну подстроку на другую
- **split(c, num)** - разбивает строку на подстроки
- **partition(c)** - разбивает строку на 3 части: начало, c, конец
- **join(str)** - объединяет строки, вставляя между ними разделитель

### Удаление пробелов strip
Можно указать символы, которые будут удалены вместе с пробелами:
```
s = '   1 a   2 '.lstrip('1 ')
 print('|' + s + '|')  # |a   2 |
```
<a name="Замена_символа_replace"></a>
### Замена символа replace
Замена всех символов / Замена определённого числа символов 
```
    text = 'https://forum.com'
    print(text.replace('/', '='))       # https:==forum.com
    print(text.replace('/', '=', 1))    # https:=/forum.com
```
Для удобства можно записывать так:<br>
`text.replace(',', '').replace('.', '').replace('\n', '')`<br>

Строки в Python являются неизменяемым типом данных (нельзя написать string[1] = 'a').<br>
Для замены символа можно преобразовать строку в список:
```
    x = "qwe"
    x_tmp = list(x)
    x_tmp[1] = 'o'
    x = ''.join(x_tmp)
```
<a name="Поиск_в_строке_find"></a>
### Поиск в строке find
**find(str)** - поиск str во всей строке
**find(str, start)** - поиск str начиная с индекса start
**find(str, start, end)** -  поиск str с индекса start до end
```
    text = 'https://forum.com'
    print(text.find('for'))     # 8
    print(text.find('for', 9))  # -1
```
Для эффективного поиска можно использовать алгоритм **Кнута-Морриса-Пратта**
<a name="Разделение_текста_split"></a>
### Разделение текста split
split() без агрументов делит строку по пробелам<br>
split(c, num) num указывает кол-во вхождений
```
text = "https://forum.vimeworld.com/staff/"
stext = text.split("/")
print(stext[len(stext)-2])
```
<a name="Соединение_строк_join"></a>
### Соединение строк join
```
    text = 'https://','forum.com'
    print(''.join(text)) # https://forum.com
    
    a = ["https:", "ref.com", "staff", "page_1"]
    print('//'.join(a[0:2]) + '/' + '/'.join(a[2:])) # https://ref.com/staff/page_1
```
<a name="Дополнительные_пробелы_rjust_и_ljust"></a>
### Дополнительные пробелы rjust и ljust
**rjust**, **ljust** - для выравнивания по правому/левому краю и добавления пробелов
```
    print('Administrator:'.rjust(14), name1)    # Administrator: Thomas
    print('User:'.rjust(14), name2)             #          User: Ray
```
### Ссылки
`path = r"C:\python\n..."`

**r** для корректной работы ссылки (избегание ситуаций с \n, \t...) 

#### end
end задаёт последний символ строки, (по умолчанию end = \n)
```
    print("test", end = " ")
    print("123")
    #test 123 (всё на одной строчке)
```
### sep
sep указывает знак-разделитель
`print('Count', x, sep='-') # Count-12`

<a name="Форматирование"></a>
### Форматирование
Вставка переменных в строку:
```
    file = "main.py"
    path = r'C:\new_project' + "\\"
    print(f"Full path: {path}{file}")
```
Именованные параметры, параметры по позиции:
```
    ref = 'https://forum.com'
    description = 'Форум'
    
    print('{description}: {ref}'.format(description=description, ref=ref))
    
    print('{0}: {1}'.format(description, ref))
```
Можно применять плейсхолдеры:
- s - для записи строки
- d - целое число
- f - число с плавающей точкой (через точку указывается кол-во знаков дробной части)
- % - умножает знак на 100 и добавляет знак процента
- e - для эеспоненциальной записи

Строку с плейсхолдером можно записать в переменную:
```
    print_url = "Url: {:s}"
    ref = 'https://forum.com'
    print(print_url.format(ref))    # Url: https://forum.com
```
Для чисел можно указать знак разделения:<br>
`print('{0:,d}'.format(1000))    # 1,000`<br>

Для дробных чисел можно указать кол-во знаков после запятой:<br>
`print('{:.2f}'.format(1000.1234))    # 1000.12`<br>

**Выравнивание**<br>
Установка минимальной ширины:<br>
```
    print('{:10.2f}'.format(10.123))    #      10.12
    print('{:10.2f}'.format(5555))      #    5555.00
```
Или с помощью специальных символов: **<**, **>** и **^** - выравнивание по левому,
правому краю и центру соответственно. Знак **.** - задаёт точную длинну строки.
```
    print(f'{ref:<20} - {description}') # https://forum.com    - Форум
    print(f'{ref:>20} - {description}') #    https://forum.com - Форум
    print(f'{ref:^20} - {description}') #   https://forum.com   - Форум
    print(f'{ref:.10} - {description}') # https://fo - Форум
```

Проценты:<br>
`print('{:.2%}'.format(.10123))    # 10.12%`<br>

Форматирование без метода format (f), можно использовать все плейсхолдеры, кроме %
```
    ref = 'https://forum.com'
    print('Url: %s' % (ref))
```

<a name="Цветной_текст_в_консоли"></a>
### Цветной текст в консоли
**Цвета**

| Цвет | Текст | Фон |
|------|-------|-----|
| Чёрный    | 30    | 40  |
| Красный    | 31    | 41  |
| Зелёный    | 32    | 42  |
| Жёлтый    | 33    | 43  |
| Синий    | 34    | 44  |
| Фиолетовый    | 35    | 45  |
| Бирюзовый    | 36    | 46  |
| Белый    | 37    | 47  |

**Эффекты**

| Код | Значение |
|-----|-------|
| 0   | Сброс к начальным значениям |
| 1   | Жирный    |
| 2   | Блёклый    |
| 3   | Курсив    |
| 4   | Подчёркнутый    |
| 5   | Редкое мигание    |
| 6   | Частое мигание    |
| 7   | Смена цвета фона с цветом текста    |

```
import ctypes
kernel32 = ctypes.windll.kernel32
kernel32.SetConsoleMode(kernel32.GetStdHandle(-11), 7)

Blood_Red = lambda x: f"\033[1;31m{x}\033[0m"
print(f"{Blood_Red('INFO')} some text")
```

<a name="Регулярные_выражения_re"></a>
### Регулярные выражения re
`import re`

**re.match** - поиск совпадения в начале строки. Если строка начинается иначе, то res = None
```
    res = re.match("Text", "Text abc Text")
    print(res) # <re.Match object; span=(0, 4), match='Text'>
    if res:
        print(res.group()) # Text
        print(res.start(), res.end()) # 0 4
```
**re.search** - аналог mach, но ищет не только в начале строки<br>
**re.findall** - ищет совпадения во всей строке
```
    res = re.findall("Text", "123 Text abc Text")
    print(res) # ['Text', 'Text']
```
**re.split** - разделяет строку по заданному шаблону, можно указать максимальное кол-во делений
`print(re.split('/', "site.com/staff/page_11", maxsplit=1)) # ['site.com', 'staff/page_11']`<br>

**re.sub** - заменяет элементы в строке, может принимать функцию во второй аргумент,<br>
в фигурных скобках можно указать диапозон повторений символа 'a{1,3}'
```
def change(c):
    if c.group(0) == '//': return "="
    else: return "_"

print(re.sub('/{1,2}', change, "https//site.com/staff/page_11")) # https=site.com_staff_page_11

print(re.sub('[sS]', "-", "asdASD")) # a-dA-D
```

**re.compile** - ипользование регулярного вырежения как отдельный объект
```
    pattern = re.compile("ge\w+")
    print(pattern.findall("general ge range gate")) # ['general']
```
**Спец. символы**:
- **.** - один любой символ, кроме \n
- **?** - 0 или 1 вхождение шаблона слева
- **+** - 1 и более вхождений шаблона слева
- \* - 0 и более вхождений шаблона слева
- \w - любая цифра или буква (\W - всё, кроме цифры или буквы)
- \d - любая цифра (\D - всё, кроме цифры)
- \s - любой пробельный символ (\S - любой НЕпробельный символ)
- \b - граница слова
- [..] - один из символов в скобках ([^..] - любой символ, кроме тех, что в скобках).
- \\ - экранирование символов (**\\.** или **\\+**)
- ^ и $ - начало и конец строки соответственно
- {n,m} - от n до m вхождений
- a|b - соответствует шаблону a или b
- () - группирует выражения и возвращает найденный текст
- \\t, \\n, \\r - тубуляция, новая строка, возврат коретки

Для выборки всех букв англ. алфавита: [a-z] / [A-Z] / [a-zA-Z]  
Для ру.: [а-я] / [А-Я], **буквы ё / Ё нужно прописывать дополнительно**

**Примеры**<br>
Первое и последнее слово:
```
    a = "https forum vimeworld.com staff"
    print(re.findall('^\w+', a), re.findall('\w+$', a)) # ['https'] ['staff']
```
Получить домены из строки с почтами
```
    a = "alex@gmail.com, ray@yandex.ru, qwe12@mail.ru"
    print(re.findall(r'(@\w+.\w+)', a)) # ['@gmail.com', '@yandex.ru', '@mail.ru']
```
Получение данных нужного формата из строки
```
    a = "adfiuhdfius14:372812.11.2007asda01:00asd12308.05.2024213dsa"
    print(re.findall(r'\d{2}:\d{2}|\d{2}.\d{2}.\d{4}', a)) # ['14:37', '12.11.2007', '01:00', '08.05.2024']
```
Поиск слов по начальным символам (1.., 3.., bc1..)
```
    a = "0x1234 bc1q8d xoifh 3oiah bcajs82 1sdfio"
    print(re.findall(r'\b[13]\w+|\bbc1\w+', a)) # ['bc1q8d', '3oiah', '1sdfio']
```


### Тернарные операторы
`print("x -", 'чётное' if x % 2 == 0 else 'нечётное')`

<a name="Range"></a>
### Range
range генерирует цифровую последовательность<br>

`range(5) # 0 ... 4`<br>
`range(2,5) # 2 ... 4`<br>
`range(2, 6, 2) # 2, 4` С приращением 2

Пример с убывающей последовательностью:<br>
`print(*range(5, 0, -1)) # 5 4 3 2 1`

Создание списка<br>
`L1 = list(range(5)) # [0, 1, 2, 3, 4]`

<a name="Арифметические_и_логические_операции"></a>
#### Арифметические и логические операции
Целочисленное деление: 9 **//** 2 = 4<br>
Степень: 2 ** 3 = 8

Для вычисления простых операций в 

#### Логические операции
& - умножение<br>
| - сложение<br>
^ - исключающее или<br>
~ - инверсия, аналогично -(x+1)<br>
Пример с обменом значений
```
    a = 12
    b = 321
    a = a ^ b
    b = a ^ b
    a = a ^ b
```

<a name="Пример_с_шифрованием"></a>
### Пример с шифрованием
```
    x = 98
    key = 52
    encrypt = x ^ key
    print(f"Зашифрованное число: {encrypt}") # 86
    decrypt = encrypt ^ key
    print(f"Изначальное значение: {decrypt}") # 98
    # 98 1100010
    # 52 0110100
    # 86 1010110
```

#### Cрез массива
```
    numbers = [1,2,3,4,5]
    for i in numbers[2:4]:
        print(i) #3, 4
```
Присваивание срезу массива:
```
    m = [1, 2, 3, 4]
    m[1:3] = [9, 8, 7]
    print(m)    # [1, 9, 8, 7, 4]
    
    m[1:4:2] = [10, 20]
    print(m)  # [1, 10, 8, 20, 4]
    
    m[1:3] = []
    print(m)  # [1, 20, 4]
```

<a name="Операторы"></a>
#### Операторы
**or, and, in (+ not)<br>**
Особенности оператора **and**:<br>
`a > 11 and "d"`<br>
если первое выражение верно, то выведется значение второго<br>
Оператор **in** проверяет, есть ли в наборе значений искомое<br>
```
    a = "abc def"
    b = 'c'
    print(b in a) # True
    
    a = [1, 2, 3, 4, 12.2, 1.1]
    b = 12.20
    print(b not in a) # False
```    

<a name="Цикл_for_с_двумя_элементами_функция_zip"></a>
### Цикл for с двумя элементами, функция zip
```
    for x, y in (10, 2), (4, 7), (0, 4):
        print(x, y)
```
Zip
```    
    a = [1, 2, 3, 4]
    b = [0, 9, 8, 7, 6, 5]
    for i, j in zip(a, b):
        print(i, j)
        # 1 0 
        # ... 
        # 4 7
```
Цикл отработает столько раз, сколько элементов в кратчайшем массиве<br>
**Zip** сопостовляет итерируемые объекты (обрезает по кратчайшему)
```
    x0 = [1, 2, 3, 4]
    x1 = [9, 8, 7, 6, 5]
    x2 = 'asdf'

    res = zip(x0, x1, x2)
    print(list(res)) # [(1, 9, 'a'), (2, 8, 's'), (3, 7, 'd'), (4, 6, 'f')]

    res = zip(x0, x1, x2)
    l0, l1, l2 = zip(*res)
    print(l0, l1, l2) # (1, 2, 3, 4) (9, 8, 7, 6) ('a', 's', 'd', 'f')
```

<a name="Аргументы_в_функции"></a>
### Аргументы в функции
Аргумент x по умолчанию<br>
`def f(y, x=1):`<br>
Параметры по умолчанию должны быть в конце<br>

К агрументам справа от * можно обращаться только по имени<br>
`def f(y = 1, *, x = 2):`<br>
`f(2, x = 3)`

Аргументы до знака / являются позиционными
`def f(number, /, *, count):`<br>

Неопределённое кол-во аргументов<br>
```
def f(*m, x):
    res = 0
    for i in m:
        res += i
    return res * x

print(f(2, 1, 4, x=2))
```

<a name="Функция_как_параметр_функции"></a>
### Функция как параметр функции
```
def fix_ref(ref, operation):
    return operation(ref)

def clear_ref(ref):
    ref = re.split('/', ref)
    if len(ref) > 1 and ref[0] == 'https:':
        return ref[2]
    else:
        print('Error ref')
def change_slash(ref):
    return (re.sub('/{1,2}', '_', ref))

def main():
    print(fix_ref("https://forum.vimeworld.com/staff/", change_slash))
    print(fix_ref("https://forum.vimeworld.com/staff/", clear_ref))
```

<a name="Функция_как_результат_функции"></a>
### Функция как результат функции
Переменная operation хранит функцию
```
def set_operation(c):
    if c == '*':
        return milt
    elif c == '+':
        return sum
    return

def milt(a, b): return a * b
def sum(a, b): return a + b

def main():
    operation = set_operation("+")
    print(operation(2, 3))
    operation = set_operation("*")
    print(operation(2, 3))
```
#### Документация к функции
```
def sort_ins():
    """Сортировка"""
    pass
   
def main():
    print(sort_ins.__doc__)
```
Функциям можно добавлять описание, далее его вызывать. Также описание выводится при наведении курсора на функцию.

<a name="lambda"></a>
### lambda
Небольшие анонимные функции. До знака **:** утснавливаются параметры, после - return.
```
    change_slash = lambda ref: re.sub('/{1,2}','_',ref)
    print(change_slash('site.com/staff/page_11'))
```

#### Преобразования
**int()**, **float()**, **str()**

<a name="Область_видимости_переменных_Global_и_nonlocal"></a>
### Область видимости переменных. Global и nonlocal
Изменение глобальный переменной. В первой функции создаётся новая локальная переменная x
```
x = 1
def test1():
    x = 2
    print(x)
    
def test2():
    global x
    x = 3
    print(x)
    
def main():
    test1() #  2
    print(x) # 1
    test2() #  3
    print(x) # 3
```
Выражение **nonlocal** прикрепляет идентификатор к переменной из ближайшего окружающего контекста<br>
(за исключением глобального контекста)
```
def test():
    x = 2
    def print_x():
        nonlocal x
        x = 1
        print(x)

    print_x() #1
    print(x) #1
```

<a name="Декораторы"></a>
### Декораторы
Декораторы позволяют модифицировать выполняемую функцию. В качестве параметра передаётся функция и в качестве результата возвращается функция.
```
def check(f):
    def check_m(*args):
        if args[1] > 0:
            try:
                result = f(*args)
                return result
            except:
                print("Некорректный массив")
        else:
            print("Множитель меньше нуля")
        return 0
    return check_m

@check
def double_m(m, x):
        i = 0
        while i < len(m):
            j = 0
            while j < len(m[i]):
                m[i][j] *= x
                j += 1
            i += 1
        return m
def main():
    m = [[1,2],[3,4,5]]
    print(double_m(m, 3)) # [[3, 6], [9, 12, 15]]
```
#### pass
Данный оператор ничего не делает (служит "заглушкой").
```
    if 1 == True:
        pass
```
<a name="Проверка_типа_объекта_isinstance"></a>
### Проверка типа объекта isinstance
Возвращает True или False
```
    x = '123'
    if isinstance(x, str):
        print('string')
```
ещё способ:
```
    u = Unit()
    print(type(u) == Unit) # True
```

<a name="Requirements"></a>
### Список пакетов в проекте (requirements.txt)
Просмотр пакетов: `pip freeze`  
Cоздать список пакетов в поректе: `pip freeze > requirements.txt`  
install: ``

<a name="Обработка_ошибок_и_исключения"></a>
### Обработка ошибок и исключения
```
    try:
        print(3/0)
    except:
        print('error')
    finally:
        print('finally')
```

Необязательный блок finally вызывается вне зависимости, было ли сгенерировано исключение.<br>
Как правило, блок finally нужен для освобождения ресурсов, закрытия файлов и т.д.<br>

```
    try:
        pass
    except Exception as ex:
        print(ex)
    else:
        print('ok')
```
В данном случае блок else выполнится, если ошибок сгенерировано не будет.

---
**Встроенные типы исключений**<br>
Базовые:<br>
- **BaseException**: базовый тип для всех встроенных исключений<br>
- **Exception**: базовый тип, который обычно применяется для создания своих типов исключений<br>
- **ArithmeticError**: базовый тип для исключений, связанных с арифметическими операциями (OverflowError, ZeroDivisionError, FloatingPointError).<br>
- **BufferError**: тип исключения, которое возникает при невозможности выполнить операцию с буффером<br>
- **LookupError**: базовый тип для исключений, которое возникают при обращении в коллекциях по некорректному ключу или индексу (например, IndexError, KeyError)<br>

От этих классов наследуются все конкретные типы исключений. Ниже приведены наиболее часто встечающиеся:<br>
- **IndexError**: если индекс при обращении к элементу коллекции находится вне допустимого диапазона<br>
- **KeyError**: если в словаре отсутствует ключ, по которому происходит обращение к элементу словаря.<br>
- **OverflowError**: если результат арифметической операции не может быть представлен текущим числовым типом (обычно типом float).<br>
- **RecursionError**: если превышена допустимая глубина рекурсии.<br>
- **TypeError**: если операция или функция применяется к значению недопустимого типа.<br>
- **ValueError**: если операция или функция получают объект корректного типа с некорректным значением.<br>
- **ZeroDivisionError**: при делении на ноль.<br>
- **NotImplementedError**: тип исключения для указания, что какие-то методы класса не реализованы<br>
- **ModuleNotFoundError**: при невозможности найти модуль при его импорте директивой import<br>
- **OSError**: тип исключений, которые генерируются при возникновении ошибок системы (например, невозможно найти файл, память диска заполнена и т.д.)<br>
---
С помощью **as** можно передать информацию для исключения.<br>
Для обработки несольких исключений в одном блоке используется: `except (ZeroDivisionError, ValueError):`
```
    try:
        x1 = int(input('Input first number:'))
        x2 = int(input('Input second number:'))
        print('Division =', x1 / x2)
    except ZeroDivisionError:
        print('Error: Zero division')
    except ValueError:
        print('Error: Incorrect value')
    except BaseException as e:
        print('Error:', e)
    finally:
        print('finally')
```
**Кастомные исключения**<br>
Для этого используется оператор **raise**, ему можно передать сообщение.
```
    try:
        x1 = int(input('Input first number:'))
        x2 = int(input('Input second number:'))
        if x1 > 999 or x2 > 999:
            raise Exception("Too big number")
        print('Division =', x1 / x2)
    except Exception as e:
        print('Error:', e)
```
**Создание типов исключений**<br>
```
class UrlAdressException(Exception):
    def __init__(self, address):
        self.address = address

    def __str__(self):
        return f"Incorrect url: {self.address}"

class Url:
    def __init__(self, address, description):
        if '.' not in address or re.search('[^\.\w/:-_=&?]', address):
            raise UrlAdressException(address)
        self.address = address
        self.description = description

    def __str__(self):
        return f'{self.address}, {self.description}'

def main():
    try:
        Url_1 = Url("https://forum1###.com", "Форум")
        print(Url_1)
    except BaseException as e:
        print("Error:", e)
```

<a name="assert"></a>
### assert
Если условие в assert неверно, то вызовется исключение AssertionError
```
  def f(n):
      assert n > 0, 'Error: n <= 0'
      return n * 2
```

```
    try:
        print(f(-12))
    except AssertionError as ex:
        print('Assert:')
        print(ex)
    except Exception as ex:
        print(ex)
```

<a name="Списки_list"></a>
### Списки (list)
Повторяющиеся элементы списка<br>
`L1 = [1] * 3`<br>
Конструктор списка может принимать другие списки<br>
`L2 = list(L1)`<br>
Можно обращаться к списку с конца<br>
`print(L1[-1]) # последний элемент`<br>
Можно разложить список<br>
`x1, x2, x3 = L1`<br>
Часть списка<br>
```
    L1 = [1, 2, 3, 4, 5, 6 ,7]
    print(L1[:2])       # [1, 2]
    print(L1[3:5])      # [4, 5]
    print(L1[1:5:2])    # [2, 4] шаг 2
    print(L1[-4:-1])    # [4, 5, 6]
```
**Методы по работе со списками:** <br>
- **append(item)**: добавляет элемент item в конец списка
- **insert(index, item)**: добавляет элемент item в список по индексу index
- **extend(items)**: добавляет набор элементов items в конец списка
- **remove(item)**: удаляет элемент item. Удаляется только первое вхождение элемента. Если элемент не найден, генерирует исключение ValueError
- **clear()**: удаление всех элементов из списка
- **index(item)**: возвращает индекс элемента item. Если элемент не найден, генерирует исключение ValueError
- **pop([index])**: удаляет и возвращает элемент по индексу index. Если индекс не передан, то просто удаляет последний элемент
- **count(item)**: возвращает количество вхождений элемента item в список
- **sort([key])**: сортирует элементы. По умолчанию сортирует по возрастанию. Но с помощью параметра key мы можем передать функцию сортировки
- **reverse()**: расставляет все элементы в списке в обратном порядке
- **copy()**: копирует список<br>

**Функции по работе со списками:** <br>
- **len(list)**: возвращает длину списка
- **sorted(list, [key])**: возвращает отсортированный список
- **sum(list)**: возвращает сумму элементов
- **min(list)**: возвращает наименьший элемент списка
- **max(list)**: возвращает наибольший элемент списка
- **del**: удаляет элемент(ы) по индексу

**Проверка наличия элемента**<br>
```
    L1 = [1, 2, 3, 4, 5, 6 ,7]
    if 3 in L1:
        L1.remove(3)
```
**Удаление элементов по индексу (del)** <br>
```
    L1 = [1,2,3,4,5]
    del L1[2]
    print(L1)   # [1, 2, 4, 5]
    del L1[2:]
    print(L1)   # [1, 2]
```
**Изменение подсписка**<br>
Длинна подсписка и списка могут быть разными.<br>
```
    L1 = [1, 2, 3, 4, 5, 6 ,7]
    L1[1:4] = [0, 9]    # [1, 0, 9, 5, 6, 7]
```
**Подсчёт вхождений**<br>
```
L1 = [1, 2, 3, 4, 3, 6 ,7]
    print(L1.count(3))  # 2
```
**Сортировка**<br>
В обычной сортировке (**sort**) заглавные символы меньше строчных
```
    L1 = ['Ray', 'bob', 'Alex']
    L1.sort()   # ['Alex', 'Ray', 'bob']
```
Для сортировки без учета регистра используется **key=str.lower** 
```
    L1 = ['Ray', 'bob', 'Alex']
    L1.sort(key=str.lower)   # ['Alex', 'bob', 'Ray']
```
Кроме sort существует функция **sorted**, она не изменяет сортируемый список, а создаёт новый для сортировки<br>
**sorted(list)** - сортирует список<br>
**sorted(list, key)** - сортирует список, применяя к элементам функцию **key**

**Фильтрация списка**<br>
Функция **filter** содержит условие, которое проверяет каждый элемент, если значение True, то элемент добавляется в список 
```
def sort_url(u):
    return u.description
def main():
    L1 = [Url("https://forum.com", "Форум"), Url("http://site.ru"), Url('https://FinViz.com', "Финансы")]
    L2 = filter(sort_url, L1)
    for i in L2:
        print(i)
```

**Проекция/преобразование списка**<br>
В функцию **map** передается 2 параметра: функция преобразования и список<br>
```
def GetDomen(u):
    u = re.split('/', u.address)[2]
    return u
def main():
    L1 = [Url("https://forum.com/discuss12/page3", "Форум"), Url("https://site.ru/stuff"), Url('https://FinViz.com/sp500', "Финансы")]
    L2 = map(GetDomen, L1)
```
**Копирование списков**<br>
При поверхностном копировании оба списка будут указывать на один и тот же список, во избежании этого, необходимо использовать глубокое копирование (**copy**)
```
    L1 = [1, 2, 3, 4]
    L2 = L1
    L1.pop()
    print(L1)   # [1, 2, 3]
    print(L2)   # [1, 2, 3]

    L1 = [1, 2, 3, 4]
    L2 = L1.copy()
    L1.pop()
    print(L1)   # [1, 2, 3]
    print(L2)   # [1, 2, 3, 4]
```

**Двумерные списки**<br>
Пример взаимодействия:
```
    L1 = [["https://forum.com/discuss12/page3", "Форум"],
          ["https://site.ru/stuff", 'Blog'],
          ['https://FinViz.com/sp500', "Финансы"]
          ]
    site = list()
    site.append("https://bybit.com")
    site.append("Биржа")
    L1.append(site)
    print(L1[-1])   # ['https://bybit.com', 'Биржа']
    L1[-1].append('desc: auto logout after few days')
    print(L1[-1])   # ['https://bybit.com', 'Биржа', 'desc...']
    L1[-1].pop()    # Удаление последнего элемента из вложенного списка (decs...)
    L1.pop()        # Удаление последнего списка
    L1[0] = ['https://ruvds.com', "Хостинг"]

    for url in L1:
        for i in url:
            print(i, end=' ')
        print(end=" | ")
```

**Примечания**<br>
Так как список динамический, на каждой итерации он будет меняться
```
    L1 = [1,2,3,4,5]
    for i in L1:
        L1.remove(i)
    print(L1)   # [2, 4]
```
При `L1[:]` удалятся все элементы

<a name="Кортежи_tuple"></a>
### Кортежи (tuple)
Кортеж (tuple) - неизменяемая последовательность элементов<br>
Для создания кортежа используются круглые скобки
```
    url_1 = ('forum.com', 'Форум')
    url_2 = 'forum.com', 'Форум'
    url_3 = ('forum.com',)

    L1 = ['forum.com', 'Форум']
    url_4 = tuple(L1)
```
Запись `url_4[0] = 'qwe'` в кортежах работать не будет<br>
Кортеж можно разложить на переменные: `address, description = url_1`<br>
Функции, возвращающие несоклько значений сразу, фактически возвращают кортеж.<br>
```
    ...
    def GetUrl(self):
        return self.address, self.description

def main():
    url_1 = Url('forum.com', 'Форум')
    T1 = url_1.GetUrl()
```
С помощью оператора * можно разложить кортеж на отдельные значения
```
class Url:
    def __init__(self, address, description='', contacts=''):
        self.address = address
        self.description = description
        self.contacts = contacts

def main():
    url_1 = ('forum.com', 'Форум')
    U1 = Url(*url_1, 'info@mail.ru')
```

<a name="Словари_dict"></a>
### Словари (dict)
Создание словаря:<br>
`bank = {'usdt': 150.64, 'usdc': 12.3, 'btc': 0.0001}`<br>

Создание словаря из списка/кортежа:
```
  L1 = [['usdt', 150.64],
          ['usdc', 12.3],
          ['btc', 0.0001]
          ]
    D1 = dict(L1)
```
**Добавление** элемента в словарь: `bank['eth'] = 2`<br>

Получать элементы можно по ключу или через **get**:

- **get(key)** - возвращает из словаря элемент, в ином случае, возвращает None
- **get(key, default)** - возвращает из словаря элемент, в ином случае, возвращает default
```
    bank = {'usdt': 150.64, 'usdc': 12.3, 'btc': 0.0001}

    print(bank.get('usdt'))                 # 150.64
    print(bank.get('usdt', 'null balance')) # 150.64
    print(bank.get('eth', 'null balance'))  # null balance
```
Удаление элементов через **del**: `del bank['usdc']`<br>
Удаление через **pop()**. Происходит аналогично **get** и имеет такие же агрументы (key / key, default)<br>
Удалить все элементы - **clear()** <br>

Метод **copy()** копирует словарь и возвращает новый (при поверхностном копировании 2 переменных ссылаются на одно и то же значение)<br>
Метод **update** объединяет 2 словаря: `D2.update(D1)`<br>

Перебор значений. Помимо обычного перебора через for i in Dict, можно использовать **items()**:
```
    for coin, value in bank.items():
        print(coin, value)
```
Можно перебирать отдельно ключи и значения: **bank.keys()** и **bank.values()** <br>
**Комплексные словари**. Пример:
```
    bank = {'usdt': {'balance': 150.64, 'blocked': 30.1}, 'usdc':{'balance': 12.3, 'blocked': 50}}
    for i in bank:
        print(i, bank[i].get('blocked'))   # usdt 30.1,  usdc 50
```

<a name="Множества_set"></a>
### Множества (set)
Множества хранят только уникальные элементы
```
    bank = {'usdt', 'usdc', 'btc', 'usdt'}
    print(bank) # {'btc', 'usdt', 'usdc'}
```
Множнество можно создать из списка или кортежа с помощью **set()** <br>
- **add()** - дбавить элемент
- **remove()** - удалить элемент
- **discard()** - удалить элемент (не генерирует ошибку, если элемента нет)
- **clear()** - очистить set
- **copy()** - копировать

**Объединение** множеств:
```
    bank = {'usdt', 'usdc', 'btc', 'usdt'}
    bank2 = {'usdc', 'eth'}
    print(bank.union(bank2)) # {'usdt', 'usdc', 'btc', 'eth'}
```
Или можно использовать операция логического сложения ( **|** ) `print(bank | bank2)`<br>
**Пересечение** множеств:
```
    bank = {'usdt', 'usdc', 'btc', 'usdt'}
    bank2 = {'usdc', 'eth'}
    print(bank.intersection(bank2)) # {'usdc'}
```
Или `bank & bank2`<br>

Модификация метода **intersection_update()** заменяет пересеченными элементами первое множество:

`bank.intersection_update(bank2)`

**Разность** множеств. Возвращаются элементы, которые есть в первом множестве, но отсутвтсуют во втором
```
    bank = {'usdt', 'usdc', 'btc', 'usdt'}
    bank2 = {'usdc', 'eth'}
    print(bank.difference(bank2)) # {'btc', 'usdt'}
```
Или `bank - bank2`

**Симметрическая разность** множества возвращает все элементы двух множеств за исключением общих:
```
    bank = {'usdt', 'usdc', 'btc', 'usdt'}
    bank2 = {'usdc', 'eth'}
    print(bank.symmetric_difference(bank2)) # {'btc', 'usdt', 'eth'}
```
Или `bank ^ bank2`

Метод **issubset()** определяет, является ли текущее множество подмножеством другого множества: 
```
    bank = {'usdt', 'usdc', 'btc', 'usdt'}
    bank2 = {'usdc', 'btc'}
    print(bank.issubset(bank2)) # False
    print(bank2.issubset(bank)) # True
```
**issuperset()** проверяет на надмножества (инверсия issubset)<br>
Тип **frozen set** является видом множеств, которое нельзя изменить: `fs = frozenset({'btc', 'eth'})`

<a name="List_comprehension"></a>
### List comprehension
list comprehension - это краткий синтаксис для получения списка на основе других наборов данных<br>
Синтаксис: `L1 = [i for i in L0 if i > 10]`
```
    bank = {'usdt': 150.64, 'usdc': 12.3, 'btc': 0.0001, 'eth': 0}
    coins = [c for c in bank if bank[c] > 0]
    for i in coins:
        print(f'{i}: {bank[i]}')
```
Возвращаемое значение может представлять из себя более сложное выражение:
```
    rate = {'usdt': 1.0001, 'usdc': 0.9999,'btc': 65100, 'eth': 3200}
    bank = {'usdt': 150.64, 'usdc': 12.3, 'btc': 0.0001, 'eth': 0}
    coins = [f'${round(bank[c] * rate[c], 2)}' if round(bank[c] * rate[c]) > 10 else 0 
             for c in bank if bank[c] > 0 and rate.get(c)]
    print(coins)    # ['$150.66', '$12.3', 0]
```

<a name="Упаковка_и_распаковка"></a>
### Упаковка и распаковка
Распаковка (деструктуризация) представляет разложение списка, кортежа и тд на отдельные переменные.<br>
Распаковка словаря:
```
    bank = {'usdt': 150.64, 'btc': 0.0001, 'eth': 0}
    u, b, e = bank
    print(u, b, e) # usdt btc eth
```
Распаковка в цикле:
```
    bank = [('usdt', 150.64),
            ('btc', 0.001),
            ('eth', 3.4),
            ]
    for coin, value in bank:
        print(coin, value)  # usdt 150.64 ...
```
Функция **enumerate()** создаёт для каждого элемента картеж, который содержит свой индекс, увеличивающийся с каждой итерацией:
```
    bank = ['usdt', 'btc', 'eth']
    for index, coin in enumerate(bank):
        print(f'{index}) {coin}')   # 0) usdt ...
```
Если какой-либо элемент не нужен, то обычно он опреледяется знаком _<br>
Но при этом определяется данная переменная
```
    bank = {'usdt': 150.64, 'usdc': 12.3, 'btc': 0.0001, 'eth': 0}
    ut, _, b, _ = bank
    print(ut, b, _) # usdt btc eth
```
Для упаковки значений используется оператор *<br>
После обозначения переменной ставится запятая **,** `*coins, = ...`
```
    *coins, = usdt, btc, eth
    print(coins)    # ['usdt', 'btc', 'eth']
```
Как правило, упаковка применяется для сбора оставшихся значений после деструктуризации. Например:
```
    first, *num = [1, 2, 3, 4, 5, 6]
    print(num)    # [2, 3, 4, 5, 6]
```
Или
```
    first, _, third, *_, last = [1, 2, 3, 4, 5, 6]
    print(first, third, last)    # 1 3 6
```
Операторы * и ** можно использовать для распаковки<br>
Для распаковки катрежей, списков, строк и множеств используется *<br>
Для распаковки словарей - **
```
    coins1 = ['usdt', 'usdc']
    coins2 = ('btc', 'eth')
    coins3 = [*coins1, *coins2]
    print(coins3)   # ['usdt', 'usdc', 'btc', 'eth']
```
При распаковке словарей повторяющиеся элементы перезаписываются:
```
    bank1 = {'usdt': 150.64, 'eth': 7.2}
    bank2 = {'usdt': 70.1, 'usdc': 12.3, 'btc': 0.0001}

    bank3 = {**bank1, **bank2}
    print(bank3) # {'usdt': 70.1, 'eth': 7.2, 'usdc': 12.3, 'btc': 0.0001}
```

### Упаковка и распаковка в параметрах функций
Общепринятые именования:<br>
*args - представляет параметры, которые передаются по позиции<br>
*kwargs - параметры, которые передаются по имени<br>
Пример:
```
def sum(*args):
    res = 0
    for i in args:
        res += i
    return res
def main():
    print(sum(1, 2, 3))
```
Оператор ** упаковывает словари
```
def print_coins(**kwargs):
    for i in kwargs:
        print(f'{i} = {kwargs[i]}')
def main():
    print_coins(coin = 'usdt', value = 15.4)
```
Для распоковки агрументов тоже используется оператор * или **
Пример со списком:
```
def print_coins(coin, value):
    print(f'{coin} : {value}')
def main():
    bank = {'usdt', 7.2}
    print_coins(*bank)
```
Пример со словарём:
```
def print_coins(**kwargs):
    for i in kwargs:
        print(f'{i} = {kwargs[i]}')
def main():
    bank = {'usdt': 150.64, 'eth': 7.2}
    print_coins(**bank)
```

<a name="Модули"></a>
### Модули
Модули имеют расширения .py, название модуля - это название файла.<br>
По умолчанию интерпретатор Python ищет модули в папке запускаемого скрипта.<br>
Содержание модуля test_module.py:
```
x = 123

def print_msg(text):
    print('msg:', text)
```
Чтобы его интеграции импользуется: `import test_module`
```
import test_module

def main():
    print(test_module.x)
    test_module.print_msg('from main module')
```
Для доступа к функционалу модуля, необходимо обратиться к нему через название.<br>
Чтобы подключить только частичный функционал моделя используется конструкция<br>
`from test_module import print_msg`<br>

Импорт всего функционала в глобальное пространство имён: `from test_module import *`
```
from test_module import *

def main():
    print(x)
    print_msg('from main module')
```
Но при импорте в глобальное пространство имён могут возникать колизии<br>

**Псевдонимы**<br>
При импорте модуля или его функциональностей можно уставноить для них псевдонимы с помощью **as**<br>
```
import test_module as msg

def main():
    print(msg.x)
    msg.print_msg('from main module')
```
```
from test_module import print_msg as display

def main():
    display('text')
```

При выполнении модуля среда присваивает переменной **_\_name__** его имя, если модуль является запускаемым, то его имя будет **_\_main__** вне зависимости от названия файла.<br>
Проверка главного модуля и запуск в нём функции main():
```
if __name__ == '__main__':
    main()
```

### Генерация байткода модулей
Если скрипт запускается первый раз после изменения, то для него создается файл с байткодом (расширение .pyc) в папке **_\_pycache__**.<br>
Это происходит со всеми скриптами, кроме запускаемого, он каждый раз компилируется заново.<br>
Байткод можно скомпилировать вручную, передав в функцию compile путь к скрипту: 
```
import py_compile

py_compile.compile('test_module.py')
```
Так же скомпилировать можно при помощи модуля compileall<br>
`python -m compileall c:\python\files -l` - так будут скомпилированы все файлы в этой папке<br>.
Без `-l` - все файлы, даже в подкаталогах. 

<a name="Randome"></a>
### Randome
- **random()** - возвращает число от 0.0 до 1.0 с плавающей запятой
- **randint()** - возвращает случайное значения между заданным диапозоном (**включая min и max**)
- **randrange()** - возвращает случайное значение из заданного диапозона (**не включая max**) (принцип, как у range)
- **shuffle()** - перемешивает список
- **choice()** - возвращает случайный элемент списка
- **choices()** - возвращает список с неуникальными случайными значениями из списка
- **sample()** - возвращает список с уникальными случайными значениями из списка
```
import random

print(random.random())            # 0.7674819847145965
print(random.randint(0, 1))       # 0 - 2
print(random.randrange(3))        # 0 - 2
print(random.randrange(2, 5))     # 2 - 4
print(random.randrange(2, 10, 2)) # 2, 4, 6, 8

L1 = [1, 2, 3, 4, 5]
random.shuffle(L1)
print(L1)                        # [4, 2, 3, 5, 1]
print(random.choice(L1))         # 1 - 5
print(random.choices(L1, k = 5)) # [2, 4, 3, 1, 2]
print(random.sample(L1, 2))      # [1, 4]
```

<a name="Math"></a>
### Math
`import math`
- **pow()** - возведение числа в степень
- **sqrt()** - квадратный корень числа
- **ceil()** - округление числа до наибольшего целого
- **floor()** - округление числа до наименьшего целого
- **factorial()** - факториал
- **degrees()** - перевод из радиан в градусы
- **radians()** - перевод из градусов в радианы
- **cos, sin, tan, acos, asin, atan** - принимают агрумент в радианах
- **log()** - логарифм
- **log10()** - десятичный логарифм<br>

Встроенные константы **pi** и **e**<br>
Функции для поска в скиске минимального и максимального элемента: **min()**, **max()** <br>
Функция **abs()** возвращает число без учета знака (абсолютное значение числа)
```
    print(pow(2, 3))                    # 8
    print(2 ** 3)                       # 8
    print(math.sqrt(144))               # 12.0
    print(144 ** 0.5)                   # 12.0
    print(math.ceil(1.01))              # 2
    print(math.floor(1.99))             # 1
    print(math.degrees(3.14))           # 179.9087476710785
    print(math.radians(180))            # 3.141592653589793
    print(math.cos(math.radians(60)))   # 0.5000000000000001
    print(math.log(10, 2))              # 3.3219280948873626
    print(math.pi)                      # 3.141592653589793
    print(math.e)                       # 2.718281828459045
    print(max([1, 3, 2]))               # 3
    print(abs(-2 - 7))                  # 9
```

Проверка на **nan**: `math.isnan(x)`

<a name="locale"></a>
### locale
`import locale`<br>
Отображение информации может отличаться от локальной среды, например, 1.250.50 / 1.250,50<br>
Изменение локальной среды для Windows: `locale.setlocale(locale.LC_ALL, 'ru')`<br>
Первый параметр указывает на изменяемую категорию:
- **LC_ALL** - все категории
- **LC_NUMERIC** - числа
- **LC_MONETARY** - валюты
- **LC_TIME** - дата и время
- **LC_CTYPE** - применяет локализацию при переводе символов в верхний или нижний регистр
- **LC_COLLIATE** - применяет локаль при сравнении строк

Для формирования чисел и валют используются **currency()** и **format_string()**, к последнему 
можно применять плейсхолдеры (%d - целое число, %f - число с плавающей точкой, %e - для эеспоненциальной записи)
```
    locale.setlocale(locale.LC_ALL, 'ru')
    x = 1200.6543
    print(locale.currency(x))               # 1200,65 ₽
    print(locale.format_string('%d', x))    # 1200
    print(locale.format_string('%f', x))    # 1200,654300
    print(locale.format_string('%.3f', x))  # 1200,654
    print(locale.format_string('%e', x))    # 1,200654e+03
```
Если в setlocale вторым параметром передается пустая строка, то среда определяется автоматически, её можно узнать с помощью **getlocale()**
```
    locale.setlocale(locale.LC_ALL, '')
    print(locale.getlocale())   # ('Russian_Russia', '1251')
```
Для разных ОС вывод может отличаться: Windows - ('Russian_Russia', '1251'), MacOS - ('ru_RU', 'UTF-8')

<a name="decimal"></a>
### decimal
При работе с обыным float могут встречаться ошибки, чтобы их избежать можно использовать модуль decimal, а именно его класс **Decimal**<br>
Нельзя смешивать в операциях объекты Decimal и float.
```
from decimal import Decimal

    print(0.1 * 3)  # 0.30000000000000004
    x = Decimal('0.1')
    print(x * 3)    # 0.3

    x = Decimal('0.200')
    print(x * 2)    # 0.400
```
**Округление**<br>
Объекты Decimal имеют метод для округления **quantize()**, его первый агрумент обозначает формат округления числа (кол-во нулей после точки)<br>
По умолчанию округление описывается константой **ROUND_HALF_EVEN**, описание констант:
- **ROUND_HALF_EVEN** - округление до ближайшего чётного числа, если округляемая часть равна 5
- **ROUND_HALF_UP** - округляет число в большую сторону, если после него идёт 5 или больше
- **ROUND_HALF_DOWN** - округляет число в большую сторону, если после него идёт число больше 5
- **ROUND_05UP** - округляет 0 до 1, если после него идёт число 5 и больше
- **ROUND_CEILING** - округляет число в большую сторону, не зависит от числет после
- **ROUND_FLOOR** - не округляет число в большую сторону, не зависит от числет после

`from decimal import Decimal, ROUND_HALF_EVEN, ROUND_HALF_DOWN, ROUND_05UP, ROUND_CEILING, ROUND_FLOOR`
```
    x = Decimal('0.537')
    print(x.quantize(Decimal('1.00')))  # 0.54
    x = Decimal('0.545')
    print(x.quantize(Decimal('1.00'), ROUND_HALF_EVEN))  # 0.54
    x = Decimal('0.555')
    print(x.quantize(Decimal('1.00'), ROUND_HALF_EVEN))  # 0.56
    print(x.quantize(Decimal('1.00'), ROUND_HALF_DOWN))  # 0.55
    x = Decimal('0.005')
    print(x.quantize(Decimal('1.00'), ROUND_05UP))       # 0.01
    x = Decimal('0.025')
    print(x.quantize(Decimal('1.00'), ROUND_05UP))       # 0.02
    x = Decimal('0.021')
    print(x.quantize(Decimal('1.00'), ROUND_CEILING))    # 0.03
    x = Decimal('0.0299')
    print(x.quantize(Decimal('1.00'), ROUND_FLOOR))      # 0.02
```

<a name="dataclass"></a>
### dataclass
Модуль **dataclasses** предоставляет декоратор **dataclass**, который поволяет создавать data-классы. 
Это позволяет сократить шаблонный код классов. Как правило, такие классы нужны для хранения определённых данных 
для которые не имеют дополнительных методов.
```
from dataclasses import dataclass

@dataclass
class Url:
    address: str
    description: str
```
Данная запись будет равна:
```
class Url:
    def __init__(self, address, description):
        self.address = address
        self.description = description

    def __repr__(self):
        return f'Url(address={self.address!r}, description={self.description!r})'

    def __eq__(self, other):
        if other.__class__ is self.__class__:
            return (self.address, self.description) == (other.address, other.description)
        return NotImplemented
```
`__repr__` - для вывода информации, `__eq__` - для сравнения объектов<br>
**Значение по умолчанию**: `description: str = ''`
```
@dataclass
class Url:
    address: str
    description: str

def main():
    url_1 = Url('https://forum.com', 'Форум')
    url_2 = Url('https://forum.com', 'Форум2')
    print(url_1)  # Url(address='https://forum.com', description='Форум')
    print(url_1 == url_2)  # False
```
Присвоение пустого изменяемого типа:
```
from dataclasses import field

@dataclass
class Cl:
    way: list = field(default_factory=list)
```
Параметры для **field**:<br>
- **init** - определяет, является ли атрибут в инициализации
- **default_factory** - присвоение значения по умолчанию для изменяемых типов
- **repr** - участие атрибута в маг. методе repr
- **compare** - сравнивать ли значения в eq
- **default** - значение по умолчанию

После формирования всех атрибутов вызывается метод `__post_init__`<br>
**InitVar** - передаёт атрибут в `__post_init__`
```
from dataclasses import InitVar

@dataclass
class Counter:
    start: int
    step: InitVar[int] = 1
    
    def __post_init__(self, step):
        if step < 0:
            step = 1
        self.start += step

def main():
    C = Counter(0, -1)
    print(C)
```

С помощью параметров можно настроить декоратор:
```
def dataclass(cls=None, /, *, init=True, repr=True, eq=True, order=False,
              unsafe_hash=False, frozen=False, match_args=True,
              kw_only=False, slots=False)
```
- **init** - для генерации конструктора (по умолчанию True)
- **repr** - для вывода информации с помощью функции `__repr__()` (по умолчанию True)
- **eq** - для сравнения двух объектов с помощью == или != (по умолчанию True)
- **order** - для генерации функций **<** - `__lt__`, **<=** - `__le__`, **>** - `__gt__`, **>=** - `__ge__` (по умолчанию False)
- **unsafe_hash** - для генерации функции `__hash__()`, которая выводит хэш объекта (по умолчанию False)

Применение параметров:
```
@dataclass(unsafe_hash=True)
class Url:
    address: str
    description: str = ''

def main():
    url_1 = Url('https://forum.com')
    print(url_1.__hash__())  # 8595482140772800576
```

<a name="match"></a>
### match
```
    match x:
        case 1 | 2:
            print('1-2')
        case 3:
            print('3')
        case _:
            print("default")
```
Можно перечислять значения через **|**<br>
Если знаечние не подходит ни под один кейс и нету default знаечния, тогда ничего не произойдёт (ошибки не будет).<br>
**Важно расположение case.** Данные записи показывают разный результат:
```
    x = [1, 2]
    match x:
        case [1, 2]:
            print('1, 2')
        case [*other]:
            print('other')
```
**Выведет**: 1, 2
```
    x = [1, 2]
    match x:
        case[*other]:
            print('other')
        case [1, 2]:
            print('1, 2')
```
**Выведет**: other

### Кортежи в match
```
def print_data(url):
    match url:
        case ('https://forum.com' | 'forum.com', 'Форум'):
            print('ok')
        case (address, 'Форум'):
            print(f'Address is {address}')
        case ('https://forum.com' | 'forum.com', description):
            print(f'Description is {description}')
        case(address, description):
            print(f'Address is {address}. Description is {description}')
        case _:
            print("Error")

def main():
    url_1 = ('https://forum.com', 'Форум')
    url_2 = ('https://Finviz.com', 'Форум')
    url_3 = ('forum.com', 'Блог')
    url_4 = ('https://forum.com', 'Форум', 1)
    print_data(url_1)   # ok
    print_data(url_2)   # Address is https://Finviz.com
    print_data(url_3)   # Description is Блог
    print_data(url_4)   # Error
```
Для пропуска значения можно указать **_**
```
    match url:
        case ('https://forum.com' | 'forum.com', 'Форум'):
            print('ok')
        case (address, 'Форум'):
            print('Undefiend is address')
        case ('https://forum.com' | 'forum.com', _):
            print('Address is ok')
```
Для неопределённого кол-ва значений указывается переменная с *, если дальнейшие переменные не нужны, то принято обозкачать *_
```
def print_data(bank):
    match bank:
        case ('usdt' | 'usdc', *count):
            res = 0
            for i in count:
                res += i
            print(f'USD: {res}')
        case ('btc', *_):
            print('BTC')
        case _:
            print("Error")

def main():
    bank_1 = ('usdt', 4, 12, 76.32, 100)
    bank_2 = ('usdc')
    print_data(bank_1)   # USD: 192.32
    print_data(bank_2)   # Error
```
### Массивы в match
```
def print_data(coins):
    match coins:
        case ['usdt' | 'usdc', *other]:
            print(f'first: usd, other: {other}')

def main():
    coins_1 = ['usdt', 'eth', 'btc', 'ltc']
    coins_2 = ['usdc']
    print_data(coins_1)   # first: usd, other: ['eth', 'btc', 'ltc']
    print_data(coins_2)   # first: usd, other: []
```
При применении массивов доступна следующая запись:
```
    match coins:
        case [*other]:
```
Тут match может принимать кортежи и массивы<br>
**case []:** принимает пустой массив
### Словарь в match
match проверяет словари на нанличие указанных элементов
```
def print_data(coins):
    match coins:
        case {'usdt': 0, 'eth': 0}:
            print('Нулевой баланс')
        case {'usdt': usdt, 'eth': eth}:
            print(f'USDT: {usdt}, ETH: {eth}')
        case {}:
            print('Нет нужных значений в словаре')
        case _:
            print('Это не соварь')

def main():
    coins_1 = {'usdt': 12, 'eth': 0.2, 'btc': 0.001}
    coins_2 = {'usdt': 0, 'eth': 0}
    print_data(coins_1)   # USDT: 12, ETH: 0.2
    print_data(coins_2)   # Нулевой баланс
```
**case {}:** соответствует любома словарю<br>
Если значение не важно, то используется констрцкция `{'key': _}`<br>
Записи с ** указывают на неопределённое кол-во элементов в словаре
```
def print_data(coins):
    match coins:
        case {'usdt': _, 'eth': _}:
            print('usdt, eth')
        case {**other}:
            print('other:', end=' ')
            for i in other:
                print(f'{i}: {other[i]}', end=' ')
            print()

def main():
    coins_1 = {'usdt': 12, 'btc': 0.001, 'ltc': 0.7 }
    coins_2 = {'usdt': 43, 'eth': 0.2}
    print_data(coins_1)   # other: usdt: 12 btc: 0.001 ltc: 0.7
    print_data(coins_2)   # usdt, eth
```
Шаблон `{'usdt': _, 'eth': _, **other}` будет соответствовать любому словарю, где есть элементы с ключами usdt и eth.<br>
Поэтому `case {'usdt': _, 'eth': _}:` и `case {'usdt': _, 'eth': _, **other}:` будут равны и выполнится первый стоящий case.

### Классы в match
```
class Unit(): #abc.ABC
    def __init__(self, name, hp, damage):
        self.name = name
        self.hp = hp
        self.damage = damage

class Battler(Unit):
    pass

class Archer(Unit):
    pass

def print_data(unit):
    match unit:
        case Unit(name='Ray' | 'Sam'):
            print('Red team')
        case Unit(name=unit_name, hp=unit_hp, damage=unit_damage):
            print(f'Unknown person: {unit_name} - {unit_hp}/{unit_damage}')
        case _:
            print('Not a unit')

def main():
    Ray = Battler('Ray', 50, 10)
    Alex = Archer('Alex', 40, 18)
    
    print_data(Ray)  # Red team
    print_data(Alex) # Unknown person: Alex - 40/18
```
Для **позиционного** получения атрибутов класса необходимо указать в нём `__match_args__`:
```
class Unit(): #abc.ABC
    __match_args__ = ('name', 'hp', 'damage')
    def __init__(self, name, hp, damage):
        self.name = name
        self.hp = hp
        self.damage = damage
        
def print_data(unit):
    match unit:
        case Unit('Ray', 50):
            print('Red team')
        case Unit('Alex', 40, 18):
            print('Blue team')
```
### Ограничение шаблонов
В case можно добавлять условия:
```
def print_data(unit):
    match unit:
        case Unit(name=unit_name) if str(unit.__class__) == '<class \'__main__.Battler\'>':
            print(f'Red team - {unit_name}')
        case Unit(name=unit_name):
            print(f'Blue team - {unit_name}')

def main():
    Ray = Battler('Ray', 50, 10)
    Alex = Archer('Alex', 40, 18)

    print_data(Ray)  # Red team
    print_data(Alex) # Unknown person: Alex - 40/18
```
Псевдонимы **as**<br>
Примеры:
```
def print_data(unit):
    match unit:
        case Unit(name="Ray"|"Sam" as unit_name):
            print(f'Red team - {unit_name}')
        case Unit('Alex') as unknown_unit if unknown_unit.hp > 50 :
            print(f'New unit: {unknown_unit.name} - {unknown_unit.hp}/{unknown_unit.damage}')
```
```
def print_data(team):
    match team:
        case (Unit() as first_unit, Unit() as second_unit):
            print(f'1) {first_unit.name}, {first_unit.hp} hp\n'
                  f'2) {second_unit.name}, {second_unit.hp} hp')
        case _:
            print('Error')
            
def main():
    Ray = Battler('Ray', 50, 10)
    Alex = Archer('Alex', 40, 18)
    Team_1 = (Sam, Alex)
    print_data(Team_1)
```

<a name="Контекстные_менеджеры"></a>
### Контекстные менеджеры
Создание собственного контекстного менеджера.<br>
`__enter__` - вызывается когда происходит инициализация менеджера контекста<br> 
`__exit__` - вызывается в конце работы контекстного менеджера

В данном примере объект **C** используется как словарь.<br>
Программа изменяет словарь, но если в процессе её работы произойдёт ошибка, то уже сделанные изменения не будут сохранены, словарь останется в изначальном виде.
```
class ConvertToRub:
    Rates = {'usd': 93, 'eur': 100}
    def __init__(self, v):
        self.__values = v
    def __enter__(self):
        self.__newValues = dict(self.__values)
        return self.__newValues
    def __exit__(self, exc_type, exc_val, exc_tb):
        if exc_type == None: # нет ошибок
            for i in self.__values:
                self.__values[i] = self.__newValues[i]
        return False # если True, то исключения не выходят за пределы, в этом случае - with

def main():
    m = {'usd': 314.17, 'eur': 51, 'btc': 0.00024}
    try:
        with ConvertToRub(m) as C:
            for i in C:
                C[i] *= ConvertToRub.Rates[i]
    except KeyError as k:
        print('Нет информации по', k)
    except Exception as ex:
        print('Ошибка:', ex)
    print(m)
```
<a name="Метаклассы"></a>
### Метаклассы
type(name, bases, dict) - передаётся имя класса, родительские классы и словарь с атрибутами
```
def print_info(self):
    print(f'{self.value}, {self.__dict__}')

def main():
    Meta = type('M', (), {'value': 0, 'print_info': print_info})
    C = Meta()
    C.print_info()
```

```
class Meta(type):
    def __new__(cls, name, base, attrs):
        attrs.update({'value': 0})
        return type.__new__(cls, name, base, attrs)

class Counter(metaclass=Meta):
    pass

def main():
    C = Counter()
    print(C.value)
```


<a name="Работа_с_файлами"></a>
## Работа с файлами
<a name="Открытие_и_закрытие_файлов"></a>
### Открытие и закрытие файлов
Файлы условно можно разделить на текстовые (txt, html, csv) и бинарные (видео, аудио, изображения)<br>
Для работы с файлами необходимо:<br>
Открыть файл **open()** <br>
Произвести с ним какие-либо действия (**read()** или **write()**)<br>
Закрыть файл **close()**. Это освободит все связанные с файлом ресурсы

В функцию **open(file, mode)** передаётся file - путь к файлу и mode - режим работы с файлом.<br>
Режимы работы с файлами:
- **r** - файл открывается для чтения. Если файл не найден, то генерируется исключение FileNotFoundError
- **w** - файл открывается для записи. Если файл не найден, то он создаётся. Если файл есть, то у него стераются все старые данные
- **a** - файл открывается для дозаписи. Если файл не найден, то он создаётся. Если файл есть, то новые данные записываются в конец
- **b** - используется для работы с бинарными файлами. Применяется вместе с другими режимами: **rb** и **wb**
- **r+** - файл открывается для чтения и записи. Если файл не найден, то генерируется исключение FileNotFoundError
- **w+** - файл открывается для чтения и записи. Если файл не найден, то он создаётся. Если файл есть, то он перезаписывается
- **a+** - файл открывается для чтения и записи. Если файл не найден, то он создаётся. Если файл есть, то новые данные записываются в конец

Чтобы избежать ошибок с открытием файла можно использовать try:
```
try:
    file = open('file.txt', w)
    try:
        print('Working...')
    finaly:
        file.cloce()
except Exception as ex
    print(ex)
```
Тут файл будет закрыт в любом случае.<br>
Наиболее удобная конструкция - **with**:
```
    with open('file.txt', 'w') as file:
        print('Working...')
```
В конце with закроет файл

<a name="Запись_в_текстовый_файл"></a>
### Запись в текстовый файл
В файл записывается именно строка, все числовые значения необходимо преобразовывать.
```
    x = 100
    with open('file.txt', 'a') as file:
        file.write(str(x))
```
Для записи списка строк используется **writelines**
```
    text = ['123\n', 'qwe']
    with open('file.txt', 'a') as file:
        file.writelines(text)
```
Запись через **print** (в консоль текст не выводится):
```
    with open('file.txt', 'a') as myfile:
        print('sometext\n', file=myfile)
```
<a name="Чтение_файла"></a>
### Чтение файла
Методы для чтения файла:
- **readline()** - считывает одну строку файла
- **read()** - считывает всё содержимое файла в одну строку
- **readlines()** - считывает все строки файла в список

В данном примене неявно применяется метод **readline**
```
    with open('file.txt', 'r') as myfile:
        for line in myfile:
            print(line)
```
**readline**:
```
    with open('file.txt', 'r') as myfile:
        line = myfile.readline()
        while line:
            print(line, end='')
            line = myfile.readline()
```
Небольшие файлы можно считать сразу в одну переменную с помощью **read**:
```
    content = myfile.read()
    print(content)
```
<a name="Кодировка"></a>
### Кодировка
Для корректного отображения символов, необходимо указать нужную кодировку, например, **encoding='utf8'**:
```
    with open('file.txt', 'r', encoding='utf8') as myfile:
        print(myfile.read())
```
<a name="Чтение_и_запись_w"></a>
### Чтение и запись w+
Чтение и запись
```
    text = ['123\n', 'qwe']
    with open('file.txt', 'w+', encoding='utf8') as myfile:
        myfile.writelines(text)
        myfile.seek(0)
        print(myfile.read())
```
После записи информации в файл происходит перемещение к первому биту файла (**seek(0)**) и далее файл считывается


<a name="CSV"></a>
### CSV
`import csv`
<a name="CSV_Запись"></a>
### Запись
Для корректной записи используется **newline=''** <br>
Чтобы данные записывались в разных строках, необходим разделитель **delimiter=';'**
```
    coins = [['usdt', 12],
            ['btc', 1],
            ['eth', 3]
            ]
    with open('data.csv', 'w', encoding='utf8', newline='') as file:
        writer = csv.writer(file, delimiter=';')
        writer.writerows(coins)
```
Числовые значения с плавающей запятой будут записываться через точку, как в python.
С такими данными нельзя производить вычисления в таблице excel, подставлять в формулы и тд.<br>
Это можно исправить, используя модуль locale:
```
    locale.setlocale(locale.LC_ALL, "ru")
    csv_format = lambda x: locale.str(x)
    
    with open('data.csv', 'a', encoding='utf8', newline='') as file:
        writer = csv.writer(file, delimiter=";")
        coin = ['usdc', csv_format(209.299)]  # 209,299
        writer.writerow(coin)
```
<a name="CSV_Чтение_файла"></a>
### Чтение файла
Для работы с русскими символами: `encoding='cp1251'`
```
    with open('data.csv', 'r', encoding='utf8', newline='') as file:
        reader = csv.reader(file, delimiter=';')
        for row in reader:
            print(f'{row[0]}: {row[1]}')
```
<a name="CSV_Запись_словаря"></a>
### Запись словаря
Сначала создается заголовки, далее происходит добавление рядов, как в предыдущих примерах
```
    coins = [{'coin': 'usdt', 'value': locale.str(120.50)},
             {'coin': 'btc', 'value': locale.str(0.0001)},
             {'coin': 'eth', 'value': locale.str(0.3)},
            ]
    
    with open('data.csv', 'w', encoding='utf8', newline='') as file:
        columns = ['coin', 'value']
        writer = csv.DictWriter(file, delimiter=';', fieldnames=columns)
        writer.writeheader()

        writer.writerows(coins)
```
<a name="CSV_Чтение_словаря"></a>
### Чтение словаря
```
    with open('data.csv', 'r', encoding='utf8', newline='') as file:
        writer = csv.DictReader(file, delimiter=';')
        for row in writer:
            print('{0}: {1}'.format(row["coin"], row["value"]))
```

<a name="Бинарные_файлы"></a>
### Бинарные файлы
Копирование изображения:
```
    image_data = []

    with open('img.jpg', 'rb') as img:
        image_data = img.read()

    with open('new_img.jpg', 'wb') as img:
        img.write(image_data)
```

<a name="pickle"></a>
### pickle
`import pickle`

Запись информации в бинарный файл .dat:
```
    coin = 'usdt'
    value = 154.12

    with open('coins.dat', 'wb') as dat:
        pickle.dump(coin, dat)
        pickle.dump(value, dat)

    with open('coins.dat', 'rb') as dat:
        coin = pickle.load(dat)
        value = pickle.load(dat)
        print(f'{coin}: {value}')
```
Запись списка:<br>
```
    coins = [['usdt', 154.12],
             ['btc', 0.0001],
             ['eth', 3]
             ]


    with open('coins.dat', 'wb') as dat:
        pickle.dump(coins, dat)

    with open('coins.dat', 'rb') as dat:
        coins = pickle.load(dat)
        for coin in coins:
            print(f'{coin[0]}: {coin[1]}')
```

<a name="shelve"></a>
### shelve
`import shelve`

Модуль shelve позволяет сохранить данные в файл, привязав их в определённому ключу (принцип, как в словарях).<br>
**shelve.open()** имеет свои флаги:
- **c** - открывает файл для чтения и записи. Если файла не существует, то он создаётся (значение по умолчанию)
- **r** - открывает файл для чтения
- **w** - открывает файл для записи
- **n** - открывает файл для записи. Если файла не существует, то он создаётся. Если он существует, то он перезаписывается

**Чтение и запись**
```
    with shelve.open('coins') as file:
        file['usdt'] = 154.12
        file['btc'] = 0.0001
        file['eth'] = 3

    with shelve.open('coins') as file:
        for i in file:
            print(f'{i}: {file[i]}')
```
Тут создадуться 3 файла coins с расширениями .bak, .dat, .dir


Для полечения данных можно использовать конструкция **if key in file** или метод **get** (второй агрумент вернётся, если ключ не будет найден)<br>
**items()** возвращает кортеж с ключом и значением
```
    with shelve.open('coins') as file:
        if 'usdc' in file: print(file['usdc'])

        print(file.get('usdc', 'Null'))     # Null

        for i in file.items():
            print(i)    # ('usdt', 154.12)...
```
**Удаление данных**<br>
**pop()** аналогичен get()<br>
**clear()** для отчистки словаря
```
    with shelve.open('coins') as file:
        btc = file.pop('btc', 'Not Found')
        print(btc)

        del file['eth']

        file.clear()
```

<a name="Json"></a>
## Json
### Запись словаря в Json
```
    import json
    
    Adm_list = Admins.find_all(class_="ipsGrid_span3")
    Admin_dict = {}
    for i in Adm_list:
        print(i.strong.text, i.a["href"])
        Admin_dict[i.strong.text] = i.a["href"]

    with open("Admin_list.json", "w", encoding="utf-8") as jfile:
        json.dump(Admin_dict, jfile, indent=1, ensure_ascii=False)
```
### Чтение Json файла
```
    with open("Admin_list.json", "r", encoding="utf-8") as jfile:
        Admin_list = json.load(jfile)
```
### Чтение страницы Json при парсинге
Некоторые запросы возвращают страницу со словарём, его можно считывать при помощи .json

```
    url = r'https://ru.pinterest.com/resource/UserExperienceResource/get/?source_url=%2Fpahitocialoni%2F_created%2F&data=%7B%22...'
    r = requests.get(url=url, headers=headers).json()
    print(r["resource_response"])
```
 
<a name="OS"></a>
## OS
`import os`
<a name="Создание_и_удаление_папки"></a>
### Создание и удаление папки
**mkdir()** / **rmdir()**  
(удаляются только пустые папки, для удаления папки с содержащим - `shutil.rmtree(tmp_dir)`)  
Указывается относительный или абсолютный путь.<br>
Происходит удаление только пустых папок.
```
    os.mkdir(r'D:\Documents\Папка 1')
    
    os.rmdir(r'D:\Documents\Папка 1')
```
### Переименование файла
Файл с новым названием сохраняется во второй путь, если указать просто new.txt, то файл будет перемещён в папку с проектом<br>
`os.rename(r'D:\Documents\file.txt', r'D:\Documents\new.txt')`
### Удаление файла
`os.remove('file.txt')`
### Проверка файла на существование
`print(os.path.exists(r'D:\Documents\file.txt')) # False`

**Перемещение файлов**  
`shutil.move(f"{tmp_dir}/{f}", f"{Dir}/{f}")`


<a name="Запуск_закрытие_приложений"></a>
### Запуск/закрытие приложений
```
os.startfile(r'C:\Users\USER\AppData\Local\GameCenter\GameCenter.exe')

os.system("taskkill /f /im GameCenter.exe")
```
При запуске **python приложений** иногда нужно указывать рабочую папку перед os.startfile: `os.chdir(work_dir)`

<a name="Просмотр_списка_файлов_в_папки"></a>
### Просмотр списка файлов в папки
`os.listdir("Admins/")`

<a name="Работа_с_zip_файлами_zipfile"></a>
### Работа с zip-файлами. zipfile
Для работы с zip файлами представлен класс ZipFile в модуле zipfile:<br>
`ZipFile(file, mode='r', compression=ZIP_STORED, allowZip64=True, compresslevel=None, *, strict_timestamps=True, metadata_encoding=None)`<br>
- **file** - путь к zip файлу
- **mode**: **r** для чтения файла, **w** для записи нового файла, **a** для добавления в файл
- **compression** - тип сжатия
  - ZIP_STORED - архивация без сжатия (по умолчанию)
  - ZIP_DEFLATED - стандартный тип сжатия zip
  - ZIP_BZIP2 - сжатие методом BZIP2
  - ZIP_LZMA - сжатие методом LZMA
- **allowZip64** - если True, то zip файл может быть меньше 4 Гб
- **compresslevel** - уровень сжатия, применяется только к ZIP_DEFLATED (0-9) и ZIP_BZIP2 (1-9)
- **strict_timestamps** - при значении False позволяет работать с zip файлами, созданными ранее 01.01.1980 и позже 31.12.2107
- **metadata_encoding** - применяется для декодирования метаданных
<br>

Методы класса ZipFile:
- **close** - закрывает zip файл
- **getinfo** - возвращает информацию об одном файле в виде объекта ZipInfo
- **namelist** - возвращает список файлов в архиве
- **infolist** - возвращает информацию обо всех файлах в архиве в виде объекта ZipInfo
- **open** - открывает zip файл
- **read** - считывает файл из архива в набор байтов
- **extract** - извлекает из архива один файл
- **extractall** - извлекает из архива все файлы
- **setpassword** - устанавливает пароль для zip файла
- **printdir** - выводит на консоль содержимое архива

<a name="Запись_файлов_в_zip_архив"></a>
### Запись файлов в zip архив
`write(filename, arcname=None, compress_type=None, compresslevel=None)`<br>

**arcname** - устанавливает название для файла. По умолчанию это название самого файла.<br>
При попытки записать файл с повторяющимся названием программа выдаст ошибку, но можно указать уникальное название вторым аргументом.
```
    with ZipFile('Archive.zip', 'w') as archive:
        archive.write('file.txt', 'file_1.txt')
        archive.write('file.txt', 'file_2.txt')
```
По умолчанию сжатие не применяется, можно указать его вручную:
```
    from zipfile import ZipFile, ZIP_DEFLATED

    with ZipFile('Archive.zip', 'w', compression=ZIP_DEFLATED, compresslevel=3) as archive:
        archive.write('file.txt')
```
<a name="Получение_информации_о_файлах_в_архиве"></a>
### Получение информации о файлах в архиве
**infolist** возвращает объекты **Zipinfo**<br>
Основные атрибуты Zipinfo:
- **filename** - название файла
- **date_time** - дата и время последнего изменения файла
- **compress_type** - тип сжатия
- **compress_size** - размер после сжатия
- **file_size** - размер до сжатия
```
    with ZipFile('Archive.zip', 'r') as archive:
        for i in archive.infolist():
            print(i)    # <ZipInfo filename='file.txt' compress_type=deflate filemode='-rw-rw-rw-' file_size=476 compress_size=264>
            print(i.filename, i.compress_type, i.file_size, i.compress_size) # file.txt 8 476 264
```
Если нужно узнать только имена файлов, то можно применить `archive.namelist()`<br>
С помощью метода **is_dir** можно узнать, является ли эдемент папкой.<br>
Можно получить информацию по отдельным файлам:
```
        info = archive.getinfo('img.jpg')
        print(info.file_size)
```

<a name="Извлечение_файлов_из_архива"></a>
### Извлечение файлов из архива
Для извлечения всех файлов из архива используется `extractall(path=None, members=None, pwd=None)`
- **path** - каталог для извлечения содержащегося архива
- **members** - список файлов, которые нужно извлечь
- **pwd** - пароль, если архив закрыт

Извлечение файлов в папку /Archive (папка создаётся автоматически):<br>

`archive.extractall(path='Archive')` 
 
Извлечение одного файла: `archive.extract('img.jpg')`

Извлечение файлов из **.rar** `pip install aspose-zip`:
```
  import aspose.zip as az

  with az.rar.RarArchive(path_to_file) as archive:
      archive.extract_to_directory(Dir)
```

### Считывание файла
**read** позволяет считать содержимое файла из архива а набор байтов (русские буквы отображаются как \xd0)

`print(archive.read('file.txt'))`
### Открытие файла
Метод **open** позволяет открывать файлы без их извлечения<br>
`open(name, mode='r', pwd=None, *, force_zip64=False)`

Создание нового файла в архиве, добавление в него текста:
```
    with ZipFile('Archive.zip', 'w') as archive:
        with archive.open('file.txt', 'w') as file:
            encoding = bytes('Тест.', 'UTF-8')
            file.write(encoding)
```

<a name="datetime"></a>
## datetime
`import datetime`
### date
```
    form datetime import date

    date = datetime.date(2018, 4, 15)
    print(date)     # 2024-03-31
    today = datetime.date.today()
    print('{}.{}.{}'.format(today.day, today.month, today.year))    # 31.3.2024
```
### time
```
    form datetime import time

    Time = datetime.time()
    print(Time) # 00:00:00
    Time = datetime.time(15, 5, 34)
    print(Time) # 15:05:34
```
### datetime
`datetime(year, month, day [, hour] [, min] [, sec] [, microsec])`<br>
Первые 3 параметра обязательные
```
    form datetime import datetime
    
    dt = datetime(2020, 12, 30, 7)
    print(dt)   # 2020-12-30 07:00:00
    
    dt = datetime.now()
    print(dt.date()) # 2024-03-31
    print(dt.time()) # 15:14:56.447161
```
<a name="Преобразование_строки_в_дату_strptime"></a>
### Преобразование строки в дату. strptime
Преобразование строки в дату.<br>
Для этого используются специальные коды:
- **%d** - день
- **%m** - месяц
- **%y** - год в виде 2х чисел
- **%Y** - год в виде 4х чисел
- **%H** - часы, 24-х часовой формат
- **%M** - минуты
- **%S** - секунды
```
    date = datetime.strptime('15:41 - 31.03.24', '%H:%M - %d.%m.%y')
    print(date)      # 2024-03-31 15:41:00
    print(date.year) # 2024
```
<a name="Форматирование_даты_и_времени"></a>
### Форматирование даты и времени
Коды для форматирования:
- **%a** - день недели сокращённо (Wed)
- **%A** - день недели полностью (Wednesday)
- **%b** - название месяца сокращённо (Oct)
- **%B** - название месяца полностью (October)
- **%d** - номер дня, дополненный нулём (03)
- **%m** - номер месяца, дополненный нулём (09)
- **%y** - год в виде 2х чисел
- **%Y** - год в виде 4х чисел
- **%H** - час, 24-х часовой формат
- **%h** - час, 12-х часовой формат
- **%M** - минута
- **%S** - секунда
- **%f** - микросекунда
- **%p** - AM/PM
- **%c** - дата и время, отформированные под текущую языкавую среду
- **%x** - дата, отформированная под текущую локаль
- **%X** - время, отформированное под текущую локаль

```
    locale.setlocale(locale.LC_ALL, "ru")

    date = datetime.now()
    print(date.strftime('%H:%M %A, %d %b %Y г.')) # 16:20 воскресенье, 31 мар 2024 г.
    print(date.strftime('%c')) # 31.03.2024 16:21:44
```
<a name="Операции_со_временем_timedelta"></a>
### Операции со временем timedelta
`from datetime import timedelta`

Можно отдельно задать период времени:<br>
`timedelta([days] [, seconds] [, microseconds] [, milliseconds] [, minutes] [, hours] [, weeks])`
```
    Time_1 = timedelta(2, hours=12)
    Time_2 = timedelta(hours=20)
    print(Time_1 - Time_2)  # 1 day, 16:00:00
    
    date_now = datetime.now()
    print(date_now - Time_2)    # 2024-03-30 20:32:44.594082 
```
timedelta имеет несколько свойств (days, seconds, microseconds) и метод, возвращаемый общее кол-во секунд total_seconds()
```
    Time_1 = timedelta(2, hours=12) - timedelta(hours=20)

    print(Time_1.days, Time_1.seconds, Time_1.microseconds) # 1 57600 0
    print(Time_1.total_seconds())   # 144000.0
```
Также время можно сравнивать:
```
    date_now = datetime.now()
    date_2 = datetime(2024, 3, 31, 16, 48)
    print(date_now < date_2) # True
```

<a name="multiprocessing_Pool"></a>
### multiprocessing Pool
`from multiprocessing import Pool`

Объявляется объект Pool для запуска нескольких процессов одновременно, у него передаётся 
параметр processes, отвечающий за максимальное кол-во одновременно запущенных процессов.<br>
```
    urls = ['https://www.otohits.net/', 'https://qiwi.com/', 'https://www.jetswap.com/']
    p = Pool(processes=3)
    p.map(Start_url, urls)
```
В данном примете запускается функция Start_url для кадого из объектов в списке urls, если 
объектов больше, чем указано процессов, то программа будет ждать пока освободится место для 
следующего объекта в очереди
```
p = multiprocessing.Process(target=func, args=(a, b,))
p.start()
p.join()
```
В скомпилированных приложениях с PyQT при запуске нескольких функций могут открываться 
несколько окон. Исправление ошибки:
```
import multiprocessing as mp

mp.freeze_support()

class ...
  with (mp.Pool(processes=3)) as p:
      p.map(LoadMulti, fls)
```


<a name="Итераторы_и_генераторы"></a>
### Итераторы и генераторы
Итераторы проходят по всем элементам, без возможности вернуться к выданным элементам после.
```
    n = [1,2,3,4]
    n2 = iter(n)
    print(next(n2)) # 1
    print(next(n2)) # 2
    print(list(n2)) # [3, 4]
```
Когда элементы кончаются генерируется исключение StopIteration. Программа - аналог for:
```
    n = [1,2,3,4]
    n_iter = iter(n)
    while True:
        try:
            x = next(n_iter)
        except StopIteration:
            break
        else:
            print(x)
```
### Выражения-генераторы
```
    g = (i*2 for i in range(1, 4))
    print(list(g))  # [2, 4, 6]
    print(list(g))  # []
```
Переменная n не будет хранить в себе все элементы сразу, поэтому код будет запускаться быстро.
```
    n = (i for i in range(1000000000))
    for i in n:
        print(i)
```
**Функция генератор.** Замораживает выполнение функции на операторе yield
```
def gen(x):
    for i in range(x):
        yield i**2
        print('next', end=' ')
def main():
    pow = gen(5)
    print(next(pow)) # 0
    print(next(pow)) # next 1
```

<a name="Тесты_doctest"></a>
### Тесты doctest
`import doctest`
```
def div(a, b):
    '''
    Функция делит a на b

    >>> div(6, 3)
    2.0
    >>> div(0, 2)
    0
    '''
    if a == 0 or b == 0:
        return None
    return a / b

def main():
    doctest.testmod(verbose=True)
```
Тесты выполняются и без вызова функции

verbose=True - для отображения всей информации о тестах<br>
verbose=False (или пустой параметр у testmod) - будут отображаться только ошибки 

<a name="Логирование_logging"></a>
### Логирование logging
```
import logging

logger = logging.getLogger(__name__)
logging.basicConfig(level=logging.INFO)

logger.debug('deb')
logger.info('inf')
logger.warning('war')
logger.error('err')
logger.critical('crt')
```
В уровне указывается от какого уровня и ниже отображать логи

Конфигурацию лучше вынести в отдельный модуль и вызвать в запускаемом файле:
```
def configure_logging(level=logging.INFO):
    logging.basicConfig(level=level, datefmt="%Y-%m-%d %H:%M:%S", 
    format="[%(asctime)s] %(module)10s:%(levelname)s - %(message)s")
```
можно указать кол-во дополнительных пробелов, например %(module)**10**s

**Логирование ошибок**  
Для вызовать Traceback:
```
    try:
        print(1 / 0)
    except Exception as e:
        logger.error('main for error', exc_info=e)
```
или `exc_info=True`  

Запись логов в файл, установка максимального размера файла:
```
logger = logging.getLogger(__name__)
log_format = logging.Formatter("[%(asctime)s] %(module)8s:%(levelname)s - %(message)s", 
                                datefmt="%Y-%m-%d %H:%M:%S")
handler = RotatingFileHandler('logs.log', maxBytes=20*1024*1024, backupCount=2)
handler.setFormatter(log_format)
logger.setLevel(logging.INFO)
logger.addHandler(handler)

logger.info('инфо')
```

<a name="Логирование_при_multiprocessing_свой_уровень_логирования_logging"></a>
### Логирование при multiprocessing, свой уровень логирования
```
import multiprocessing as mp

mp.freeze_support()

logger = mp.get_logger()
logger.setLevel(21)
formater = logging.Formatter("[%(asctime)s] %(module)7s: %(message)s", datefmt="%Y-%m-%d %H:%M:%S")
# Логи в виде файла
f_handler = RotatingFileHandler('logs.log', maxBytes=20 * 1024 * 1024, backupCount=2, errors='ignore',)
f_handler.setFormatter(formater)
# Логи в консоли
s_handler = logging.StreamHandler()
s_handler.setFormatter(formater)

logger.addHandler(f_handler)
logger.addHandler(s_handler)

class Logs:
    def __init__(self, l):
        self.logget = l

    def add(self, text:str):
        self.logget.log(21, f"{text}")

    def error(self, exc, er_text):
        self.logget.error(f"{er_text}", exc_info=exc)
```


<a name="ООП"></a>
# ООП
___
### Атрибуты класса
**Общие** атрибуты класса (любой объект класса будет ссылаться на один и тот же объект):
```
    u = Unit()
    u2 = Unit()
    Unit.hp = 90
    print(u.hp, u2.hp) # 90 90
```
Динамическая установка нового атрибута: `setattr(Unit, 'armor', 2)`<br>
Установка новго атрибута для объекта класса: `u.mana = 50`<br>
Получение атрибута через getattr (если атребута не существется, вернется третий агрумент):<br>
`getattr(Unit, 'armor', -1)`<br>
Проверка на наличие атрибута: `hasattr(Unit, 'hp')`<br>
Удаление атрибута: `del Unit.hp` или `delattr(Unit, 'hp')`<br>

<a name="Конструктор"></a>
### Конструктор
Функция `__init__(self)` является конструктором<br>
После создания объекта класса можно динамически добавлять к нему новые переменные
```
class url:
    def __init__(self, address, description=''):
        self.address = address
        self.description = description

def main():

    url_1 = url('https://forum.com/stuff', 'Форум')
    url_1.note = 'reports dont work'
    print(url_1.note)
```

<a name="Деструктор"></a>
### Деструктор
Деструктор `__del(self)__` вызывается при удалении объекта, интерпретатор автоматически определяет, когда удалять объект
```
class url:
    def __init__(self, address, description=''):
        self.address = address
        self.description = description
        print(f'Создана ссылка: {self.address} {self.description}.')

    def __del__(self):
        print(f'Объект url ({self.address}) удалён.')
def create_url():
    url_1 = url('https://forum.com/stuff', 'Форум')
def main():
    create_url()
    print('Конец программы.')
    
# Создана ссылка: https://forum.com/stuff Форум.
# Объект url (https://forum.com/stuff) удалён.
# Конец программы.
```
В данном примере объект url создается в функции create_url(), поэтому жизнь этого объекта ограничена областью функции.

<a name="Приватные_атрибуты"></a>
### Приватные атрибуты
Введение. **Инкапсуляция** - концепция ооп, которая предполагает скрытие функционала и предотвращение прямого доступа к нему.<br>
Приватные атрибуты: `self.__info`<br>
К приватному атрибуту можно обратиться вне класса через `_ClassName__info`
```
class url:
    def __init__(self, address, description=''):
        self.__address = address
        self.__description = description
    def print_url(self):
        print(self.__address)

def main():
    url_1 = url('https://forum.com/stuff', 'Форум')
    url_1.__address = 0
    url_1.print_url()       # https://forum.com/stuff
    print(url_1.__address)  # 0

    url_1._url__address = 0
    url_1.print_url()       # 0
```
При обращении `url_1.__address` создается новая переменная `__address`, вместо нужной `_url__address`

<a name="Аннотации_свойств_Геттеры_и_сеттеры"></a>
### Аннотации свойств. Геттеры и сеттеры
Для создания свойства-геттера над свойством ставится аннотация @property<br>
Для сеттера - @имя_свойства_геттера.setter<br>
Так же можно прописать deleter<br>
**Сеттер определяется после геттера**
```
class Unit:
    def __init__(self, name, hp):
        self.__name = name
        self.__hp = hp

    @property
    def hp(self):
        return self.__hp
    @hp.setter
    def hp(self, hp):
        self.__hp -= hp
    @hp.deleter
    def hp(self):
        del self.__hp

def main():
    Builder = Unit('Builder', 30)
    Builder.hp = 10
    print(Builder.hp)
```

<a name="Наследование"></a>
### Наследование
Наследование имеет вид: `class Battler(Unit):`<br>
Дочерний элемент не видит приватные атрибуты родителя.<br>
```
class Unit:
    def __init__(self, name, hp):
        self.name = name
        self.__hp = hp

    @property
    def hp(self):
        return self.__hp

    def TakeDamage(self, dmg):
        self.__hp -= dmg
        if self.__hp > 0:
            print(self.name + "`s hp is", self.__hp)
        else:
            print(self.name, 'is dead')

class Battler(Unit):
    damage = 20
    def Hit(self, Unit):
        Unit.TakeDamage(self.damage)
```
Множественное наследование:
```
class Unit:
    def __init__(self, name, hp):
        self.name = name
        self._hp = hp
    def Go(self):
        print('Unit goes')
    def print_info(self):
        print(f'{self.name}, {self._hp}')

class Seller:
    def __init__(self, name, hp, shop_type):
        self.name = name
        self._hp = hp
        self.shop_type = shop_type
    def print_info(self):
        print(f'{self.name}, {self._hp}, Sell: {self.shop_type}')

class Character(Unit, Seller):
    def __init__(self, *args):
        Seller.__init__(self, *args)
    def print_info(self):
        Seller.print_info(self)

def main():
    Sam = Character("Sam", 20, 'Armor')
    Sam.print_info()     # Sam, 20, Sell: Armor
    Unit.print_info(Sam) # Sam, 20
    print(Character.__mro__) # (<class '__main__.Character'>, <class '__main__.Unit'>, <class '__main__.Seller'>, <class 'object'>)
```
Если родительские классы имеют одинаковые методы, то вызовется метод первого родителя.<br>
Порядок вызова можно узнать через class.mro() или аналогичный магический метод

<a name="Переопределение_методов"></a>
### Переопределение методов
```
class Unit:
    def __init__(self, name, hp):
        self.name = name
        self.hp = hp
        
    def PrintInfo(self):
        print(self.name, 'Health:', self.hp)


class Battler(Unit):
    def __init__(self, name, hp, damage):
        super().__init__(name, hp)
        self.damage = damage
        
    def PrintInfo(self):
        super().PrintInfo()
        print("Damage:", self.damage)
```

<a name="Статические_методы"></a>
### Статические методы
Для объявления статических методов используется аннтоация @staticmethod<br>
Если в агрументах статического метода есть self, то его необходимо передать.
```
class url:
    protocol = 'http'
    @staticmethod
    def PrintProtocil():
        print(url.protocol)

def main():
    url_1 = url()
    url_2 = url()
    url.protocol = 'https'    # protocol изменен у url_1 и url_2
    url_1.PrintProtocil()
```
При изменении атрибутов класса напрямую, меняется информация во всех экземплярах класса.

<a name="Строковое_представление_объекта"></a>
### Строковое представление объекта (класс object)
С 3 версии языка Python все классы неявно наследуют все методы у класса object.<br>
Один из этих методов - `__str__()`, он выводит объект в виде строки (`<__main__.url object at 0x000001DA32EAD520>`).<br>
Данный метод можно переопределить, но он должен всегда возвращать строку:
```
class url:
    def __init__(self, address, description):
        self.address = address
        self.description = description

    def __str__(self):
        return f'{self.address}, {self.description}'

def main():
    url_1 = url('forum.com', 'Форум')
    print(url_1)
```

<a name="Перегрузка_операторов"></a>
### Перегрузка операторов
Переопределение встроенных операторов сложения, вычитания и т.д.<br>
Существует множество операторов: Сложение `__add__(a, b)`, объединение: `__concat__(a, b)`,<br>
< - `__lt__()`, > - `__gt__()`...<br>
Возвращаемый тип ряда операторов жестко не опрелён.<br>
Add:
```
class Balance:
    gold = 0
    silver = 0
    copper = 0
    def __init__(self, gold, silver, copper):
        self.gold = gold
        self.silver = silver
        self.copper = copper
    def __add__(self, other):
        self.copper += other.copper
        if self.copper >= 100:
            self.silver += 1
            self.copper -= 100
        self.silver += other.silver
        if self.silver >= 100:
            self.gold += 1
            self.silver -= 100
        self.gold += other.gold
        return 'G:',self.gold, ' S:', self.silver, ' C:', self.copper

def main():
    B1 = Balance(1, 52, 77)
    B2 = Balance(5, 88, 45)
    print(B1 + B2)
```
Bool:
```
    ...
    def __bool__(self):
        if self.gold >= 2:
            return True
        return False

def main():
    B1 = Balance(5, 51, 77)
    while B1:
        print('Buy')
        B1.gold -= 2
    else:
        print('You do not have enough money')
```
Обращение по индексу:
```
    ...
    def __getitem__(self, item):
        if item == 0: return f'G: {self.__gold}'
        elif item == 1: return f'S: {self.__silver}'
        elif item == 2: return f'C: {self.__copper}'

def main():
    B1 = Balance(5, 51, 77)
    print(B1[2])
```
in:
```
    ...
    def __contains__(self, item):
        if item == 'gold' and self.__gold > 0: return True
        if item == 'silver' and self.__silver > 0: return True
        if item == 'copper' and self.__copper > 0: return True
        return False

def main():
    B1 = Balance(5, 0, 77)
    print('silver' in B1)
```
Парные операторы:
```
    # __eq__, __ne__
    # __gt__, __le__
    # __lt__, __ge__
    
    ...
    def __eq__(self, other):
        if self.gold == other.gold and self.silver == other.silver and self.copper == other.copper: return True
        return False
    def __ne__(self, other):
        return not self.__eq__(other)

def main():
    B1 = Balance(1, 15, 75)
    B2 = Balance(5, 88, 45)
    print(B1 != B2)
```

<a name="Абстрактные_классы"></a>
### Абстрактные классы
В Python инструменты для создания абстрактных классов находятся в модуле **abc**<br>
`import abc`<br>
Абстрактные классы наследуются от **abc.ABC**, абстрактные методы имеют аннотацию **@abc.abstractmethod**<br>
Дочерние классы должны реализовывать все абстрактные методы
```
import abc

class Unit(abc.ABC):
    def __init__(self, name, hp, damage):
        self.name = name
        self.hp = hp
        self.damage = damage

    @abc.abstractmethod
    def Attack(self): pass

class Battler(Unit):
    def Attack(self):
        print(f'Deal area damage ({self.damage})')

class Archer(Unit):
    def Attack(self):
        print(f'Hit the target ({self.damage})')
```
### Класс-декоратор
```
class CheckLower:
    def __init__(self, func):
        self.__func = func
    def __call__(self, s, *args, **kwargs):
        return self.__func(s).lower() if isinstance(s, str) else None

@CheckLower
def get_domen(s: str):
    return s.split('.')[0].split('//')[-1]

def main():
    print(get_domen('https://Site.com'))
```

<a name="Методы_классов"></a>
### Методы классов
`__dict__` - выводит информацию об атрибутах класса
```
  print(Unit.__dict__)
  # {'__module__': '__main__', 'hp': 100, 'dmg': 10, '__dict__': <attribute '__dict__' of 'Unit' objects>,
  # '__weakref__': <attribute '__weakref__' of 'Unit' objects>, '__doc__': None}
```
`__doc__` - вывод документации <br>
`__new__` - вызывается до создания объекта класса<br>
`__getattribute__` - вызывается, когда происходит обращение к атрибутам класса
```
        def __getattribute__(self, item):
        if item == 'hp':
            print('error')
            return None
        return object.__getattribute__(self, item)

  u = Unit(15, 2)
  print(u.hp) # error; None
```
`__setattr__` - вызывается при установке значения атрибуту
```
    def __setattr__(self, key, value):
        object.__setattr__(self, key, value)
```
`__getattr__` - вызывается при обращении к несуществующему атрибуту<br>
`__delattr__` - вызывается при удалении атрибута
```
    def __delattr__(self, item):
        object.__delattr__(self, item)
```
`__set__(self, instance, value)` - сеттер для дескриптеров<br>
`__get__(self, instance, owner)` - геттер для дескриптеров<br>
`__call__(self, *args, **kwargs)` - срабатывает при вызове класса, например, Person()<br>
`__str__` - вызывается, если напечатать класс в print/str<br>
`__repr__` - вызывается, если напечатать класс в print/str (для разработчиков)<br>
`__len__` - len(), ещё вызывается функцией bool() если не определён магический метод bool<br>
`__bool__` - вызывается при использования класса в условных операторах и при функции bool()<br>
`__abs__` - abs()

`__add__` - операция сложения: class + ... <br>
`__radd__` - операция сложения: ... + class <br>
`__iadd__` - операция сложения: class += ... <br>
По аналогии: sub (-), mul (*), truediv (/), floordiv (//), mod (%)<br>

`__hash__` - вызывается при попытки взять хэш объекта (если в классе есть магический меотд eq, то простой вызов hash() от объекта вызовет ошибку, поэтому необходимо переопределять маг. метод hash)<br>
`__getitem__` - позволяет обратиться к объекту по индексу `class[i]`<br>
`__setitem__` - для `class[i] = x`<br>
`__delitem__` - для `dell class[i]`<br>
`__iter__` - получение итератора<br>
`__next__` - переход к след. знаечнию<br>


**@classmethod**. Не работает с локальными атрибутами класса
```
class Unit:
    x_min = 0
    x_max = 20
    @classmethod
    def check_coords(cls, x):
        return cls.x_min < x < cls.x_max
        
    def main():
        print(Unit.check_coords(10))
```
**@staticmethod**. Не работает с атрибутами класса 
```
    @staticmethod
    def pow2(x):
        return x*x
```

`dir(class)` - просмотр всех свойств класса/метода/функции<br>
`getattr(class, value_str)` - возвращает значение атрибута класса<br>
`setattr(class, value_str, value)` - устанавливает значение value для атрибута класса<br>
`issubclass(class1, class2)` - проверка - является ли class1 подклассом class2<br>  


Паттерн моносостояние:
```
  class Unit:
    __atr = {}
    
    def __init__(self, hp, dmg):
        self.__dict__ = self.__atr
```
Создаёт общую ссылку на словарь атрибутов. Все объекты класса становтся одинаковы

В коллекцию `__slots__` добавляются все допустимые **локальные** свойства класса, блокирует создание новых свойств.
Если использовать данную коллекцию, то `__dict__` не будет создан. В самом классе можно создавать любые атрибуты.<br>
При использовании данной коллекции будет занято меньше памяти и методы класса будут работать быстрее.
```
class Money2:
    __slots__ = ('usd')
    UDSRUB = 93
```


<a name="Дополнительные_модули"></a>
# Дополнительные модули
<a name="NumPy"></a>
# NumPy
`pip install numpy`  
`import numpy as np`  
<a name="np_Создание_массива"></a>
## Создание массива
```
  a = np.array([1,2,3])
  print(a.dtype)      # int64
```
Можно задать **тип элементов** массива при его объявлении: `a = np.array([1, 2, 3, 4], 'float64')`  
Изменить тип массива: `a = np.float64(a)`  
Если данные в массиве разных типов, всё приводится под один тип, например, str (<U21)  
Вывод элементов по их индексам:
```
  a = np.array([1, 2, 3])
  print(a[ [1,1,1] ])     # [2 2 2]
```
Выводит элементы, где указано значение True:
```
  a = np.array([1, 2, 3, 4, 5])
  print(a[ [True, False, True, True, False] ])    # [1 3 4]
```
Изменение формата массива, например, из одномерного в двумерный:
```
  a = np.array([1, 2, 3, 4])
  a = a.reshape(2, 2)
  [[1 2]
   [3 4]]
```

**empty** создает массив заполняя его произвольными данными:
```
np.empty((3, 2), dtype='int16')
[[24864 28448]
 [25966 25645]
 [28009 28261]]
```
**eye** создает массив из нулей и единиц на главной диагонали:
```
np.eye(3, 2)
[[1. 0.]
 [0. 1.]
 [0. 0.]]
```
или создаёт квадратную матрицу при указании одного параметра  
**identity** создает квадратную матрицу с единицами на главной диагонали  
**zeros** создаёт матрицу указанного размера, заполняя её нулями  
**ones** заполняет матрицу единицами  
**full** заполняет матрицу указанными значениями: `np.full((3,2), 12)`

**asmatrix** создаёт матрицу из строки:  
`np.asmatrix('1 2 3 4')   # [[1 2 3 4]]`  
```
np.asmatrix('1, 2; 3, 4')
[[1 2]
 [3 4]]
```
**diag** создаёт матрицу с указанными элементыми на главной диагонали:
```
np.diag([1,2])
[[1 0]
 [0 2]]
```
или выводит главную диагональ матрицы:
```
np.diag([[1,2], [3,4]])
[1 4]
```
**diagflat** принимает матрицу как единый список и строит из нее новую матрицу:
```
np.diagflat([[1,2], [3,4]])
[[1 0 0 0]
 [0 2 0 0]
 [0 0 3 0]
 [0 0 0 4]]
```
**trace** - вывод суммы главной диагонали
**tri** создаёт матрицу, разбирую главной диагональю на треугольники:
```
np.tri(3)
[[1. 0. 0.]
 [1. 1. 0.]
 [1. 1. 1.]]
```
**tril** приводит матрицу к треугольному виду (элементы над гл. диагональю - 0):
```
np.tril([(1,2,3), (4,5,6), (7,8,9)])
[[1 0 0]
 [4 5 0]
 [7 8 9]]
```
Можно сформировать матрицу на основе одномерного массива:
```
np.tril([1,2,3])
[[1 0 0]
 [1 2 0]
 [1 2 3]]
```
**triu** - обратный эффект от tril (гл. диагональ сохраняется)  
**vander** создаёт матрицу Вандермонда:
```
np.vander([1,2,3])
[[1 1 1]
 [4 2 1]
 [9 3 1]]
```
**tile** - повторение элементов
```
np.tile([[1,0],[0,1]], (2,3))
# [[1 0 1 0 1 0]
#  [0 1 0 1 0 1]
#  [1 0 1 0 1 0]
#  [0 1 0 1 0 1]]
```
**repeat** повторение элементов масива
```
a = np.repeat(2,4) # [2 2 2 2]
a = np.array([[1,3], [2,4]])
print(np.repeat(a, 2)) # [1 1 3 3 2 2 4 4]
print(np.repeat(a, [1, 2], axis=0))
# [[1 3]
#  [2 4]
#  [2 4]]
```
**arange** - аналог range  
**linspace** делит массив на равные части: `np.linspace(0, 7, 3)   # [0.  3.5 7. ]`  
**logspace** аналог linspace, но считает log от start и stop    
**geomspace** выстраивает геометрическую прогрессию:
```
np.geomspace(1, 8, 4)   # [1. 2. 4. 8.]
np.geomspace(1, 8, 3)   # [1. 2.82842712 8.]
```
**copy** создание копии массива `b = np.copy(a)`  
**fromfunction** формирует массив на основе функции (или lambda) в аргументы подставляются индексы массива
```
def GetValue(x, y):
    return x+y*x

a = np.fromfunction(GetValue, (3, 3))
[[0. 0. 0.]
 [1. 2. 3.]
 [2. 4. 6.]]
```
или
`np.fromfunction(lambda x, y: x+y*x, [2, 2])`  
**fromiter** итерирует переданный объект и создаёт из него массив:  
`np.fromiter("asd", dtype='<U1')  # ['a' 's' 'd']`  
можно передавать 
**fromstring** формирует массив из строки, можно задать сепаратор
`np.fromstring("1-2-3", dtype='int16', sep='-')  # [1 2 3]`

Можно узнать тип переменных в массиве / его размер (`a.dtype` / `a.size`)  
Поменять тип переменных - `a.dtype = np.float64()`  
Выводит кол-во байт в одном элементе массива `a.itemsize`    
Кол-во осей - `a.ndim` (двумерный массив - 2)  
Узнать / задать размеры массива - `a.shape` (2x3x4 = 6x4 = 24x1)  
Транспонирование матрицы (столбцы становятся строками): `a.T`  
```
[[1 2]
 [3 4]
 [5 6]]
 
[[1 3 5]
 [2 4 6]]
```

<a name="np_Удаление_элементов_из_массива"></a>
## Удаление элементов из массива  
`arr = np.delete(arr, (1))` - удаление второго элемента  
**Удаление** элементов из **двумерного** массива:  
```
arr = np.array([1,2,3,4,5,6]).reshape(3, 2)
arr = np.delete(arr, [0,2], axis=0)   # удаление первой и третьей строки
```
**axis=0** - удаление строки в двумерном массиве  
**axis=1** - удаление столбца в двумерном массиве 

<a name="np_Представление_массивов"></a>
## Представление массивов
Оба массива изменят свою форму:
```
  a = np.array(([1,2,3,4,0,9,8,7]))
  b = a
  a.shape = 2, 4
```
С помощью **view/copy** можно зафиксировать(скопировать) представление:
```
  b = a.view()  # или copy()
  a.shape = 2, 4
```
Тогда массив a будет 2x4, но массив b останется 1x8

-1 в **reshape** подгоняет автоматически количество столбцов/строк
```
a = np.arange(6)
a.reshape(-1,2) # матрица 3 на 2
```
или `a.shape = -1, 2`

`a.shape = -1` выводит элемента массива в список (1 строка * n элементов)

Изменение размета матрицы:  
`a.resize(2, 3)` - меняет кол-во строк/столбцов в массиве (число должно быть равно количеству элементов)  
`a.resize(3, 3, refcheck=False)` флаг **refcheck** позволяет менять размер массива как угодно, подставляя на пустые элементы 0

Чтобы транспонировать одномерный массив нужно сначала создать из него двумерный:
```
a = np.arange(6)  # [0 1 2 3 4 5]
a.shape = 1, -1
a = a.T           
# [[0]
# [1]
# [2] ... ]
```

**expand_dims** - добавляет новую ось (меняет представление массива, не создаёт новую матрицу)  
**append** - добавляет элементы в массив  
```
a = np.arange(6)
b = np.arange(9, 3, -1)
b.shape = 1, -1

a = np.expand_dims(a, axis=0)
a = np.append(a, b, axis=0)
```
**delete** - удаление элемента в массиве  
`a = np.delete(a, 0, axis=1)`

**axis=-1** - указывает на последнюю ось

**squeeze** - удаляет оси, где кол-во элементов равно 1   
`a = np.squeeze(a)`  
можно указать ось (axis=0), но если ось будет содержать больше 1 элемента программа выдаст ошибку

Добавление осей с помощью **newaxis**
```
a = np.arange(6)
a = a[: , np.newaxis] # shape: (6, 1)
# [[0]
# [1] ... ]
```
`a = a[np.newaxis, : ] # shape: (1, 6)`

<a name="np_Объединение_разделение_массивов"></a>
## Объединение / разделение массивов
**Объединение** массивов вертикально / горизонитально:
```
a = np.array(([1, 2], [3, 4]))
b = np.array(([5, 6], [7, 8]))

c = np.hstack([a, b]) # (2, 4)
c = np.vstack([a, b]) # (4, 2)
```
**Объединение** массивов как столбцы / строки:  
`c = np.column_stack([a, b])`  
Вариант с **row_stack** устарел, нужно использовать **vstack**

**Объединение многомерных** массивов (выбирается по какой оси axis будет произведено объединение):
```
a = np.arange(8)
b = np.arange(8, 16)
a.resize(2, 2, 2)
b.resize(2, 2, 2)

c = np.concatenate([a, b], axis=2)
```
**Объединение** по первой оси **r_** и по второй оси **c_**:  
`a = np.r_[5:8, 50, np.arange(4), [0, -1]]` - одномерный массив  
`a = np.c_[5:8, np.arange(1,4)]` - массив 3x2

`a = np.c_[[range(4), np.arange(5,9)], [[-1], [-2]]]` - массив 2x5

**Разделение массивов** hsplit и vsplit:
```
a = np.arange(10)
print(np.hsplit(a, 2)) # по горизонтали

a.shape = 10, -1
print(np.vsplit(a, 2)) # по вертикали
```
**array_split** позволяет делить массивы по произвольной оси  
`np.array_split(a, 2, axis=0)`

<a name="np_Срезы_массивов"></a>
## Срезы массивов
Срезы НЕ создают новый массив:
```
a = np.arange(10)
b = a[2] = -1
print(a[2]) # -2
```
Изменение значений у элементов в срезе: `a[-3: -1] = -1` можно присваивать другие и массивы

Получение столбца через срез:
```
a = np.arange(9)
a.resize(3, 3)
print(a[:, 0]) # первый столбец (0, 3, 6)
```
С помощью **flat** можно переберать элементы массива как в одномерном массиве
```
    for i in a.flat:
        print(i, end=' ')
```
Полные срезы можно прописывать как троеточие:  
`a[..., 1]` эквивалент `a[:, :, 1]`

Создание копии среза (указываются индексы элементов в дополнительных квадратных скобках)
```
a = np.arange(9, 0, -1)
b = a[[0, 0, 1, 7]] # [9 9 8 2]
```
При этом **сохраняется форма** в соответсивии со списком индексов (работает только с многомерными массивами numpy в качестве списка индексов)
```
a = np.arange(9, 0, -1)
indx = np.array([[0, 3], [5, 7]])
print(a[indx]) 
# [[9 6]
#  [4 2]]
```

Вывод несколькоих элементов по индкесам [x1, x2], [y1, y2]:  
`print(a[[1, 2],[0, 1]])` выведет a[1, 0] и a[2, 1]

Можно присвоит сразу нескольким элементам новые значения (по индексам):  
`a[[0, 1, 7]] = [-1, -2, -8]`

Вывод элементов, где указано True (длина списка должна быть равна длине массива):
```
a = np.arange(3)
bIndx = [False, True, True]
print(a[bIndx])
```

**Фильтрация элементов**:
```
a = np.arange(4)
cond = a < 2 # [ True  True False False]
print(a[cond]) # [0 1]
```
или проще: `print(a[a < 2])`  
Создается список с булевыми значениями, далее он используется как фильтр  

<a name="np_Математические_операции_над_массивами"></a>
## Математические операции над массивами
К массивам numpy можно применять базовые операции: +, -, *, /, //, %, **  
`a *= 3` в результате это действие будет применено к каждому элементу  
`print(-a) # [ 0 -1 -2]` минус впереди меняет знаки элементов

Математичесике операции можно проводить между массивами, для этого необходимо чтобы
размеры массивов были согласованы, например, 1x3 + 1x3; 1x3 * 2x3; 3x3 * 3x3  
Тип данных при a += b будет выбран более общий

**sum** - сумма `a.sum()`  
**mean** - среднее арифметическое  
**max/min** - максимальное/минимальное значение  
Mожно указать ось по которой будет проводиться операция.  
`a.sum(axis=1)` на выходе получится массив сумм по каждой строке

**negative** изменение знаков в массиве `np.negative(a, out=a)`

Можно передавать число или массив `np.abs(a)` (также можно указывать ось):  
**np.abs** - вычисление модуля  
**np.amax** - максимальное значение  
**np.amin** - минимальное значение  
**np.argmax** - максимальный индекс  
**np.argmin** - минимальный индекс  
**np.around** - округление до ближайшего целого  
**np.mean** - среднее значение  
**np.log**, **np.log2**, **np.log10** - логарифм по основанию x 

**Тригонометрические** функции:  
**np.sin**, **np.cos**, **np.tan**, **np.arccos**, **np.arcsin**, **np.arctan**

**Булевы** операции: ==, !=, >, <, >=, <=. Сравнение происходит по элементам  
```
a = np.array([1,2,3])
b = np.array([1,4,5])
print(a == b) # [ True False False]
```
Для инвертации булевых массивов используется **~**: `print(~(a == b)) # [False  True  True]`


Проверить эквивалентность массивов можно: `np.array_equal(a, b) # True/False`  
Функции **any**/**all** возвращают True/False если удовлетворено одно/все условия.  
`np.any(a == b) # True (проверяется булевый массив [ True False False])`

**inf** и **nan**  
nan никак не изменяется при арифметических операциях и влияет на некоторые расчёты, например при sum    
inf * 0 = nan
```
a = np.array([1, np.nan, np.inf])
a -= 3
print(a) # [-2. nan inf]
print(a.sum()) # nan
```
**np.isinf** проверяет элемент на inf по аналогии с **isnan**    
Функция **isfinite** выбирает только элементы с числовыми значениями

**iscomplex** указывает комплексные числа:  
```
a = np.array([1, 2.6, np.nan, np.inf, 1+4j]) 
print(np.iscomplex(a))# [False False False False  True]
```
**isreal** выбирает действительные числа (даст инфертированный результат iscomplex)

**Логические операции**:
```
a = np.array([1,0,0,-3])
b = np.array([2,4,0,0])

print(np.logical_and(a, b)) # [ True False False False]
print(np.logical_or(a, b))  # [ True  True False  True]
print(np.logical_xor(a, b)) # [False  True False  True]
print(np.logical_not(a))    # [False  True  True  True]
```
Если брать сырой массив, то отрицательные числа будут равны True 

<a name="np_Генерация_случайных_чисел"></a>
## Генерация случайных чисел
**np.random.rand** - `np.random.rand(2) # [0.5655633, 0.43250973]` генерирует массив из случайных элементов от 0 до 1 (не включая 1), можно передать несколько аргументов для генерации двумерного массива  
**np.random.randint** - генерирует целые числа, можно указать диапазон, для создания массива из случайных чисел указывается size=5 или (5,2)    
**np.random.randn** - Гауссовские случайные величины с нулевым математическим ожиданием и единичной дисперсией  
**np.random.beta**, **np.random.pareto** - бета распределение/распределение Порето, можно указать size  

Задать **сид** для генерации случайных чисел:
```
np.random.seed(13)
a = np.random.randint(10, size=10)
```
При одинаковом сиде всегда будут получаться одинаковый набор случайных значений

**np.random.shuffle** - перемешивает элементы в массиве (в двумерном массиве перемешивает строки). Не создаёт копию массива  
**np.random.permutation(x)** - перемешивает x элементов от 0 до x-1  

**np.median** - медианное значение (элементы сортируются по возрастанию, одна половина меньше медианного значения, другая - больше)
```
a = np.array([0, 1, 2, 90, 55, 100])
print(np.median(a)) # 28.5
```
**np.var** - диссперсия случайной величины:  
((x1 - среднее арифм.)^2 + ... + (xn - среднее арифм.)^2) / n
```
a = np.array([1, 2, 3])
print(np.var(a)) # 0.6666666666666666
```

<a name="np_Матричное_умножение"></a>
## Матричное умножение  
`np.dot(a, b)` размеры должны быть согласованы. (a, b) и (b, a) даст разные результаты  
Предпочтительнее использовать не **dot**, а **matmul**  
**dot(a, b)** можно заменить оператором **@**: `a @ b`

**Внутреннее умножение inner**  
```
a = np.arange(3)
b = np.ones(3)
print(np.inner(a, b)) # 3 (можно и через dot)
```
**Внешнее умножение outer**  
```
print(np.outer(a, b))
# [[0. 0. 0.]
#  [1. 1. 1.]
#  [2. 2. 2.]]
```

## Множества
Дано `a = np.array([1, 1, 3, 6, 4, 6])`

**unique** выделяет только уникальные элементы из массива  
`setA = np.unique(a) # [1 3 4 6]`

Параметр **return_counts=True** дополнительно возвращает количество повторений элементов  
`setA = np.unique(a, return_counts=True) # (array([1, 3, 4, 6]), array([2, 1, 1, 2]))`

Параметр **return_index=True** дополнительно возвращает индексы элементов  
`setA = np.unique(a, return_index=True) # (array([1, 3, 4, 6]), array([0, 2, 4, 3]))`

Параметр **return_inverse=True** дополнительно возвращает индексы **всех** элементов  
`setA = np.unique(a, return_inverse=True) # (array([1, 3, 4, 6]), array([0, 0, 1, 3, 2, 3]))`  

Можно восстановить изначальный массив:
```
setA, ret = np.unique(a, return_inverse=True)
print(setA[ret]) # [1 1 3 6 4 6]
```

В двумерном массиве **unique** без параметром тоже вернёт уникальнае значения  
```
a = np.array([[7,3,1], [5,3,1], [7,3,1]])
setA = np.unique(a) # [1 3 5 7]
```

Можно указать ось: `setA = np.unique(a, axis=0) # [[5 3 1], [7 3 1]]`

Дано:
```
a = np.array([1, 2, 3])
b = np.array([0, 1, 3, 5, 7])
```

**isin** вернёт массив указывающий, какие элементы масисвов пересекаются 
`np.isin(a, b) # [ True False  True]`

**intersect1d** - вернёт пересекающиеся элементы массивов  
`np.intersect1d(a, b) # [1 3]`

**union1d** - объединение массивов  
`np.union1d(a, b) # [0 1 2 3 5 7]`

**setdiff1d** - вычитание множеств  
`np.setdiff1d(a, b) # [2]`

**setxor1d** - xor, всё, кроме пересекающихся элементов  
`np.setxor1d(a, b) # [0 2 5 7]`

**np.ix_** - приведение к общему виду (только одномерные массивы)
```
a = np.array([1, 2, 3])
b = np.array([4, 5])
a1, b1 = np.ix_(a, b)
print(a1.shape, b1.shape) # (3, 1), (1, 2)
```

---
Проверка на **равенство** массивов `np.allclose(a,b)`  
Сделать массив **неизменяемым** `a.flags.writeable = False`  
Получить индексы определённых элементов `np.where(a == a.max())`  

Аналог **enumerate**
```
a = np.arange(9).reshape(3,3)
for indx, val in np.ndenumerate(a):
  print(indx, val) # (0, 0) 0 ... (1, 2) 5 ...

for indx in np.ndindex(a.shape):
  print(indx, a[indx]) # (0, 0) 0 ... (1, 2) 5 ...
```
**bincount** повторения для каждого числа (массив длиной 0 : максимальное число в массиве)
```
a = np.array([6,3,3,1,5,3,2])
print(np.bincount(a)) # [0 1 1 3 0 1 1]
```



<a name="Pandas">.</a>
# Pandas
`pip install pandas`  
`import pandas as pd`

Используется 2 основных объекта: **Series** (для одномерных массивов) и **DataFrame**

Для получения данных используются методы, начинающиеся со слова read_ ... (read_csv, read_excel, read_sql и тд)  
Также можно получать данные из словарей в python: pd.DataFrame.from_dict()
```
coins = {'usdt': [1.001, 1.002], 'btc': [94000, 93600]}
df = pd.DataFrame.from_dict(coins)
#     usdt    btc
# 0  1.001  94000
# 1  1.002  93600
```
или `df = pd.DataFrame(coins.items(), columns=['code', 'value'])`

```
coins = {'usdt': 0.999, 'btc': 104000}
df = pd.DataFrame.from_dict(coins, orient='index', columns=['value'])
#            value
# usdt       0.999
# btc   104000.000
```
<a name="Pandas_read_to"></a>
### read_excel
Для этого необходим openpyxl `pip install openpyxl`
```
  import openpyxl

  excl = pd.read_excel(path, sheet_name=sh if sh else 0)
  excl = excl.fillna('')

  for row in excl.values:
    ...
```
Примеры с гибкими настройками:  
`excl = pd.read_excel(path5, usecols=[0,1,2], header=None, skipfooter=0, skiprows=1)`

`table = pd.read_excel(fr"{path_to_catalogs}\Настройки прайса поставщика.xlsx", header=0, nrows=100000, skiprows=range(1,10),
                                  usecols=["Почта", "Код прайса"], sheet_name=0)`  
В skiprows указывается **range** чтобы можно было обращаться к столбцам по имени в usecols

**Ошибка**: There is no item named 'xl/sharedStrings.xml' in the archive  
Решается изменением движка на **calamine** `pip install python-calamine`  
pandas_monkeypatch() в начале кода
```
from python_calamine.pandas import pandas_monkeypatch

pandas_monkeypatch()
table = pd.read_excel(path, usecols=[*cls], skiprows=skipR, engine='calamine')
```

Получение содержимого ячеек  
`excl.loc[i]["17КодУникальности"]` или `ex.loc[3][5]`

Если установлен параметр **header=None**, то к ячейкам можно обращаться:
`ex.loc[3, 5]`

### read_csv
`table = pd.read_csv(path, sep=';', encoding='windows-1251', usecols=[0,1,2], header=None, skipfooter=0, skiprows=1)`

### to_csv
`df.to_csv('coins.csv', sep=';', index=False)`

### read_sql
`df = pd.read_sql(f"SELECT Период_обновления_не_более FROM data07 WHERE Настройка = '{file_name}'", connection_db)`  
pandas рукомендует использовать подключения из SQLAlchemy:  
```
db_url = "postgresql+psycopg2://user:pass@host:5432/db_name"
engine = create_engine(url=db_url, echo=False)

df = pd.read_sql("select * from users", engine)
```

### to_sql
Автоматически определяет лимиты символов в таблицах, заменяет пустые или некорректные строки на (NULL/0)
```
from sqlalchemy import create_engine
db_url = "postgresql+psycopg2://postgres:password@host:5432/db_name"
engine = create_engine(url=db_url, echo=False)

def is_float(x):
    try:
        x = float(str(x).replace(',', '.'))
        if math.isnan(x) or math.isinf(x):
            return False
        if 1E+37 < x < 1E-37: # real
            return False
        return True
    except:
        return False

def get_correct_df(path_to_file, cols, table_name):
    with engine.connect() as sess:
        res = sess.execute(text(f"SELECT column_name, character_maximum_length FROM information_schema.columns WHERE table_name = '{table_name}'")).all()
        for i in res:
            cols[i[0]].append(i[1])

    df = pd.read_excel(path_to_file, usecols=[cols[c][0] for c in cols], na_filter=False)

    df = df.rename(columns={cols[c][0]: c for c in cols})
    for c in cols:
        char_limit = cols[c][1]
        if char_limit:  # str
            df[c] = df[c].apply(lambda x: str(x)[:char_limit] or None)
        else:  # float/int
            df[c] = df[c].replace('', 0)
            df = df[df[c].apply(is_float)]
    return df

if __name__ == '__main__':
    table_name = 'data07'
    cols = {"code": ["Настройка"], "sell_os": ["Продаём для ОС"], "markup_opt": ["Наценка на оптовые товары"],
            "step_opt": ["Шаг опт"]}
    df = get_correct_df("catalog.xlsx", cols, table_name)
    print(df)
    df.to_sql(name=table_name, con=engine, if_exists='append', index=False, index_label=False, chunksize=1000)
```

### Запись данныз из БД в excel
```
import openpyxl

  limit = 10000
  n = 0
  with sq.connect(db_name) as con:
      cur = con.cursor()
      while True:
        try:
              writer = pd.ExcelWriter(path_to_save + 'Результат.xlsx', engine='openpyxl')
              while True:
                  df = pd.read_sql(f"SELECT Ключ1_поставщика, Артикул_поставщика FROM res LIMIT {limit} OFFSET {n}", con)
                  for i in df:
                      df.to_excel(writer, index=False, sheet_name=f'Результат{int(n / limit)}')
                  
                  n += limit
                  if len(df) < limit:
                      break
              writer.close()
              break
          except PermissionError as ex:
              print('Ошибка доступа. Закройте Результат.xlsx')
              print(ex)
              time.sleep(7)
```
В sheet_name можно указать название листа (опционально)

<a name="Pandas_Общая_информация"></a>
### Общая информация

---
**info()** выводит информацио о датафрейме (кол-во записей, описание колонок, кол-во пустых значений) 
`df.info()`

**df.shape** возвращает размеры датафрейса (строки, колонки)  
**columns** - название всех коло  
**head(3) / tail(5)** - первые/последние записи (без учёта заголовка)  
**dtypes** - типы элементов в колоноках  
**count()** - кол-во заполненных элементов по каждому столбцу  
`df['Наименование']` - отдельный столбец (Series)  
`df[['Наименование', 'Количество']]` - несколько столбцов  
`df.loc[2]` - отдельная строка  
`df.loc[[2, 5]]` - несколько строк  
`df.iloc[[2, 5], [0, 1]]` - выбор колонок по их номеру  
`df['ЦенаП'].mean()` - среднее значение  
`df['ЦенаП'].median()` - медианное значение  
`df['ЦенаП'].describe()` - выводит все статистики  
`df['ЦенаП'].agg(['mean', 'count'])` - можно передать несколько агрегатных функций

Можно совмещать: `df.loc[[2, 5], ['Наименование', 'Количество']]`

**Фильтры**  
`df[df['Количество'] > 9]`  
`df[df['Количество'].isin([1,5,10])]` **in**  
`df[(df['Количество'] > 1) & (df['Кратность лота'] > 1)]` несколько фильтров, применяется (**&** и **|**)  
`df[df['АртикулП'].notna()]` не нулевое значение / нулевое - **isna()**  

`df['АртикулП'].isna().sum()` - кол-во элементов

Вывод определённых столбцов с применённым фильтром  
`df.loc[df['АртикулП'].isna(), 'Наименование']`  
или `df['Наименование'][df['АртикулП'].isna()]`  

**Сортировка**  
`df.sort_values('ЦенаП')`  
`df.sort_values('ЦенаП', ascending=False)` False в порядке убывания, True наоборот  
`df.sort_values(['ЦенаП', 'Наименование'], ascending=[True, True])` сортировка нескольких столбцов  

Глубокое **копирование**: `df2 = df.copy(deep=True)`  
**Объединение** датафреймов: `df3 = pd.concat([df, df2])`  
**Объединение** по другой оси: `df3 = pd.concat([df, df2], axis=1)` (увеличивается кол-во строк)  
**Создание нового столбца**, **применение** к нему анонимной функции:  
`df['rub'] = df[1].apply(lambda x: f"{x * 95} rub")`  

**Изменение порядка столбцов**  
`df = df.reindex(columns=cols)`

**Объединение join**
```
coins = {'usdt': 1.0001, 'btc': 94300}
coins2 = {'eth': 2060, 'ltc': 93, 'usdt': 1.0001}
df = pd.DataFrame(coins.items(), columns=['code', 'value'])
df2 = pd.DataFrame(coins2.items(), columns=['code', 'value'])
```
Default - **inner**
```
df3 = pd.merge(df, df2, how='inner')
#    code   value
# 0  usdt  1.0001
```
_С on=['code']_
```
df3 = pd.merge(df, df2, on=['code'])
#    code  value_x  value_y
# 0  usdt   1.0001   1.0001
```
**outer**
```
df3 = pd.merge(df, df2, how='outer')
#    code       value
# 0   btc  94300.0000
# 1   eth   2060.0000
# 2   ltc     93.0000
# 3  usdt      1.0001
```
**right / left**
```
df3 = pd.merge(df, df2, how='right')
#    code      value
# 0   eth  2060.0000
# 1   ltc    93.0000
# 2  usdt     1.0001
```

**Group by**  
`df.groupby('БрендП')['ЦенаП'].mean()` - средняя цена в разрезе брендов  
`df.groupby(['БрендП', 'Количество'])['ЦенаП'].mean()`  
`df['БрендП'].value_counts()` - количество записей в группах

<a name="Pandas_Создание_графиков"></a>
### Создание графиков
```
import matplotlib.pyplot as plt

df['Количество'].plot(kind='hist', bins=50)
plt.show()
```
В параметры можно передать тип диаграммы **kind** (hist, kde) и точность **bins**  
Ограничение оси x:  
`df['Количество'].plot(kind='kde', xlim=[0, 1000])`  
Построение нескольких линий на графике:  
`df.groupby('Кратность лота')['Количество'].plot(kind='kde', xlim=[0, 1000], legend=True)`  
**legend=True** чтобы подписывать линии 

`df['БрендП'].value_counts()` похожа на group by, выводит кол-во элементов в каждой группе

Новый столбец `df['newCol'] = df['Количество'] > 1`  

Столбец по несокльким условиям (Количество > 1 и Цена >= 100):
```
df['newCol'] = df['Количество'] > 1
df.loc[df['newCol'] == True, 'newCol'] = df['ЦенаП'] >= 100
print(df[['ЦенаП', 'Количество', 'newCol']].head(20))
```

Переименование столбцов:  
`df.rename(columns={'ЦенаП': 'Цена Поставщика'})[['Наименование', 'Цена Поставщика']]`  
Применение функций к названиям столбцов: `df = df.rename(columns=str.upper)`

Изменение столбцов:  
`df['Наименование'] = df['Наименование'].apply(lambda x: x.lower())`  
Более быстрое решение - `df['Наименование'] = df['Наименование'].str.lower()`


---
<a name="matplotlib"></a>
# matplotlib
`pip install matplotlib`  
`import matplotlib.pyplot as plt`

Выбор метода для отображения графиков
```
matplotlib.use("Qt5Agg")
print(matplotlib.get_backend()) # qtagg (default) / TkAgg / Qt5Agg
```

<a name="matplotlib_Отображение_графика"></a>
### Отображение графика
```
plt.plot([1,5,-2,3,-4,0])
plt.show()
```
Изначально график берет значения масива (y) и индексы элементов (x), 
но можно задать x отдельно:
```
x = np.array([1,3,4,5])
y = np.array([1,5,-2,3])
plt.plot(x, y)
```
`plt.grid()` - добавить сетку на график

Добавить **несколько линий**:
```
x2 = np.array([0,1,2,3])
y2 = np.array([-3,2,0,1])
plt.plot(x, y, x2, y2)
```
или 
```
plt.plot(x, y)
plt.plot(x2, y2)
```
Изменить **тип линии**:  
`plt.plot(x, y, '--')`  
или
```
l1 = plt.plot(x, y)
plt.setp(l1, linestyle='--')
```
### Типы линий 
'-' непрерывная, '--' штриховая, '-.' штрихпунктирная, ':' пунктирная, ''/'None' без оотбражения линии

Изменение **цвета** линии:  
`plt.plot(x, y, 'r')` можно добавить и тип `'r--'`  
или  
`plt.plot(x, y, color='#0000AA')` / `color=(0,1,1,0.3)` (+альфаканал опционально, можно менять отдельно через **alpha**)

**Маркеры** на графике (дополнительные знаки на ключевых точках линии)  
`plt.plot(x, y, 'r--o')` - жирная точка, `'r--x'` - крест  
Можно задать параметром: `marker='+'`  
**Цвет** маркера: `markerfacecolor='r'` (цвет заливки фигур)  
**Размер** маркеров: `markersize=5`

**Ширина** линии - `linewidth=3`

### Заливка на графике  
`plt.fill_between(x, y)` - обычная заливка, от нулевой оси до линии графиак  
**Условия** заливки`plt.fill_between(x, y, where=(0.2<y))`  
Можно добавлять другие параметры, например, color

<a name="matplotlib_Разделение_окна_вывод_нескольких_графиков"></a>
### Разделение окна, вывод нескольких графиков  
subplot(nrows, ncols, index) - принимает кол-во строк, столбцов и индекс текущих координатных осей  
Окно с двумя графиками, 1 ряд, 2 столбца:
```
ax1 = plt.subplot(1,2,1)
plt.plot(np.random.random(5))
ax2 = plt.subplot(1,2,2)
plt.plot(np.random.random(5))
ax1.grid()
ax2.grid()
plt.show()
```
Окно с тремя графиками, в первой строке 2 и 1 во второй:
```
ax1 = plt.subplot(2,2,1)
plt.plot(np.random.random(5))
ax2 = plt.subplot(2,2,2)
plt.plot(np.random.random(5))
ax3 = plt.subplot(2,1,2)
plt.plot(np.random.random(5))
```
В ax3 указывается индекс 2, чтобы графики не наслаивались на друг-друга  
Если все элементы меньше 10, то можно указывать без запятой:  
`ax3 = plt.subplot(212) # 2,1,2`

Другой способ отображения нескольких графиков:  
```
f, ax = plt.subplots(2,2)
f.set_size_inches(5,5)
f.set_facecolor('#eee')
ax[0,0].plot(np.random.random(5))
ax[0,0].grid()
```
set_size_inches задаёт размер окна в дюймах  
set_facecolor фоновый цвет окна

Создание окна:
```
f2 = plt.figure(figsize=(7,4))
plt.plot(np.arange(5))
```
Можно задать размер графика в окне:
```
ax1 = f2.add_axes([0,0,1,1]) # график будет занимать всё окно
ax1.plot(np.arange(5))
```
В add_axes задаются размеры окна в процентах

Добавление графика (**add_subplot**) в окно:  
`ax1 = f2.add_subplot(1,2,1)`

Класс **GridSpec** для компановки графиков:
```
from matplotlib.gridspec import GridSpec

gs = GridSpec(nrows=2, ncols=3)
ax1 = plt.subplot(gs[0,0])
```
Можно задавать отдельное окно и указывать размеры столбцов/строк:
```
w = [1,2,5]
h = [2,1]
fig = plt.figure(figsize=(6,3))
gs = GridSpec(nrows=2, ncols=3, figure=fig, width_ratios=w, height_ratios=h)
ax1 = fig.add_subplot(gs[:,2])
ax1.plot(np.random.random(5))
ax2 = plt.subplot(gs[1,:2])
ax2.plot(np.random.random(5))
plt.show()
```

<a name="matplotlib_Изменение_осей"></a>
### Установка лимитов по осям
Ограничение по x (от 3 до конца линии), по y (от 0.5 до 1):
```
fig = plt.figure(figsize=(5,5))
ax1 = fig.add_subplot()
ax1.plot(np.random.random(5), color='r')
ax1.set(xlim=3, ylim=(0.5,1))
```
или `ax1.set_xlim(3)`  
или задать лимиты для последнего активного графика: `plt.xlim(0,3)`

### Изменение осей
**Локаторы** (для изменения значений на рисках)

**NullLocator**  
`from matplotlib.ticker import NullLocator`  
Отключение рисок осей (**xaxis** / **yaxis**): `ax1.xaxis.set_major_locator(NullLocator())`

- **LinearLocator** - Разделение оси ровно на N меток: `LinearLocator(5)`
- **MultipleLocator** - Задаётся шаг рисок: `MultipleLocator(base=.5)`
- **IndexLocator** - Указывается шаг рисок и смещение первой риски: `IndexLocator(base=.5, offset=1)`
- **FixedLocator** - Указываются фиксированные риски: `FixedLocator([1,3,5])`
- **MaxNLocator** - Создаёт примеро N кол-во рисок, устанавливает удобные для чтения значения: `MaxNLocator(7)`

Включение **мелкой (minor)** сетки:  
```
ax1.minorticks_on()
ax1.grid(which='major', lw=2)
ax1.grid(which='minor')
```

**Форматоры** (для изменения)

**NullFormatter**
Скрыть все значения на оси 
`ax1.xaxis.set_major_formatter(NullFormatter())`

- **FormatStrFormatter** - задаёт str формат рискам: `FormatStrFormatter("%.2f usd")`
- **FuncFormatter** - формат рискам задаёт указанная функция: `FuncFormatter(lambda x, pos: f"[+{x}]" if x > 0 else f"[{x}]")`
- **ScalarFormatter** - выносит спепень значений рисок вверх графика
```
    ax1.plot(np.random.random(10) * 1e5)
    sf = ScalarFormatter()
    sf.set_powerlimits((-5, 5)) # вынесет "1e5" вверх, если значения рисок больше 1e5 или меньше -1e5
    ax1.yaxis.set_major_formatter(sf)
```
Для того чтобы **глобально** задать ScalarFormatter:
```
import matplotlib
matplotlib.rcParams["axes.formatter.limits"] = (-5, 5)
```
- **FixedFormatter** - фиксированные риски: `FixedFormatter(['a', 'b', 'c'])`

<a name="matplotlib_Дополнительные_элементы_в_окне"></a>
### Дополнительные элементы в окне
**figtext** - текст поверх всего  
**set_xlabel** - название осей  
**annotate** - аннотации (_xy_ - координаты куда будет указывать стрелка, 
_xytext_ - координаты, где будет начинаться стрелка и текст)
```
fig = plt.figure(figsize=(5,5))
ax1 = fig.add_subplot()
plt.figtext(0.1, 0.5, 'Текст в окне')
fig.suptitle('Заголовок окна')
ax1.set_xlabel('Ox') # или plt.xlabel('Ox') для активного окна 
ax1.set_ylabel('Oy')
ax1.text(0.2,0.7, 'Текст в окне с графиком')
ax1.annotate('Аннотация', xy=(0.1, 0.1), xytext=(0.5, 0.4), arrowprops={'facecolor': 'green', 'shrink':0.1})
```

Можно изменять все эти элементы с помощью **bbox**:  
`ax1.text(0.2,0.7, 'Текст в окне с графиком', bbox={'boxstyle': 'square', 'facecolor': '#FFAAAA'})`

Объектам можно менять параметры с помощью фунции **set**: `ax1.set(facecolor='lightgray')`

Задать название для линий и добавить информациюнное поле (легенду):
```
ax.plot(np.random.random(10), label='№1')
ax.plot(np.random.random(10), label='№2')
ax.legend()
```
или 
```
l1, = ax.plot(np.random.random(10))
l2, = ax.plot(np.random.random(10))
ax.legend((l2, l1),['a', 'b'])
```
или просто `ax.legend(['a', 'b'])`

Место расположения легенды: `ax.legend(loc='lower right')` / `ax.legend(bbox_to_anchor=(0.2, 0.4))`

<a name="matplotlib_Фигуры_разные_типы_графиков"></a>
### Фигуры, разные типы графиков
Добавление ломаной линии, в Line2D передаются списки координат x и y:
```
from matplotlib.lines import Line2D

line = Line2D([1,2,3], [1,3,5])
ax.add_line(line)
```
Добавление фигур:
```
from matplotlib.patches import *

rect = Rectangle((0.5,1), 2, 1, facecolor='b')
ax.add_patch(rect)
```

**Ступенчатый график**  
```
m = np.arange(5)
ax.step(m, m, where='pre')
```
В **where** можно указать способ построения графика: **pre** (по-умолчанию, 
сначала вверх, потом влево), **post** инверсия pre, **mid** метка по центру ступени

**Стековый график** (каждая следующая функция прибавляет к себе предыдещие значения другой функции)
```
m1 = np.arange(0,5,0.5) ** 2
m2 = np.arange(0,5,0.5) ** 2
ax.stackplot(np.arange(len(m1)), m1, m2)
```

**stem графики** (линии от точек до базовой линии)  
`ax.stem(np.random.randint(-5,5,5), '--r', basefmt=':', markerfmt='x', bottom=1)`  
_bottom_ - базовая линия

**Тотечный график**
```
x = np.random.randint(-5,5, 55)
y = np.random.randint(-5,5, 55)
ax.scatter(x,y, alpha=0.5)
```
**Гистограммы**  
Метод **hist**
```
x = np.random.randint(-10,10, 55)
ax.hist(x, 20) # устанавливается точность диагрыммы, (default 10)
```
Метод **bar** / **barh** (для отображение графика по вертикали)
```
x = np.random.randint(-10,10, 10)
ax.bar(np.arange(10), x) 
```
Для сравнений нескольких наборов данных можно вывести несколько столбцов рядом:
```
w = 0.5
ax.bar(np.arange(10)-w/2, x1, width=w)
ax.bar(np.arange(10)+w/2, x2, width=w)
```
**Круговая диаграмма**
```
coins = ['BTC', 'ETH', 'LTC', 'USDT']
vals = [45, 25, 20, 10]
exp = [0, 0.2, 0, 0]    # выдвинутые части
ax.pie(vals, labels=coins, explode=exp, autopct='%.2f', shadow=True)
```
Параметр **wedgeprops=dict(width=0.6)** добавляет отверстие в центре круга

### Вывод изображения на графике
```
from PIL import Image

img = Image.open('img2.png')
plt.imshow(img)
```
Вывод произвольного изображения, выбор цветового канала (**cmap**):
```
data = np.random.randint(0,255, (50,50))
plt.imshow(data, cmap='plasma')
```
Преобразовать изображение в другой цветовой канал, вывести цветовой канал в окно:
```
img = Image.open(file).convert('L')
im = plt.imshow(img, cmap='plasma')
plt.colorbar(im)
```
Параметр **origin='lower'** поворачивает изображение

Метод **pcolormesh** работает быстрее imshow, но не сохраняет пропорции изображения 
и работает только с двумерными массивами (НЕ с rgb, rgba)  
`plt.pcolormesh(data, cmap='plasma', edgecolor='black')`

<a name="matplotlib_Трехмерные_графики"></a>
### Трехмерные графики
Создание 3д поля:
```
fig = plt.figure(figsize=(6,6))
ax_3d = fig.add_subplot(projection='3d')
```
Подписать оси: `ax_3d.set_xlabel('x')`

Произвольная 2д линия в 3д:
```
x = np.random.random(5)
z = np.arange(5)
ax_3d.plot(x,x,z)
```
Добавление полигонов (**plot_wireframe** - каркас, **plot_surface** - полигоны залитые цветом):
```
x = np.arange(-np.pi,np.pi,0.1)
y = np.arange(-np.pi,np.pi,0.1)
x, y = np.meshgrid(x, y)
z = np.sin(x) * np.cos(y)
ax_3d.plot_wireframe(x,y,z)
```
Чтобы изменить **количество полигонов** можно менять параметры **rstride** и **cstride**, чем больше значение, тем больше сами полигоны  
`ax_3d.plot_surface(x,y,z, rstride=7, cstride=7)`

Отображение 3д графика в виде отдельных точек: 
`ax_3d.scatter(x,y,z, s=1) # s задаёт размер точек`

Отрисовки линии уровней **contour** (4 параметром можно указать точность):  
`ax_3d.contour(x,y,z, 15) # или передать список уровней вместо числа`  
Линии уровней в виде поверхностей - **contourf**  
Можно указать набор цветов **cmap** / **colors=['r','b']** (перечислить цвета или задать статичный)

Отображение уровней 3д графика в 2д:
```
fig, ax = plt.subplots(1, 2)
x = np.arange(-np.pi,np.pi,0.1)
y = np.arange(-np.pi,np.pi,0.1)
x, y = np.meshgrid(x, y)
z = np.sin(x) * np.cos(y)
ax[0].contour(x,y,z)
ax[1].contourf(x,y,z)
```
Чтобы подписать значение уровней на графике:
```
a1 = ax[0].contour(x,y,z)
a1.clabel()
```
В clabel можно задать цвет (_colors_) и формат (_fmt_)

Чтобы нарисовать уровни для одомерных массивов (**tricontour** / **tricontourf                                                                      **):
```
x = np.random.rand(10)
y = np.random.rand(10)
z = np.cos(x) * np.sin(y)
ax.tricontour(x,y,z)
```

<a name="matplotlib_Анимация_графиков"></a>
### Анимация графиков
Вариант 1 (полностью перересовывает график каждый кардр):
```
x = np.arange(-np.pi, np.pi, 0.1)

plt.ion() # включение интерактивного режима отображение графиков
for offset in np.arange(0, 10, 0.1):
    y = np.cos(x + offset)
    plt.clf() # отчистка окна
    plt.plot(x,y)
    # для обновления в окне
    plt.draw()
    plt.gcf().canvas.flush_events()
    time.sleep(0.05)
    
plt.ioff() # выход из инт. режима
plt.show()
```
Вариант 2:
```
plt.ion()
fig, ax = plt.subplots()
x = np.arange(-np.pi, np.pi, 0.1)
y = np.cos(x)
line, = ax.plot(x,y)

for offset in np.arange(0, 10, 0.1):
    y = np.cos(x + offset)
    line.set_ydata(y)
    # для обновления в окне
    plt.draw()
    plt.gcf().canvas.flush_events()
    time.sleep(0.05)
    
plt.ioff()
plt.show()
```
Вариант через **FuncAnimation**:
```
from matplotlib.animation import FuncAnimation

def update_f(frame, line, x):
    # line - ссылка на Line2D
    line.set_ydata(np.cos(x+frame))
    return [line]

def main():
    fig, ax = plt.subplots()
    x = phasa =  np.arange(-np.pi, np.pi, 0.1)
    y = np.cos(x)
    line, = ax.plot(x,y)

    anim = FuncAnimation(fig, 
                 func=update_f, # функция обновления кадра
                 frames=phasa, # параметр, меняющийся каждый кадр (фаза)
                 fargs=(line,x), # доп. параметры для функции
                 interval=10, # задежка между кадрами
                 blit=True, # двойная буферизация
                 repeat=False)
    plt.show()
```
Вариант через **ArtistAnimation** (расчёт кадров заранее):
```
from matplotlib.animation import ArtistAnimation

fig = plt.figure()
ax = fig.add_subplot(projection='3d')
x =  np.arange(-np.pi, np.pi, 0.1)
y =  np.arange(-np.pi, np.pi, 0.1)
x, y = np.meshgrid(x, y)

phasa = np.arange(0, 5, 0.1)
frames = []

for p in phasa:
    z = np.sin(x+p) * np.cos(y)
    line = ax.plot_surface(x, y, z, color='g')
    frames.append([line])
anim = ArtistAnimation(fig, frames, interval=50, blit=True, repeat=True)
plt.show()
```

---
<a name="Многопоточность"></a>
### Многопоточность
Пример запуска несокльких функций одновременно. **start** зпаускает функции, **join** - дожидается их отработки
```
threads = [Thread(target=test_f, daemon=True) for _ in range(5)]
for t in threads:
    t.start()
for t in threads:
    t.join()
```
При вызове функций с долгой работой программа может отработать некорректно, для исправления добавляется блокировка **Lock**:
```
from threading import  Lock
x = 0
lock = threading.Lock()

def test_f():
    lock.acquire()
    global x
    a = x + 1
    time.sleep(1)
    x = a
    lock.release()
```
Также возможно обойтись без блокировки, использую **очередь**:
```
from queue import Queue
x = 0
queue = Queue()
queue.put(0)

def test_f():
    global queue
    a = queue.get() + 1
    time.sleep(1)
    queue.put(a)
```
Пример с кнопкой **PyQt6**:
```
from PyQt6 import QtCore, QtWidgets
from PyQt6.QtWidgets import QApplication, QPushButton, QMainWindow
import sys
from threading import Thread

def test_f(x):
    print('start 1')
    time.sleep(x)
    print('stop 1')

def thread_test(func, args):
    thread = Thread(target=func, args=(args,), daemon=True)
    thread.start()
    return thread

class MainWindow(QMainWindow):
    def __init__(self):
        super().__init__()
        self.centralwidget = QtWidgets.QWidget(parent=self)

        button1 = QPushButton("test 1", parent=self.centralwidget)
        button1.setGeometry(QtCore.QRect(10, 30, 75, 23))

        self.setCentralWidget(self.centralwidget)
        button1.clicked.connect(lambda: thread_test(test_f, 3))

if __name__ == '__main__':
    app = QApplication(sys.argv)
    window = MainWindow()
    window.show()
    app.exec()
```

<a name="multiprocessing"></a>
### multiprocessing
_В функции нельзя передавать данные которые не сериализуются через pickle_

Запуск нескольких функций в несколько процессов:
```
from multiprocessing import Pool, Process

processes = [Process(target=test_f, daemon=True) for _ in range(3)]
for p in processes:
    p.start() # запуск процессов
for p in processes:
    p.join() # ожидание завершения всех процессов
```
Объявляется объект Pool для запуска нескольких процессов одновременно, в него передаётся 
параметр processes, отвечающий за максимальное кол-во одновременно запущенных процессов.
```
from multiprocessing import Pool

urls = ['https://www.otohits.net/', 'https://qiwi.com/', 'https://www.jetswap.com/']
p = Pool(processes=3)
p.map(Start_url, urls)
```
В данном примете запускается функция Start_url для кадого из объектов в списке urls, если 
объектов больше, чем указано процессов, то программа будет ждать пока освободится место для 
следующего объекта в очереди.

**Pool** процессов и получение информации из return:
```
def test_f(x):
    print('start')
    time.sleep(x)
    return 'test'

if __name__ == '__main__':
    with Pool(processes=3) as p:
        res = p.map(test_f, [2 for i in range(3)])
```
В скомпилированных приложениях с PyQT при запуске нескольких функций могут открываться 
несколько окон. Исправление ошибки:
```
import multiprocessing as mp
mp.freeze_support()
```
Можно объявлять общую переменную для процессов через **mp.Manager**:
```
mng = mp.Manager()
cnt = mng.Value('cnt', 0)

fls = []
for i in price_list:
    fls.append([i, host, user, password, db_name, cnt])

with (mp.Pool(processes=threads)) as p:
    p.map(update_file, fls)

print(cnt.value)

def update_file(args):
    ... , cnt = args
    cnt.value += 1
```

<a name="Asyncio"></a>
# Asyncio
Работает в 1 поток  
`import asyncio`

Пример:
```
async def f_a():
    print('start a')
    await asyncio.sleep(2)
    print('stop a')

async def f_b():
    print('start b')
    await asyncio.sleep(3)
    print('stop b')

async def main():
    await asyncio.gather(f_a(), f_b())

if __name__ == '__main__':
    t = time.time()
    asyncio.run(main())
    print(time.time() - t)
```
или
```
async def main():
    asyncio.create_task(f_a())
    await asyncio.create_task(f_b())
```
В асинхронный функциях **нельзя** писать непредсказуемые **блокирующие** функции, 
которые могут надолго затормозить всю работу (например, обычный requests.get)

Пример с асинхронным request.get:
`pip install aiohttp`
```
import aiohttp

async def get_req():
    async with aiohttp.ClientSession() as session:
        async with session.get('https://ya.ru') as resp:
            print(resp.status)
            
async def main():
    await asyncio.gather(*[get_req() for _ in range(3)])
```

Асинхронаня работа с **PostgreSQL**. Пример с пулом запросов к БД:   
`pip install asyncpg`
```
import asyncpg

async def create_req(pool_db, x):
    await pool_db.fetch(f"insert into users values('dflt', {x})")

async def main():
    pool_len = 50
    pool = []
    pool_db = await asyncpg.create_pool(user='postgres', 
    host='localhost', password='psw', port='5432', database='test_db')

    for i in range(1, 1001):
        pool.append(asyncio.create_task(create_req(pool_db, i)))
        if i % pool_len == 0 or i == 1000:
            await asyncio.gather(*pool)
            pool = []
            print(i)
```

<a name="Другое"></a>
# Другое

---
<a name="Работа_с_почтой_(imaplib_smtplib)"></a>
# Работа с почтой (imaplib, smtplib)
`import imaplib`

**Получение содержимого письма, закачка прикреплённых файлов**:  
password для IMAP  
В mail.uid(...) третим параметром указывается фильтр (ALL / UnSeen / фильтр по времени и тд.)
```
def get_mail(id, mail):
    _, res = mail.uid('fetch', id, "(RFC822)")
    raw_email = res[0][1]
    msg = email.message_from_string(raw_email.decode("utf-8"))
    sender = msg['Return-path']
    print(sender)   # отправитель
    header = decode_header(msg['Subject'])[0][0].decode()
    print(header) # Заголовок (Без темы - NoneType)
    
    for part in msg.walk():
    if part.get_content_disposition() == 'attachment':
        file_name = decode_header(part.get_filename())[0][0].decode()
        #print(file_name, file_format)
        if part.get_content_maintype() != 'multipart' and part.get('Content-Disposition') is not None:
             open(f'{Dir}/{file_name}', 'wb').write(part.get_payload(decode=True))
    
def main():
    mail = imaplib.IMAP4_SSL('imap.yandex.ru')
    mail.login('Max210mm@yandex.ru', password)
    mail.select("inbox")
    _, res = mail.uid('search', "Seen") # ALL / UnSeen

    last_mail_id = res[0].split()[-1]
    get_mail(last_mail_id, mail)
```
### Письма с определённой даты
```
  now = datetime.datetime.now()
  t = (now - datetime.timedelta(days=14)).strftime("%d-%b-%Y")
  _, res = mail.uid('search', '(SINCE "'+ t +'")', "Seen")
```


### Отправка писем c вложением
```
    import os
    import smtplib
    from email.mime.application import MIMEApplication
    from email.mime.multipart import MIMEMultipart
    from email.header import Header

    msg = MIMEMultipart()
    msg["Subject"] = Header("Заголовок 5")
    msg["From"] = login
    msg["To"] = 'test_mail@gmail.com'

    s = smtplib.SMTP("smtp.yandex.ru", 587, timeout=10)

    try:
        s.starttls()
        s.login(login, password)

        file_path = r"C:\other\price_processing\res3\VALA_3.csv"
        
        with open(file_path, 'rb') as f:
            file = MIMEApplication(f.read())
        
        file.add_header('Content-Disposition', 'attachment', filename='VALA_3.csv')
        msg.attach(file)

        s.sendmail(msg["From"], 'test_mail@gmail.com', msg.as_string())
    except Exception as ex:
        print(ex)
    finally:
        s.quit()
```

### Отправка писем без вложений
```
    from email.mime.text import MIMEText
    
    msg = MIMEText("asdfgh8", "plain", "utf-8")

    msg["Subject"] = Header("Заголовок 8")
    msg["From"] = login
    msg["To"] = "tmptr101@gmail.com" #login

    s = smtplib.SMTP("smtp.yandex.ru", 587, timeout=10)
    try:
        s.starttls()
        s.login(login, password)
        s.sendmail(msg["From"], "tmptr101@gmail.com", msg.as_string())
    except Exception as ex:
        print(ex)
    finally:
        s.quit()
```


<a name="Определение_кодировки_chardet"></a>
## Определение кодировки chardet
`pip install chardet`

Позволяет автоматически определить кодировку
```
import chardet

with open(fr"{path_to_prices}\{file_name}", 'rb') as f:
    dc = chardet.detect(f.read())
    
enc = dc['encoding']

table = pd.read_csv("file.csv", header=None, sep=';', encoding=enc)
```

<a name="Dadata"></a>
# Dadata
Получение данных о компаниях и тд  
`pip install dadata`  
`pip install httpx`  

Api ключ получается на одноимёном сайте, для бесплатного тарифа лммит 10 000 запросов в день

Пример поиска информации о компании по её названию и ФИО руководителя:
```
from dadata import Dadata

with Dadata(api_key_dd, api_secrey_key_dd) as dadata:
    for company_data in dadata.suggest(name="party", query=f"Тест Имя Фамилия Отчество"):
        print(company_data)
        
        # {'value': 'ООО "ТЕСТ"', 'unrestricted_value': 'ООО "ТЕСТ"', 'data': {'kpp': '770000000', ...,
        # 'management': {'name': 'Имя Фамилия Отчество', 'post': 'ГЕНЕРАЛЬНЫЙ ДИРЕКТОР', 
        # 'start_date': 9999999999999, ...}, ... 'full': 'Общество с ограниченной ответственностью', 
        # 'short': 'ООО'}, 'name': {'full_with_opf': 'ОБЩЕСТВО С ОГРАНИЧЕННОЙ ОТВЕТСТВЕННОСТЬЮ "ТЕСТ"', 
        #'short_with_opf': 'ООО "ТЕСТ"', ...}, 'inn': '77111111', 'ogrn': '2222222222222', 
        # 'address': {'value': 'г Москва, ул ...}
```



<a name="ООП"></a> 
# ООП
### Атрибуты класса
**Общие** атрибуты класса (любой объект класса будет ссылаться на один и тот же объект):
```
    u = Unit()
    u2 = Unit()
    Unit.hp = 90
    print(u.hp, u2.hp) # 90 90
```
Динамическая установка нового атрибута: `setattr(Unit, 'armor', 2)`  
Установка новго атрибута для объекта класса: `u.mana = 50`  
Получение атрибута через getattr (если атребута не существется, вернется третий агрумент):  
`getattr(Unit, 'armor', -1)`  
Проверка на наличие атрибута: `hasattr(Unit, 'hp')`  
Удаление атрибута: `del Unit.hp` или `delattr(Unit, 'hp')`  

<a name="Конструктор"></a>
### Конструктор
Функция `__init__(self)` является конструктором  
После создания объекта класса можно динамически добавлять к нему новые переменные
```
class url:
    def __init__(self, address, description=''):
        self.address = address
        self.description = description

def main():

    url_1 = url('https://forum.com/stuff', 'Форум')
    url_1.note = 'reports dont work'
    print(url_1.note)
```

<a name="Деструктор"></a>
### Деструктор
Деструктор `__del(self)__` вызывается при удалении объекта, интерпретатор автоматически определяет, когда удалять объект
```
class url:
    def __init__(self, address, description=''):
        self.address = address
        self.description = description
        print(f'Создана ссылка: {self.address} {self.description}.')

    def __del__(self):
        print(f'Объект url ({self.address}) удалён.')
def create_url():
    url_1 = url('https://forum.com/stuff', 'Форум')
def main():
    create_url()
    print('Конец программы.')
    
# Создана ссылка: https://forum.com/stuff Форум.
# Объект url (https://forum.com/stuff) удалён.
# Конец программы.
```
В данном примере объект url создается в функции create_url(), поэтому жизнь этого объекта ограничена областью функции.

<a name="Приватные_атрибуты"></a>
### Приватные атрибуты
Введение. **Инкапсуляция** - концепция ооп, которая предполагает скрытие функционала и предотвращение прямого доступа к нему.  
Приватные атрибуты: `self.__info`  
К приватному атрибуту можно обратиться вне класса через `_ClassName__info`
```
class url:
    def __init__(self, address, description=''):
        self.__address = address
        self.__description = description
    def print_url(self):
        print(self.__address)

def main():
    url_1 = url('https://forum.com/stuff', 'Форум')
    url_1.__address = 0
    url_1.print_url()       # https://forum.com/stuff
    print(url_1.__address)  # 0

    url_1._url__address = 0
    url_1.print_url()       # 0
```
При обращении `url_1.__address` создается новая переменная `__address`, вместо нужной `_url__address`

<a name="Аннотации_свойств_Геттеры_и_сеттеры"></a>
### Аннотации свойств. Геттеры и сеттеры
Для создания свойства-геттера над свойством ставится аннотация @property  
Для сеттера - @имя_свойства_геттера.setter  
Так же можно прописать deleter  
**Сеттер определяется после геттера**
```
class Unit:
    def __init__(self, name, hp):
        self.__name = name
        self.__hp = hp

    @property
    def hp(self):
        return self.__hp
    @hp.setter
    def hp(self, hp):
        self.__hp -= hp
    @hp.deleter
    def hp(self):
        del self.__hp

def main():
    Builder = Unit('Builder', 30)
    Builder.hp = 10
    print(Builder.hp)
```

<a name="Наследование"></a>
### Наследование
Наследование имеет вид: `class Battler(Unit):`  
Дочерний элемент не видит приватные атрибуты родителя.  
```
class Unit:
    def __init__(self, name, hp):
        self.name = name
        self.__hp = hp

    @property
    def hp(self):
        return self.__hp

    def TakeDamage(self, dmg):
        self.__hp -= dmg
        if self.__hp > 0:
            print(self.name + "`s hp is", self.__hp)
        else:
            print(self.name, 'is dead')

class Battler(Unit):
    damage = 20
    def Hit(self, Unit):
        Unit.TakeDamage(self.damage)
```
Множественное наследование:
```
class Unit:
    def __init__(self, name, hp):
        self.name = name
        self._hp = hp
    def Go(self):
        print('Unit goes')
    def print_info(self):
        print(f'{self.name}, {self._hp}')

class Seller:
    def __init__(self, name, hp, shop_type):
        self.name = name
        self._hp = hp
        self.shop_type = shop_type
    def print_info(self):
        print(f'{self.name}, {self._hp}, Sell: {self.shop_type}')

class Character(Unit, Seller):
    def __init__(self, *args):
        Seller.__init__(self, *args)
    def print_info(self):
        Seller.print_info(self)

def main():
    Sam = Character("Sam", 20, 'Armor')
    Sam.print_info()     # Sam, 20, Sell: Armor
    Unit.print_info(Sam) # Sam, 20
    print(Character.__mro__) # (<class '__main__.Character'>, <class '__main__.Unit'>, <class '__main__.Seller'>, <class 'object'>)
```
Если родительские классы имеют одинаковые методы, то вызовется метод первого родителя.  
Порядок вызова можно узнать через class.mro() или аналогичный магический метод

<a name="Переопределение_методов"></a>
### Переопределение методов
```
class Unit:
    def __init__(self, name, hp):
        self.name = name
        self.hp = hp
        
    def PrintInfo(self):
        print(self.name, 'Health:', self.hp)


class Battler(Unit):
    def __init__(self, name, hp, damage):
        super().__init__(name, hp)
        self.damage = damage
        
    def PrintInfo(self):
        super().PrintInfo()
        print("Damage:", self.damage)
```

<a name="Статические_методы"></a>
### Статические методы
Для объявления статических методов используется аннтоация @staticmethod  
Если в агрументах статического метода есть self, то его необходимо передать.
```
class url:
    protocol = 'http'
    @staticmethod
    def PrintProtocil():
        print(url.protocol)

def main():
    url_1 = url()
    url_2 = url()
    url.protocol = 'https'    # protocol изменен у url_1 и url_2
    url_1.PrintProtocil()
```
При изменении атрибутов класса напрямую, меняется информация во всех экземплярах класса.

<a name="Строковое_представление_объекта"></a>
### Строковое представление объекта (класс object)
С 3 версии языка Python все классы неявно наследуют все методы у класса object.  
Один из этих методов - `__str__()`, он выводит объект в виде строки (`<__main__.url object at 0x000001DA32EAD520>`).<br>
Данный метод можно переопределить, но он должен всегда возвращать строку:
```
class url:
    def __init__(self, address, description):
        self.address = address
        self.description = description

    def __str__(self):
        return f'{self.address}, {self.description}'

def main():
    url_1 = url('forum.com', 'Форум')
    print(url_1)
```

<a name="Перегрузка_операторов"></a>
### Перегрузка операторов
Переопределение встроенных операторов сложения, вычитания и т.д.  
Существует множество операторов: Сложение `__add__(a, b)`, объединение: `__concat__(a, b)`, 
< - `__lt__()`, > - `__gt__()`...  
Возвращаемый тип ряда операторов жестко не опрелён.  
Add:
```
class Balance:
    gold = 0
    silver = 0
    copper = 0
    def __init__(self, gold, silver, copper):
        self.gold = gold
        self.silver = silver
        self.copper = copper
    def __add__(self, other):
        self.copper += other.copper
        if self.copper >= 100:
            self.silver += 1
            self.copper -= 100
        self.silver += other.silver
        if self.silver >= 100:
            self.gold += 1
            self.silver -= 100
        self.gold += other.gold
        return 'G:',self.gold, ' S:', self.silver, ' C:', self.copper

def main():
    B1 = Balance(1, 52, 77)
    B2 = Balance(5, 88, 45)
    print(B1 + B2)
```
Bool:
```
    ...
    def __bool__(self):
        if self.gold >= 2:
            return True
        return False

def main():
    B1 = Balance(5, 51, 77)
    while B1:
        print('Buy')
        B1.gold -= 2
    else:
        print('You do not have enough money')
```
Обращение по индексу:
```
    ...
    def __getitem__(self, item):
        if item == 0: return f'G: {self.__gold}'
        elif item == 1: return f'S: {self.__silver}'
        elif item == 2: return f'C: {self.__copper}'

def main():
    B1 = Balance(5, 51, 77)
    print(B1[2])
```
in:
```
    ...
    def __contains__(self, item):
        if item == 'gold' and self.__gold > 0: return True
        if item == 'silver' and self.__silver > 0: return True
        if item == 'copper' and self.__copper > 0: return True
        return False

def main():
    B1 = Balance(5, 0, 77)
    print('silver' in B1)
```
Парные операторы:
```
    # __eq__, __ne__
    # __gt__, __le__
    # __lt__, __ge__
    
    ...
    def __eq__(self, other):
        if self.gold == other.gold and self.silver == other.silver and self.copper == other.copper: return True
        return False
    def __ne__(self, other):
        return not self.__eq__(other)

def main():
    B1 = Balance(1, 15, 75)
    B2 = Balance(5, 88, 45)
    print(B1 != B2)
```

<a name="Абстрактные_классы"></a>
### Абстрактные классы
В Python инструменты для создания абстрактных классов находятся в модуле **abc**  
`import abc`  
Абстрактные классы наследуются от **abc.ABC**, абстрактные методы имеют аннотацию **@abc.abstractmethod**  
Дочерние классы должны реализовывать все абстрактные методы
```
import abc

class Unit(abc.ABC):
    def __init__(self, name, hp, damage):
        self.name = name
        self.hp = hp
        self.damage = damage

    @abc.abstractmethod
    def Attack(self): pass

class Battler(Unit):
    def Attack(self):
        print(f'Deal area damage ({self.damage})')

class Archer(Unit):
    def Attack(self):
        print(f'Hit the target ({self.damage})')
```
### Класс-декоратор
```
class CheckLower:
    def __init__(self, func):
        self.__func = func
    def __call__(self, s, *args, **kwargs):
        return self.__func(s).lower() if isinstance(s, str) else None

@CheckLower
def get_domen(s: str):
    return s.split('.')[0].split('//')[-1]

def main():
    print(get_domen('https://Site.com'))
```

<a name="Методы_классов"></a>
### Методы классов
`__dict__` - выводит информацию об атрибутах класса
```
  print(Unit.__dict__)
  # {'__module__': '__main__', 'hp': 100, 'dmg': 10, '__dict__': <attribute '__dict__' of 'Unit' objects>,
  # '__weakref__': <attribute '__weakref__' of 'Unit' objects>, '__doc__': None}
```
`__doc__` - вывод документации  
`__new__` - вызывается до создания объекта класса  
`__getattribute__` - вызывается, когда происходит обращение к атрибутам класса
```
        def __getattribute__(self, item):
        if item == 'hp':
            print('error')
            return None
        return object.__getattribute__(self, item)

  u = Unit(15, 2)
  print(u.hp) # error; None
```
`__setattr__` - вызывается при установке значения атрибуту
```
    def __setattr__(self, key, value):
        object.__setattr__(self, key, value)
```
`__getattr__` - вызывается при обращении к несуществующему атрибуту  
`__delattr__` - вызывается при удалении атрибута
```
    def __delattr__(self, item):
        object.__delattr__(self, item)
```
`__set__(self, instance, value)` - сеттер для дескриптеров  
`__get__(self, instance, owner)` - геттер для дескриптеров  
`__call__(self, *args, **kwargs)` - срабатывает при вызове класса, например, Person()  
`__str__` - вызывается, если напечатать класс в print/str  
`__repr__` - вызывается, если напечатать класс в print/str (для разработчиков)  
`__len__` - len(), ещё вызывается функцией bool() если не определён магический метод bool  
`__bool__` - вызывается при использования класса в условных операторах и при функции bool()  
`__abs__` - abs()

`__add__` - операция сложения: class + ...  
`__radd__` - операция сложения: ... + class  
`__iadd__` - операция сложения: class += ...  
По аналогии: sub (-), mul (*), truediv (/), floordiv (//), mod (%)

`__hash__` - вызывается при попытки взять хэш объекта (если в классе есть магический меотд eq, 
то простой вызов hash() от объекта вызовет ошибку, поэтому необходимо переопределять маг. метод hash)  
`__getitem__` - позволяет обратиться к объекту по индексу `class[i]`  
`__setitem__` - для `class[i] = x`  
`__delitem__` - для `dell class[i]`  
`__iter__` - получение итератора  
`__next__` - переход к след. знаечнию  


**@classmethod**. Не работает с локальными атрибутами класса
```
class Unit:
    x_min = 0
    x_max = 20
    @classmethod
    def check_coords(cls, x):
        return cls.x_min < x < cls.x_max
        
    def main():
        print(Unit.check_coords(10))
```
**@staticmethod**. Не работает с атрибутами класса 
```
    @staticmethod
    def pow2(x):
        return x*x
```

`dir(class)` - просмотр всех свойств класса/метода/функции  
`getattr(class, value_str)` - возвращает значение атрибута класса  
`setattr(class, value_str, value)` - устанавливает значение value для атрибута класса  
`issubclass(class1, class2)` - проверка - является ли class1 подклассом class2    


Паттерн моносостояние:
```
  class Unit:
    __atr = {}
    
    def __init__(self, hp, dmg):
        self.__dict__ = self.__atr
```
Создаёт общую ссылку на словарь атрибутов. Все объекты класса становтся одинаковы

В коллекцию `__slots__` добавляются все допустимые **локальные** свойства класса, блокирует создание новых свойств.  
Если использовать данную коллекцию, то `__dict__` не будет создан. В самом классе можно создавать любые атрибуты.  
При использовании данной коллекции будет занято меньше памяти и методы класса будут работать быстрее.
```
class Money2:
    __slots__ = ('usd')
    UDSRUB = 93
```


<a name="Jinja2"></a>
## Jinja2
`pip install Jinja2`

- {{ }} - выражение для вставки конструкций Python в шаблон
- {%%} - спецификатор шаблона
- {##} - блок комментариев
- `# ##` - строковой комментарий
```
from jinja2 import Template

bank = {'usd': 105, 'btc': 0.002}
tm = Template("USD: {{d.usd}}")
msg = tm.render(d = bank)
print(msg)
```
**Экранирование**: `{%raw%}{{d.usd}}{%endraw%}` - выведет {{d.usd}}  
Для экранирования ссылок в вэбе используется:
```
    link = '<a href="#">ref</a>'
    tm = Template("{{link | e}}")
    msg = tm.render(link = link) # &lt;a href=&#34;#&#34;&gt;ref&lt;/a&gt;
```
или
```
from markupsafe import escape

link = '<a href="#">ref</a>'
msg = escape(link)
```
**Блок for**
```
    bank = [{'coin': 'usdt', 'value': 105},
            {'coin': 'btc', 'value': 0.002},
            {'coin': 'eth', 'value': 3.4}]
    text = '''{% for c in bank -%}
    <option value="{{ c.coin }}">{{ c.value }}</option>
{% endfor -%}'''
    msg = Template(text).render(bank = bank)
    print(msg)
```
Чтобы убрать перенос строк, необходимо добавить знак **-** в начало или конец выражений: {%**-** или **-**%}

**if**
```
    text = \
    "{% for c in bank %}" \
        "{% if c.value > 0 %}"\
            "<option value=\"{{ c.coin }}\">{{ c.value }}</option>\n"\
        "{% else %}"\
            "<option value=\"{{ c.coin }}\"> - </option>\n"\
        "{% endif %}"\
    "{% endfor %}"
```
**Фильтры**  
`text = "Максимальный ордер: {{ (orders | max(attribute='value')).id_order }} id"`  
`text = "{{ orders | random }}"`
```
    text = "{% for c in coin -%}" \
           "{% filter upper %}{{c.coin}}{% endfilter %}\n" \
           "{% endfor %}"
```
**Макросы**
```
    text = '''
{%- macro input(name, value='', type='text', size=20) -%}
    <input type="{{type}}" name="{{name}}" value="{{value | e}}" size="{{size}}">
{%- endmacro -%}
    
<p>{{ input('username') }}
<p>{{ input('email') }}
<p>{{ input('password') }}
    '''
```
**call**
```
    text = '''
    {%- macro show_coins(coins) -%}
    <ul>
    {% for c in coins -%}
        <li>{{c.coin}} {{caller(c)}}
    {%- endfor -%}
    </ul>
    {%- endmacro -%}
    
    {% call(c1) show_coins(coins) %}
    <ul>
    <li>Buy: {{c1.buy}}
    <li>Sell: {{c1.sell}}
    </ul>
    {% endcall -%}
    '''
```

**Загрузчики шаблонов**

**FileSystemLoader**
```
    file_loader = FileSystemLoader('stuff')
    env = Environment(loader=file_loader)
    msg = env.get_template('w.htm').render(coins = orders)
```
Загружает html документ из папки stuff, вставляет необходимые значения в {% %}

**FunctionLoader**
```
def tmp_coin_info(c):
    if c:
        return '''{{coin | upper}}, цена: {{ price }}$, в наличии {{ qty }} ({{ price * qty }}$)'''
    else:
        return '''{{coin | upper}}, цена: {{ price }}$'''
def main():
    coin = 'btc'
    price = 61400
    qty = 0.00003
    file_loader = FunctionLoader(tmp_coin_info)
    env = Environment(loader=file_loader)
    msg = env.get_template(qty).render(coin = coin, price = price, qty = qty)
```

**include** - добавление других файлов в страницу
```
{% include 'header.html'%}
<p>Тело страницы
{% include 'footer.html'%}
```
В header.html и другие включаемые элементы можно добавлять переменные, далее они опредеяются в render  
Игронирование ненайденных файлов - `{% include 'header2.html' ignore missing %}`  
Вставка нескольких блоков:
```
{% for i in ('x1.html', 'x2.html', 'x3.html') -%}
{% include i ignore missing %}
{% endfor -%}
```
`{% include ['x3.html', 'x2.html'] ignore missing %}` - вставится один, существующий, блок

**import** - не добавляет файл, но позволяет использовать его функционал  
Использование макроса из другого файла
```
{% import 'show_info.html' as info %}
{{info.show(coin, price)}}
```
или

`{% from 'show_info.html' import show %}`

**block**  
`{% block title%}{% endblock title%}` после endblock имя блока необязательно  
`{{ self.title() }}` - повторение блока  
`{% block table %}{{ super() }}{% endblock %}` - вызов содержимого блока из родительского элемента  
`{% block item scoped %}{{ c }}{% endblock %}` - **scoped** позволяет использовать 
локальные переменные из других блоков, например, если блок item в цикле  
`{% extends 'page.html' %}` - расширяет файл (запускать необходимо файл, где прописан extends)


<a name="Базы_Данных"></a>
# Базы Данных
<a name="SQLite"></a>
# SQLite
`import sqlite3 as sq`

**Типы данных:**
- NULL - NULL
- INTEGER - целочисленный тип (1-8 байт)
- REAL - вещественный тип (8 байт)
- TEXT - строковой тип
- BLOB - двоичные данные

**Создание БД**
```
    with sq.connect('site.db') as con:
        cur = con.cursor()
        cur.execute("""CREATE TABLE IF NOT EXISTS users(
        id INTEGER PRIMARY KEY AUTOINCREMENT,
        name Text NOT NULL,
        old INTEGER,
        balance REAL NOT NULL DEFAULT 0
        )""")
```
IF NOT EXISTS для проверки на наличие уже существующей таблицы с таким названием

`cur.execute("DROP TABLE users")` **удаление таблицы**, можно добавить проверку IF EXISTS

Полям можно применять павила: PRIMARY KEY, AUTOINCREMENT, NOT NULL, DEFAULT 0

**Добавление записей**:  
`INSERT INTO users (name, old, balance) VALUES('Max', 22, 120.5)`  
`INSERT INTO users VALUES(1, 'Max', 22, 120.5)`  
`INSERT INTO users2 (id, name, old, balance) SELECT * FROM users`  
Если значения в values соответствуют всем полям в таблице, то указывать названия столбцов не обязательно  
Если название поле является зарезервированным значением, то необходимо брать его в ``  
`cur.execute("INSERT INTO users VALUES(NULL, ?, ?, ?)", user)` - добавление одной записи в виде списка  
`cur.executemany("INSERT INTO users VALUES(NULL, ?, ?, ?)", users)` - добавление нескольких записей

**ВЫбор записей**:  
`SELECT rowid, * FROM users`  
rowid - скрытое поле  
Условия для WHERE: = или == или LIKE, >, >=, <, <=, BETWEEN x AND y, IN (x, y)  
`SELECT * FROM users WHERE old BETWEEN 20 AND 40`  
`SELECT name, balance FROM users WHERE old BETWEEN 20 AND 40 AND name IN ('Max', 'Ray')`

`cur.execute("SELECT * FROM users WHERE name = :Name", {'Name': name})`

**Сортировка записей**:  
`SELECT * FROM users WHERE balance > 0 ORDER BY old DESC`  
DESC - по убыванию, ASC - по возрастанию (используется по умолчанию, можно не указывать явно)

**Ограниение кол-ва выбранных записей**:  
`SELECT * FROM users LIMIT 2 OFFSET 1` **==** `SELECT * FROM users LIMIT 1, 2`  
ВЫбираются 2 записи со смещением на 1 элемент вниз (вывод: 2, 3 id)

**Получение записей**:  
- fetchone() - выбирается первая запись
- cur.fetchmany(x) - выбираются первые x записей
- fetchall() - выбираются все записи
```
      cur.execute("SELECT * FROM users")
      res = cur.fetchone()    # (1, 'Tom', 31, 55.0)
      res2 = cur.fetchmany(2) # [(2, 'Max', 22, 120.5), (3, 'Ray', 19, 0.0)]
```

**Изменение записей**:  
`UPDATE users SET balance = balance + 100 WHERE old > 20`  
`UPDATE users SET balance = 20 WHERE name LIKE '_a%'`  
**_** - один любой символ  
**%** - любая последовательность символов

**Удаление записей**:  
`DELETE FROM users WHERE id == 3`

**Агрегирующие функции**:  
count() - число записей, sum(), avr(), min(), max()  
`SELECT count(id) as count FROM users WHERE balance > 100`  
count() можно оставить без аргументов  
Примеры:  
`SELECT id, max(balance) as balance FROM users`  
`SELECT count(DISTINCT name) FROM users` - вернёт число  
`SELECT DISTINCT name FROM users` - вернёт уникальные значения  
DISTINCT - для выбора только уникальных значений

**Группировка записей**:  
`SELECT name, sum(balance) as sum FROM users GROUP BY name ORDER BY sum`

### JOIN
```
SELECT name, sum(orders.size) as order_sum FROM orders
JOIN users ON orders.id = users.id
GROUP BY name
```
JOIN (INNER) - объединяет таблицы, но игнорирует записи с неполными данными, например, неизвестный id пользователя<br>
LEFT JOIN - работает со всеми записями, подставляет NULL в случае отсутствия параметра

### UNION
```
SELECT id, size FROM orders
UNION SELECT id, size FROM orders2
```
Объединяет таблицы, сохраняет только уникальные записи.  

### Вложенные запросы
```
SELECT name FROM orders
JOIN users ON users.id = orders.id
WHERE balance > (SELECT balance FROM users WHERE name = 'Ray')
```

### executescript
Запрос записывается в чистом виде, без подставления значений из программы.  
Через знак **;** можно писать несколько команд

В примере ниже rollback(), в случае ошибки, откатит изменения в БД до BEGIN 
```
    con = None
    try:
        con = sq.connect('site.db')
        cur = con.cursor()

        cur.executescript("""UPDATE users SET balance = balance + 1;
        BEGIN;
        UPDATE users SET balance = balance + 0.5;
        UPDATE users SET balance = balance + 0.3
        """)

        con.commit()
    except sq.Error as er:
        if con: con.rollback()
        print('Ошибка:', er)
    finally:
        if con: con.close()
```
```
    sql_req = f"""UPDATE users SET balance = balance + 200 WHERE name = '{name}';
    INSERT INTO users VALUES(NULL, '{user[0]}', {user[1]}, {user[2]})
    """
    with sq.connect('site.db') as con:
        cur = con.cursor()
        cur.executescript(sql_req)
```

**lastrowid** - возвращает rowid последней добавленной записи
```
    cur.execute("INSERT INTO users VALUES(NULL, 'Mia', 28, 240)")
    last = cur.lastrowid
    cur.execute("SELECT * FROM users WHERE rowid = ?", (last,))
```

### Обращение к записям, как к словарям
```
    with sq.connect('site.db') as con:
        con.row_factory = sq.Row
        cur = con.cursor()
        
        cur.execute("SELECT * FROM users WHERE balance > 100")
        res = cur.fetchall()
        for u in res:
            print(u['name'], round(u['balance'], 2))
```
### Добавление изображений
```
    def readImg(name):
        try:
            with open(f'img/{name}.jpg', 'rb') as i:
                return i.read()
        except Exception as ex:
            print(ex)
            return False
      ...
      img = readImg('Max')
      if img:
          img = sq.Binary(img)
          cur.execute("UPDATE users2 SET img = ? WHERE name = 'Max'", (img,))
```
### Получение изображений
```
  def saveImg(name, data):
      try:
          with open(name, 'wb') as i:
              i.write(data)
      except Exception as ex:
          print(ex)
          return False
      return True
      ...
      cur.execute("SELECT img FROM users2 WHERE name = 'Max'")
      img = cur.fetchone()[0]
      saveImg('Max.png', img)
```

### Получене запросов для формирования БД
Возможно полностью восстановить БД с помощью полученных запросов. (можно сохранить в файл .sql)
```
    with sq.connect('site.db') as con:
        for i in con.iterdump():
            print(i)
```
**Вывод**:  
CREATE TABLE orders( ...  
INSERT INTO "orders" VALUES(1,'usdt',32,0.999) ...

Затем с помощью executescript можно создать БД заново

### Создание БД в памяти
```
    con = sq.connect(':memory:')
    with con:
        ...
```

<a name="MS_SQL_Server"></a>
# MS SQL Server
`pip install pyodbc`  
`import pyodbc`

Необходимо скачать SQL Server 2022 Express и SQL Server Management Studio (SSMS)
```
connection_db = pyodbc.connect("Driver={SQL Server};Server=DESKTOP-APRV96U\SQLEXPRESS;Database=prices;Trusted_Connection=yes;")
cur = connection_db.cursor()

cur.execute(f"INSERT INTO Время_изменений VALUES('{i}', '{files[i]}')")

cur.commit()
connection_db.close()
```
Или
```
    with pyodbc.connect("Driver={SQL Server};Server=DESKTOP-APRV96U\SQLEXPRESS;Database=prices;Trusted_Connection=yes;") as con:
        cur = con.cursor()
        cur.execute("INSERT INTO res (Ключ1_поставщика, Артикул_поставщика) VALUES ('321', 'post1')")
```
Имя сервера Server и название БД Database берутся из SQL Server Management Studio


<a name="PostgreSQL"></a>
# PostgreSQL
`pip install psycopg2`

Вход в консольный вид программы (SQL Shell (psql)). Все поля, кроме пароля, можно пропустить, нажав Enter.  
Для подключения к БД: **\c DB_name**  
После каждого запроса **в консоли** добавляется точка с запятой: **SELECT * FROM users;**

Создание БД: **CREATE DATABASE db2**  
Удаление БД: **DROP DATABASE db2**  
Создание таблицы:
```
CREATE TABLE users(
	Id SERIAL PRIMARY KEY,
	Name CHARACTER VARYING(50),
	Age INTEGER
)
``` 
Удаление таблицы: **DROP TABLE users**

### Типы данных:
- **SERIAL** - целое число с автоувеличением (1 - 2147483647)
- **SMALLSERIAL** - аналог serial (1 - 32767)
- **BIGSERIAL** - аналог serial (1 - 9223372036854775807)
- **BIGINT** - от -9223372036854775808 до 9223372036854775807
- **NUMERIC** - числа с фиксированным кол-вом запятых numeric(precision, scale), precision указывает на максимальное количество цифр, которые может хранить число, scale представляет максимальное количество цифр, которые может содержать число после запятой.
- **DECIMAL** - 131072 знаков в целой части и до 16383 знаков в дробной части
- **REAL** - хранит числа с плавающей точкой из диапазона от 1E-37 до 1E+37
- **DOUBLE PRECISION** - числа с плавающей точкой из диапазона от 1E-307 до 1E+308
- **MONEY** - для работы с денежными единицами, от -92233720368547758.08 до 92233720368547758.07
- **CHARACTER** (**CHAR**) - строка с фиксированным кол-вом символов n
- **CHARACTER VARYING** (**VARCHAR**) - строка, где можно указать максимальное кол-во символов n
- **TEXT** - текст произвольной длины
- **BYTEA** - для хранения бинарных данных
- **TIMESTAMP** - хранит дату и время
- **TIMESTAMP WITH TIME ZONE** - помимо даты и времени хранит данные о часовом поясе
- **DATE** - дата
- **TIME** - время
- **TIME WITH TIME ZONE** - хранит время с точностью до 1 микросекунды с указанием часового пояса
- **INTERVAL** - временной интервал
- **BOOLEAN** - логический тип (true, TRUE, 't', 'true', 'y', 'yes', 'on', '1' / false, FALSE, 'f', 'false', 'n', 'no', 'off', '0')
- **CIDR** - хранит интернет-адрес (IPv4 и IPv6)
- **INET** - хранит интернет-адрес в формате CIDR / x, где x - кол-во бит в адресе
- **MACADDR** - MAC-адрес
- **MACADDR8** - MAC-адрес в формате EUI-64
- **POINT** - координаты (x, y)
- **LINE** - линия {A, B, C}
- **LSEG** - отрезок ((x1, y1), (x2, y2))
- **BOX** - прямоугольник ((x1, y1), (x2, y2))
- **PATH** - набор соединенных точек. Закрытый путь (многоугольник) - ((x1, y1), ... ). Открытый путь - [(x1, y1), ... ]
- **CIRCLE** - окружность <(x, y), r>
- **JSON** - json в текстовом виде
- **JSONB** - json в бинарном виде
- **UUID** - универсальный идентификатор, например, a0eebc99-9c0b-4ef8-bb6d-6bb9bd380a11 использование: `id UUID primary key default gen_random_uuid()`
- **XML** - xml


### Атрибуты:
- **PRIMARY KEY** - первичный ключ. Может быть составным, если необходимо чтобы два и боле столбцов уникально идентицицировали записи (не может быть записей, где во всех первичных ключах одинаковое значение)
- **UNIQUE** - поля будут иметь только уникальные значения
- **NULL** / **NOT NULL** - допускается ли нулевое значение
- **DEFAULT** - значение по умолчанию (DEFAULT 10)
- **CHECK** - задаёт ограничения CHECK(Age > 0 AND Age < 120). Можно задать ограничения после определения всех столбцов в таблице

С помощью оператора **CONSTRAINT** можно задать имя для ограничения, например:  
CONSTRAINT usersAgeCheck CHECK(Age > 0 AND Age < 120)

По умолчанию имя будет задано автоматически. По имени ограничения можно к нему обращаться, 
например, чтобы удалить его. Ограничения можно просмотреть в DB_name/Schemas/public/Tables/Table_name/Constraints

**Внешние ключи**  
Для установки связи между таблицами используется ключевое слово **REFERENCES**  
UserId INTEGER REFERENCES Users (Id)

**ON DELETE** и **ON UPDATE** определяют действия при удалении / изменении записи в главной таблице:
- **CASCADE** - автоматически удаляет/изменяет запись
- **RESTRICT** - отсутствуют действия
- **NO ACTION** - действие по умолчанию. Отсутствуют действия, генерирует ошибку, в отличие от RESTRICT выполняет отложенную проверку
- **SET NULL** - при удалении связанной строки устанавливает для столбца внешнего ключа NULL
- **SET DEFAULT** - устанавливает указанное значение по умолчанию (берётзя значение при объявлении поля), при удалении связанной строки

Пример (каскадное удаление):
```
CREATE TABLE Orders (
  Id SERIAL PRIMARY KEY,
  UserId INTEGER,
  ... ,
  FOREIGN KEY (UserId) REFERENCES Users (Id) ON DELETE CASCADE
)
```
Users (Id) должно быть уникальным или PRIMARY KEY

<a name="PostgreSQL_Последовательности_SEQUENCE"></a>
### Последовательности SEQUENCE
Последовательности создают автоинкремент   
SERIAL - встроенная последовательность с названием вида: test_table_id_seq  
при `create table test_table( id serial ...)`

Создать последовательность: `create sequence test_table_id_seq`  
Для её применения, можно задать её при создании талицы: `id bigint NOT NULL unique DEFAULT (nextval('test_table_id_seq'))`

Сгенерировать новый элемент последовательности: `select nextval('test_table_id_seq')`

Можно указать цикличность в последовательности: `create sequence test_table_id_seq maxvalue 4 cycle`
Тогда значения после 4 будут считаться с 1, но значения будут повторяться.
Также можно указывать **maxvalue**, **minvalue**, **start**, **increment**


Для сброса последовательности - `SELECT setval('test_table_id_seq', 1, false)`  
или `ALTER SEQUENCE test_table_id_seq restart 1`  
Но после этого id будут **повторяться**, если в таблице ещё остались данные, чтобы это обойти 
можно использовать:  
```
ALTER SEQUENCE test_table_id_seq restart 1;
update test_table set id = nextval('test_table_id_seq');
```

### Изменение таблиц
Для изменения таблиц используется выражение **ALTER TABLE**:
```
ALTER TABLE Users
ADD Email VARCHAR(50) NOT NULL
```
Возможные действия: 
- ADD столбец тип данных [ограничения]
- DROP COLUMN столбец
- ALTER COLUMN столбец параметры
- ADD [CONSTRAINT] ограничения
- DROP [CONSTRAINT] имя_ограничений

Для изменения типа столбца используется **TYPE**:  
```
ALTER TABLE Users
ALTER COLUMN Email TYPE VARCHAR(50)
```

При изменнии ограничений используется **SET**:  
```
ALTER TABLE Users
ALTER COLUMN Email
SET NOT NULL
```
Удаление ограничений **DROP** - `DROP NOT NULL`

Изменение ограничений таблицы:
```
ALTER TABLE Users
ADD UNIQUE (Email)
```
или задать имя при добавлении ограничения: `ADD CONSTRAINT UniqueEmail UNIQUE (Email)`  
Удалить ограничение по имени: `DROP CONSTRAINT UniqueEmail`

Переименование столбца: `RENAME COLUMN Email TO mail`  
Переименование таблицы: `RENAME TO Customers`

### Добавление записей INSERT
`INSERT INTO Users VALUES(1, 'Max', max@gmail.com)`  
или  
`INSERT INTO Users (name, Email) VALUES('Max', max@gmail.com)`

При добавлении записи, если присутствует UNIQUE поле, можно использовать приписку `ON CONFLICT DO NOTHING` для избежания ошибки

Можно получить данные полей (**RETURNING**), значения которые явно не указывались при добавлении:  
`INSERT INTO Users (name, Email) VALUES('Max', max@gmail.com) RETURNING Id`

### Выборка данных SELECT
`SELECT Цена * Кол_во AS Сумма FROM Products`  
`SELECT Users.name, Products.* FROM Users, Products WHERE ...`

Можно объединять столбцы в один и добавлять разделительный знак:  
`SELECT res._07Код_поставщика || ' ' || COUNT(data07.Настройка) AS info FROM res`

### Фильтрация
Операции сравнения: =, != (<>), <, >, <=, >=

Сравнение без учёта регистра - **ILIKE**

Логические операции: **AND**, **OR**, **NOT**  
AND выполняется перед OR  
**NULL** проверяется через **IS** (**IS NULL** / **IS NOT NULL**)

### Обновление данных UPDATE
`UPDATE Products SET Price = Price + 1000, Discount = 15 WHERE Price > 20000`

### Удаление
`DELETE FROM Users` - удаление всех записей, но можно добавить фильтр WHERE

Получение (retutning) кол-ва удалённых записей:
```
WITH deleted AS 
(DELETE FROM res where Производитель_поставщика = 'NOVA BRIGHT' returning *)
SELECT count(*) FROM deleted
```

<a name="PostgreSQL_DISTINCT_ORDER_BY_LIMIT_OFFSET"></a>
### Выбор уникальных значений DISTINCT
`SELECT DISTINCT name FROM Users`

### Сортировка ORDER BY
Сортировать можно не только по обычным полям, но и по выражениям:   
`SELECT * FROM Products ORDER BY Count * Price`  
По умолчанию происходит сортировка по возрастанию (ASC), можно изменить это условие, дописав в конце DESC

Можно сортировать по нескольком полям: `ORDER BY Manufacturer ASC, Price DESC`  
Вначале произойдёт сортировка по первому полю, далее, если эти поля равны, то произойдёт сортировка по второму полю 

### LIMIT, OFFSET
LIMIT позволяет выбрать первые x записей  
OFFSET указывает, с какой записи начать выбирать записи

Например, в конце select запроса можно добавить: `LIMIT 3 OFFSET 2`  
Если нужно выбрать все записи, начиная от записи x, то LIMIT не указывается или к нему дописывается ALL

Конструкция `LIMIT 3 OFFSET 2` при повторном запросе может выводить **разные результаты**, чотбы это предотвратить добавляется **ORDER BY**:  
`SELECT Ключ1_поставщика, Артикул_поставщика FROM res ORDER BY _17КодУникальности OFFSET 4 LIMIT 2`

### IN
Проверка на совпадение с элементом из списка: `WHERE name IN ('Max', 'Alex')`  
Возможен вариант с **NOT IN**

### BETWEEN
Проверка на вхождение в диапазон (включительно): `WHERE Price BETWEEN 1000 AND 5000`  
Или **NOT BETWEEN**

<a name="PostgreSQL_Регулярные_выражения_LIKE"></a>
### LIKE
Сравнивает значение с шаблоном: `WHERE name LIKE 'M%'`  
**%** используется для обозначения любого кол-ва символов, в том числе и пустой строки  
**_** обозначает любой один символ

### Регулярные выражения
Регулярные выражения как модуль re в python
`update price_list set КлючП = regexp_replace(АртикулП, '\W|_', '', 'g')`  
(\W выбирает всё, кроме цифр, букв и **нижнего подчеркивания** _ ) 

### Агрегатные функции
- **AVG** - среднее значение
- **BIT_AND** / **BIT_OR** - побитовое умножение / сложение (логическое И / ИЛИ)
- **BOOL_AND** / **BOOL_OR** - логическое умножение / сложение для bool
- **COUNT(*)** - кол-во строк в запросе
- **COUNT(expression)** - кол-во строк в запросе, где знаечние expression не NULL
- **SUM** - сумма
- **MIN** / **MAX** - минимум / максимум, не учитывают значения NULL
- **STRING_AGG(expression, delimiter)** - соединяет с помощью delimiter все текстовые значения из expression в одну строку

Примеры:  
`SELECT AVG(Price * Count) as AverageValue FROM Products`  
`SELECT COUNT(*) FROM Products`  
`SELECT COUNT(DISTINCT name) FROM Users`  
`SELECT STRING_AGG(DISTINCT name, ', ') FROM Users` Output: Max, Alex, Tom

**CONCAT** - объекдинение полей / произвольных данных  
`update tablename set cols_name CONCAT(article,' ',count,' шт.')`

### GROUP BY
```
SELECT Manufacturer, COUNT(*)
FROM Products
GROUP BY Manufacturer
```
### HAVING
Аналог WHERE для GROUP BY 
```
SELECT Manufacturer, COUNT(*)
FROM Products
WHERE Price > 1000
GROUP BY Manufacturer
HAVING COUNT(*) > 1
ORDER BY COUNT(*) DESC
```
### GROUPING SETS
Объединяет несколько групп в одной таблице
```
SELECT Manufacturer, COUNT(*) AS Models, ProductCount
FROM Products
GROUP BY GROUPING SETS(Manufacturer, ProductCount)
```
Таблица будет условно разбира на две части: Manufacturer и Models ; Models и ProductCount
N1 5 null  
N2 8 null  
null 3 6  
null 2 4
### ROLLUP
Добавляет суммирующую строку в результирующий набор
```
SELECT Manufacturer, COUNT(*) AS Models, ProductCount
FROM Products
GROUP UP ROLLUP(Manufacturer)
```
или при нескольких критериях можно получить суммирующую строку для каждой группы:  
GROUP UP ROLLUP(Manufacturer, ProductCount)
### CUBE
Похож на ROLLUP, но добавляет суммирующие строки для каждой комбинации групп

### Подазапросы
`SELECT * FROM Products WHERE Price > (SELECT AVG(Price)FROM Products)`

### Массивы
`tags VARCHAR(20)[]`  
`INSERT INTO servers (name, refs) VALUES ('Название', '{"vk.com/", "t.me/"}')`

Выборка определённых значений: `SELECT tags[1:3] FROM servers`  
Измененеи конкретного значения: `UPDATE servers SET tags[2] = 'site.com'`

<a name="PostgreSQL_Перечисления_enum"></a>
### Перечисления enum
```
CREATE TYPE server_status AS enum ('run', 'stopped');
CREATE TABLE servers(
  id SERIAL PRIMARY KEY,
  name VARCHAR(50) UNIQUE,
  status server_status
)
```
При добавлении записей поле status может принимать только данные из enum

Изменение перечисления:
`ALTER TYPE server_status ADD 'blocked'`

Просто так удалить enum нельзя, можно создать новый enum и заменить на него:
```
ALTER TABLE servers ALTER COLUMN server_status TYPE new_status
USING server_status::text::new_status
```
Удаление: `DROP TYPE server_status`

<a name="PostgreSQL_JOIN"></a>
### Объединение JOIN
```
SELECT res._17КодУникальности, data07.Настройка, data07.Отсрочка
FROM res
JOIN data07 ON data07.Настройка = res._07Код_поставщика
```
Объединяет таблицы по условям после ON

**LEFT JOIN** берёт все значения из первой таблицы, записям, которые не совпадают по условию, добавляется NULL  
**RIGHT JOIN** и **FULL JOIN** работают по аналогии

Примеры:  
Для каждой записи из таблицы res будет выведена доступная информация или NULL:
```
SELECT res._17КодУникальности, data07.Настройка, data07.Отсрочка, data15.ЦенаБ
FROM res
LEFT JOIN data07 ON data07.Настройка = res._07Код_поставщика
LEFT JOIN data15 ON data15._15 = res._15КодТутОптТорг
```
Выбор записей, данных которых нет во второй таблице:
```
SELECT res._17КодУникальности FROM res
LEFT JOIN data07 ON data07.Настройка = res._07Код_поставщика
WHERE data07.Настройка IS NULL
```
При WHERE res._07Код_поставщика IS NULL работать не будет, в этом примере нужно обращаться ко второй таблице

Выведет кол-во совпадающих записей:
```
SELECT res._07Код_поставщика, COUNT(data07.Настройка) FROM res
LEFT JOIN data07 ON data07.Настройка = res._07Код_поставщика
GROUP BY res._07Код_поставщика
```
Сумма количества всех записей, у которых совпадают условия в join:
```
SELECT SUM(S.C) FROM (SELECT COUNT(data07.Настройка) AS C FROM res
JOIN data07 ON data07.Настройка = res._07Код_поставщика
GROUP BY res._07Код_поставщика) AS S
```
или вариант с итоговой строкой:
```
SELECT res._07Код_поставщика, COUNT(data07.Настройка) FROM res
JOIN data07 ON data07.Настройка = res._07Код_поставщика
GROUP BY ROLLUP(res._07Код_поставщика)
```
**CROSS JOIN** - декартово произведение, перемножаются все записи (выводит n1 * n2 записей), то же самое, что и SELECT * FROM Users, Products

<a name="PostgreSQL_UNION_EXCEPT_INTERSECT"></a>
### Объединение таблиц UNION
При объекдинении типы данных должны совпадать
```
SELECT name, age FROM Users
UNION SELECT name, age FROM Employees
```
Выберутся только уникальные записи, но с помощью UNION ALL выведутся и повторяющиеся записи

### Разность множеств EXCEPT
Можно выбрать данные из первой таблицы, которые не совпадают с данными из второй таблицы:
```
SELECT _07Код_поставщика FROM res
EXCEPT SELECT Настройка FROM data07
```
Если поменять содержимое SELECT`ов местами, то результат изменится

### Пересечение множеств INTERSECT
```
SELECT _07Код_поставщика FROM res
INTERSECT SELECT Настройка FROM data07
```
Пример выборки данных, которые не пересекаются:
```
SELECT _07Код_поставщика FROM res
UNION SELECT Настройка FROM data07
EXCEPT SELECT _07Код_поставщика FROM res
INTERSECT SELECT Настройка FROM data07
```

<a name="PostgreSQL_Оконные_функции"></a>
### Оконные функции
Добавление доп столбца с номером строки:
```
select id, pay_method, cost, user_id,
row_number() OVER () as num
from orders
```
В **OVER** можно добавлять сортировку и группировку  
`OVER (partition by user_id order by cost)`  
В каждой группе **user_id** будет применена выбранная функция. Например, row_number 
будет устанавливать свою нумерацию строк в каждой группе

| user_id | num |
|---------|-----|
| 1       | 1   |
| 1       | 2   |
| 2       | 1   |
| 2       | 2   |

`sum(cost) OVER (order by cost) as sum_cost`  
Тут будет указана сума полей от первой строки до текущей:

| cost  | sum_cost |
|-------|----------|
| 500   | 500      |
| 2500  | 3000     |

Без order by будет выведена общая сумма значений в каждой строке

Несколько одинаковых **OVER** можно вынести отдельно с помощью **WINDOW**:
```
select id, pay_method, cost, user_id,
sum(cost) OVER w,
avg(cost) OVER w::int
from orders
WINDOW w as (partition by user_id order by cost)
```

Оконные функции работают с результатом выборки, в них нельзя использовать where  
Можно использовать подзапрос для использования **WHERE**:
```
select * from(
select id, pay_method, cost, user_id,
sum(cost) OVER (partition by user_id order by cost) as sum_cost
from orders) where sum_cost > 1000
```
Пример функции **lag** (ищет строки перед последней строкой фрейма):
```
select id, pay_method, cost, user_id,
lag(cost) OVER (order by cost DESC) - cost as lag_cost
from orders
```
Тут cost сравнивается с предыдущим значением, выводится их разница

| cost | lag_cost |
|------|--------|
| 8000 | [null] |
| 4000 | 4000   |
| 2500 | 1500 |


<a name="PostgreSQL_пример_psycopg2"></a>
### Пример в python
```
import psycopg2

host = "127.0.0.1"
user = "postgres"
password = "123456"
db_name = "prices"

  connection = psycopg2.connect(host=host, user=user, password=password, database=db_name)
  with connection.cursor() as cur:
      cur.execute("DELETE FROM data07")
  connection.commit()
  connection.close()
```

### WITH (CTE)
with содержит вложенный запрос и позволяет далее сортировать и тд новые столбцы
```
with info_table as (
select id, pay_method, cost, user_id,
sum(cost) OVER (partition by user_id order by cost) as sum_cost
from orders)
select * from info_table order by sum_cost
```

<a name="PostgreSQL_Оптимизация_INDEX"></a>
### Оптимизация
Повторные аналогичные запросы кэшируются и далее их обтаботка происходит почти моментально, 
максимальный кэш для Postgres указывается в параметре **shared_buffers** (\PostgreSQL\17\data\postgresql.conf).  
Команда для вывода этого параметра: **show shared_buffers**

Для быстрого выполнения запросов используется индексация полей:  
`CREATE INDEX res_04_code_index ON res(04Код)`  
По умолчанию тип индекса - Сбалансированное дерево (**btree**), подходит для операций обычных операций по типу: >, <, =

Чтобы ускорить работу операторов LIKE, ILIKE используется тип индекса **gin**:  
`CREATE INDEX res_14_index ON res USING gin (_14Производитель_заполнен gin_trgm_ops)`  
Для этого нужно доп. расширение **pg_trgm**: `CREATE EXTENSION IF NOT EXISTS pg_trgm`

Добавление/удаление индексов: **CREATE**/**DROP**  
Просмотр всех индексов: `SELECT * FROM pg_indexes where schemaname = 'public'`  
В одном интексе можно указать **несколько** полей, если нужно оптимизировать запрос с AND  

<a name="PostgreSQL_Удалённое_подключение_к_БД"></a>
### Удалённое подключение БД к другому компьютеру
В \PostgreSQL\17\data\pg_hba.conf добавляется строка после  
`# TYPE  DATABASE        USER            ADDRESS                 METHOD`  
**host    all             all             127.0.0.1/32            scram-sha-256**  

Подставляется **IPv4** компьютера клиента  
Далее лучше остановить службу Postgres  
На сервере в Брандмауэр/Дополнительные параметры - добавляется новое правило во входящие запросы.  
**Настройка правила**:  
1. Для порта
2. Протокол TCP, определённый порт: 5432
3. Разрешить подключение
4.  (+) Доменный, (+) Частный, (+) Публичный
5. Произвольное имя

Включить службу Postgres  
С клиентской машины подключаться к БД по IPv4 сервера  
Чтобы обращаться с сервера к БД, нужно добавить в pg_hba.conf IPv4 сервера или использовать 127.0.0.1

<a name="PostgreSQL_Ошибки"></a>
### Ошибки
`psycopg2.errors.InFailedSqlTransaction: ОШИБКА: текущая транзакция прервана, 
команды до конца блока транзакции игнорируются`  
Ошибка выполнения запроса, исправляется откатом до момена выполнения комманды: `connection.rollback()` 


<a name="SQLAlchemy"></a>
# SQLAlchemy
`pip install sqlalchemy`

<a name="SQLAlchemy_синхронные_асинхронные_запросы"></a>
### Синхронные запросы
Для PostgreSQL `pip install psycopg2`
```
from sqlalchemy import create_engine, text
import psycopg2

engine = create_engine("postgresql+psycopg2://postgres:pass@localhost:5432/test_db")
# engine = create_async_engine(url=db_url)
def main():
    with engine.connect() as con:
        res = con.execute(text("select count(*) from users"))
        print(f"{res.first()=}") # res.first()=(1000,)
```
Сырые запросы необходимо оборачивать в смециальную функцию **text**

Параметр **echo** для отображения в консоли информации о запросах  
**pool_size** - кол-во одновременных подключений к БД  
**max_overflow** - максимальное кол-во доп. подключений к БД (если кол-во подключенй уже равно pool_size)

### Асинхронные запросы
```
from sqlalchemy.ext.asyncio import create_async_engine
import asyncio
import asyncpg

engine = create_async_engine("postgresql+asyncpg://postgres:pass@localhost:5432/test_db")
# engine = create_async_engine(url=db_url)
async def main():
    async with engine.connect() as con:
        res = await con.execute(text("select count(*) from users"))
        print(f"{res.first()=}") # res.first()=(1000,)
```
engine.**connect**() - **без** коммита в конце  
engine.**begin**() - **с** коммитом в конце

<a name="SQLAlchemy_Создание_таблиц"></a>
### Создание таблиц
models.py:
```
from sqlalchemy import Table, Column, MetaData, Integer, String

metadata_obj = MetaData()

products_table = Table('products', metadata_obj,
                       Column('id', Integer, primary_key=True),
                       Column("name", String))
```
main.py:
```
from models import metadata_obj
metadata_obj.create_all(engine)
```
Для удаления всех записей из таблицы: `metadata_obj.drop_all(engine)`  
Можно менять состояние echo до запросов и после: `engine.echo = False`

<a name="SQLAlchemy_Insert"></a>
### Insert
```
from sqlalchemy import insert
from models import metadata_obj, products_table

def insert_into_db():
    with engine.connect() as con:
        req = insert(products_table).values(
            [{"name": "Аккумулятор"},
             {"name": "Батарейка"}]
        )
        con.execute(req) # без text
        con.commit()
```

Проверка на длину поля перед добавлением:  
models.py:
```
from sqlalchemy import event
...
@event.listens_for(UsersOrm, 'before_insert')
def check_len(mapped, connect, target):
    if len(target.name) > 150:
        target.name = target.name[:150]
```

<a name="SQLAlchemy_Работа_с_сессиями"></a>
### Работа с сессиями
```
from sqlalchemy.orm import sessionmaker

session = sessionmaker(engine)
with session() as sess:
    res = sess.execute ...
```
или при асинхронной работе: `from sqlalchemy.ext.asyncio import async_sessionmaker`

<a name="SQLAlchemy_insert_in_ORM"></a>
### insert in ORM (add / add_all)
models.py:
```
from sqlalchemy import String
from sqlalchemy.orm import DeclarativeBase, Mapped, mapped_column

class Base(DeclarativeBase):
    pass

class ProductsOrm(Base):
    __tablename__ = "products"
    id: Mapped[int] = mapped_column(primary_key=True)
    name: Mapped[str] = mapped_column(String(150)) # ограничение символов
```
main.py:
```
from models import ProductsOrm

def insert_into_db():
    with session() as sess:
        product_hook = ProductsOrm(name='Hook')
        product_nail = ProductsOrm(name='Nail')
        sess.add_all([product_hook, product_nail])
        sess.commit()
```
При асинхронной работе:
```
async def insert_into_db():
    async with session() as sess:
        product_hook_a = ProductsOrm(name='Hook (A)')
        sess.add(product_hook_a)
        await sess.commit()
```

<a name="SQLAlchemy_Создание_таблиц_через_классы"></a>
### Создание таблиц через классы
(enum, допустимое NULL значение, каскадное удаление, время создания / изменнеия записи)

models.py:
```
from sqlalchemy import String, ForeignKey, text
from sqlalchemy.orm import DeclarativeBase, Mapped, mapped_column
import enum
import datetime
from typing import Annotated

# Можно задавать шаблоны типов данных в базовом классе
str_150 = Annotated[str, 150] 
class Base(DeclarativeBase):
    type_annotation_map = {
        str_150: String(150)
    }
    
intpk = Annotated[int, mapped_column(primary_key=True)] # отдельный шаблон для типов данных

class UsersOrm(Base):
    __tablename__ = "users"
    id: Mapped[intpk]
    name: Mapped[str_150]
    # или name: Mapped[str] = mapped_column(String(10))

class PayMethod(enum.Enum): # enum в БД
    card = "card"
    cash = "cash"

class OrdersOrm(Base):
    __tablename__ = "orders"
    id: Mapped[intpk]
    pay_method: Mapped[PayMethod] # enum
    addition: Mapped[str | None] # / mapped_column(nullable=True) / Optional[str] (from typing import Optional)
    user_id: Mapped[int] = mapped_column(ForeignKey("users.id", ondelete="CASCADE"))
    created_at: Mapped[datetime.datetime] = mapped_column(
        server_default=text("TIMEZONE('utc', now())")) # На уровне БД
    updated_at: Mapped[datetime.datetime] = mapped_column(
        server_default=text("TIMEZONE('utc', now())"),
        onupdate=lambda t=datetime.UTC: datetime.datetime.now) # onupdate на уровне ORM
```
main.py (меняется только объект с метаданными):
```
from models import Base
Base.metadata.create_all(engine)
```
Создание **отдельных** таблиц:
```
class Base_1(DeclarativeBase):
    pass
class MyTmpTable(Base):
    ...
```
Для этого определяется новый класс **Base_1** в models, далее от него наследуется группа 
моделей, с которой необходимо отдельно взаимодействовать, например, `Base_1.metadata.create_all(engine)`


**Удалить** таблицу (drop):
```
from sqlalchemy import inspect

inspct = inspect(engine)
if inspct.has_table(Price_1.__tablename__):
    Price_1.__table__.drop(engine)  # без with session() ...
```
Если удалить таблицу в `with session() as sess:`, то программа может зависнуть

Проверка на существование таблицы, затем удаление, чтобы опять создать таблицу: `Base.metadata.create_all(engine)`

Выключить **autovacuum**:  
`sess.execute(text(f"ALTER TABLE {Price_1.__tablename__} SET (autovacuum_enabled = false);"))`  
Полезно для временных таблиц, в которых производятся большие расчёты и далее данные передаются в другую таблицу


<a name="SQLAlchemy_Тип_полей"></a>
### Тип полей
```
import uuid
from sqlalchemy import REAL, String, Uuid, text, Integer, Numeric

uuidpk = Annotated[uuid.UUID, mapped_column(Uuid, primary_key=True, server_default=text("gen_random_uuid()"))]
str_x = lambda x:Annotated[String, mapped_column(String(x), nullable=True)]
intgr = Annotated[int, mapped_column(Integer, nullable=True)]
real = Annotated[REAL, mapped_column(REAL, nullable=True)]
numeric = Annotated[Numeric, mapped_column(Numeric(12,2), nullable=True)]
```

<a name="SQLAlchemy_func"></a>
### func
**Дополнтиельный столбец**
```
from sqlalchemy import func
dupl = select(func.concat(children_price).label('_07supplier_code'), *cols_for_total.keys()).where(Price_1._07supplier_code == price_code)
sess.execute(insert(TotalPrice_1).from_select(['_07supplier_code', *cols_for_total.values()], dupl))
```
**CONCAT** объединяет данные (поля, произвольный текст)

**COUNT()**:  
`cnt = sess.execute(select(func.count()).select_from(Price_1)).scalar()`

**FLOOR** округление до целого в меньшую сторону

**func.regexp_substr** пример с получением первых 3х слов:
```
sess.execute(update(Price_1).where(Price_1._07supplier_code == price_code)
.values(_18short_name=func.regexp_substr(Price_1._03name, r'(\S+.){1,2}(\S+){0,1}')))
```

**regexp_replace** пример с удалением лишних пробелов:
```
sess.execute(update(Price_1).where(Price_1._07supplier_code == price_code)
                            .values(_01article=Price_1._01article.regexp_replace(' +', ' ', 'g')
                                     .regexp_replace('^ | $', '', 'g')))
```

<a name="SQLAlchemy_select_update"></a>
### select
```
from sqlalchemy import select
res = con.execute(select(ProductsOrm)).all()
```
`res.scalars().all()` вернёт не список кортежей, а обычный список
### update
В текст сырого запроса не подставляются данные через f строку
```
def update_product_name(id, new_name):
    with engine.connect() as con:
        req = text("UPDATE products SET name=:new_name WHERE id=:id")
        req = req.bindparams(new_name=new_name, id=id)
        con.execute(req)
        con.commit()
```
Не через сырой запрос:  
`from sqlalchemy import update`  
**where**  
`req = (update(ProductsOrm).values(name=new_name).where(ProductsOrm.id==id))`  
(в случае с объектом Table - `where(ProductsTable.c.id==id)`)

**filter_by** (без указания таблицы)  
`req = (update(ProductsOrm).values(name=new_name).filter_by(id=id))`

`engine = create_engine("postgresql://postgres:098-=-@localhost/price_processing")`

<a name="SQLAlchemy_select_update_через_ORM"></a>
### select через ORM
Если первичный ключ один, то передаётся проосто один параметр 
```
def select_products_orm():
    with session() as sess:
        req = select(ProductsOrm)
        res = sess.execute(req)
        print(res.scalars().all())
```
Пример (переименование столбца, приведение столбца к типу int, агрегатные функции,
LIKE, GROUP BY):  
_SQL_:
```
select pay_method, avg(cost)::int as avg_cost from orders 
where cost > 0 and (addition not LIKE '%canceled%' or addition is NULL) 
group by pay_method
```
```
from sqlalchemy import select, func, cast, Integer, or_, and_, not_

with session() as sess:
    query = select(OrdersOrm.pay_method, cast(func.avg(OrdersOrm.cost), Integer).label("avg_cost")
                   ).select_from(OrdersOrm
                   ).where(and_(OrdersOrm.cost > 0, 
                   or_(not_(OrdersOrm.addition.contains("canceled")), OrdersOrm.addition == None))
                   ).group_by(OrdersOrm.pay_method)
    print(query.compile(compile_kwargs={'literal_binds': True}))
    res = sess.execute(query).all()
    print(res[0].avg_cost)
```
**compile** позволяет подставить в запрос выбранные параметры при его отображении в консоли  
В res можно обращаться к полям, в том числе к переименованным столбцам


### update через ORM
Выполняется 2 запроса: получение объеквта и изменение. Через сырые запросы быстрее
```
def update_product_orm(id, new_name):
    with session() as sess:
        product_nail = sess.get(ProductsOrm, {'id':id})
        product_nail.name = new_name
        # sess.flush()
        sess.commit()
```
**.flush()** отправляет данные в БД, но не делает коммит, можно использовать для формирования дефолт значений у объекта  
**.expire_all()** / **.expire(product_obj)** - отменяет все изменения у всех объектов / у конкретного  
**.refresh(product_obj)** - обновляет актуальные на текущий момент данные у объекта

### delete через ORM
```
from sqlalchemy import delete
with session() as sess:
    sess.execute(delete(Data07))
    sess.commit()
```
или   
`sess.query(PriceReport).where(PriceReport.price_code == price_code).delete()`

<a name="SQLAlchemy_JOIN_OVER_WITH"></a>
### Пример с JOIN, OVER, WITH
_SQL_:
```
with info_table as (
select *, cost-avg_cost as cost_diff from (
select ord.user_id, ord.pay_method, ord.cost, u.name, 
avg(cost) OVER (partition by pay_method)::int as avg_cost
from orders ord join users u on user_id = u.id) as sub_t)
select * from info_table order by cost_diff DESC
```
```
from sqlalchemy.orm import aliased

ord = aliased(OrdersOrm)
u = aliased(UsersOrm)
subq = select(
    ord, u,
    func.avg(ord.cost).over(partition_by=ord.pay_method).cast(Integer).label("avg_cost")
).join(u, ord.user_id == u.id).subquery("sub_t")
cte = select(
    subq.c.user_id, subq.c.pay_method, subq.c.cost, subq.c.name, subq.c.avg_cost,
    (subq.c.cost - subq.c.avg_cost).label("cost_diff")
).cte("info_table")
query = select(cte).order_by(cte.c.cost_diff.desc())
```

<a name="SQLAlchemy_Relationship"></a>
### Relationship
models.py:
```
from sqlalchemy.orm import relationship

class UserOrm(Base):
    ...
    orders: Mapped[list["OrdersOrm"]] = relationship(back_populates="user")

class OrdersOrm(Base):
    ...
    user: Mapped["UserOrm"] = relationship(back_populates="orders")
```
**Ленивый** запрос:
```
with (session() as sess):
    query = select(UserOrm)
    res = sess.execute(query)
    res = res.scalars().all() # scalars для конвертации к модели

    user1 = res[0].orders
    print(user1)
    user2 = res[1].orders
    print(user2)
```
Тут будет сделано 3 запроса: получение всех пользователей, получение 
информации по каждому указанному пользователю.

Вариант с **joinedload**:
```
query = select(UserOrm).options(joinedload(UserOrm.orders))
res = sess.execute(query)
res = res.unique().scalars().all() # unique выполнится на стороне питона
```
Будет сделан 1 запрос, новых запросов при обращении к конкретным пользователям не будет

**selectinload** выполяет 2 запроса, выборка конкретных пользователей 
и загрузку данных по всем этим пользователям:  
`select(UserOrm).options(selectinload(UserOrm.orders))`

**joinedload** лучше использовать при m2o, o2o  
**selectinload** лучше использовать при o2m, m2om

relationship c условием и сортировкой:
```
class UserOrm(Base):
    ...
    orders_card: Mapped[list["OrdersOrm"]] = 
      relationship(back_populates="user",
      primaryjoin=("and_(UserOrm.id==OrdersOrm.user_id, OrdersOrm.pay_method=='card')"),
      order_by="OrdersOrm.cost.desc()")
```
```
query = select(UserOrm).options(selectinload(UserOrm.orders_card))
        res = sess.execute(query)
        res = res.scalars().all()
        for u in res:
            print(u.orders_card)
```
Также в relationship есть параметр `lazy='selectin'`, отвечающий за 
  тип подгрузки (joinedload/selectinload), но лучше выбирать тип в `... options(selectinload ...`

`from sqlalchemy.orm import contains_eager`  
**contains_eager** уменьшает кол-во запросов к БД, уменьшая кол-во подгружаемых связей  
`query = select(UserOrm).join(UserOrm.orders).options(contains_eager(UserOrm.orders)).where(OrdersOrm.pay_method=='card')`

<a name="SQLAlchemy_Вывод_информации_о_моделях_в_консоль"></a>
### Вывод информации о моделях в консоль
```
class Base(DeclarativeBase):
    def __repr__(self):
        cols = []
        for c in self.__table__.columns.keys():
            cols.append(f"{c}={getattr(self, c)}")
        return f"<{self.__class__.__name__} {', '.join(cols)}>"
```
Переопределяется метод **__repr__** в базовой модели (models.py)

<a name="SQLAlchemy_LIMIT"></a>
### LIMIT
Выбор одного самого дорогого заказа у каждого пользователя:
```
subq = select(OrdersOrm.id).filter(OrdersOrm.user_id==UserOrm.id).order_by(OrdersOrm.cost.desc()).limit(1).scalar_subquery().correlate(UserOrm)
query = select(UserOrm).join(OrdersOrm, OrdersOrm.id.in_(subq)).options(contains_eager(UserOrm.orders))
res = sess.execute(query)
res = res.unique().scalars().all()

for u in res:
    print(u.orders)
```

<a name="SQLAlchemy_INDEX_CHECK"></a>
### INDEX, CHECK
```
from sqlalchemy import Index, CheckConstraint

class OrdersOrm(Base):
    ...
    __table_args__ = (
        Index("user_id_id_index", "user_id", "id"),
        CheckConstraint("cost >= 0", name="cost_check")
    )
```
Индекс типа **Hash** (только ядл операции ==)  
`Index("sum_table_id_compare_hash_index", "id_compare", postgresql_using="hash"),`


<a name="SQLAlchemy_Конвертация_моделей_в_pydantic"></a>
### Конвертация моделей в pydantic
`pip install pydantic`  
Конвертирует ответ алхимии в pydantic модель для удобной работы, например, для дальнейшей конвертации в json

Для начала надо описать модели, например, schemas.py:
```
from pydantic import BaseModel
from models import PayMethod

class UsersAddDTO(BaseModel):
    name: str

class UsersDTO(UsersAddDTO):
    id: int

class OrdersAddDTO(BaseModel):
    cost: int
    pay_method: PayMethod
    addition: str | None

class OrdersDTO(OrdersAddDTO):
    id: int

class UsersRelDTO(UsersDTO):
    orders: list["OrdersDTO"]

class OrdersRelDTO(OrdersDTO):
    user: "UsersDTO"
```
```
from schemas import UsersDTO

res = sess.execute(select(UsersOrm)).scalars().all()
print([UsersDTO.model_validate(row, from_attributes=True) for row in res])
# [UsersDTO(name='Mia', id=1), UsersDTO(name='Alex', id=2)]
```

При **relationship**:  
```
res = [UsersRelDTO.model_validate(row, from_attributes=True) for row in res]
# [UsersRelDTO(name='Mia', id=1, orders=[OrdersDTO(cost=4000, pay_method=<PayMethod.card: 'card'>, addition=None, id=1), OrdersDTO(...
```
Для запросов, которые возвращают не модель, а произвольные данные, можно создать свой pydantic класс:
```
class AvgCostDTO(BaseModel):
    name: str
    avg_cost: int
    
req = select(UsersOrm.name, cast(func.avg(OrdersOrm.cost), Integer).label("avg_cost")).join(UsersOrm.orders).group_by(UsersOrm.name)
res = sess.execute(req).all()
print([AvgCostDTO.model_validate(row, from_attributes=True) for row in res])
```

<a name="SQLAlchemy_Связь_Many_to_Many"></a>
### Связь Many to Many
Связь просиходит через доп. таблицу (ProductsAndTagsRelOrm)
models.py:
```
class ProductsOrm(Base):
    __tablename__ = "products"
    id: Mapped[intpk]
    name: Mapped[str_150]

    tags_rel: Mapped[list["TagsOrm"]] = relationship(
        back_populates="products_rel", secondary="products_tags_rel",
    )

class TagsOrm(Base):
    __tablename__ = "tags"
    id: Mapped[intpk]
    name: Mapped[str] = String(100)

    products_rel: Mapped[list["ProductsOrm"]] = relationship(
        back_populates="tags_rel", secondary="products_tags_rel",
    )

class ProductsAndTagsRelOrm(Base):
    __tablename__ = "products_tags_rel"
    priduct_id: Mapped[int] = mapped_column(ForeignKey("products.id", ondelete="CASCADE"), primary_key=True)
    tag_id: Mapped[int] = mapped_column(ForeignKey("tags.id", ondelete="CASCADE"), primary_key=True)

```
main.py:
```
query = select(ProductsOrm).options(selectinload(ProductsOrm.tags_rel))
res = sess.execute(query)
res = res.unique().scalars().all()
```



<a name="PyQt"></a>
# PyQt
`pip install PyQt5`

В Qt Designer создается шаблон в формате .ui (имеет структуру xml). В процессе создания окна можно запустить его в тестовом режиме: From - Preview

Для вставки текста используется элемент Label, внутри поля можно установить отступы margin. 
Чтобы поменять стили, нужно нажать ПКМ по бъекту в окне Object Inspector, далее change styleSheet.

Для того чтобы импортировать шаблон в программу нужно сначала конвертировать его в код.  
`pip install pyqt5-tools`  
Далее в терминале: `pyuic5 -x main.ui(шаблон) -o form.py(название нового файла)`  
Для PySide: `pyside6-uic your_file.ui -o ui_your_file.py`
В новом файле будет находиться код, создающий окно, например:
```
from PyQt5 import QtCore, QtGui, QtWidgets

class Ui_MainWindow(object):
    def setupUi(self, MainWindow):
        MainWindow.setObjectName("MainWindow")
        self.SendButton = QtWidgets.QPushButton(self.centralwidget)
        self.SendButton.setGeometry(QtCore.QRect(400, 320, 75, 23))
        self.SendButton.setObjectName("SendButton")
        ...
        self.retranslateUi(MainWindow)
        QtCore.QMetaObject.connectSlotsByName(MainWindow)

    def retranslateUi(self, MainWindow):
        _translate = QtCore.QCoreApplication.translate
        ...
        self.RemoveButton.setText(_translate("MainWindow", "remove"))
    
if __name__ == "__main__":
    import sys
    app = QtWidgets.QApplication(sys.argv)
    MainWindow = QtWidgets.QMainWindow()
    ui = Ui_MainWindow()
    ui.setupUi(MainWindow)
    MainWindow.show()
    sys.exit(app.exec_())
```

### Добавление функционала к кнопкам
В методе setupUi класса Ui_MainWindow дописывается self.add_functions()  
Далее новый метод объявляется:
```
    def add_functions(self):
        Buttons = [self.AddButton, self.RemoveButton, self.SendButton]
        for b in Buttons:
            b.clicked.connect(lambda _, t=b.text(): self.print_info(t))

    def print_info(self, x):
        print(x)
```

### Многопоточность
Запуск функций по кнопкам, если функция не завершила свою работу программа не зависнет и будет возможность продолжать пользоваться другими элементами меню
```
class Ui_MainWindow(object):
    ...
    def add_functions(self):
        self.AddButton.clicked.connect(lambda _, x=1, t=self.AddButton.text(): self.qprint(x, t, self.AddButton))
        
    def qprint3(self, x, t, btn):
        self.act2 = Action(x, t)
        self.act2.startSignal.connect(lambda _, b=btn: self.setEnabled(b))

        self.t2 = QtCore.QThread()
        self.act2.moveToThread(self.t2)
        self.t2.started.connect(self.act2.start)
        self.act2.finishSignal.connect(self.t2.quit)
        self.t2.start()

        self.act2.finishSignal.connect(lambda _, b=self.AddButton: self.setInfo(b))
     
    def setInfo(self, b):
        b.setEnabled(not b.isEnabled())


class Action(QtCore.QObject):
    startSignal = QtCore.pyqtSignal(int)
    finishSignal = QtCore.pyqtSignal(int)
    def __init__(self, x, t):
        super(Action, self).__init__()
        self.x = x
        self.t = t

    def start(self):
        self.startSignal.emit(1)
        time.sleep(self.x)
        print(self.t)
        self.finishSignal.emit(1)
```
другой вариант:
```
class Ui_MainWindow(object):
    ...
    def refresh_log_1(self):
        self.t = ThreadAction(self)
        self.t.printSignal.connect(self.print_log_1)
        self.t.start()

    def print_log_1(self, t):
        self.textBrowser_1.setPlainText(t)
        self.textBrowser_1.moveCursor(QtGui.QTextCursor.End)

class ThreadAction(QtCore.QThread):
    printSignal = QtCore.pyqtSignal(str)
    log_file_1 = 'calculate_res.log'
    def __init__(self, mainApp=None):
        super(ThreadAction, self).__init__()
        self.mainApp = mainApp

    def run(self):
        while True:
            try:
                if os.path.exists(self.log_file_1):
                    with open(self.log_file_1, 'r') as f:
                        l = f.readlines()[-max_log_lines:]
                        l = ''.join(l)
                        self.printSignal.emit(l)
            except Exception as ex:
                print('Main Error:', ex)
            time.sleep(3)
```

### Всплывающие окна
```
from PyQt5.QtWidgets import QMessageBox

    def push(self):
        ErrorMsg = QMessageBox()
        ErrorMsg.setWindowTitle('Ошибка')
        ErrorMsg.setText('Процесс прерван')
        ErrorMsg.setIcon(QMessageBox.Warning)
        ErrorMsg.setStandardButtons(QMessageBox.Reset|QMessageBox.Ok|QMessageBox.Cancel)
        ErrorMsg.setDefaultButton(QMessageBox.Ok)
        ErrorMsg.setInformativeText("Функция завершилась с ошибкой")
        ErrorMsg.setDetailedText("Код ошибки: 2403")
        ErrorMsg.buttonClicked.connect(self.error_actions)

        ErrorMsg.exec_()

    def error_actions(self, btn):
        if btn.text() == 'OK':    # именно капсом
            print('Ok')
        elif btn.text() == 'Reset':
            print('Reset')
```
Кнопки Ok, Cancel и Reset просто закрывают окно
- **setWindowTitle** - название окна
- **setText** - заголовок внутри окна
- **setIcon** - устанавливает иконку в сплывающем окне
- **setStandardButtons** - устанавливаются кнопки для окна, перечесляются через черту |
- **setDefaultButton** - подсвечивает кнопку
- **setInformativeText** - основное тело окна
- **setDetailedText** - добавляет кнопку "Show Details" и после показывает в новом поле указанный текст
- **buttonClicked** - для обработки нажатий на кнопки в окне

### Элементы в Qt Designer
- **Tab Widget** - для создания вкладок
- **Vertical Layout** - пространство, в котором все элементы добавляются сверху вниз и занимают 100% ширины

### Заполнение таблицы
```
from PyQt5.QtWidgets import QTableWidgetItem

    headers = ['mail', 'path', 'type']
    items_name = ['Название', 'Название + расширение', 'Часть']
    
    self.tableWidget.setColumnCount(len(headers))
    self.tableWidget.setHorizontalHeaderLabels(headers)
    self.tableWidget.setColumnWidth(0, 170)
    self.tableWidget.setColumnWidth(1, 200)
    self.tableWidget.setRowCount(len(data))

    for id, m in enumerate(data):
        conv_cols_cb = QtWidgets.QComboBox()
        conv_cols_cb.addItems(items_name)
        for i in self.items_db:
            if m[2] == self.items_db[i]:
                conv_cols_cb.setCurrentIndex(i)
        self.tableWidget.setItem(id, 0, QTableWidgetItem(m[0]))
        self.tableWidget.setItem(id, 1, QTableWidgetItem(m[1]))
        self.tableWidget.setCellWidget(id, 2, conv_cols_cb)
```
**setColumnWidth** для изменения размера столбца  
**setRowCount** задаёт длину таблицы  

**QTableWidgetItem** добавляет текст в ячейку (если может папость число, лучше обернуть значение в **str()**)  
**QtWidgets.QComboBox()** - создаётся выпадающий список, далее с помощью **setCellWidget** виджет добавляется в ячейку  
**setCurrentIndex** - устанавливается элемент по умолчанию

Для запрета на **редактирование** таблицы: `self.SettingsTable.setEditTriggers(QtWidgets.QAbstractItemView.NoEditTriggers)`

Чтобы нельзя было редактировать ячейки можно вставлять в них текстовый объект **QLabel**:
```
  tx = QtWidgets.QLabel(str(d[c]))
  tx.setStyleSheet("padding-left: 2px;")
  self.FilesTable.setCellWidget(id, c, tx)
```

Изменить **цвет** ячейки:  
```
from PyQt5.QtGui import QColor
self.FilesTable.item(self.selected_row, 2).setBackground(QColor(169, 252, 187))
```

**Добавление действия** при изменении ячейки: `self.FilesTable.cellChanged.connect(self.ChangeItem)` (удаление - disconnect)



<a name="PySide"></a>
# PySide6
`pip install PySide6`
 
Создание py файла с UI: `pyside6-uic your_file.ui -o ui_your_file.py`

```
import sys
from PySide6.QtWidgets import QApplication, QMainWindow
from price_processing_2_ui import Ui_MainWindow

class MainWindow(QMainWindow, Ui_MainWindow):
    def __init__(self):
        QMainWindow.__init__(self)
        self.setupUi(self)
        
def main():
    app = QApplication(sys.argv)
    window = MainWindow()
    window.show()
    app.exec()
```

### QThread, Signal, emit, Slog
Запуск задачи в фоновом процессе, не блокирую основной процесс для UI.  
Пример 1:
```
from PySide6.QtCore import QThread, Signal, Slot

class NewQthread(QThread):
    textSignal = Signal(str)
    
    def __init__(self, parent=None):
        QThread.__init__(self, parent)
    
    def run(self):
        print('start T')
        time.sleep(3)
        self.textSignal.emit('finish T')
 
class MainWindow(QMainWindow, Ui_MainWindow):
    def __init__(self):
        QMainWindow.__init__(self)
        self.setupUi(self)
        self.Start_Button.clicked.connect(self.StartSearching)
        
    def StartSearching(self):
        self.newThread = NewQthread()
        self.newThread.textSignal.connect(self.getSignal)
        if not self.newThread.isRunning():
            self.newThread.start()
            
    @Slot(str)
    def getSignal(self, msg):
        print('text:', msg)
```
Пример 2:
```
class LoopThread(QThread):
    SetButtonEnabledSignal = Signal(bool)

    def __init__(self, parent=None):
        QThread.__init__(self, parent)

    def run(self):
      self.SetButtonEnabledSignal.emit(False)
     
class MainWindow(QMainWindow, Ui_MainWindow):
    def __init__(self):
        ...
        self.LThread = LoopThread()
        self.LThread.SetButtonEnabledSignal.connect(lambda _: self.set_enabled_start_buttons(_, self.pushButton, self.checkBox))
        self.pushButton.clicked.connect(self.start_thread)
       
    def start_thread(self):
        if self.LThread.isRunning():
            return
        self.LThread.start()
```


### Таблица QTableView
```
self.model = QStandardItemModel()
self.model.setHorizontalHeaderLabels(['Code', 'Status', 'Time'])
self.tableView.setModel(self.model)
self.tableView.verticalHeader().hide()
self.tableView.setEditTriggers(QTableView.NoEditTriggers)
self.tableView.horizontalHeader().setSectionResizeMode(1, QHeaderView.ResizeMode.Stretch)

def add():
    d = [1, 'MIK', '0:00:15']
    data = [QStandardItem(i) for i in d]
    self.model.appendRow(data)
    
def remove():
    self.model.removeRow(1)
    
def edit():
    self.model.setData(self.model.index(0,1), 'TEST')
```


### multiprocessing (Pipe)
Pipe поздаёт 2 объекта (sender и listener), которые позволяют общаться с запущенными процессами (multiprocessing.Pool).  
Обычные сигналы в процесс не передать.
```
from PySide6.QtCore import QThread, Signal
import multiprocessing as mp
from multiprocessing import Pipe

class MultiThread(QThread):
    def __init__(self, sender, parent=None):
        self.sender = sender
        QThread.__init__(self, parent)

    def run(self):
        with multiprocessing.Pool(processes=2) as pool:
            args = [[i, self.sender] for i in range(3)]
            pool.map(MultFunc, args)

def MultFunc(args):
    i, q_ = args
    time.sleep(1)
    q_.send([i, 'abc'])

class ListenerThread(QThread):
    def __init__(self, listener, parent=None):
        self.listener = listener
        QThread.__init__(self, parent)

    def run(self):
        while True:
            print(self.listener.recv())


class MainWindow(QMainWindow, Ui_MainWindow):
    def __init__(self):
        self.sender, self.listener = Pipe()
        self.MT = MultiThread(self.sender)
        self.LT = ListenerThread(self.listener)
        self.LT.start()
    
    def start_mult(self):
        self.MT.start()
```

### QFileDialog
Выбор файла из проводника
```
from PySide6.QtWidgets import QFileDialog
...
    self.FileBrowse_Button.clicked.connect(self.FileSelect)
    
    def FileSelect(self):
        file_name = QFileDialog.getOpenFileName(filter='Excel File (*.xlsx *.xls)')[0]
        if file_name:
            self.Path_lineEdit.setText(file_name)
```

### Дополнительно
`self.Logs_textBrowser.setOpenExternalLinks(True)` - для возможности переходить по ссылкам (`<a href='{url}'>`) в _textBrowser_



<a name="Django"></a>
# Django
<a name="Django_Установка_Django"></a>
## Установка Django
В командной строке перейти в папку с будущим проектом, далее:  
Установка виртуального окружения: `py -m venv djvenv`  
Запуск виртуальной среды(activate.bat): `.\djvenv\Scripts\activate`  
Закрыть виртуальную среду: `deactivate`

При открытии проекта в pycharm должна автоматически создасться виртуальная среда, 
иначе необходимо добавить её вручную Settings - Project: django_project - Python Interpretator - Add - 
Virtual Environment - Exsisting - path to python.exe

Далее `pip install django==4.2.1`

Создание нового проекта django: `django-admin startproject (sitename)`

Запуск локального сервера (перед этим сначала надо перейти в папку с сайтом cd sitename):  
`python manage.py runserver` (**порт**, по умолчанию - 8000)

Для остановки сервера: **ctrl+c** в терминале

Добавление приложения: `python manage.py startapp name`  
Для регистрации приложения необходимо добавить в settings.py параметр **name.apps.nameConfig** 
(берётся класс из apps.py) в список **INSTALLED_APPS**


<a name="Django_Представления"></a>
## Представления
Добавление рабочего каталога: ПКМ по каталогу (папка с названием проекта) - Mark Directory as - Sources Root  
В каталоге приложения, в views.py, добавляются функции, возвращающие страницы:
```
from django.http import HttpResponse

def index(request):
    return HttpResponse("Сервера:")
```
Далее их необходимо добавить в **SiteName/urls.py**:  
```
from django.urls import path, include

urlpatterns = [
    path('admin/', admin.site.urls),
    path('', include('monitoring.urls')),
]
```
Но лучшей практикой будет создать отдельный файл **urls.py** в разделе с приложением:
```
from django.urls import path
from monitoring import views

urlpatterns = [
    path('', views.index),
    path('versions/', views.versions),
]
```
path ' ' - обозначает пустой домен (http://127.0.0.1:8000/)


<a name="Django_Конверторы"></a>
## Конверторы
Добавление паттерна с произвольным значением:  
`path('versions/<slug:v>/, views.versions),`  
Однотипные пути будут обрабатываться по очереди, поэтому сначала надо описывать паттерн 
`versions/int/` потом `versions/slug/`
```
def versions(request, v):
    return HttpResponse(f"<h3>Версия {v}</h3>")
```

Конверторы:
- **str** - строка, без символов /
- **int** - целые положительные числа
- **slug** - набор латинских символов, цифр, -, _
- **uuid** - цифры, малые лат. символы и -
- **path** - str с символом /

Создание своего класса-конвертера (converters.py):
```
class VersionsConverter:
    regex = "[0-9]{2}"

    def to_python(self, value):
        return int(value)

    def to_url(self, value):
        return "%02d" % value
```
Регистрация конвертера:
```
from django.urls import path, register_converter
from . import converters

register_converter(converters.VersionsConverter, 'version')

urlpatterns = [ path('versions/<version:v>', views.versions), ]
```


<a name="Django_Отладка_проекта"></a>
## Отладка проекта
Настройка запуска локального сервера с возможностью отладки.

Edit Configurations... (возле кнопки запуска) - "+" (Add New Configuration)  
Working Directory: .../django/SiteName  
Script path: .../django/SiteName/manage.py  
Parameters: runserver

### GET POST
`http://127.0.0.1:8000/versions/?serv=MinePixel&online=25`  
`path('versions/', views.versions)`

request хранит словари GET и POST
```
def versions(request):
    print(request.GET)
```


<a name="Django_Page_not_found"></a>
## Page not found 404
Для настройки страницы необходимо в **settings.py**:
```
DEBUG = False
ALLOWED_HOSTS = ['127.0.0.1']
```
В **urls.py** определяется переменная **handler404**
```
from monitoring.views import page_not_found
handler404 = page_not_found
```
views.py:
```
from django.http import HttpResponseNotFound

def page_not_found(request, exception):
    return HttpResponseNotFound("<h1>Страница не найдена</h1>")
```
Далее можно вызывать страницу 404 самому, используя `raise Http404`, импортируя Http404 из django.http


<a name="Django_redirect"></a>
## redirect
(301 - страница перемещена на другой постоянный url адрес, 302 - на временный)  
`from django.shortcuts import redirect`  
`return redirect('/')` - переадресация на начальную страницу (код 302)  
`return redirect('/', permanent=True)` - код 301

`return redirect(add_server, param)`  
redirect на другие страницы работает только если они добавлены в urlpatterns 

или через name:  
`path('versions/', views.add_server, name='v')`  
`return redirect('v')`

**reverse**:  
```
from django.urls import reverse

red = reverse('v', args=(11,))
return redirect(red)
```
или вместо redirect можно импортировать из django.http _HttpResponseRedirect_ (302) и _HttpResponsePermanentRedirect_ (301)


<a name="Django_Шаблоны"></a>
## Шаблоны
`from django.template.loader import render_to_string`

`view-source:http://127.0.0.1:8000/` в браузере для просмотра html кода

Если шаблон сохранен в: app_name/templates/index.html то можно указать только название шаблона.  
Если приложений несколько, то лучше в templates создать папку с именем приложения  
**app_name / templates / app_name / index.html**
```
    t = render_to_string('app_name/index.html')
    return HttpResponse(t)
```
или
```
from django.shortcuts import render

return render(request, 'monitoring/index.html')
```

Передача данных в шаблоны:
```
  def index(request):
    server_1 = { 'name': 'MinePixel', 'online': 25}
    data = {
        'name': 'Список серверов:',
        'server': server_1
    }
    return render(request, 'monitoring/index.html', data)
```
html:
```
<h1>{{ name }}</h1>
<p>{{ server.name }} online: {{ server.online }}</p>
```
Обращение через точку происходит к ключам вложенных словарей

**Шаблонные фильтры**  
`{{ server.online|add:"7" }}` (также происходит преобразование к int)

- **capfirst** - делает первую букву заглавной
- **upper / lower**
- **cut** - удаляет символы, можно применять несколько раз (name|cut:"a"|cut:"bc")
- **default** - значение по умолчанию
- **divisibleby** - проверка числа на кратность x, возвращает True/False (сначала преобразует к int)
- **first / last** - первый и последний элемент списка/кортежа
- **join**
- **length** - длина списка/кортежа
- **slugify** - приводит пеерменную к slug (Server Name => server-name)
- **linebreaks** - добавляет переносы строк, если передан многострочный текст
- **truncatewords:x** - оставляет только первые x слов, далее добавляет "..."
- **truncatechars:x** - первые x символов

Все фильтры: https://docs.djangoproject.com/en/4.2/ref/templates/builtins/

Фильтры можно использовать в самой программе на python:  
`from django.template.defaultfilters import slugify`

**Отключение экранирования**: `{% autoescape off %} {% endautoescape %}`  
Также позволяет отображать html блоки не в виде обычного текста <..>

### if, for
Подусловия **в скобках не работают**!
```
    {% for s in servers %}
    <li> <b>{{ s.name }}</b> online: {{ s.online }} </li>
    {% if not forloop.last %}
    <hr>
    {% endif %}
    {% endfor %}
```
Объект forloop создаётся в каждом цикле, хранит значения **first, last, counter, revcounter, parentloop** 

### with
```
{% with server.tags.all as tags %}
  {% for t in tags %}
  <p>{{ t }}</p>
  {% endfor %}
{% endwith %}
```

### url
`<``a href="{% url 'server' s.id %}">{{ s.name }}<``/a>`  
После имени 'server' указываются параметры, они могут быть именованными (id=s.id)

В html указывается имя из urlpatterns:  
`path('server/<``int:server_id>', views.server, name='server')`


<a name="Django_Наследование_шаблонов_extends"></a>
## Наследование шаблонов extends
Создаётся папка templates в корневой папке сайта, путь к ней добавляется в settings.py, 
TEMPLATES - 'DIRS': **BASE_DIR / 'templates'**

В данной папке создаётся общий шаблон, например, с шапкой, в body пишется: {% block content %}{% endblock %}

Далее сами страницы лишь расширяют общий шаблон:
```
{% extends 'base.html' %}

{% block content %}
<h1>{{ name }}</h1>
{% endblock %}
```


<a name="Django_Включение_других_элементов_страницы_include"></a>
## Включение других элементов страницы include
`{% include 'monitoring/includes/SocialMedia.html' %}`  
Внутри включенного элемента **можно использовать переменные** из основного блока html.  
Использование переменных можно отключить, добавив **only** после пути к включаемому объекту html.  
Можно передать новые переменные с помощью **with x=2 y=3**.


<a name="Django_Подключение_статических_файлов"></a>
## Подключение статических файлов
В папке приложения создаётся каталог static, далее /name_app и в нём все необходимые папки со
статическими данными (css, js, images)  
Перед запуском проекта на **рабочем сервере** необходимо создать общую папку static, 
добавить её в STATIC_ROOT, далее (**python manage.py collectstatic**)    
Дополнительные пути к static папкам можно добавить в settings.py `STATICFILES_DIR = [ '.../static' ]`

```
{% load static %}

<link rel="stylesheet" 
href="{% static 'monitoring/css/add_server_form.css' %}">
```

Чтобы в режиме **DEBUG = False** на локальном сервере отображалась статика:  
`python manage.py runserver --insecure`


<a name="Django_Пользовательские_теги_шаблонов"></a>
## Пользовательские теги шаблонов
Создаётся папка templatetags в папке приложения, туда добавляется пустой __ init__.py 
и файл для описания тегов .py  
servers_tags.py:
```
from django import template
import monitoring.views as views

register = template.Library()

@register.simple_tag()
def get_versions():
    return views.versions_db
```
Для использования в html необходимо загрузить теги: `{% load servers_tags %}`  
При вызове `{% get_versions %}` выведется вся информация из return (**переберать get_versions в for нельзя**)  
При `{% get_versions as versions %}` ничего не будет выведено, а лишь создасться переменная versions, которую **можно** перебрать в **for**  
Можно указывать имя для тега `@register.simple_tag(name='get_v')` и обращаться по имени, а не через get_versions

Тег для вставки html кода (**inclusion_tag**)
```
@register.inclusion_tag('monitoring/versions_list.html')
def show_versions(selected_v=''):
    versions = views.versions_db
    return {'versions': versions, 'selected_v': selected_v}
```
`{% show_versions selected_v=vr %}`


<a name="Django_БД"></a>
## БД
Подключение **Postgres**:  
`pip install psycopg2`  
settings.py:
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'db_name',
        'USER': 'postgres',
        'PASSWORD': 'pass',
        'HOST': '127.0.0.1',
        'PORT': '5432'
    }
}
```

Модели описываются в models.py:
```
from django.db import models

class Servers(models.Model):
    name = models.CharField(max_length=30)
```
Параметры:
- **max_length** - максимальная длина символов/максимальный размер в байтах, если файл бинарный
- **blank** - возможность оставить поле пустым (True/False)
- **auto_now_add** - для времени. Сохраняет время создания записи
- **auto_now** - для времени. Сохраняет время обновления записи
- **default** - значение по умолчанию
- **db_index** - индексация параметра (True)
- **unique** - True, если параметр должен принимать только уникальные значения
- **on_delete** - поведение при удалении поля (подробнее ниже)
- **null** - True, если значение NULL допустимо

Если при обновлении models.py необходимо добавить поле с ключом unique=True, то сначала 
добавляется пустое поле, далее применяется миграция, после необходимо заполнить его уникальными
данными и далее установить unique=True и применить снова миграцию

Создание файла миграции:  
D:\Documents\django\testsite> **python manage.py makemigrations**

**python manage.py sqlmigrate monitoring 0001** - для вывода в терминал запроса sql,
генерирующего таблицу

Создание таблиц в БД - **python manage.py migrate**

Переход в оболочку django: **python manage.py shell**  
Выход - **quit()**

`from monitoring.models import Servers`
```
s1 = Servers(ip='1.2.3', name='abc')
s1.ip # вывод поля
s1.save()
```
**_** - содержит на последний созданный объект  
можно `s1.ip = '1.1.1'`


Просмотр истории sql запросов:
```
from django.db import connection
connection.queries  # / [-1]
```

Для установки улучшенной версии оболочки джанго можно установить пакет **ipython** (выход из консоли - **exit**)

Для удобства также можно использовать пакет **django-extensions**   
После установки необходимо в settings.py **INSTALLED_APPS** добавить **'django_extensions'**

`python manage.py shell_plus --print-sql`

Ключ **--print-sql** сразу выводит sql запросы
Ключ **--print-sql** сразу выводит sql запросы

Создание записей сразу, без save():  
`Items.objects.create(name='Glock-18 | Дух воды', price=240, count=3)`

Отобразить записи - `Servers.objects.all()` или млжно указать определённое кол-во записей
в [ ], тогда к sql запросу применится LIMIT  
Для отображения необходимой информации можно переопределить метод str в models.py
```
    def __str__(self):
        return f"({self.pk}) {self.name}"
```
**WHERE/WHERE NOT**

Выбор записей с условиями - **filter** (`Servers.objects.filter(version="1.12.2")`), возвращает список объектов  
Исключение записей с определёнными параметрами - **exclude**  
Выбор только **уникальных** записей - filter(...)**.distinct**

**Выбор SELECT**:

`Servers.objects.all()` / `Servers.objects.values()` / `Servers.objects.values('name', 'ip')`  

Можно выбирать поля из связанных таблиц:  
`Items.objects.values("name", "rare__name")`

**get** - возвращает только одну запись, при отсутствии записи с 
выбранными параметрами генерирует ошибку, не работает с лукапами (gte и тд)

**Lookups**:  
__gte **>=** ; __gt **>** ; __lte **<=** ; __lt **<**  
`Servers.objects.filter(point__gt=22)`

- **__contains** - атрибут включает в себя указанную часть  
- **__icontains** - без учета регистра (для SQLite не работает)
- **__in**=(20,32) - луюбое значение в скобках
- **__startswith** - поиск только сначала
- **__isnull** - True/False

через запятую перечисляются все условия (AND, а для OR нужен класс Q)  
`Items.objects.filter(name__icontains='А', pk__gt=1)`

---

**Сортировка ORDER BY**  
Сортировка по возрастанию: `Servers.objects.filter(online__gt=0).order_by("version")`  
По убыванию: `"-version"`

Для сортировки по умолчанию (Items.objects.all(), filte и тд), при выводе записей:
```
class Servers(models.Model):
    name = models.CharField(max_length=30)
    ...

    class Meta:
        ordering = ['point']  # '-point'
```
Также в Meta можно добавить индексацию:  
`indexes = [models.Index(fields=['-point'])]`  
Так данные будут отсортированы и уменьшится скорость выполнения sql запросов  

**Изменение** данных:  
```
s = Servers.objects.get(pk=2)
s.name = "newName"
s.save()
```
Изменение параметров сразу во всех записях: `Servers.objects.update(point=0)`  
Применять update к подобным `all()[1:4]` записям нельзя.  
Изменять определённые записи: `Items.objects.filter(pk__gt=1).update(count=5)`  
Можно изменять выборки данных:
```
items = Items.objects.filter(pk__gt=1)
items.update(count=3)
```

**Удаление** записей: `Servers.objects.filter(pk=3).delete()`

**Добавление поля с unique=True**  
Сначала выполняется миграция с _blank=True_ и _default=''_
```
class Items(models.Model):
    slug = models.SlugField(max_length=150, blank=True, db_index=True, default='')
```
`python manage.py makemigrations`  
`python manage.py migrate`  
`python manage.py shell_plus --print-sql`  
```
for i in Items.objects.all():
 ...:     i.slug = 'slug-'+str(i.pk)
 ...:     i.save()
```
`slug = models.SlugField(max_length=150, unique=True, db_index=True)`  
`python manage.py makemigrations`  
`python manage.py migrate`


<a name="Django_get_absolute_url"></a>
## get_absolute_url
Ссылка на запись **get_absolute_url** в models.py:
```
    def get_absolute_url(self):
        return reverse('item_info', kwargs={'item_slug': self.slug})
```
Вызов: `<a href="{{ s.get_absolute_url }}">`


<a name="Django_Пользовательский_менеджер_модели"></a>
## Пользовательский менеджер модели
В models добавляется новый класс:
```
class NotZeroPointManager(models.Manager):
    def get_queryset(self):
        return super().get_queryset().filter(point__gt=0)
```
Далее создаётся его объект и objects, чтобы можно было обращаться к обычному менеджеру:
```
class Servers(models.Model):
    ...
    objects = models.Manager()
    pointed = NotZeroPointManager()
```
`servers = Servers.pointed.all()`


**Choices**  
Позволяет хранить несколько значений с их метками
```
class Servers(models.Model):
    class VersionList(models.TextChoices):
        V_1_12_2 = '1.12.2', 'Версия 1.12.2'
        V_1_16_5 = '1.16.5', 'Версия 1.16.5'
        V_1_21 = '1.21', 'Версия 1.21'

    version = models.CharField(choices=VersionList.choices, default=VersionList.V_1_21)
```
```
Servers.VersionList.choices   # [('1.12.2', 'Версия 1.12.2'), ...]
Servers.VersionList.labels    # ['Версия 1.12.2', ...]
Servers.VersionList.values    # ['1.12.2', ...]
```


<a name="Django_Связи_моделей"></a>
## Связи моделей
Значения параметра **on_delete**:
- models.CASCADE - при удалении записи из первичный модели происходит удаление из всех других
- models.PORTECT - запрещает удаление записи из первичный модели, если она используется ещё где-то
- models.SET_NULL - при удалении из первичный модели во вторичных устанавливается NULL
- models.SET_DEFAULT - после удаления устанавливает значение по умолчанию, которое определяется через класс ForeignKey
- models.DO_NOTHING

Для формирования связи **many-to-one**:
```
class Servers(models.Model):
    version = models.ForeignKey('VersionList', on_delete=models.PROTECT, null=True)
    
class VersionList(models.Model):
    v = models.CharField(max_length=15)
```
После миграции нужно добавить записи в VersionList и далее присвоить всем записям в 
Servers значение version_id отличное от NULL.  
После этого можно убрать параметр null=True в version и выполнить миграцию снова, выбрав 2) Ignore for now

Теперь при обращении к записи из Servers можно обратиться к version.v  
Люкапы можно применять к `version.v__in=[1,2]`, так и к `version.v_id__in=[1,2]`  
Можно передавать объект модели:
```
types = ItemType.objects.filter(pk__in=[2,3])
Items.objects.filter(item_type__in=types)
```

ORM-команды many-to-one. Получение всех записей из основной таблицы по выбранной категории 
(атрибут - **ModelName_set**):  
```
v = VersionList.objects.get(v='1.12.2')
v.servers_set.all() # для таблицы Servers
```
Вместо servers_set можно указать атрибут для обратного связывания **related_name**:  
`version = models.ForeignKey(... related_name='versions')` 

Список версий можно использовать в фильтре:
```
vers = VersionList.objects.all()
Servers.objects.filter(version__in=vers)
```
Использование поля из первичной модели (**foreignkey__attr**):  
`Items.objects.filter(item_type__slug='Desert_Eagle')`  
Дополнительно можно прописывать и _люкапы_ (**item_type__slug__contains**)  
Или поля из вторичной модели:  
`VersionList.objects.filter(versions__point__gt=0)`

Для первичной модели можно тоже указать метод **get_absolute_url**:  
`def get_absolute_url(self): return reverse('home', kwargs={'item_type': self.slug})`


**many-to-many**  
Создаётся класс для связи (в примере назван TagsList), далее в основной класс добавляется:  
`tags = models.ManyToManyField('TagsList', blank=True, related_name='tags')`  
После миграции создадуться две таблицы: для контента и для связи.

**Установка** связи set:
```
s = Servers.objects.get(pk=4)
s.tags.set(TagsList.objects.filter(pk__in=[1, 6, 7]))
```
s.tags.set() - передяется 1 тег / список тегов  
```
tag_st, tag_sv = ItemTags.objects.filter(name__in=['StatTrak', 'Сувенирное'])
i = Items.objects.get(pk=7)
i.tags.set([tag_st, tag_sv])
```
Задавать связь прямо во время создания записи (create) нельзя.

**Добавление** связи add:  
`s.tags.add(TagsList.objects.get(pk=6))`  
add принимает id и добавляется только один тэг, который надо взять или через get или filter()[0]
Добавлять можно через обе таблицы: `i.tags.add(tag_st)` или `tag_st.tag_r.add(i2)` (related_name='tag_r')

**Удаление** связи remove:  
`s.tags.remove(TagsList.objects.get(pk=5))` или `i.tags.remove(tag_sv)`

**Вывод** тегов: `s.tags.all()`

Просмотр связей тега (берётся _related_name_):  
`tag.tags.all()`

В шаблонах html:  
`{% with server.tags.all as tags %} {% for t in tags %} ... {% endfor %} {% endwith %}`

**one-to-one**  
`refs = models.OneToOneField(...)`
```
s = Servers.objects.get(name__contains='OldSchool')
sm  = SocialMedia.objects.get(vk__contains='OldSchool')
s.refs = sm
s.save()
```
или
```
s2 = StickerSets.objects.create(stkr_set='drop | Paris 2023;;;')
i2 = Items.notNullCount.get(pk=9)
s1.stickers = i2  # related_name='stickers' в основной модели
i2.save()
``` 
Если значение меняется через связующую переменную (sm.refs = s), то сохранять нужно 
всё равно s. Сохраняется тот объект, в котором произошли изменения.  
Через основную модель можно менять поля в связанной:
```
s.refs.vk = 'newVk'
s.refs.save()
```


<a name="Django_Класс_Q"></a>
## Класс Q
`from django.db.models import Q`

Примеры:  
`Servers.objects.filter((Q(point__gt=0) & ~Q(point=140)) | Q(version_id=1))`    
WHERE ((point > 0 AND NOT (point = 140)) OR version_id = 1)

`Items.objects.filter(Q(count__gt=0), Q(price__gt=400) | Q(quality_id__gt=4))`  
WHERE (count > 0 AND (price > 400 OR quality_id > 4))

`Items.objects.filter(Q(count__gt=0) & Q(price__gt=400) | Q(quality_id__gt=4))`
WHERE ((count > 0 AND price > 400) OR quality_id > 4)

**&** - AND; **|** - OR; **~** - NOT

Возможно формировать условия отдельно:
```
conditions = []
conditions.append(Q(item_type__in=item_types))
Items.notNullCount.filter(*conditions).select_related('rare')
```

**first/last**  
`Servers.objects.first()` вернётся первая запись из выборки

**latest/earliest** - запись с наибольшим/наименьшем значением  
`Servers.objects.earliest("point")`

Для полей с временными значениями можно использовать **get_previous_by_...** / **get_next_by_...** (подставляется необходимое поле)  
Поле **не должено** быть **null=True**
```
s = Servers.objects.get(pk=4)
s.get_previous_by_time_create()
s.get_next_by_time_create(pk__gt=3)
```
Проверка на наличие записей **exists**  
Проверка записей с определённым тегом, используется атрибут для обратного связывания 'tags' 
```
t = TagsList.objects.get(pk=1)
t.tags.exists()   # False/True
```
**count** для вывода кол-ва записей
```
t.tags.count()  # кол-во
t.tags.all()    # <QuerySet [...]>
```


<a name="Django_Класс_F"></a>
## Класс F
`from django.db.models import F`

Для использования значений из полей этой же записи в sql запросах  
`Servers.objects.filter(point__gt=F("online"))`  
`Items.objects.update(price=F('price')*1.1)`  
`s.point = F("point")+1` + s.save()


<a name="Django_Добавление_новых_временных_полей"></a>
## Добавление новых временных полей
Добавление временного поля для выборки со значением по умолчанию:
```
from django.db.models import Value
lst = Items.objects.annotate(new_col=Value(10))

for id, i in enumerate(lst):
    if id == 0:
        print(list(i.__dict__)[1:])
    print(list(i.__dict__.values())[1:])

```
В annotate при использовании **F**, уже не нужен класс Value:  
`lst = Items.objects.filter(price__lt=1000).annotate(summ=F('price') * F('count'))`

Можно объявлять несоклько полей:  
`lst = Items.objects.filter(price__lt=1000).annotate(summ=F('price') * F('count'), new_s=F('summ') * Decimal('1.1'))`


<a name="Django_Агрегирующие_функции"></a>
## Агрегирующие функции
`from django.db.models import Avg, Count, Max, Min, Sum`

`Servers.objects.aggregate(Max("online"))` Out: {'online__max': 2360}

`Servers.objects.aggregate(x=Sum("online")/Sum("point"))` Out: {'x': 20}


<a name="Django_GROUP_BY"></a>
## GROUP BY
Объединение записей по полю version_id. В _Count_ указывается любое поле
`Servers.objects.values("version_id").annotate(total=Count("id"))`

Out:  
`<QuerySet [{'version_id': 1, 'total': 2}, {'version_id': 2, 'total': 1}, {'version_id': 3, 'total': 1}]>`

**GROUP BY** происходит в конструкциях, где сначала идёт **values**, затем **annotate**

Подсчёт записей для каждой категории.   
Новые переменные можно использовать сразу же в фильтре. В примере используется поле для обратного связывания (related_name='rare_r').  
`lst = Rare.objects.annotate(total=Count('rare_r')).filter(total__gt=0).order_by('pk')`

Импорт **функций** применяемых на стороне СУБД:  
`from django.db.models.functions import Length`  
`Items.objects.values('name').annotate(len_name=Length('name'))`


<a name="Django_Django_Debug_Toolbar"></a>
## Django Debug Toolbar
`pip install django-debug-toolbar`

Установка: https://django-debug-toolbar.readthedocs.io/en/latest/installation.html

Для обычного проекта:  
Добавить в settings.py MIDDLEWARE - `"debug_toolbar.middleware.DebugToolbarMiddleware",`  
Добавить `INTERNAL_IPS = ["127.0.0.1"]`  
В INSTALLED_APPS - `"debug_toolbar",`

В testsite/urls.py:
```
from debug_toolbar.toolbar import debug_toolbar_urls
urlpatterns = [ ... ] + debug_toolbar_urls()
```


<a name="Django_Оптимизация_запросов"></a>
## Оптимизация запросов
В Django Debug Toolbar можно посмотреть SQL запросы для каждой страницы.   
Запросы помеченные как **similar queries** или **Duplicated n times** лучше оптимизировать. 
Для этого прописывается:

**select_related** - "жадная" загрузка связанных данных по ключу типа ForeignKey  
**prefetch_related** "жадная" загрузка связанных данных по ключу типа ManyToManyField

В views.py, в функциях:
`servers = Servers.objects.all().select_related("version")`

Далее все подзапросы объединятся в один с помощью _JOIN_


<a name="Django_Админ_панель"></a>
## Админ панель
Для удобства можно поменять язык в settings.py c `LANGUAGE_CODE = 'en-us'` на  `ru-RU`

Создание супер-пользователя:  
`python manage.py createsuperuser`

Регистрация модели в admin.py:
```
from .models import Servers
admin.site.register(Servers)
```
Теперь в http://127.0.0.1:8000/admin после авторизации появится добавленная модель, где 
можно будет редактировать её поля. Справа вверху будет кнопка "_Смотреть на сайте_" только если 
в моделе указан метод get_absolute_url

В ` def __str__` у всех моделей должно возвращаться **str**, например, `return f'{self.name} {self.pk}'`

Изменение заголовков админ панели в site\urls.py:  
`admin.site.site_header = "Панель администрирования"`  
`admin.site.index_title = "Мониторинг серверов"`

Изменение названия модели в models.py - class Servers - class Meta:  
`verbose_name = "Сервера"` для ед. числа  
`verbose_name_plural = "Сервера"` для множественного числа

Изменение названия таблицы с моделями в apps.py - class MonitoringConfig:  
`verbose_name = "Сервера"`

**Отображение полей в таблице**. admin.py:
```
@admin.register(Servers)
class ServersAdmin(admin.ModelAdmin):
    list_display = ('id', 'name', 'version', 'online', 'point')
    list_display_links = ('id', 'name')  # кликабельные поля
    ordering = ['point', 'id']  # сортировка
```
При добавлении декоратора строка `admin.site.register(Servers, ServersAdmin)` уже **не нужна**  
В **list_display** можно прописывать поля из **связанных таблиц** `rare__slug`  
Для связанных таблиц будет выводиться значение из метода `__str__`

Чтобы переименовать поля в шапке таблицы необходимо в models.py нужным значениям 
добавить параметр `verbose_name = "имя"`

Для редактирования значений в таблице необходимо в соответствующем классе в admin.py 
добавить `list_editable = ('version', )` (именно кортеж).  
Редактируемое поле не может быть кликабельным (list_display_links)

**Пагинация страниц** в admin.py: `list_per_page = 20`

**Добавление собственного поля**  
admin.py:
```
@admin.register(Items)
class ItemsAdmin(admin.ModelAdmin):
    list_display = ('name', 'price', 'count', 'rare', 'show_sum')
    ...
    @admin.display(description='Сумма', ordering='price')
    def show_sum(self, items: Items):
        return f"{items.price * items.count} р."
```
Новый метод добавляется в **list_display**  
Для возможности сортировать по столбцу прописывается **ordering**

**Добавление действия над выбранными записями**  
admin.py:
```
from django.contrib import admin, messages

@admin.register(Items)
class ItemsAdmin(admin.ModelAdmin):
    ...
    actions = ['set_null_count']
    
    @admin.action(description='Установить кол-во 0')
    def set_null_count(self, request, queryset):
        updated_rows = queryset.update(count=0)
        self.message_user(request, f"Для {updated_rows} предметов установлено кол-во 0", 
                            messages.WARNING)
```
self.message_user для вывода сообщения в админ панеле после применения действия  
Чтобы изменить вид уведомления можно добавить messages.WARNING (Знак '!' на желтом фоне)

Для корректного отображения полей типа **BooleanField** в админ панели:
```
class Servers(models.Model):
    class Status(models.IntegerChoices):
        ACTIVE = 1, 'Работает',
        INACTIVE = 0, 'Не работает'
       
    status = models.BooleanField(choices=tuple(map(lambda x: (bool(x[0]), x[1]), Status.choices)),
                                  default=Status.INACTIVE, verbose_name="Статус")
```

**Поиск по полям**. Добавляет строку для ввода сверху, ищет указанный фрагмент хотя бы в одном поле  
`search_fields = ['name__startwith', 'tags__name']`

**Добавить фильтр** (боковая панель)   
`list_filter = ['tags', 'version', 'status']`

Создание собственного фильтра:
```
class StickerFilter(admin.SimpleListFilter):
    title = 'С наклейками'
    parameter_name = 'stickers'

    def lookups(self, request, model_admin):
        return [('True', 'С наклейками'), ('False', 'Без наклеек')]

    def queryset(self, request, queryset):
        if self.value() == 'True':
            return queryset.filter(stickers__isnull=False)
        if self.value() == 'False':
            return queryset.filter(stickers__isnull=True)

@admin.register(Items)
class ItemsAdmin(admin.ModelAdmin):
    # StickerFilter указывается не как строка
    list_filter = ['item_type', 'rare', 'quality', StickerFilter]
```

**Изменение записи. Редактирование полей**  
- `fields = ['name', 'version']` - поля, которые будут отображаться 
- `exclude = ['refs']` - для отображения всех полей кроме указанных
- `readonly_fields = ['online']` - поля только для чтения


<a name="Django_Метод_save_в_models_py"></a>
## Метод save в models.py
При сохранении записи позволяет автоматически генерировать поля
```
from django.template.defaultfilters import slugify
...
    def save(self, *args, **kwargs):
        self.slug = slugify(rus_to_eng_translit(self.name))
        super().save(*args, **kwargs)
```
Функция **slugify** игнорирует русские буквы, можно дописать свою функцию rus_to_eng_translit

**Другой способ**:  
Автозаполняется в реальном времени  
_Не работает с полями типа readonly_fields_  
В admin.py - `prepopulated_fields = {'slug': ('name',)}`

При редактировании созданной записи автозаполнение **может не работать**, для этого необходимо очистить 
**обязательные** поля, например, name и slug, после этого сохранить изменения, админ 
панель укажет на пустые обязательные поля и далее для поля slug будет рабоать автозаполнение


**Удобное отображение полей many to many в виде двух списков**  
`filter_horizontal = ['tags']` или `filter_vertical = ['tags']`  
Добавится поиск и добавление/удаление по ЛКМ x2

**Изменение внешнего вида админ панели**  
Шаблон для админ панели берется в _External Libraries - django_venv/Lib/site-packages/django/contrib/admin_  
**base_site.html копируется** в созданную папку testsite/templates/admin  
Расширяется блок **extrastyle** и добавляется **load static**  
Новый **base_site.html**:
```
{% extends "admin/base.html" %}

{% load static %}
...
{% block extrastyle %}
<link href="{% static '/css/admin/admin.css' %}" rel="stylesheet">
{% endblock %}
```
В testsite добавляется: static/css/admin/admin.css, чтобы он подгружался 
необходимо добавить в settings.py `STATICFILES_DIRS = [ BASE_DIR / 'static', ]`

Теперь можно менять стили у объектов в админ панеле, например:
```
#header{ 
	background: #3c2f70;
}
div.breadcrumbs, .module caption, #changelist-filter-header{
	background: #544494;
}
```


<a name="Django_forms"></a>
## forms
Форма для **GET** запроса:
```
<form action="">
    <p><label for="id_1">Название сервера: </label>
    <input type="text" name="name" id="id_1"></p>
    <p><button type="submit">Добавить</button></p>
</form>
```
При action="" обрабока формы будет перенаправлять на текущую страницу   
(можно указать другую, напримр, "/" - для начальной страницы и тд)  
127.0.0.1:8000/add/?name=asd&version=2  
В функции представления (views.py) можно получить данные из формы через **request.GET**

**POST** запрос: 
```
<form action="" method="post">
  {% csrf_token %}
  ...
```
Для безопасности передаётся специальный токен и переменные из формы уже не винды в адресной строке  
Поля доступны через **request.POST**


**Встроенные формы django**  
необходимо создать sitename/app/forms.py:
```
from django import forms
from .models import VersionList

class AddServer(forms.Form):
    name = forms.CharField(max_length=30, label='Название сервера')
    version = forms.ModelChoiceField(queryset=VersionList.objects.all(), required=False)
```
Параметры forms:
- required - для обязательного заполнения формы (по умолчанию True)
- label - название
- empty_label - первый пункт в выборе (заглушка)
- initial - значение по умолчанию (True для CheckBox)
- max_length / min_length
- error_messages - словарь, хранящий сообщения об ошибках: ({'required': 'Необходимо заполнить поле'})

Далее в views.py добавить:
```
def add_server(request):
    if request.method == 'POST':
        form = AddServer(request.POST)
        if form.is_valid():
            print(form.cleaned_data)
    else:
        form = AddServer()
    return render(...)
```
is_valid - проверка на корректные данные  
cleaned_data - выводит очищенные данные

html:
```
<form action="" method="post">
        {% csrf_token %}
        {{ form.as_p }}
        <button type="submit">Добавить</button>
</form>
```
.as_p / .as_ul / .as_table

**Оформление**  
Можно прописывать атрибуты в forms.py:  
`name = forms.CharField(max_length=30,widget=forms.TextInput(attrs={'placeholder': "Название"}))`  
или указать в attrs класс: `attrs={'class': 'input_name'}`

Чтобы убрать точки в errors: `.errors li{ list-style: none; }`

**Сохранение в БД**  
views.py (для распоковки необходимо чтобы поля в forms и models совпадали):
```
def add_server(request):
    if request.method == 'POST':
        form = AddServer(request.POST)
        if form.is_valid():
            try:
                Servers.objects.create(**form.cleaned_data)
                return redirect('home')
            except:
                form.add_error(None, 'Ошибка добавления сервера')
```
html:
```
<form action="" method="post">
        {% csrf_token %}
        <div class="main_error">{{ form.non_field_errors }}</div>
        <table class="form_table">
        {% for f in form %}
        <tr><td class="td_name" valign="top">{{ f.label }}</td><td class="td_input">{{ f }}
        <div class="errors">{{ f.errors }}</div></td></tr>
        {% endfor %}
        </table>
        <button type="submit">Добавить</button>
    </form>
```
или можно обращаться к полю отдельно:  
`<tr><td class="td_name" valign="top">{{ form.name.label }}</td><td class="td_input">{{ form.name }}<div class="errors">{{ form.name.errors }}</div></td></tr>`


Проверка на корректное заполнение формы (**Валидация полей формы**)  
Добавление проверок с указанными сообщениями при некорректном вводе
```
from django.core.validators import MinLengthValidator, MaxLengthValidator

class AddItemForm(forms.Form):
    name = forms.SlugField(max_length=150, label="Название в URL:",
                           validators=[
                               MinLengthValidator(5, message='Название должно быть не меньше 5 символов'),
                               MaxLengthValidator(100, message='Название должно быть не более 100 символов')])
```

Создание собственного валидатора (при многократном применении):  
```
from django.core.exceptions import ValidationError
from django.utils.deconstruct import deconstructible

@deconstructible
class IpValidator:
    Allowed_chars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz1234567980-_.:'
    code = 'ip'
    def __init__(self, message=None):
        self.message = message if message else 'Используются неразрешенные символы'

    def __call__(self, value, *args, **kwargs):
        if not (set(value) <= set(self.Allowed_chars)):
            raise ValidationError(self.message, code=self.code)
``` 
Вариант валидатора в виде метода класса формы  
Создаётся метод **clean_<название_поля>**, например для поля ip - def clean_ip
```
class AddServer(forms.Form):
    ip = forms.CharField(max_length=30, label='Ip адресс сервера:')

    def clean_ip(self):
        ip = self.cleaned_data['ip']
        Allowed_chars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz1234567980-_.:'

        if not (set(ip) <= set(Allowed_chars)):
            raise ValidationError('Используются неразрешенные символы')
```

Привязка **модели** к форме
```
class AddItemForm(forms.ModelForm):
    item_type = forms.ModelChoiceField(queryset=ItemType.objects.all(), empty_label="Не выбрано", label="Тип предмета")
    rare = forms.ModelChoiceField(queryset=Rare.objects.all(), empty_label="Не выбрано", label="Редкость")
    quality = forms.ModelChoiceField(queryset=Quality.objects.all(), empty_label="Не выбрано", label="Качество")
    name = forms.CharField(validators=[RuValidator()], label="Название")

    class Meta:
        model = Items
        fields = ['name', 'slug', 'price', 'count', 'item_type', 'rare', 'quality']  # '__all__'
        widgets = {
            'name': forms.TextInput(attrs={'style': 'background-color: red;'})
        }
        labels = {'price': 'Цена'}
        
    def clean_name(self):
        name = self.cleaned_data['name']
        if len(name) < 5:
            raise ValidationError('Слишком коротное название (минимум 5 символов)')

        return name
```
views.py:
```
def sell(request):
    if request.method == 'POST':
        form = AddItemForm(request.POST)
        if form.is_valid():
            form.save()
        ...
```
**fields** определяет какие подя будут в форме, для добавления всех полей - `'__all__'`  
Поля будут взяты из модели. Можно переопределить поля, прописав их перед классом Meta, но
слетят названия (verbose_name)  
В Meta можно добавлять виджеты полям и задавать label  
В AddItemForm можно по-прежнему прописывать методы для валидации (например, clean_name)


<a name="Django_Загрузка_файла_на_сервер"></a>
## Загрузка файла на сервер
**Вариант с формой**:  
Создать папку для файлов, например, site/uploads  
Для загрузки изображений необходимо импортировать мобуль Pillow  
forms.py:
```
class UploadFileForm(forms.Form):
    banner = forms.ImageField(label='Баннер')
```
html:
```
<form action="" method="POST" enctype="multipart/form-data">
    {% csrf_token %}
    {{ form.as_p }}
    <p><button type="submit">Загрузить</button></p>
</form>
```
views.py (загрузка файла частями):
```
def upload_file(f):
    with open(f"uploads/{f.name}", 'wb+') as file:
        for chunk in f.chunks():
            file.write(chunk)
            
def contacts(request):
    if request.method == 'POST':
        form = UploadFileForm(request.POST, request.FILES)
        if form.is_valid():
            upload_file(form.cleaned_data['banner'])  # указывается название поля как в form
    else:
        form = UploadFileForm()
    return render(request, 'monitoring/contacts.html',
                  {'name': 'Обратная связь', 'main_page': main_page, 'menu': menu, 'form': form})
```
**Вариант без формы**:  
В `<form>` добавляется `<input type='file' name='file_upload'>`  
В views.py для обращения к файлу: `request.FILES['file_upload']`

**Вариант с моделью**:  
В Settings.py создаётся папка с медиа конетнтом: `MEDIA_ROOT = BASE_DIR / 'media'`   
Добавляется поле в models.py:  
`banner = models.ImageField(upload_to='banners/%Y/', default=None, blank=True, null=True, verbose_name='Баннер')`  
В html форме указать enctype: `<form action="" method="post" enctype="multipart/form-data">`  
views.py (указать request.FILES):
```
def add_server(request):
    if request.method == 'POST':
        form = AddServer(request.POST, request.FILES)
        if form.is_valid():
            form.save()
            return redirect('home')
    else:
        form = AddServer()
    return render(request, ...)
```
forms.py: добавить в форму, в класс Meta `fields = ['banner', ...]`

Для `upload_to='banners/%Y/'` будет создана папка **media/banners/2025** (возможны другие варианты, наример, `'item_icons/%Y/%m/%d'`)  
Загружаемые файлы с **одинаковыми названиями** будут переименовываться, к ним автоматически добавятся рандомные символы (image_tw5MmLb.PNG)


<a name="Django_Отображение_картинок_на_сайте"></a>
## Отображение картинок на сайте
В Settings.py указывается папка для медиа файлов: `MEDIA_URL = '/media/'`  
В urls.py добавить (только в режиме отладки):
```
from testsite import settings
from django.conf.urls.static import static

if settings.DEBUG:
    urlpatterns += static(settings.MEDIA_URL, document_root=settings.MEDIA_ROOT)  
```
Вывод изображения: `<img src="{{ s.banner.url }}">`

Вывод изображений в админ панеле (в списке). admin.py:
```
from django.utils.safestring import mark_safe

@admin.register(Servers)
class ServersAdmin(admin.ModelAdmin):
    ...
    list_display = ('name', 'img_banner', 'version', 'online', 'point', 'online_point_ratio', 'status')


    @admin.display(description='Баннер')
    def img_banner(self, servers: Servers):
        if servers.banner:
            return mark_safe(f"<img src='{servers.banner.url}'>")
        return 'Без фото'
```
Вывод в редакторе записей:
```
fields = ['name', 'banner', 'img_banner', 'online', 'status']
readonly_fields = ['img_banner', 'online']
```
В админке, при редактировании записи, для удобства можно продублировать панель с кнопками 
(Сохранить запись и тд) сверху. В class ServersAdmin(admin.ModelAdmin) добавляется:  
`save_on_top = True`


<a name="Django_Class_Based_Views"></a>
### Class Based Views (CBV). Классы View и TemplateView
**Базовый класс представления View**

_views.py_:
```
from django.views import View

class Add_Server(View):
    def get(self, request):
        form = AddServer()
        return render(request, ...)
    def post(self, request):
        form = AddServer(request.POST, request.FILES)
        if form.is_valid():
            form.save()
            return redirect('home')
        return render(request, ...)
```
Для обработки get и post запросов есть одноименные функции  
_urls.py_:  
`path('add/', views.AddServer.as_view(), name='add'),`

**TemplateView**
```
class HomePage(TemplateView):
    template_name = 'monitoring/index.html'
    extra_context = {
        'name': 'Список серверов',
        'main_page': main_page,
        'menu': menu,
        'servers': Servers.objects.filter(status=Servers.Status.ACTIVE)[:max_servers_on_page].select_related("version")
    }
```
Этот способ не будет работать с динамически появляющимися данными (home/?item_type=1)

Для GET запросов в класс HomePage добавляется метод get_context_data:
```
  def get_context_data(self, **kwargs):
      context = super().get_context_data(**kwargs)
      context['name'] = 'Список серверов'
      context['main_page'] = main_page
      context['menu'] = menu
      context['vr'] = self.request.GET.get('vr', '')
      context['servers'] = Servers.objects.filter(status=Servers.Status.ACTIVE)[:max_servers_on_page].select_related("version")
      return context
```

В _urls.py_ тоже можно определять словарь extra_context:  
`path('', views.HomePage.as_view(extra_context={'title': 'Home Page'}), name='home'),`


<a name="Django_ListView"></a>
## ListView
Указывается модель, откуда брать объекты: `model = Items`  
Можно указать **пользовательский менеджер** в методе **get_queryset**  
По умолчанию берется шаблон: _имя_приложения / имя_модели_list.html_  
Переопределяется: `template_name = 'skins/index.html'`  
И в шаблоне перебирается список **object_list** `{% for i in object_list %}`  
Переопределяется: `context_object_name = 'items'`
```
class HomePage(ListView):
    # model = Items
    template_name = 'skins/index.html'
    context_object_name = 'items'
    extra_context = {
        'menu': menu,
        'item_type': None,
        'tag': None,
    }

    def get_queryset(self):
        return Items.notNullCount.all().select_related('rare')
```

**ListView с фильтром**  
`allow_empty = True` - чтобы при пустом списке генерировалась ошибка 404

```
class ItemCategory(ListView):
    template_name = 'skins/index.html'
    context_object_name = 'items'
    allow_empty = False

    def get_queryset(self):
        return Items.notNullCount.filter(item_type__slug=self.kwargs['item_type']).select_related('rare')

    def get_context_data(self, **kwargs):
        context = super().get_context_data(**kwargs)
        item_type = context['items'][0].item_type
        context['menu'] = menu
        context['item_type'] = item_type.slug
        context['tag'] = None
        return context
```
`self.kwargs['item_type']` - берется значение из urls.py:  
`path('type/<slug:item_type>', views.ItemCategory.as_view(), name='home'),`


<a name="Django_DetailView"></a>
## DetailView
Необходим для отображения информации по объекту из БД  
По-умолчанию добавляет в шаблон объект модели с названием **object**  
Для переопределения объекта: `context_object_name = 'item'`  
Если объект берется по slug/pk, объявить названия переменных:  
`slug_url_kwarg = 'item_slug'` или `pk_url_kwarg`  
**def get_object** - отбираются записи по определённым условиям, чтобы нельзя 
было перейти на страницу с объектом, у которого, например, нулевое кол-во 
(передаётся пользовательский менеджер для удобства, но условия прописать тоже можно)
```
class ShowItemInfo(DetailView):
    model = Items
    template_name = 'skins/item_info.html'
    slug_url_kwarg = 'item_slug'
    context_object_name = 'item'
    extra_context = {
        'menu': menu,
    }

    def get_object(self, queryset=None):
        return get_object_or_404(Items.notNullCount, slug=self.kwargs[self.slug_url_kwarg])
```


<a name="Django_FormView"></a>
## FormView
Форма передаётся в шаблон с названием **form**  
При успешном заполнении формы будет вызван _def form_valid_ и далее произойдёт перенаправление 
на **success_url = reverse_lazy('home')**  
**reverse_lazy** указывается, потому что на момент создания класса маршруты ещё не существуют и обычный reverse выдаст ошибку
```
from django.urls import reverse_lazy

class AddItem(FormView):
    form_class = AddItemForm
    template_name = 'skins/sell.html'
    success_url = reverse_lazy('home')
    extra_context = {'menu': menu}

    def form_valid(self, form):
        form.save()
        return super().form_valid(form)
```

<a name="Django_CreateView"></a>
## CreateView
Сохраняет данные в БД без доп. метода form_valid
```
class AddItem(CreateView):
    form_class = AddItemForm
    template_name = 'skins/sell.html'
    success_url = reverse_lazy('home')
    extra_context = {'menu': menu}
```
Если не указывать _success_url_, то после добавления записи, в качестве ссылки для 
перенаправления, возьмётся **def get_absolute_url** из _models.py_ 

**CreateView** без формы, через модель:
```
class AddItem(CreateView):
    model = Items
    fields = ['name', 'icon', 'price', 'count', 'item_type', 'rare', 'quality']  # '__all__'
    template_name = 'skins/sell.html'
    extra_context = {'menu': menu}
```

<a name="Django_UpdateView"></a>
## UpdateView
Обновление записей по pk/slug. _urls.py_:  
`path('edit/<int:pk>', views.UpdateItemClass.as_view(), name='edit_item'),` или `<slug:slug>`

Через **модели** (без валидаторов):
```
class UpdateItemClass(UpdateView):
    model = Items
    fields = ['name', 'icon', 'price', 'count', 'item_type', 'rare', 'quality']  # '__all__'
    template_name = 'skins/sell.html'
    extra_context = {'menu': menu}
```

Через **формы** (с валидаторами):
```
class UpdateItemClass(UpdateView):
    form_class = AddItemForm
    template_name = 'skins/sell.html'
    success_url = reverse_lazy('home')
    extra_context = {'menu': menu}

    def get_queryset(self):
        return Items.notNullCount.all()  # filter(pk=self.kwargs['pk'])
```
Для **ImageFieldFile** было добавлено в _forms.py_:
```
from django.db.models.fields.files import ImageFieldFile

class AddItemForm(forms.ModelForm):
    ...
    def clean_icon(self):
        icon = self.cleaned_data['icon']
        if isinstance(icon, ImageFieldFile):
            return icon

        w, h = icon.image.size
        if h > 2000 or w > 2000:
            raise ValidationError('Максимальное разрешение изображения 2000 x 2000')
        if h != w:
            raise ValidationError('Соотношение сторон должны быть одинаковые')
        return icon
```

<a name="Django_DeleteView"></a>
## DeleteView
```
class DeleteItemView(DeleteView):
    model = Items
    context_object_name = 'item'
    template_name = 'skins/delete_item.html'
    success_url = reverse_lazy('home')
    extra_context = {'menu': menu}
```
Шаблон:
```
<form action="" method="post" enctype="multipart/form-data">
    {% csrf_token %}
    <h3>{{ item.name }} ({{ item.quality.name }}, {{ item.rare.name}})</h3>
    <p><img src="{{ item.icon.url }}"></p>
    <p>{{ item.price }}руб. [{{ item.count }}]</p>
    <p class="add_item_button"><button type="submit">Удалить</button></p>
</form>
```


<a name="Django_Mixins"></a>
## Mixins
Вспомогательаные классы для упрощения кода. В папке с приложением нужно создать файл _utils.py_:
```
menu =  [...]

class DataMixin():
    item_type = None
    extra_context = {'menu': menu}

    def __init__(self):
        if self.item_type is not None:
            self.extra_context['item_type'] = self.item_type
            
    def get_mixin_context(self, context, **kwargs):
        context['menu'] = menu
        context['item_type'] = self.item_type
        context.update(kwargs)
        return context
```
_views.py_:
```
class HomePage(DataMixin, ListView):
    template_name = 'skins/index.html'
    context_object_name = 'items'
    tag = None

    def get_queryset(self):
        return Items.notNullCount.all().select_related('rare')


class ItemCategory(DataMixin, ListView):
    template_name = 'skins/index.html'
    context_object_name = 'items'

    def get_queryset(self):
        return Items.notNullCount.filter(item_type__slug=self.kwargs['item_type']).select_related('rare')

    def get_context_data(self, **kwargs):
        context = super().get_context_data(**kwargs)
        return self.get_mixin_context(context, item_type=self.kwargs['item_type'], tag=None)
```
В HomePage переменные (например, tag) DataMixin подхватит в get_mixin_context и добавит в extra_context


**Пагинация**  
`from django.core.paginator import Paginator`  
Для создании пагинации в одноимённый класс передаётся список и кол-во объектов на одной странице:
`p = Paginator(item, 2)`  
- **p.count** - общее кол-во элементов
- **p.num_pages** - кол-во страниц
- **p.page_range** - возвращает итератор для страниц _range(1, 4)_

Взять страницу: `p1 = p.page(1)`  
- **p1.object_list** - список элементов на странице
- **p1.has_next() / p1.has_previous()** - проверка на существование следующей / предыдущей страницы (True/False)
- **p1.has_other_pages()** - проверка, существуют ли ещё какие-то страницы
- **p1.next_page_number() / p1.previous_page_number()** - номер следующей / предыдущей страницы или _raise EmptyPage_

Пагинация для **функции представления**:
```
def info(request):
    items = Items.notNullCount.all()
    paginator = Paginator(items, 3)
    page_num = request.GET.get('page', 1)
    page_obj = paginator.page(page_num)
    return render(request, 'skins/info_page.html', {'menu': menu, 'page_obj': page_obj})
```
```
{% for item in page_obj %}
    <p>{{ item.name }} ({{ item.price }} руб.)</p>
{% endfor %}
<ul>
    {% for p in page_obj.paginator.page_range %}
    <li><a href="?page={{ p }}">{{ p }}</a></li>
    {% endfor %}
</ul>
```

Пагинация для **ListView**:
```
class DataMixin():
    paginate_by = 5  # кол-во объектов на странице
    ...
    
class HomePage(DataMixin, ListView):
    ...
```
При использовании пагинации в ListView, в шаблон передаются **page_obj** и **paginator**  
_Шаблон_:
```
{% block page_nums %}
{% if page_obj.has_other_pages %}
    {% if page_obj.has_previous %}
    <a href="?page={{ page_obj.previous_page_number }}"><span class="page_num" style="margin-right:15px; font-weight: 900;" >&lt;</span></a>
    {% endif %}
    {% for p in paginator.page_range %}
        {% if page_obj.number == p %}
        <a href="?page={{ p }}"><span class="page_num selected_page_num">{{ p }}</span></a>
        {% elif p == 1 and page_obj.number > 3 %}
        <a href="?page={{ p }}"><span class="page_num" >{{ p }}</span></a>
        <span>...</span>
        {% elif p == paginator.num_pages and page_obj.number < paginator.num_pages|add:-2 %}
        <span>...</span>
        <a href="?page={{ p }}"><span class="page_num" >{{ p }}</span></a>
        {% elif p >= page_obj.number|add:-2 and p <= page_obj.number|add:2 %}
        <a href="?page={{ p }}"><span class="page_num">{{ p }}</span></a>
        {% endif %}
    {% endfor %}
    {% if page_obj.has_next %}
    <a href="?page={{ page_obj.next_page_number }}"><span class="page_num" style="margin-left:15px; font-weight: 900;" >&gt;</span></a>
    {% endif %}
{% endif %}
{% endblock %}
```


<a name="Django_Авторизация"></a>
## Авторизация
Для авторизации создаётся отдельное приложение users, которое потом можно 
легко перенести в другой проект  
`python manage.py startapp users`  
В _settings.py_, в INSTALLED_APPS добавляется `'users'`
В папке приложения users создаётся _urls.py_:
```
from django.urls import path
from . import views

urlpatterns = [
    path('login/', views.login_user, name='login'),
    path('logout/', views.logout_user, name='logout'),
]
```
В папке проекта, в _urls.py_ добавляется, в **urlpatterns[ ]**:  
`path('users/', include('users.urls', namespace="users")),`  
**namespace** необходим для создания маршрутов вида: `users:login`

Для авторизации создаётся шаблон в _users/templates/users_, расширяется 
базовый шаблон, подключаются стили:
```
{% extends 'base.html' %}

{% load static %}

{% block extrastyle %}
<link rel="stylesheet" href="{% static 'skins/css/sell_style.css' %}">
{% endblock %}

{% block content %} ...
```
Для приложения users создаётся свой _forms.py_:
```
from django import forms

class LoginUserForm(forms.Form):
    username = forms.CharField(label='Логин', widget=forms.TextInput(attrs={'class': 'form-input'}))
    password = forms.CharField(label='Пароль', widget=forms.PasswordInput(attrs={'class': 'form-input'}))
```
_views.py_ для users:
```
from django.http import HttpResponseRedirect
from django.shortcuts import render
from .forms import LoginUserForm
from django.contrib.auth import authenticate, login, logout
from django.urls import reverse

def login_user(request):
    if request.method == 'POST':
        form = LoginUserForm(request.POST)
        if form.is_valid():
            cd = form.cleaned_data
            user = authenticate(request, username=cd['username'], password=cd['password'])
            if user and user.is_active:
                login(request, user)
                return HttpResponseRedirect(reverse('home'))
    else:
        form = LoginUserForm()

    return render(request, 'users/login.html', {'form': form})

def logout_user(request):
    logout(request)
    return HttpResponseRedirect(reverse('users:login'))
```
**user.is_active** для проверки активного пользователя (не забанен и т.д)

Кнопки **Вход**/**Выход** на сайте
```
{% if user.is_authenticated %}
<li style="margin-left: auto;"><a href="#">{{ user.username }}</a> | <a href="{% url 'users:logout' %}">Выйти</a></li>
{% else %}
<li style="margin-left: auto;"><a href="{% url 'users:login' %}">Войти</a> | <a href="#">Регистрация</a></li>
{% endif %}
```


<a name="Django_Шаблонные_контекстные_процессоры"></a>
## Шаблонные контекстные процессоры
В _settings.py_ TEMPLATES перечислены переменные, которые доступны в любых шаблонах, например,
**request** и **user** (появляется благодаря **auth**).  
Добавление своего значения:  
Создаётся функция для получения словаря, например, в новом файле _context_processors.py_:  
`def get_skins_context(request): return {'main_menu': menu}`  
Далее она добавляется в _settings.py_:  
`TEMPLATES = [...{'OPTIONS': {'context_processors': [..., 'users.context_processors.get_skins_context',] }]`  
Теперь в шаблонах можно использовать новое значение: `{% for m in main_menu %}`


<a name="Django_LoginView_AuthenticationForm_LogoutView"></a>
## LoginView, AuthenticationForm, LogoutView
```
from django.contrib.auth.views import LoginView
from django.contrib.auth.forms import AuthenticationForm

class LoginUser(LoginView):  # views.LoginUser.as_view()
    form_class = AuthenticationForm
    template_name = 'users/login.html'

    def get_success_url(self):
        return reverse_lazy('home')
```
Вместо переопределения get_success_url можно добавить `LOGIN_REDIRECT_URL = 'home'` в _settings.py_  
Также есть **LOGOUT_REDIRECT_URL** и **LOG_URL** для перенаправления неавторизованного пользователя при его попытке просмотреть закрытую страницу

Для перехода на указанную страницу после авторизации в форму добавляется скрытое поле со значением **next** 
(http://127.0.0.1:8000/users/login/?next=/sell/):
```
<form action="" method="post">
    {% csrf_token %}
    <input type="hidden" name="next" value="{{ next }}" />
    <table class="from-table">
        <tr><td colspan=2><div class="form-error">{{ form.non_field_errors }}</div></td></tr>
        {% for f in form %}
        <tr><td><label class="form-field" for="{{ f.id_for_label }}">{{ f.label }}</label></td><td>{{ f }}</td></tr>
        <tr><td colspan=2><div class="form-error">{{ f.errors }}</div></td></tr>
        {% endfor %}
    </table>
    <p class="from_button"><button type="submit">Войти</button></p>
</form>
```
Приоритеты для редиректа - def get_success_url, next, LOGIN_REDIRECT_URL

Использование своих форм в LoginView. _forms.py_:
```
from django.contrib.auth.forms import AuthenticationForm
from django.contrib.auth import get_user_model

class LoginUserForm(AuthenticationForm):
    username = forms.CharField(label='Логин', widget=forms.TextInput(attrs={'class': 'form-input'}))
    password = forms.CharField(label='Пароль', widget=forms.PasswordInput(attrs={'class': 'form-input'}))

    class Meta:
        model = get_user_model()
        fields = ['username', 'password']
```
Далее в _class LoginUser(LoginView)_: `form_class = LoginUserForm`

**LogoutView**  
```
from django.contrib.auth.views import LogoutView
...
path('logout/', LogoutView.as_view(), name='logout'),
```
Работает **ТОЛЬКО С POST** запросами. Поэтому в шаблоне для кнопки выхода добавляется form:
```
<form method="post" action="{% url 'users:logout' %}" style="display:inline;">
  {% csrf_token %}
  <button type="submit" class="logout_button">Выйти</button>
</form>
```


<a name="Django_Login_Required"></a>
## Login Required
Запрещает доступ к страницам для неавторизованных пользователей, перекидывает на страницу авторизации, 
указанную в _settings.py_ (**LOGIN_URL**)  
Параметр **next** принимает значение закрытой страницы и после авторизации пользователь возвращается на неё

Декоратор для функции представления:
```
from django.contrib.auth.decorators import login_required

@login_required
def info(request):
    ...
```
Может принимать параметр: `@login_required(login_url='/admin/')`

Класс LoginRequiredMixin:
```
from django.contrib.auth.mixins import LoginRequiredMixin

class AddItem(LoginRequiredMixin, DataMixin, CreateView):
    ...
```

Добавление информации о пользователе при заполнении формы:
```
class Items(models.Model):
    owner = models.ForeignKey(get_user_model(), on_delete=models.SET_NULL, 
        related_name='owners', null=True, default=None)
```
```
class AddItem(LoginRequiredMixin, DataMixin, CreateView):
    ...
    def form_valid(self, form):
        item = form.save(commit=False)
        item.owner = self.request.user
        return super().form_valid(form)
```
`<p>Продавец: {{ item.owner.username|default:"-" }}</p>`


<a name="Django_Регистрация_пользователя"></a>
## Регистрация пользователя
```
class RegisterUserForm(forms.ModelForm):
    username = forms.CharField(label='Логин', widget=forms.TextInput(attrs={'class': 'form-input'}))
    password = forms.CharField(label='Пароль', widget=forms.PasswordInput(attrs={'class': 'form-input'}))
    password2 = forms.CharField(label='Повторение пароля', widget=forms.PasswordInput(attrs={'class': 'form-input'}))

    class Meta:
        model = get_user_model()
        fields = ['username', 'email', 'password', 'password2']
        labels = {'email': 'E-mail',}

    def clean_password2(self):
        cd = self.cleaned_data
        if cd['password'] != cd['password2']:
            raise forms.ValidationError('Пароли не совпадают')
        return cd['password']

    def clean_email(self):
        email = self.cleaned_data['email']
        if get_user_model().objects.filter(email=email).exists():
            raise forms.ValidationError("Пользователь с таким E-mail адресом уже существует")
        return email
```
По-умолчанию разные пользователи могут иметь один и тот же email, поэтому нужна проверка clean_email
```
def register(request):
    if request.method == 'POST':
        form = RegisterUserForm(request.POST)
        if form.is_valid():
            user = form.save(commit=False)
            user.set_password(form.cleaned_data['password'])
            user.save()
            return render(request, 'users/register_done.html')
    else:
        form = RegisterUserForm()
    return render(request, 'users/register.html', {'form': form})
```
**set_password** шифрует пароль и дальше использует его хэш, ключ для шифрования берется из _settings.py_ **SECRET_KEY**


<a name="Django_UserCreationForm"></a>
## UserCreationForm
```
from django.contrib.auth.forms import UserCreationForm

class RegisterUserForm(UserCreationForm):
    username = forms.CharField(label='Логин', widget=forms.TextInput(attrs={'class': 'form-input'}))
    password1 = forms.CharField(label='Пароль', widget=forms.PasswordInput(attrs={'class': 'form-input'}))
    password2 = forms.CharField(label='Повторение пароля', widget=forms.PasswordInput(attrs={'class': 'form-input'}))

    class Meta:
        model = get_user_model()
        fields = ['username', 'email', 'password1', 'password2']
        labels = {'email': 'E-mail',}

    def clean_email(self):
        email = self.cleaned_data['email']
        if get_user_model().objects.filter(email=email).exists():
            raise forms.ValidationError("Пользователь с таким E-mail адресом уже существует")
        return email
```
def clean_password2 уже не нужен, эту проверку берет на себя UserCreationForm
```
from django.views.generic import CreateView

class RegisterUser(CreateView):
    form_class = RegisterUserForm
    template_name = 'users/register.html'
    success_url = reverse_lazy('users:login')
```


<a name="Django_Авторизация_через_email"></a>
## Авторизация через email
В новом файле _authentication.py_, по аналогии с классом `from django.contrib.auth.backends import ModelBackend`:
```
from django.contrib.auth.backends import BaseBackend
from django.contrib.auth import get_user_model

class EmailAuthBackend(BaseBackend):
    def authenticate(self, request, username=None, password=None, **kwargs):
        user_model = get_user_model()
        try:
            user = user_model.objects.get(email=username)
            if user.check_password(password):
                return user
            return None
        except (user_model.DoesNotExist, user_model.MultipleObjectsReturned):
            return None

    def get_user(self, user_id):
        user_model = get_user_model()
        try:
            return user_model.objects.get(pk=user_id)
        except user_model.DoesNotExist:
            return None
```
В _settings.py_ добавляется второй способ авторизации:
```
AUTHENTICATION_BACKENDS = [
    'django.contrib.auth.backends.ModelBackend',  # по username + pass
    'users.authentication.EmailAuthBackend', # по email + pass
```


<a name="Django_Профиль_пользователя"></a>
## Профиль пользователя
```
class ProfileUserForm(forms.ModelForm):
    username = forms.CharField(disabled=True, label='Логин', widget=forms.TextInput(attrs={'class': 'form-input'}))
    email = forms.CharField(disabled=True, label='E-mail', widget=forms.TextInput(attrs={'class': 'form-input'}))

    class Meta:
        model = get_user_model()
        fields = ['username', 'email']
        labels = {'email': 'E-mail',}
```
`disabled=True` для запрета на редактирование
```
class ProfileUser(LoginRequiredMixin, UpdateView):
    model = get_user_model()
    form_class = ProfileUserForm
    template_name = 'users/profile.html'

    def get_success_url(self):
        return reverse_lazy('users:profile')

    def get_object(self, queryset=None):
        return self.request.user
```


<a name="Django_PasswordChangeView"></a>
## PasswordChangeView
```
from django.contrib.auth.forms import PasswordChangeForm

class UserPasswordChangeForm(PasswordChangeForm):
    old_password = forms.CharField(label='Старый пароль', widget=forms.PasswordInput(attrs={'class': 'form-input'}))
    new_password1 = forms.CharField(label='Новый пароль', widget=forms.PasswordInput(attrs={'class': 'form-input'}))
    new_password2 = forms.CharField(label='Повторение нового пароля', widget=forms.PasswordInput(attrs={'class': 'form-input'}))
```
```
from django.contrib.auth.views import PasswordChangeView

class UserPasswordChange(PasswordChangeView):
    form_class = UserPasswordChangeForm
    success_url = reverse_lazy('users:password_change_done')
    template_name = 'users/password_change_from.html'
```
```
from django.contrib.auth.views import PasswordChangeDoneView

urlpatterns = [
    path('password-change/', views.UserPasswordChange.as_view(), name='password_change'),
    path('password-change/done/', PasswordChangeDoneView.as_view(template_name='users/password_change_done.html'), 
            name='password_change_done'), ]
```


<a name="Django_Почтовый_сервис"></a>
## Почтовый сервис
**Вариант для тестирования** (письма выводятся в консоль)

В _settings.py_ добавить:  
`EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'`

```
from django.core.mail import send_mail

send_mail('Заголовок', 'Сообщение', 'from@test@mail.ru', 
    ['to@test@mail.ru'], fail_silently=False,)

# Content-Type: text/plain; charset="utf-8"
# MIME-Version: 1.0                        
# Content-Transfer-Encoding: 8bit          
# Subject: =?utf-8?b?0JfQsNCz0L7Qu9C+0LLQvtC6?=
# From: from@test@mail.ru
# To: to@test@mail.ru
# Date: Thu, 27 Nov 2025 09:19:28 -0000
# Message-ID: <176423516827.4904.2515406098060429092@LAPTOP-F92KK16H>

# Сообщение
```

**Подключение сторонних почтовых сервисов**   
В _settings.py_ можно убрать **EMAIL_BACKEND**, потому что по-умолчанию используется smtp. Или:  
`EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'`

**Gmail**  
_settings.py_:
```
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 465
EMAIL_HOST_USER = 'test@gmail.com'
EMAIL_HOST_PASSWORD = 'abcdabcdabcdabcd'
EMAIL_USE_SSL = True

DEFAULT_FROM_EMAIL = EMAIL_HOST_USER
SERVER_EMAIL = EMAIL_HOST_USER
EMAIL_ADMIN = EMAIL_HOST_USER
```
EMAIL_HOST_PASSWORD - пароль для приложений (можно установить только если есть двухфакторка на аккаунте)  
Во время тестов может не работать отправка сообщений из-за VPN  
При отправке сообщения на несуществующий email, отправляет сообщение себе же (address not found)


<a name="Django_Восстановление_пароля"></a>
## Восстановление пароля
*необходим почтовый сервис (EMAIL_BACKEND)

Создаются шаблоны:
- **password_reset_form.html** - обычный шаблон с формой. Вводится email, куда придёт ссылка вида: http://127.0.0.1:8000/users/password-reset/Ng/czxijo-965df7ab956af9e059e478c80dd3f1d0/ (`password-reset/<uidb64>/<token>/`)
- **password_reset_done.html** - уведомление об отправке ссылки для восстановления на почту. Шаблон на основе _(External Libraries)\djvenv\Lib\site-packages\django\contrib\admin\templates\registration\password_reset_done.html_
- **password_reset_confirm.html** - обычный шаблон с формой. Установка нового пароля
- **password_reset_complete.html** - шаблон с сообщением об успешном изменении пароля
- **password_reset_email.html** - текст сообщений, который будет высылаться по почте. Шаблон на основе _.../password_reset_email.html_. Меняется только ссылка (url '**users**:password_reset_confirm')

_password_reset_done.html_:
```
{% extends "base.html" %}
{% load i18n %}

{% block content %}
<h1>Сброс пароля</h1>

<p>{% translate 'We’ve emailed you instructions for setting your password, if an account exists with the email you entered. You should receive them shortly.' %}</p>
<p>{% translate 'If you don’t receive an email, please make sure you’ve entered the address you registered with, and check your spam folder.' %}</p>

{% endblock %}
```

_urls.py_:
```
from django.contrib.auth.views import PasswordResetView, PasswordResetDoneView, PasswordResetConfirmView, PasswordResetCompleteView

urlpatterns = [ ...
    path('password-reset/', PasswordResetView.as_view(template_name='users/password_reset_form.html',
                                                      email_template_name='users/password_reset_email.html',
                                                      success_url=reverse_lazy('users:password_reset_done')),
         name='password_reset'),
    path('password-reset/done/', PasswordResetDoneView.as_view(template_name='users/password_reset_done.html'),
         name='password_reset_done'),
    path('password-reset/<uidb64>/<token>/', PasswordResetConfirmView.as_view(template_name='users/password_reset_confirm.html',
                                                                              success_url=reverse_lazy('users:password_reset_complete')),
         name='password_reset_confirm'),
    path('password-reset/complete/', PasswordResetCompleteView.as_view(template_name='users/password_reset_complete.html'),
         name='password_reset_complete'),
]
```


<a name="Django_AbstractUser"></a>
## AbstractUser
Расширение модели User, добавление полей для аватарки и даты рождения  
_users/models.py_:
```
from django.db import models
from django.contrib.auth.models import AbstractUser

class User(AbstractUser):
    photo = models.ImageField(upload_to="users/%Y/%m/", blank=True, null=True, verbose_name='Аватарка')
    date_birth = models.DateTimeField(blank=True, null=True, verbose_name='Дата рождения')
```
_users/admin.py_:
```
from django.contrib import admin
from django.contrib.auth.admin import UserAdmin
from .models import User

admin.site.reginster(User, UserAdmin)
```
_settings.py_:  
`AUTH_USER_MODEL = 'users.User'  # users - приложение`  
по-умолчанию **auth.User**

Далее, чтобы применить миграции без ошибок, проще удалить все миграции из всех приложений (кроме файлов `__init__.py`) и обнулить БД  
Необходимо опять создать суперпользователя  
Чтобы стандартная модель User корректно работала, нужно проверить, что везде используется get_user_model(), а не просто User

Шаблон _profile.html_:
```
<form action="" method="post" enctype="multipart/form-data">
    {% csrf_token %}
    {% if user.photo %}
    <p><img src="{{ user.photo.url }}"></p>
    {% else %}
    <p><img src="{{ default_icon }}"></p>
    {% endif %}
    <input type="hidden" name="next" value="{{ next }}" />
    {% include 'skins\includes\default_form.html' %}
    <p class="add_item_button"><button type="submit">Сохранить</button></p>
</form>
```
_users/forms.py_:
```
class ProfileUserForm(forms.ModelForm):
    ...
    cur_year = datetime.datetime.today().year
    date_birth = forms.DateField(widget=forms.SelectDateWidget(
        years=tuple(range(cur_year-120, cur_year))))
```
В _views.py_ добавляется `extra_context = {'default_icon': DEFAULT_USER_ICON}`  
В _settings.py_ - `DEFAULT_USER_ICON = MEDIA_URL + 'users/user-default-icon.png'`


<a name="Django_Permissions_Groups"></a>
## Permissions, Groups
Установка необходимых прав для просмотра страниц (можно установить через админ панель). 
При отсутствии прав будет генерироваться ошибка 403 Forbidden  
Формат прав: **<приложение>.<действие>_<таблица>**  
Все права можно посмотреть в БД, таблица **auth_permission**

Для **классов** представлений:
```
from django.contrib.auth.mixins import PermissionRequiredMixin

class AddItem(PermissionRequiredMixin, LoginRequiredMixin, DataMixin, CreateView):
    ...
    permission_required = 'skins.add_items'  # skins.change_items и тд
```
Для **функций** представлений:
```
from django.contrib.auth.decorators import permission_required

@permission_required(perm='skins.view_items', raise_exception=True)
def info(request):
    ...
```
raise_exception для генерации кода 403

В каждый шаблон передаётся **perms**, что позволяет делать проверки на наличие прав в шаблоне:
```
{% if perms.skins.change_items %}
<p><a href="{% url 'edit_item' item.pk %}" class="ref_a">Изменить</a></p>
{% endif %}
```

Чтобы не добавлять каждому пользователю отдельные права, можно создать группы (таблица **auth_group**)

Через объект пользователя можно работать с группами/разрешениями:
```
from users.models import User

user = User.objects.get(pk=2)
user.groups
user.user_permissions
```

`user.user_permission.add(1)` - добавляется по id, тут из auth_permission  
или  
```
from django.contrib.auth.models import Permission
p = Permission.objects.get(codename='add_itemtype')
user.user_permission.add(p)
```
`user.user_permissions.remove(p)` - удалить разрешение  
`user.user_permissions.clear()` - удалить все разрешения
`user.user_permissions.all()` - просмотр  
`user.user_permissions.set([list])` - просмотр

С группами работает также. Модель для групп:  
`from django.contrib.auth.models import Group`

**Создать своё разрешение**:
```
from django.contrib.auth.models import Permission
from django.contrib.contenttypes.models import ContentType
content_type = ContentType.objects.get_for_model(User)
permission = Permission.objects.create(codename='social_auth', name='Social Auth', content_type=content_type) 
```


<a name="Django_Логирование"></a>
## Логирование
`pip install concurrent-log-handler` - для создание логовс позможностью указать максимальный размер  
Сохранение логов самого django ("GET / HTTP/1.1" 200 29123). _settings.py_:
```
LOGGING = {
    'version': 1,
    'disable_existing_loggers': False,
    'formatters': {
        'verbose': {
            'format': '{asctime} [{levelname}] {module}: {message}',
            'style': '{',
            'datefmt': "%Y-%m-%d %H:%M:%S"
        },
    },
    'handlers': {
        'r_handler': {
            'level': 'INFO',
            'class': 'concurrent_log_handler.ConcurrentRotatingFileHandler',
            'filename': BASE_DIR / 'logs/test.log',
            'maxBytes': 1024 * 1024 * 1,  # 5 MB
            'backupCount': 2,
        },
    },
    'loggers': {
        'django': {
            'handlers': ['r_handler'],
            'level': 'INFO',
            'propagate': True,
        },
    },
}
```

Логер для приложения skins:
```
    ...
    'loggers': {
        'skins': {
            'handlers': ['r_handler'],
            'level': 'INFO',
            'propagate': True,
        },
    },
    ...
```
```
import logging
logger = logging.getLogger(__name__)
...
logger.info(f"{request.path} ({request.user})")
```


<a name="Django_Обработка_ошибок"></a>
## Обработка ошибок в фукнциях/классах представления
```
import traceback
from django.http import Http404
from django.views import View

def error_catcher(f):
    def try_f(request, *args, **kwargs):
        try:
            return f(request, *args, **kwargs)
        except Exception as e:
            logger.error(traceback.format_exc(), exc_info=e)
            raise Http404

    return try_f

class ErrorCatcher(View):
    def dispatch(self, request, *args, **kwargs):
        try:
            logger.info(f"{request.path}") #  ({request.user})
            response = super().dispatch(request, *args, **kwargs)
        except Exception as e:
            logger.error(traceback.format_exc(), exc_info=e)
            raise Http404
        return response
```
_views.py_:
```
@error_catcher
def info(request):
    ...

class Home(DataMixin, ListView, ErrorCatcher):
    ...
```






<a name="Selenium"></a>
# Selenium
`pip install selenium`

Список опций для гугла: https://peter.sh/experiments/chromium-command-line-switches/

<a name="Запуск_страницы_в_браузере"></a>
### Запуск страницы в браузере
Ссылка открывается в отдельном браузере
```
from selenium import webdriver

driver = webdriver.Chrome()

try:
    driver.get(url=url)
    time.sleep(5)
except Exception as ex:
    print(ex)
finally:
    driver.close()
    driver.quit()
```

### Изменение размера браузера
`driver.maximize_window()`

### Сохранение скриншота страницы
2 способа:
```
driver.get_screenshot_as_file('img_1.png')

driver.save_screenshot('img_2.png')
```
<a name="Изменение_user_agent"></a>
### Изменение user agent
```
useragrnt = 'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/123.0.0.0 Safari/537.36'
option = webdriver.ChromeOptions()
option.add_argument(f'user-agent={useragrnt}')


def main():
    driver = webdriver.Chrome(options=option)
```

<a name="Поиск_элемента"></a>
### Поиск элемента
Конструкция By позволяет искать элементы по ID, NAME, CLASS_NAME, XPATH и тд.  
В данном примере XPATH был скопирован с элемента в DevTools (пкм-copy-Xpath)
```
from selenium.webdriver.common.by import By

play_button = driver.find_element(By.XPATH, '//*[@id="movie_player"]/div[28]/div[2]/div[1]/button')
play_button.click()
```
Поиск атрибута по по тексту:  
`safety_ref = driver.find_element(By.PARTIAL_LINK_TEXT, 'Безопасность').get_attribute('href')`


Поиск по кастомному атрибуту:
```
      headers = driver.find_elements(By.XPATH, "//a[@data-shortcut='node-description']")
      for h in headers:
          print(h.get_attribute('href'))
```
Тут поиск происходит в блоке `<a>`

Поиск по атрибуту без конкретного значения:
```
      headers = driver.find_elements(By.XPATH, '//a[@data-shortcut]')
      #headers = driver.find_elements(By.CLASS_NAME, "structItem-title")
      for h in headers:
          if h.get_attribute('data-shortcut') == 'node-description':
              print(h.text)
```
Ещё пример:
```
      head = driver.find_element(By.CLASS_NAME, 'node.node--id30.node--depth2.node--forum.node--read')
      h2 = head.find_element(By.CLASS_NAME, 'node-subNodeFlatList')
      h3 = h2.find_elements(By.CLASS_NAME, 'subNodeLink.subNodeLink--forum ')
      for i in h3:
          print(i.get_attribute('href'))
```
<a name="Ввод_данных_в_input"></a>
### Ввод данных в input
После ввода информации происходит нажатие на кнопку login, которую программа находит по названию класса.<br>
Оригинальное название класса кнопки - btn btn-primary, чтобы не возникало ошибок необходимо заменить пробел на точку
```
from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.common.keys import Keys
```
```
        driver.get(url=url)
        time.sleep(5)
        Email_input = driver.find_element(By.ID, 'Email')
        Email_input.clear()
        Email_input.send_keys(Email)
        time.sleep(2)
        Password_input = driver.find_element(By.ID, 'Password')
        Password_input.clear()
        Password_input.send_keys(Password)
        time.sleep(2)
        #Password_input.send_keys(Keys.ENTER)
        login_button = driver.find_element(By.CLASS_NAME, 'btn.btn-primary').click()
```
<a name="Selenium_cookies"></a>
### cookies
Сохранение cookies
```
        with open('cookies', 'wb') as cookies_file:
            pickle.dump(driver.get_cookies(), cookies_file)
```
Загрузка cookies
```
        for cookie in pickle.load(open('cookies', 'rb')):
            driver.add_cookie(cookie)
        time.sleep(5)
        driver.refresh() # или get url
```
### Отключение режимо WebDriver
`option.add_argument('--disable-blink-features=AutomationControlled')`

Для проверки можно использовать: https://intoli.com/blog/not-possible-to-block-chrome-headless/chrome-headless-test.html

<a name="Фоновый_режим"></a>
### Фоновый режим
`option.add_argument('--headless')`

<a name="Перемещение_между_вкладками"></a>
### Перемещение между вкладками
После окончания работы необходимо вернуться на первую вкдалку, чтобы не было ошибок
```
    try:
        driver.get(url=url)
        ...
        driver.close()
        driver.switch_to.window(driver.window_handles[0])
        
    except Exception as ex:
        print(ex)#Se connecter
    finally:
        driver.close()
        driver.quit()
```
Открыть вкладку в **новом окне**: `driver.execute_script(f"window.open('{url}')")`  
Чтобы её **закрыть**: `driver.switch_to.window(driver.window_handles[1])`, потом `driver.close()` 

### implicitly_wait
Программа продолжит работу сразу после того, как код выполнится (ожидание продлится до 5 сек):<br> 
`driver.implicitly_wait(5)`

<a name="Добавление_скриптов"></a>
### Добавление скриптов
Добавление JS скрипта для скролла вниз:  
`driver.execute_script('window.scrollBy(0,document.body.scrollHeight)')`

Скрипт для получения координат ползунка:  
`driver.execute_script("return window.pageYOffset")`

<a name="Selenium_Получение_содержимого_страницы"></a>
### Получение всего содержания страницы
Перед сохранением лучше максимизировать эеран, чтобы не отображалась мобильная версия.  
Данный способ, в отличие от request, прогружает страницу и только потом её сохраняет (полезно при парсинге некоторых сайтов)
```
    driver.maximize_window()
    time.sleep(3)
    with open(url.split('/')[2].replace('.', '_') + '.html', 'w', encoding='utf-8') as file:
        file.write(driver.page_source)
```

<a name="ActionChains"></a>
### ActionChains
Нажатие кнопки без привязки к элементу:  
`ActionChains(driver).send_keys(Keys.ENTER).perform()`

Перемещение к элементу:
```
from selenium.webdriver.common.action_chains import ActionChains

end_line = driver.find_elements(By.CLASS_NAME, 'vbI.XiG')[-1]
action = ActionChains(driver)
action.move_to_element(end_line).perform()
```

<a name="Selenium_Профили_в_браузере"></a>
### Профили в браузере
Необходимо скачать chromedriver, желательно своей версии браузера:  
https://developer.chrome.com/docs/chromedriver/downloads?hl=ru  
https://googlechromelabs.github.io/chrome-for-testing/

Далее создаётся пустая папка для профиля и в коде указывается путь до неё и до скаченного chromedriver.exe
```
from selenium import webdriver
from selenium.webdriver.chrome.service import Service

option = webdriver.ChromeOptions()
option.add_argument('--disable-blink-features=AutomationControlled')
option.add_argument('--allow-profiles-outside-user-dir')
option.add_argument('--enable-profile-shortcut-manager')
option.add_argument('--enable-aggressive-domstorage-flushing')
browser_profile_dir = fr"{os.getcwd()}/profile"  # папка заполнится сама
option.add_argument(fr"user-data-dir={browser_profile_dir}")
option.add_argument('--profile-directory=profile')  # название профиля

app_path = fr"{os.getcwd()}\chromedriver\chromedriver.exe"
service = Service(executable_path=app_path)
driver = webdriver.Chrome(service=service, options=option)
```



<a name="Exe_файл"></a>
# Exe файл
Установка - `pip install pyinstaller`  
Exe - `pyinstaller main.py`  
Флаг для автоподтверждения: -y  

Запуск простого файла **.py** с параметрами: `python main.py test_arg 150`  
Запуск **exe** с параметрами (через .bat):  
**cm.bat** (%1 - первый параметр bat):
```
cd D:\PycharmProjects\test\dist\main\
start main.exe %1
```
**python**:  
`os.system(r'D:\PycharmProjects\test\dist\main\cm.bat SomeParam1')`
---
Запуск файла **py** из другого python скрипта **в новом окне консоли**:
```
import subprocess
os.chdir(work_dir)
subprocess.Popen(['start', os.path.join('venv', 'Scripts', 'python.exe'), 'main.py'], shell=True, cwd=work_dir)
```
Завершить **py** скрипт через **pid** (`os.getpid()`):  
```
import signal
os.kill(pid_id, signal.SIGTERM)
```

<a name="OpenCV"></a>
# OpenCV
<a name="Поиск_изображений"></a>
### Поиск изображений
```
import cv2                    # opencv-python
from PIL import ImageGrab     # PIL-Tools
import numpy as np

img = ImageGrab.grab(bbox=(0, 0, 1400, 900))
img.save('images/grabIm.png')
img = cv2.imread('images/grabIm.png')
img_rgb = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
img_rgb = cv2.Canny(img_rgb, 1, 240)

template = cv2.imread('images/test.jpg')
template = cv2.cvtColor(template, cv2.COLOR_BGR2GRAY) 
template = cv2.Canny(template, 101, 101)
w, h = template.shape[:2]

res = cv2.matchTemplate(img_rgb, template, cv2.TM_CCOEFF_NORMED)
threshold = 0.7
loc = np.where(res >= threshold)
total = 0
for pt in zip(*loc[::-1]):  # Switch collumns and rows
    cv2.rectangle(img, pt, (pt[0] + h, pt[1] + w), (0, 0, 255), 2)
    cv2.imshow("qwe", img)
    cv2.waitKey(0)
    total = +1
if total:
    print('+')
else:
    print('no')
```
### Зацикленный поиск изображения
```
def find_img(self, x1, y1, x2, y2, search_b, delay):
    while True:
        time.sleep(delay)
        img = ImageGrab.grab(bbox=(x1, y1, x2, y2))
        img.save('images/grabIm.png')
        img = cv2.imread('images/grabIm.png')
        img_rgb = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
        img_rgb = cv2.Canny(img_rgb, 1, 240)

        template = cv2.imread(search_b)
        template = cv2.cvtColor(template, cv2.COLOR_BGR2GRAY)
        template = cv2.Canny(template, 101, 101)
        w, h = template.shape[:2]

        res = cv2.matchTemplate(img_rgb, template, cv2.TM_CCOEFF_NORMED)
        threshold = 0.7
        loc = np.where(res >= threshold)
        total = 0
        for pt in zip(*loc[::-1]):  # Switch collumns and rows
            total = +1
        if total:
            break
```
### Получение части сохранённого изображения
```
img = cv2.imread('savedImg.png')
img = img[50:100, 200:300]  # y1:y2, x1:x2
```


<a name="Beautifulsoup"></a>
# Beautifulsoup
`pip install beautifulsoup4`  
`pip install lxml` – парсер

`from bs4 import BeautifulSoup`
<a name="Beautifulsoup_Получение_данных_о_странице"></a>
### Получение данных о странице
`pip install requests`
```
import requests
url = "https://forum.vimeworld.com/staff/"

headers = {
    "Accept": "*/*",
    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/115.0.0.0 Safari/537.36"
}
req = requests.get(url, headers=headers)
page = req.text
print(page)
```
<a name="Сохранение_страницы"></a>
### Сохранение страницы
Чтобы не посылать много запросов, можно скачать страницу
```
with open("index.html", "w", encoding="utf-8") as file:
    file.write(page)
```
Чтобы сохранить некоторые страницы их неободимо сначала прогрузить через **selenium** и далее сохранить 
с помощью `driver.page_source`

<a name="Поиск_элемента_на_странице"></a>
### Поиск элемента на странице
Вывод списка (тикер/цена)
```
with open('D:/Documents/всякое/c/Калькулятор доходности майнинга для видеокарт.html', encoding="utf-8") as file:
    page = file.read()

soup = BeautifulSoup(page, "lxml")
f = soup.find("tbody").find_all("tr")
f.remove(soup.find("tbody").find("tr", class_="static"))
for i in f:
    ticker = i.find(class_="crypto-coin__abbr").text
    print(ticker, '\t', i.find(class_="col-green column_desktop text-right").find(class_="text-val").text)
```
Если на скаченной странице не выводятся все элементы, то `soup = BeautifulSoup(page, "html.parser")`
Поиск элементов  
`f = soup.find("tbody").find_parent()`  
В параметрах можно указать фильтр  

**.find_parents()** - Поиск всех родителей (до \<html>)

**.next_element (.previous_element)** – Следующий элемент в глубь (при переносе строки ничего не возвращает, необходим двойной вызов метода)

**find_next() (find_previous())** – Сразу возвращает след. элемент

**find_next_sibling() (.find_previous_sibling())** - Следующий соседний элемент

<a name="Парстинг_атрибутов"></a>
### Парстинг атрибутов
```
f = soup.find(class_="notification notification_wrap notification_danger")
print(f.get("id"))
print(f["id"])
```
<a name="Поиск_элемента_в_тексте"></a>
### Поиск элемента в тексте
Поиск по полному тексту  
`f = soup.find("span", string="Firo (Zcoin)")`

Поиск по части текста (re – модуль регулярных выражений)  
`f = soup.find("span", string=re.compile("Firo"))`

Поиск части без учета регистра  
`soup.find_all(string = re.compile("[Дд]оход"))`

Обращение к тегам  
`soup.a["target"]`
<a name="Антибот_система"></a>
### Антибот система
Взять Accept и User-Agent (можно сгенерировать с помощью библиотек)

![img.png](img/img.png)


<a name="Telegram"></a>
# Telegram

<a name="pyTelegramBotAPI"></a>
## pyTelegramBotAPI
`pip install pyTelegramBotAPI`

Для начала работы необходимо получить api token в BotFather

Пример бота с командами **/start** и **/list 2**
```
import telebot

bot = telebot.TeleBot(TG_TOKEN)

@bot.message_handler(commands=['start'])
def start_command(message):
    bot.send_message(message.chat.id, f"Привет, твой ID: {message.chat.id}")
    
@bot.message_handler(commands=['list'])
def orders_list(message):
    try:
        page_num = re.search(r'/list \d+', message.text)
        if not page_num:
            page_num = 1
        else:
            page_num = int(message.text[6:])
        ...
    except Exception as ex:
        bot.send_message(message.chat.id, text='Ошибка!, parse_mode='HTML')
        
if __name__ == '__main__':
    bot.infinity_polling()
```
**Inline кнопки**
```
from telebot import types
keyboard = types.InlineKeyboardMarkup()

# одна шарокая кнопка (callback_data не обрабатываются в message_handler)
keyboard.row(types.InlineKeyboardButton(text=f"{event_name}", callback_data=f"/info {i['id']}"))

# 2 кнопки в одном ряду
prev_btn = types.InlineKeyboardButton(text=f"{left}", callback_data=f"/list {int(prev)}")
next_btn = types.InlineKeyboardButton(text=f"{right}", callback_data=f"/list {int(next)}")
keyboard.row(prev_btn, next_btn)

bot.send_message(chat_id, text="...", parse_mode='HTML', reply_markup=keyboard)
```
**Обработка команд при нажатии кнопок**
```
@bot.callback_query_handler(func=lambda call: True)
def but_pressed(call):
    if not check_user_id(call.message.chat.id):
        return
    if call.data[:5] == '/info':
        event_id = call.data[6:]
        ...
```


<a name="aiogram"></a>
## aiogram
`pip install aiogram`

Пример:
```
from aiogram import Bot, Dispatcher, types
from aiogram.filters import Command

bot = Bot(token=TOKEN)
dp = Dispatcher()

@dp.message(Command('help'))
async def handle_help(message: types.Message):
    await bot.send_message(chat_id=message.chat.id, text=f"Your id is {message.chat.id}")

@dp.message()
async def echo_msg(message: types.Message):
    await message.answer(text=f"{message.from_user.full_name} sent {message.text}")

async def test_f():
    ...

async def main():
    logging.basicConfig(level=logging.INFO)
    await asyncio.gather(dp.start_polling(bot), test_f())


if __name__ == '__main__':
    asyncio.run(main())
```
Необходимо соблюдать **порядок расположения функций**, например, если функция handle_help будет до echo_msg, 
то первая никогда не выполнится, /help будет отлавливаться echo_msg

Отправлять сообщения можно несколькими способами: **message.answer()** / **bot.send_message()**  
**Не у всех** сообщений есть **message.text** (например, если отправят фото)


<a name="pyrogram"></a>
## pyrogram
Автоматизация взаимодействия программы с tg аккаунтом

Получение API ключа:  
https://my.telegram.org/auth  
Вход - API development tools - set App title, Short name, select Desktop - App api_id, App api_hash

Пример атоматизации общения со сторонним ботом:
```
from pyrogram import Client
bot_id = 'test_parser_bot'
client = Client(name='my_session', api_id=data['api_id_tg'], api_hash=data['api_hash_tg'])

client.start()
# получить id последнего сообщения
last_msg_id = next(client.get_chat_history(bot_id, limit=1, offset_id=-1)).id 

# отправить сообщение
client.send_message(bot_id, "test msg")

# ожидание нового сообщения
while True:
    time.sleep(2)
    msg = next(client.get_chat_history(bot_id, limit=1, offset_id=-1))
    if not msg.outgoing and msg.id != last_msg_id:
        last_msg_id = msg.id
        
        # получение текста
        print(msg.text)
        num_search = re.search(fr"номер: \d+\", msg.text)
        if num_search:
            num = re.search(r"\d+", num_search.group()).group()
        
        # получение ссылки из, прикреплённой к ответу, кнопки
        url = msg.reply_markup.inline_keyboard[0][0].url
        
        break

    print('waiting...') 

client.stop()
```
При первом запуске pyrogram потребует авторизоваться и ввести код из tg, далее **куки** с авторизацией сохранятся в **my_session.session**



<a name="WhatsApp"></a>
# WhatsApp

## pywhatkit
`pip install pywhatkit`

_Не всегда работает стабильно, для более стабильной работы с whatsapp лучше использовать 
selemium с профилем браузера (потому что через cookies тоже проблемы), где уже произведена авторизация_

Рассылка сообщений.  
Работает с вэб версией whatsapp. Необходимо заранее авторизироваться в браузере по-умолчанию. 
```
import pywhatkit

# В начале код страны: +...
phone = '+7 (900) 100 20 30'  # или другие варианты c '+' ('+79001002030')
pywhatkit.sendwhatmsg_instantly(phone_no=phone, message=msg, wait_time=15, tab_close=True)
```
Изначально время задержки указано 15 сек, чтобы успели прогрузиться все элементы страницы. 
Иначе сообщение может быть в TextArea, но не успеть отправиться.



<a name="Other"></a>
# Other
<a name="Other_Практика"></a>
### Практика
Синтактический сахар и тд.

`n = m if m > 0 else -1`

`l = l or []`

```
for x, y in (10, 2), (4, 7), (0, 4):
    print(x, y)
```

`x = 1; y = 2; x += y`

Создание двумерного массива:  
`M = [[0] * x for i in range(y)]`

`if 1 < x < 10:`

Создание словаря:  
```
x = ['a', 'b', 'c']
d = {x[i]:i for i in range(len(x))}
```

```
v1, v2 = input().split()
v1, v2 = map(int, input().split())
```

```
x = dict(enumerate('qwe'))
print(x)    # {0: 'q', 1: 'w', 2: 'e'}
```

`x[:] = x[::-1]`

```
u = Unit(15, 2)
params = Unit.get_param(u)
```

`if type(x) in (int, float)`

```
u = Unit(15, 2)
u.__dict__['hp'] = 10
```

`len(x.strip(ascii_letters + '-'))`

`all(isinstance(i, int) for i in x) # True/False`
или **any**
```
print(bool(''), bool([]), bool(0))      # False
print(bool('asd'), bool(10), bool(-3))  # True
```

`timeit.timeit(class.method)` измеряет скорость работы метода класса (данный пример зациклится, если в методе будет print)

`b.clicked.connect(lambda: self.print_info(b.text()))` передача метода с подставленным значением, но без вызова этого метода

`print(f"{x=}") # x=2`

Обрабный проход по массиву:  
`for i in reversed(range(3)):` 


<a name="Other_Парсинг"></a>
### Парсинг
Запросы на добавление новой информации на сайты отображаются в разделе Network
(можно указать фильтр Fetch/XHR). После отчистки консоли (Ctrl + L или по кнопке) нужно 
загрузить новую информацию на сайт, например, путём скролла страницы вниз. В запросах можно 
найти нужную информацию либо в формате: site.com/get/?page=2, либо во вкладке Response в виде json.

Сайт для просмотра json - https://jsonviewer.stack.hu/

<a name="Other_UserWarning"></a>
### UserWarning
Убрать UserWarning:
```
import warnings
warnings.filterwarnings('ignore')
```

<a name="Git"></a>
# Git
В VCS активировать систему контроля версий (может предложить докачать компонент Git)  
Создать, если нету .gitignore, добавить:
```
/venv/
/.idea/
```
? (Создаём локльный репозиторий VCS - Create Git Repository)  
Указать отслеживаемые файлы: ПКМ – Git – Add  
Сделать коммит: ПКМ – Git – Commit file  
Посмотреть разницу (Show Diff)  

Для пуша первый раз необходимо указать ссылку на репозиторий (ссылка кончается .git)  
**Запушить**: Commit and push  
**Подтянуть** изменения: Git – Update project  
**Клонировать** пароект: VCS - Get from Version Control - далее вставить ссылку `https://github.com/user/project_name.git`

**Заугрузка проекта из консоли**
### Работа с проектом из консоли Git Bash  
**Клонировать** проект: `git clone https://github.com/user/project_name.git`  
При (_fatal: not a git repository (or any of the parent directories): .git_) - `git init`  
Для того, чтобы **подтянуть** проект в него сначала добавляются файлы с помощью git add  
Чтобы добавить все файлы из папки: `git add .`  
Можно посмотреть информацию о выбранных файлах: `git status`  
Коммит: `git commit -m "some texe"`  
В конце: `git push`

Подтянуть изменения: 
```
cd project_files
# output: ~/files/project_files (master)
git pull
```


<a name="Установка_программы_на_сервер"></a>
# Установка программы на сервер
Подключиться через Putty к консоли  
Обновить пакеты на сервере:  
`sudo apt update`  
`sudo apt –y upgrade`

Добавление диалоговых окон:  
`apt-get install dialog`

Настройка языка:  
`apt-get install locales`  
`dpkg-reconfigure locales`

Выбрать указанные языки, установить default **en_US**  

![img.png](img/img2.png)  

`locale`  
`LANG=en_US.UTF-8`

Установка питона:  
`sudo apt –y install python3-pip`

Доп. средства разработки:  
`sudo apt –y install build-essential libssl-dev libffi-dev python3-dev`

Виртуальное окружение:  
`sudo apt –y install python3-venv`

Для фонового запуска программ:  
`sudo apt –y install screen`

Через FileZilla перекинуть все папки проекта, кроме venv, .idea и dist.  
В консоли перейти в папку с программой (ls для просмотра файлов)  
`cd FolderName`

Переход в виртуальное окружение:  
Создать папку venv  
`python3 –m venv venv` (linux)  
`python –m venv venv` (windows)

Активация виртуального окружения:  
`source venv/bin/activate` (linux)  
`C:\files\priject\venv\Scripts\activate` (windows)

Установка необходимых библиотек:  
_Для начала необходимо создать список пакетов в поректе (**pip freeze > requirements.txt**)_  
_Просмотр пакетов - **pip freeze**_

`pip3 install –r requirements.txt`  

Для того, чтобы бот работал постоянно  
`screen –S Bot`

Запуск:  
`python3 main.py`

---


**screen ls** – посмотреть запущенные скрины  
Свернуть скрин: **Ctrl+A, D**  
Остановить программу в скрине: **Ctrl+C**  
Удалить Screen: **Ctrl+D, K**; **exit** (?или :quit)  
Перейти к свернутому скрину: **screen –r Bot**  
Если скрин подключен (Attached), то нужно сначала отключиться: **screen –rd Bot**  