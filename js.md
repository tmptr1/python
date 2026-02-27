# JS
### [Основы](#Основы)
- [Типы данных](#Типы_данных)





<a name="Основы"></a>
## Основы
_index.html_:
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <link type="text/css" href="style.css" rel="stylesheet"/>
</head>
<body>

<script src="js/test.js"></script>
</body>
</html>
```
Браузеры могут кэшировать внешние js файлы

Вывод элемента в html:  
- `document.write("<h1>Заголовок</h1>");` (устаревший метод)  
- `document.body.innerHTML = "<p>Строка 2</p>";`

Вывод в консоль (F12): `console.log('Hi')`


<a name="Типы_данных"></a>
### Типы данных
_Переменные не привязаны жёстко к типу данных_

Типы данных: **String**, **Number**, **Bigint**, **Boolean**, **Undefined**, **Null**, **Symbol**, **Object**

В **String** можно использовать любык кавычки: 'Abc', "Abc", \`Abc\`  
_**Экранирование**_ кавычек через \

_**Интерполяция**_ (вставка значений в текст):
```
var x = 10;
var s = `x: ${x}`;  // Только косые кавычки
console.log(s);
```
Для вставки многострочного текста тоже используются _косые кавычки_

Вывод максимальных значений для **Number**:  
`console.log(Number.MAX_VALUE)  // 1.7976931348623157e+308`  
`console.log(Number.MIN_VALUE)  // 5e-324`

При попытки вывести значение, больше максимального, выведется максимальное значение

Для определения **Bigint** к числу дописывается **n**: `var x = 150n`

**Object**:  
`var coin = {};` _пустой объект_  
`var coin = {name: 'USDT', value:1.001};`


С помощью **typeof** можно узнать тип переменной (исключение null - выдаёт object):
```
var x;
console.log(typeof(x));  // undefined
x = 'asd';
console.log(typeof(x));  // string
x = 11;
console.log(typeof(x));  // number

console.log(typeof(null));  // object !!
```