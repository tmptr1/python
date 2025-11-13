### [HTML ](#HTML)
- [Списки](#Списки)
- [Таблицы](#Таблицы)
- [Формы ввода](#Формы_ввода)
- [Ссылки](#Ссылки)
### [CSS ](#CSS)
- [Псевдоклассы](#Псевдоклассы)
- [Изменение объекта transform](#Изменение_объекта_transform)
- [Переходы transition](#Переходы_transition)
- [Анимации](#Анимации)
- [Адаптив](#Адаптив)
### [Flexbox ](#Flexbox)
### [Grid Layout](#Grid_Layout)
### [Вёрстка ](#Вёрстка)
- [Блочная верстка (float)](#Блочная_верстка_float)
- [Вертикальное меню display:block](#Вертикальное_меню_display_block)
- [Горизонтальное меню](#Горизонтальное_меню)
- [Пример примитивной страницы](#Пример_примитивной_страницы)
- [Простой шаблон на Flexbox](#Простой_шаблон_на_Flexbox)
- [Простой шаблон на Grid Layout](#Простой_шаблон_на_Grid_Layout)


<a name="HTML"></a>
# HTML
Для выбора стандарта HTML 5.x - <!DOCTYPE html>

Выравнивания **align** - left, right, center, justify (по ширине всей страницы)

Комментарии: `<!-- 123 -->`

**< img >** параметры:
- scr - адрес загружаемого рисунка
- align (bottom, left, right, middle, top)
- alt - альтернативное описание изображения (отображается при неудачной загрузке изображения)
- title - описание изображения (при наведении курсора)
- border - толщина рамки
- height/width
- hspace/vspace - отступы по горизонтали/вертикали

**Выделение текста**:
- < b > - <b>полужирный текст</b>
- < u > - <u>подчеркивание</u>
- < i > - <i>курсив</i>
- < sup > - X<sup>2</sup>
- < sub > - X<sub>2</sub>

Параметры линии **hr**
- align - center, left, right
- color
- Noshade - отменяет трехмерные эффекты
- size - толщина
- width

<a name="Списки"></a>
### Списки
**ul списки**<br>
type = disk, circle, square - изменение маркеры списка  
list-style: none - убрать маркеры
```
<ul type='square'>
  <li>
      <b>usdt</b>
      <ul>
          <li>buy: 1.007</li>
          <li>sell: 1.006</li>
      </ul>
  </li>
</ul>
```
Для изменения ориентации списка в li указывается display: inline;

**ol нумерованные списки**<br>
type = A, a, I, i, 1 - установка системы нумерации<br>
start = 3 - можно указать начальное значение<br>
< li value= 6 > - элементу можно задать своё значение, далее продолжится отсчёт

**< pre >** - отображает текст "как есть"<br>
Полезно для вставки листингов программ

**Вставка спецсимволов**
- & lt; - **&lt;**
- & gt; - **&gt;**
- & nbsp; - пробел
- & copy; - **&copy;**
- & amp; - **&amp;**
- & quot; - **&quot;**

<a name="Таблицы"></a>
### Таблицы
```
<table border=1>
	<tr><td>coin</td><td>price</td></tr>
	<tr><td>usdt</td><td>1.004</td></tr>
</table>
```
**tr** - строки, **td** - столбцы<br>
Параметры:
- **border** - по умолчанию 0
- **align** - left, right, center
- **background** - фоновое изображение для таблицы (url)
- **cellpadding** - расстояние между граничей ячейк и её содержимым
- **cellspacing** - расстояние между смежными ячейками
- **width**
- **bgcolor** - #RRGGBB

Для tr и td параметрами можно задавать выравнивание содержимого, цвет, ширину, valign (выравнивание по вертикали)

Формирование произвольной таблицы
```
<table width="20%" border=1 cellpadding=4 cellspacing=4>
  <tr>
      <td>1</td>
      <td colspan=2>2</td>
  </tr>
  <tr>
      <td rowspan=2>3</td>
      <td>4</td>
      <td>5</td>
  </tr>
  <tr>
      <td>6</td>
      <td>7</td>
  </tr>
</table>
```
<table width="20%" border=1 cellpadding=4 cellspacing=4>
  <tr>
      <td>1</td>
      <td colspan=2>2</td>
  </tr>
  <tr>
      <td rowspan=2>3</td>
      <td>4</td>
      <td>5</td>
  </tr>
  <tr>
      <td>6</td>
      <td>7</td>
  </tr>
</table>

<a name="Ссылки"></a>
### Ссылки
Чтобы все относительные пути достраивались от определённой сылки:
```
<head>
  <baseurl href="http://site.ru">
</head>
```
Ссылки-якори<br>
`<a href="#ref"><img src="images / jpg"></a>`><br>
`<a href="#desc">Описание</a>`<br>
Маркеры можно обозначать через <a name ... или добавив к блоку нужный id<br>
`<a name="ref"></a>`<br>
`<p id="desc">Описание. ...</p>`

Параметр **target** указывает в какой вкладке открыть ссылку<br>
**_blank** - в новой вкладке<br>
**_self** - в текущей (по умолчанию)

**div** - тэг блокового элемента<br>
**span** - тэг текстового уровня

### Фреймы
```
<frameset cols="20%, *">
  <frame name="menu" src="menu.html" noresize>
  <frame name="content" src="index.html">
</frameset>
```
Страница разбирвается на части cols/rows в пропорции "x%, * ". * - для обозначения оставшегося пространства<br>
**noresize** для запрета на изменение пропорции пользователем

Загрузка нового html в определённом фрейме<br>
`<a href="page2.html" target="content">Страница 2</a>`

**Плавающие фреймы**<br>
Позволяют создать окно с сайтом или html, этот блок добавляется в **body**
```
<iframe src="https://aacalc.ru" height="500" width="50%" scrolling="yes">
  <p>Ваш браузер не поддерживает плавующие фреймы</p>
</iframe>
```

<a name="Формы_ввода"></a>
### Формы ввода
```
<form action="send.php" method="post">
  <p><input type="text" name="name" value="">
  <p><textarea name="disc" rows="4" cols="30"></textarea>
  <p><input type="submit" value="Сохранить">
</form>
```
```
<?php
$name = $_REQUEST['name'];
header("Content-type: text/html; charset=utf-8");
echo "<p>$name";
?>
```

**input types**:
- text <input type="text">
- button <input type="button" value="button">
- checkbox (checked для галочки по умолчанию) <input type="checkbox">
- radio <input type="checkbox">
- password <input type="password">
- hidden <input type="hidden">
- reset <input type="reset">
- submit <input type="submit">

value="Начальное значение"

### select
```
<select name="time" size="3">
    <option value="1">1 месяц</option>
    <option value="3">3 месяца</option>
    <option value="6">6 месяцев</option>
    <option value="12">1 год</option>
</select>
```
Параметры:<br>
**size** - кол-во элементов в окне, (без параметра - выпадающий список)<br>
**multiple** - для выбора нескольких значений из списка

### textarea
Ввод многострочного текста<br>
`<textarea>Текст по умолчанию</textarea>`<br>
Параметры:
- cols/rows - высота/ширина поля
- name
- maxlenght - максимальное кол-во вводимых символов (некоторые браузеры не поддерживают)



<a name="CSS"></a>
# CSS
Подключение слитей (в head):  
`<link type="text/css" href="css/style.css" rel="stylesheet">`  
style.css: `pre {color: grey}`  

Добавление стилей в самом html документе  
В head `<style> p {color: blue} </style>`  
Или отдельные тэги `<p style="color: orange;"></p>`

Добавление стилей в css: `@import url("/css/main.css");`

Настройка прозрачности (задаётся параметром alpha):  
`rgba(144, 100, 144, 0.5)`

**Параметры:**
- **margin** - отступы между элементами (сверху справа снизу слева), если аргумент один, 
то подставится везде. auto для одинаковых отступов (эффект центрирования, который работает только по горизонтали)
- **padding** - расстояние между содержимым блока и границей
- **padding-bottom** - расстояне между текстом блока и границей блока
- **font-family** - шрифт, можно указать несколько, если первый не будет найден на
компьютере пользователя, то применится второй
- **font-size**
- **font-weight** - толщина шрифта
- **border**: 3px, solid, darkred - рамки (толщина, тип линии, цвет)
- **list-style: none** - убирает маркеры у ul
- **display** - inline-block чтобы отображать тэг как блоковый, но разрешая отображать в
этой же строке другие элементы. inline для отображения элементов li в одну строку
- **min-width** - минимальная ширины блока для **блокового** элементы
- **float** - расположение (left/right)
- **overflow** - hidden для включения объекта в блок, auto для возможности прокрутить ползунки и посмотреть весь блок
- **overflow-y (/x)** - при hidden даёт возможность прокручивать ползунок только по одной оси
- **border-radius** - скругление границ. 1 или 4 аргумента
- **content** - добавляет текст (используется с псевдоэлементами :after, :before)
- **text-align** - выравнивание текста
- **background** - Примеры: **изображение -** lightgrey url("../images/header.jpg") no-repeat center // **градиент -** linear-gradient(to top, red, orange) // **градиент с углом deg -** linear-gradient(45deg, #000, #FFF) // **круговой градиент -** radial-gradient(#000, #FFF)
- **transition** - плавное изменение характеристик, если в class:hover меняется background, то в class **transition: background 1s linear** позволит менять задний цвет плавно, в течении 1 секунды 
- **word-break** - перенос слов, при параметре **break-word** длинные слова будут переноситься
- **z-index** - задаётся приоритет накладывания объектов на друг друга
- **box-shadow** - тень от блока (2px 2px 5px black) - offset x, y, размытие, цвет


id - для уникалных блоков  
class - для повторяющихся элементов

Добавление стилей для дочерних элементов тэга/id/class:  
`#product_form p b ... { }` или `ul li { }`  
Стили добавить стиль только для конкретной вложенности:  
`#product_form p > b { }`  
Для конкретного типа input:  
`.td_input input[type='text']`  
Чтобы явно указать к какому элементу можно добавлять стили: `ul.coin_list { ... }`  

Применение стилей для элементов одного уровня вложенности:  
`ul + p { }` - применяется только к первому элементу p

**Расширения** для стилей: <br>
`.item.selected { }`
```
  <li class="item">usdt</li>
  <li class="item selected">eth</li>
```
или в случае с id: `#form#selected`

<a name="Псевдоклассы"></a>
### Псевдоклассы  
Для всех элементов:
- **focus** - элемент с активным фокусом (выбор поля для ввода)
- **hover** - при наведении курсора
- **active** - при нажатии кнопки мыши
- **first-child** - применяется к первому дочернему элементу
- **nth-of-type(n/odd/even)** - для выбора конкретных элементов параметры: n / odd - нечетные элементы / even - четные
- **not** - инверсия, например, для всех дочерних элементов, кроме первого: _:not(:first-child)_

Для ссылки:
- **link** - не посещённая ссылка
- **visited** - посещённая
- **active** - выбранная ссылка
- **hover**

если active и hover будут менять одни и те же параметры, то не будет работать корректно
```
.product_input:focus{
    background: #FFFFF0;
}
```
Псевдокласс first-child: `ul li:first-child`

**Псевдоэлементы**:
- **first-letter** - выбор первой буквы элемента 
- **first-line** - первая строка
- **before** - стиль перед элементом
- **after** - после

Элементам можно добавлять позиционирование **position** (элементы будут занимать определённое место на странице):  
- **static** - стандартное позиционирование
- **absolute** - элемент позиционируется относительно границ объекта-контейнера
- **relative** - элемент позиционируется относительно своей позиции по умолчанию
- **fixed** - элемент позиционируется относительно окна браузера

<a name="Изменение_объекта_transform"></a>
### Изменение объекта transform
С помощью **transform** можно:   
- поворачивать объект **rotate(35deg)**
- менять размер **scale(2, 3)** (+ scaleX / scaleY), при помощи отрицательных значений можно зеркально отражать объект
- добавлять оффсет **translate(50px, 30px)** (+ translateX / translateY)
- наклон объекта **skew(35deg, 15deg)** (+ skewX / skewY)

Комбинирование параметров: **transform: rotate(35deg) scale(2);**  
**transform-origin** указывает точку относительно которой будет пременена вся трафнсформация, 
например, 400px 500px или right bottom

<a name="Переходы_transition"></a>
### Переходы transition
Создание 2х секундного перехода (изменение цвета) при :hover
```
#anim{
    background-color: red;
    transition-property: background-color;
    transition-duration: 2s;
}
#anim:hover{
    background-color: orange;
}
```
Через **transition-property** можно указать какие параметры будут меняться  
Можно указать несколько свойств: `transition-property: background-color, height, width;` или выбрать все свойства **all**  
Также можно дополнительно уточнить время перехода для каждого свойства: `transition-duration: 2s, 4s, 1s;`  

Можно контролировать выполнение анимации **transition-timing-function**:
- **linear** - линейный переход
- **ease** - анимация ускоряется только в середине
- **ease-in** - ускорение в начале
- **ease-out** - ускорение в конце
- **ease-in-out** - ускоряется к середине и замедляется к концу
- **cubic-bezier** - для анимации примеянется функция Безье

Задержка перед анимацией: `transition-delay: 1s;`

Применение настроек анимации в одном параметре **transition** `transition: background-color 2s ease-in-out 1s;`

<a name="Анимации"></a>
### Анимации
```
@keyframes changeColor {
    from {
        background-color: yellow;
    }
    to {
        background-color: green;
    }
}
keyframes
#anim_div{
    animation-name: changeColor;
    animation-duration: 10s;
}
```
Можно указывать шаги в анимациях и запускать несколько анимаций сразу:
```
@keyframes changeColor {
    from {
        background-color: yellow;
    }
    33% {
        background-color: green;
    }
    66% {
        background-color: blue;
    }
    to {
        background-color: gray;
    }
}
@keyframes appearance{
    from{
        opacity: 0;
    }
    to{
        opacity: 1;
    }
}
#anim_div{
    animation-name: changeColor, appearance;
    animation-duration: 5s, 3s;
}
```
**animation-iteration-count** для проигрывания анимации n раз или **infinite**  
**animation-direction: alternate;** после проигрывания анимации запускает анимацию в обратную сторону  
**animation-fill-mode: forwards;** после окончания анимации конечный стиль остаётся
**animation-delay** задержка анимации перед стартом  
**animation-timing-function** плавность анимации (аналог transition-timing-function)  

Упращённая запись через **animation**:  
`animation: animation-name animation-duration animation-timing-function animation-iteration-count animation-direction animation-delay animation-fill-mode`  
Пример: `animation: changeColor 5s infinite alternate forwards;`

<a name="Адаптив"></a>
### Отзывчивая верстка viewport
`<meta name="viewport" content="width=device-width">`  
Необходимо убрать все фиксированные величины ширины блоков в px  
Верстка строится на **flex**

### media запросы
@media (max-width:767px) применится если ширина экрана меньше 767px

Составные условия приминения медиа запроса:     
@media (max-width:767px) or (orientation:landscape) # или portrait
```
<meta name="viewport" content="width=device-width">
<style type="text/css">
    ...
    #row {
        display: flex;
        float: left;
        width: 50%;
    }
    #content, #footer p, .nav{
        max-width: 1200px;
        margin: 0 auto; 
    }
    
    @media (max-width:1200px){
        #menu ul, #content, #footer p, .nav{
            max-width: 970px;
        }
    }
    @media (max-width:992){
        #menu ul, #content, #footer p, .nav{
            max-width: 750px;
        }
    }
    @media (max-width:767px){
        #menu ul, #content, #footer p, .nav{
            max-width: none;
        }
        #row {
            width: 100%;
        }
    }
</style>
```
Можно сделать отзывчиво-адаптивную вёрстку, указав media только для мобильных версий

Картинкам лучше всего ставить **max-width: 100%** чтобы они не вылезали за пределы своего блока-родителя

Хорошей практикой считается:  
`<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">`

### Заметки
Страница часто разбивается на общий блок wrapper, в котором содержутся блоки page(content+header) и footer.

У **page** задается min-height: 100%, потому что конетнт может занимать и больше, чем 100%.
Выделяется место для footer`а - padding-bottom: 50px. Для вычисления блока с учётом всех отступов - box-sizing: border-box. 

У **footer** задаётся height: 50px и margin-top: -50px. На случай добавления отступов в этот блок - box-sizing: border-box

У **header** задаётся max-width и height. Фоном подставляется картинка- background: lightgrey url("../images/header.jpg") no-repeat center.
Указывается цвет фона до того, как на нём будет прогружена картинка, путь до файла, отмена повторения, центрирование.

У html и body - height: 100%. background: lightgrey url("../images/bg.jpg") no-repeat 50% 0 fixed.
По центру, по горихонтали (50%), сверху отображение с самого начала, фиксировано (неподвижно при прокрутке)


<a name="Flexbox"></a>
# Flexbox
```
#rows_wrap{
    display: flex;
    flex-direction: column;
}
```
Блокам внутри rows_wrap с помощью **flex-direction** можно задавать порядок отображения: row, row-reverse, column, column-reverse

Расположение блоков в случае, если они не вместились в блок
```
#rows_wrap{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    height: 70px;
    border: 3px solid blue;
}
```
**flex-wrap**: wrap / wrap-reverse создаёт дополнительные row / column для блоков  
Можно указать всё в одном параметре **flex-flow: (flex-direction) (flex-wrap)**

Порядок отображения блоков **order**. По умолчанию равен 0
```
.row {
    padding: 5px;
    background-color: yellow;
    border: 1px solid black;
}
.tier_1{
    order: 1;
}
.tier_2{
    order: -1;
}
...
<div class="row">block 1</div>
<div class="row tier_1">block 2</div>
<div class="row tier_2">block 3</div>
```
Выведутся сначала наименьшие значения (block 3, block 1, block 2) 

**justify-content** выравнивает элементы по основной оси
- flex-start - (по умолчанию) элементы начинаются с левого края / сверху
- flex-end - элементы начинаются с правого края / снизу
- center - элементы по центру
- space-between - боковые элементы у границ, между элементами равномерное пространство
- space-around - расстояния между блоками равномерное, расстояния перед границами - половина расстояния между блоками

**align-items** выравнивает элементы по поперечной оси
- stretch - раслягивает на всю высоту или ширину
- flex-start - элементы прижимаются к левому краю / верху
- flex-end - элементы прижимаются к правому краю / низу
- center - по центру
- baseline - выравнивание в соответсивии со своей базовой линией

**align-self** позволяет переопределять align-items у определённого элемента (auto - значение по умолчанию)
`<div class="row" style="align-self:flex-start">block 2</div>`

**align-content** - выраванивание столбцов/рядов (stretch, flex-start, flex-end, center, space-between, space-around).  
Имеет смысл только есть в родительском блоке больше 2х столбцов/строк
```
#rows_wrap{
    width: 25%;
    display: flex;
    flex-flow: wrap column;
    align-content: space-between;
    height: 200px;
}
```

Размеры элементов  
**flex-basis** определяет начальный размер элементов
```
<div class="row" style="flex-basis: auto; width: 100px;">block 1</div> Размеры width
<div class="row" style="flex-basis: auto; width: auto;">block 2</div> Размеры содержимого блока
<div class="row" style="flex-basis: 100px;">block 3</div> Размер 100px
```

**flex-shrink** уменьшает элементы если размер родительского блока слишком маленький
```
<div class="row" style="flex-basis: 100px; flex-shrink: 3;">block 1</div>
<div class="row" style="flex-basis: 100px; flex-shrink: 2;">block 2</div>
<div class="row" style="flex-basis: 100px; flex-shrink: 1;">block 3</div>
```
Если родительский блок меньше суммы длины/высоты объектов, то их размеры урезаются. Чем больше значение, тем больше уменьшается блок

**flex-grow** аналог flex-shrink, он увеличивает элементы, если есть свободное место. 
Значение 0 по умолчанию, оно не меняет размер блока.

**flex** объединяет все свойства - **flex: (flex-grow) (flex-shrink) (flex-basis)**. Пример параметров: **0 1 auto**

_Шаблон сайта на Flexbox есть ниже_


<a name="Grid_Layout"></a>
# Grid Layout
**display**:  
**grid** - блоки в родителе отображаются как ряды и занимают всю ширину  
**inline-grid** - как grid, но по ширине равны своему сорержимому

**grid-template-columns** / **grid-template-rows** - задаётся кол-во столбцов/строк (кол-во строк может увеличиваться, если дочерних элементов слишком много)
```
#content{
    border: 3px solid blue;
    display: grid;
    grid-template-rows: 100px 100px;
    grid-template-columns: 50% 50%; }
.item{
    background-color: yellow;
    border: 1px solid gray; }
...
<div id="content">
    <div class="item">Grid item 1</div>
    <div class="item">Grid item 2</div>
    <div class="item">Grid item 3</div>
</div>
```
Будет отображена сетка 2 на 2  
Для удобства можно использовать **repeat**:  
`grid-template-columns: repeat(2, 50%);` (50% 50%)  
`repeat(2, 100px 50px);` (100px 50px 100px 50px)  
`100px repeat(3, 50px);` (100px 50px 50px 50px)

**grid** совмещает параметры строк и колонок  
grid: grid-template-rows / grid-template-columns;  
`grid: repeat(4, 50px) / repeat(2, 50%)`

Можно использовать автоматические размеры **auto** `repeat(3, auto)`  
или пропорции **fr** `2fr 1fr` (первая часть в 2 раза больше второй)

**Отступы** между блоками: `grid-column-gap: 5px;` / `grid-row-gap`  
или если отступы между строками и столбцами одинаковые - `grid-gap: 5px;`

**Позиционирование элементов**  
**grid-row-start** / **grid-row-end** указывают с какой и для какой строки будет растянут элемент (для столбцов аналогично)
```
.vip_item{
    grid-row-start: 1;
    grid-row-end: 4; }
```
или через **grid-row**: `grid-row: 1 / 4;`  
**span** указывает на сколько секций растянуть блок: `grid-row: 1 / span 2;`  
**grid-area** объединяет 4 параметра - grid-area: row-start / column-start / row-end / column-end

**Направление блоков**  
**grid-auto-flow**: row (по умолчанию) / column  
**order** определяет порядок расположеня блоков, чем меньше значение - тем ближе к началу блок

**Именованные** grid линии  
```
#content{
    ...
    grid-template-columns: [firstcol] 1fr 1fr 1fr [lastcol]; }
.huge_item{
    grid-column: firstcol / lastcol; }
```
тут блок займёт всё пространство по ширине  
При переименовании столбцов + repeat можно явно указать где будет расположен блок
```
#content{
    ...
    grid-template-columns: repeat(2, [col] 1fr);
    grid-template-row: repeat(3, [row] 1fr); }
.vip_item{
    grid-column: col  2;
    grid-row: row  3; }
```
блок будет пернесён в 2 колонку, 3 ряд

_Шаблон сайта на Grid Layout есть ниже_


<a name="Вёрстка"></a>
# Вёрстка
<a name="Блочная_верстка_float"></a>
### Блочная верстка (float)
```
<style type="text/css">
  div{
      margin: 0;
/*			padding: 5px;*/
      heigth: 50px;
/*			border: 1px solid black;*/
  }
  #header{
      background-color: #4ed9af;
  }
  #LeftSidebar{
      float: left;
      width: 150px;
  }
  #main{
      background-color: #dbfff4;
      height: 200px;
      margin-left: 150px;
  }
  #footer{
      background-color: #89ccb8;
  }
  #menu{
      float: left;
      width: 50px;
  }
  #content{
      height: 80px;
      margin-left: 60px;
  }
  #wrapper{
      background-color: #b3ffe8;
  }

</style>
<div id="header">header</div>
<div id="wrapper">
    <div id="LeftSidebar">LSidebar</div>
    <div id="main">
        <div id="menu">
            menu
        </div>
        <div id="content">
            content
        </div>
    </div>
</div>
<div id="footer">footer</div>
```
В обёртку wrapper помещается сайд бар и блок с контентом, если сайдбар 
короче блока с контентом, то фон wrapper`а принимает цвет сайдбара

<a name="Вертикальное_меню_display_block"></a>
### Вертикальное меню display: block
Некоторым элементам нельзя задать размеры и отступы, например для сслки **a**,
чтобы избежать этого ограничения необходимо поменять тип display на block
```
ul.nav{
  margin: 0;
  padding-left: 0;
  list-style: none;
}
ul.nav a{
  display: block;
  background-color: #3dffc5;
  text-decoration: none;
  color: black;
  height: 30px;
}
ul.nav li:last-child a{
  border-bottom: 1px solid black;
}
...
<div id="LeftSidebar">
  <ul class="nav">
      <li><a href="#">Меню</a></li>
      <li><a href="#">Каталог</a></li>
      <li><a href="#">Контакты</a></li>
  </ul>
</div>
```
<a name="Горизонтальное_меню"></a>
### Горизонватльное меню
Способ с **float: left** и **display: block**
```
ul.nav{
    margin: 0;
    padding-left: 0;
    list-style: none;
}
ul.nav a{
    display: block;
    margin: 5px;
    padding: 3px;
    background-color: #3dffc5;
    text-decoration: none;
    color: black;
    height: 20px;
}
ul.nav a:hover{
    background-color: #0f6;
}
ul.nav li{
    float: left;
}
...
<ul class="nav">
    <li><a href="#">Меню</a></li>
    <li><a href="#">Каталог</a></li>
    <li><a href="#">Контакты</a></li>
</ul>
```
Способ с **display: inline** и **display: inline-block**
```
ul.nav a{
    display: inline-block;
    margin: 5px;
    padding: 3px;
    background-color: #3dffc5;
    text-decoration: none;
    color: black;
    height: 20px;
}
ul.nav li{
    display: inline;
}
```
<a name="Пример_примитивной_страницы"></a>
### Пример примитивной страницы
```
<html>
<head>
    <meta charset="UTF-8">
    <title>Test</title>
    <!-- <link type="text/css" rel="stylesheet"> -->
     <style type="text/css">
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        #header{
            background-color: #9afcb6;
        }
        #menu{
            background-color: #bbfadc;
        }
        ul.nav{
            background-color: #bbfadc;
            list-style: none;
        }
        ul.nav li{
            display: inline;
        }
        ul.nav a{
            text-decoration: none;
            display: inline-block;
            height: 20px;
            color: black;
        }
        ul.nav a:hover{
            font-weight: bold;
        }
        ul.nav li{
            padding-left: 10px;
        }
        ul.nav li:first-child{
            padding-left: 0;
        }
        #wrapper{
            border-top: 1px solid #ccc;
            background-color: #c7fcd6;
            min-width: 768px;
            margin: 0 auto; 
        }
        #L_side{
            float: left;
            width: 10%;
        }
        #R_side{
            float: right;
            width: 10%;
        }
        #main{
            background-color: #deffe7;
            margin-left: 10%;
            margin-right: 10%;
            box-sizing: border-box;
            padding: 15px;
            width: 80%;
            min-height: 200px;
        }
        #main:after{
            clear:both; 
            display:table;
            content:'';
        }
        #main p{
            margin-bottom: 10px;
        }
        #footer{
            background-color: #77a183;
        }
        #menu ul, #content, #footer p{
            max-width: 1200px;
            margin: 0 auto; 
        }
        #wrapper, #menu, #header, #footer{
            min-width: 768px;
            min-height: 30px;
        }
        #menu, #header, #footer{
            padding: 10px;
        }
    </style>
</head>
<body>
<div id="header"><p align="center">header</p></div>
<div id="menu">
    <ul class="nav">
        <li><a href="#">Главная</a></li>
        <li><a href="#">Каталог</a></li>
        <li><a href="#">Инфо</a></li>
    </ul>
</div>
<div id="wrapper">
    <div id="content">
        <div id="L_side">L_side</div>
        <div id="R_side">R_side</div>
        <div id="main">
            <h2>Main</h2>
            <p>В начале для ряда селекторов определяется максимальная ширина...</p>
        </div>
    </div>  
</div>
<div id="footer"><p>footer</p></div>
</body>
</html>
```

<a name="Простой_шаблон_на_Flexbox"></a>
### Простой шаблон на Flexbox
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Test</title>
     <style type="text/css">
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body{
            background-color: #d4f7ff;
        }
        #wrapper{
            max-width: 1200px;
            margin: 0 auto;
            background-color: lightblue;
            display: flex;
            flex-direction: column;
        }
        #content{
            display: flex;
            flex-direction: row;
        }
        #item{
            background-color: lightskyblue;
            border: 1px solid black;
            min-height: 200px;
/*            flex-grow: 1;*/
        }

        #header{
            background-color: skyblue;
        }
        #footer{
            background-color: skyblue;
        }

        @media (max-width:767px){
            #content {
            flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div id="wrapper">
        <div id="header">header</div>
        <div id="content">
            <div id="item" style="flex-grow: 1;">item 1</div>
            <div id="item" style="flex-basis: 90%;">item 2</div>
        </div>
        <div id="footer">footer</div>
    </div>
</body>
</html>
```

<a name="Простой_шаблон_на_Grid_Layout"></a>
### Простой шаблон на Grid Layout
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Test</title>
     <style type="text/css">
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        #wrapper{
            max-width: 1200px;
            margin: 0 auto;
            min-height: 1000px;
            background-color: lightgrey;
        }
        #content{
            min-height: 700px;
            display: grid;
            grid-template-areas: "header header header"
                                ". . ."
                                 "sidebar . main"
                                 ". . ."
                                 "footer footer footer";
            grid-template-columns: 250px 5px 1fr;
            grid-template-rows: 100px 5px 1fr 5px 100px;

        }
        @media (max-width: 767px){
            #content{
                grid-template-areas: "header"
                                    "."
                                     "sidebar"
                                     "."
                                     "main"
                                     '.'
                                     "footer";
                grid-template-columns: 1fr;
                grid-template-rows: 100px 5px auto 5px 1fr 5px 100px;
            }
        }

        .header{
            grid-area: header;
            background-color: #ffb94f;
        }
        .sidebar{
            grid-area: sidebar;
            background-color: #ffe1b5;
        }
        .main{
            grid-area: main;
            background-color: #fff2de;
        }
        .footer{
            grid-area: footer;
            background-color: #e3b674;
        }
    </style>
</head>
<body>
    <div id="wrapper">
        <div id="content">

            <div class="header">header</div>
            <div class="sidebar">sidebar</div>
            <div class="main">main</div>
            <div class="footer">footer</div>
        </div>
    </div>
</body>
</html>
```