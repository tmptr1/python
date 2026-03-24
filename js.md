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
Для отладки используется вкладка в браузере Sources

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

_Двоичный_ формат: `var x = 0b10111;  // 23`

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

**Область видимости**  
- var - уровень функции
- let, const - уровень блока кода

```
if(1){
    var a = 10
    let b = 20
}
console.log(a)  // 10
console.log(b)  // Uncaught ReferenceError: b is not defined
```
Привер с разными областями видимости:
```
let a = 1
var b = 2
function f(){
    let a = 11
    var b = 22
    {
        let a = 111
        var b = 222
        console.log('Block let', a)  // 111
        console.log('Block var', b)  // 222
    }
    console.log('Func let', a)  // 11
    console.log('Func var', b)  // 222
}
f();
console.log('Global let', a)  // 1
console.log('Global var', b)  // 2
```
Если **не указывать** тип переменной, то она будет **глобальной**:
```
function f(){a = 1};
f();
console.log(a)  // 1
```
**НО** при строгом режиме **use strict** выдаст ошибку:
```
"use strict";
function f(){a = 1};
f();
console.log(a)  // Uncaught ReferenceError: a is not defined
```
use strict можно объявлять как глобально, так и отдельно, например, внутри функции

JavaScript сначала обходит код и собирает информацию о переменных, а уже вторым обходом запускает всю логику.  
Поэтому **объявленные переменные после их вызова не выдают ошибок _(только var)_**, а обозначаются как undefined
```
console.log(x)  // undefined
console.log(x2)  // Uncaught ReferenceError: x2 is not defined
var x = 1
```


### Операции
**===** и **!==** - сравнивается значение и тип
```
console.log(2=='2');  // true
console.log(2==='2');  // false
```
И - **&&**, Или - **||**  
если первое условие прошло, то возвращается значение второго:  
`console.log(true && 'txt');  // txt`  
аналогично с _Или_

Не - **!**  
_Отрицательные числа_ - _**true**_  
`console.log(Boolean(-10));  // true`

**Условные конструкции**:  
`x > 0 && console.log('Hi');`

**Операции присваивания**:
```
var x = true;
var y = false;
y &&= x;  // y = y && x
console.log(y);  // false

x = true;
y = false;
y ||= x;  // y = y || x
console.log(y);  // true
```

**Тернарный оператор**:  
`res = x > 5 ? 'да': 'нет';`

Оператор **??** проверяет значение на _**null**_ и _**undefined**_, при совпадении возвращает правую часть:  
`console.log(5 ?? 'default');  // 5`  
`console.log(null ?? 'default');  // default`

Оператор **??=**  
```
var x;  // undefined
let msg;
msg ??= 'default msg';
console.log(msg);  // default msg
```

**Преобразование** строки в число:
```
var x = '23 text';  // только если число идёт впереди
let q = 1;
console.log(x + q);  // 23 text1
console.log(parseInt(x) + q);  // 24
```
если преобразовать не вышло, то _**NaN**_  
Аналогично с **parseInt** работает **parseFloat**

Также преобразовывать можно с **+** и **-** :  
console.log(+'345.12' - 10);  // 335.12`


<a name="Массивы"></a>
### Массивы
```
var m = [1, 'B', 'C'];  // НЕ строго типизированны
m[6] = 'Hi';
console.log(m);  // ['A', 'B', 'C', empty × 3, 'Hi']
console.log(m[3]);  // undefined
```
Можно изменять элементы массива, которые выходят за его пределы, тогда промежуточные значение будут - _undefined_  

Двумерные массивы: `var m = [[1,2,3], [4,5,6]];`


### Условия if
Если действие условия в одну строку:  
`if(x !== null && x !== undefined) console.log(``value is ${x}``);`

С **else** аналогично:
```
if(x < 10) console.log('10+');
else console.log('10-');
```

**else if**:
```
if(x < 10){
    console.log('10+');
}
else if (x == 10){
    console.log('10');
}
else{
    console.log('10-');
}
```


### switch:
```
var x = 10;

switch(x){
    case 1:
        console.log('one')
        break;
    case 10:
        console.log('ten')
        break;
}
```
В последнем case можно не ставить break

Без **break** будут выполняться нижние case, вне зависимости от значения переменной:
```
let x = 10;

switch(x){
    case 10:
        console.log('ten');
        x -= 5;
    case 20:
        console.log('twenty');
}
// ten
// twenty
console.log(x); // 5
```

**Оъединение** case и значение **default**:
```
switch(x){
    case 5:
    case 10:
        console.log('five or ten');
        break;
    case 20:
        console.log('twenty');
        break;
    default:
        console.log('other value')
}
```

### Циклы
```
for(let i = 0; i < 3; i++){
    console.log(i);
}
```
первую и последнюю часть в **for** можно вынести: `for(;i < 3;)`

Если цикл простой: `for(let i=0; i < 3; console.log(i++));`

Можно прописывать **несколько** счётчиков:
```
for(let i=0, j=0; i < 3, j < 2; i++, j++){
    console.log(i, j);
}
// 0 0
// 1 1
```
Выполняется, пока одно из условий не прекратит выполнение цикла

```
let i = 0;
while (i < 3){
    console.log(i);
    i++;
}
```

Гарантированное выполнение одной итерации:
```
let i = 4;
do{
    console.log(i);
    i++;
}while (i < 3)
// 4
```
**continue**, **break**:
```
for (let i=0; i < 10; i++){
    if (i%2 == 0) continue
    if (i > 5) break
    console.log(i)
}
// 1 3 5
```

**for...in** перебирает свойства в объекте:
```
const coin = {name: 'BTC', val: 65000};
for (prop in coin) console.log(prop, coin[prop]);
// name BTC
// val 65000
```
**for...of** для перебора наборов данных: 
```
let m = ['A1', 'B2', 'C3']
for (i of m) console.log(i);

let s = 'word'
for (i of s) console.log(i);  // w, o, r, d
```

### Функции
```
function send_text(){
    console.log('fff')
}
```
В параметрах функции можно указать значения по-умолчанию

Можно присваивать переменным функции и затем менять их:
```
function start() {console.log('start')}
function stop() {console.log('stop')}

let event = start;
event();
event = stop;
event();
```
**Анонимные** функции объявляются в переменной:
```
let event = function start() {
    console.log('start');
}
event();
```
**Локальные** функции. Вызываются только в основной функции. Минус - создаются каждый раз при вызове функции.
```
function test_f() {
    print_text();
    print_text();

    function print_text(){
        console.log('text');
    }
}
```

**spread-оператор** распаковывает массив:
```
let m = [1, 'B', true]

function test(num, char, bool) {
    console.log(num, char, bool);
}
```
Можно передать в функцию **произвольное кол-во аргументов**, они попадут в **arguments**
```
function test() {
    for (i of arguments) console.log(i);
}
```
**rest-оператор** позволяет упаковать аргументы в массив:
```
function test(...m) {
    console.log(m);  // Array
}

test(1,4,'a');
```
Если функция **возвращает больше одного значения**, то в return указывается массив
```
function test(a, b) {
    let sum = a + b;
    let mult = a * b;
    return [sum, mult]
}

let res = test(2, 3);
console.log(res[0]);
console.log(res[1]);
```
или вернуть **объект**: `return {sum: sum, mult: mult}`

**Функция** может **возвращать функцию**:
```
function f_select(option) {
    if (option == 'sum') return function(a, b){ return a+b}
    else if (option == 'mult') return function(a, b){ return a*b}
    else return function() {return 0}
}

let f = f_select('mult')
let res = f(2, 3);
console.log(res);
```

**Стрелочная функция** для упрощения определения функции:
- **Без** параметров: `let f = () => console.log('FF');`
- Если параметр только **один**, то можно убрать скобки: `let f = x => console.log(x);`
- Для **return**: `let f = (a, b) => a * b;`
- Если возвращается **объект**: `let f = x => ({square: x*x, double: x*2});`

Если инструкций много:
```
let f = (a, b) => {
    let c = a + b;
    return c;
}
```


### Замыкания
Функция запоминает своё состояние
```
function f(){
    let x = 0;
    function inner(){
        x ++;
        console.log(x);
    }
    return inner;
}
fn = f();
fn();  // 1
fn();  // 2
```
В возвращаемую функцию тоже можно **передавать параметры**. 2 Варианта использования:
```
function f(a){
    return function(b) { return a * b; };
}
f1 = f(2);
console.log(f1(3));   // 6
console.log(f(3)(4)); // 12
```
Можно возвращать **несколько функций** и вызывать их:
```
function f(a){
    function print() { console.log(a); };
    function increment() { a++; };
    return [print, increment]
}
fn = f(2);
fn[0]();  // 2
fn[1]();
fn[0]();  // 3
```

### Переопределение анонимной функции
```
function f(){
    console.log('hi')
    f = () => console.log('bye')
}
f();  // hi
f();  // bye
```

### Изменение значений по ссылке
```
function f1(arr){
    arr = [4, 8, 3]
}
function f2(arr){
    arr[1] = 9
}
var m = [2,4,5]
f1(m);  // [2, 4, 5]
f2(m);  // [2, 9, 5]
```
В функцию передаётся **ссылка на объкет/массив**, если попытаться изменить параметр полностью, то он не поменяется.  



<a name="ООП"></a>
### ООП

Объект можно создать: `const product = new Object();` или `const product = {};`

Параметры объекта:  
`const product = {name:'Tire', price:6500};`  
или
```
var name = 'Tire'
var price = 6500
const product = {name, price};
```

Создание объекта с помощью **Object.fromEntries**, данные берутся из массива `[Ключ, Значение]`:
```
var data = [["name", "Tire 5"], ["price", 6500]]
const product = Object.fromEntries(data)
```

**Методы**:
```
const product = {name:'Tire', price:6500};
product.print_into = function(){
    console.log(product.name, product.price)
}
product.print_into()
```
или при объявлении объекта (**this** возвращает ссылку на объект):
```
const product = {
    name: 'Tire', 
    price: 6500,
    print_into: function(){
        console.log(this.name, this.price);
    },
    print_name(){ console.log(this.name); }  // Сокращённый вариант
};
```
Присваивание метода как существующей функции:
```
function print_price() {return console.log(this.price) }

const product = {
    name: 'Tire',
    price: 6500,
    show_price: print_price,  // можно и просто - print_price,
};

product.show_price()
```
Но надо быть осторожнее в функции, потому что **this вне объекта**, обращается к **окну браузера**

---
Альтернативный вариант присваивания свойств (через массив):
```
const product = {
    ["name"]: 'Tire', 
    ["price"]: 6500,
    ["print_info"](){
        console.log(this.name, this.price)
    },
};

product["name"] = 'Tier A210'
```
или через строки: `"base price": 6500, ...`  
Так можно объявлять свойства, с пробелом в названии


Определение полей через массивы позволяет динамически определять их названия:
```
function create_product(param_1, value_1){
    return {
        [param_1]: value_1
    };
}
const product = create_product('name03', 'H120');
console.log(product.name03)
```

**Удаление** свойств/методов:
```
const product = {
    name: 'Tire',
    price: 6500,
};
delete product.price;

console.log(product.price);  // undefined
```

### this
В зависимости от сдеры (веб-браузер/node.js и тд) this ссылается на разные объекты  
Для веб-браузера: _Window {window: Window, self: Window, document: document, ..._

**globalThis** ссылается на глобальный контекст вне зависимости от среды

В функциях this ссылается а внешний контекст в котором он **вызывается** (а не определяется)
```
function f(){
    var x = 1;
    console.log(this.x);  // 2
    console.log(x);  // 1
}
var x = 2;
f();
```

Контекст во вложенных функциях:
```
var A = 0;
var B = 0
function f(){
    var A = 1;
    B = 1;
    function f_in(){
        console.log(this.A);  // 0
        console.log(this.B);  // 1
    };
    f_in();
}
f();
```

Явное указание контекста **apply** и **call**:
```
var x = 0;
function f(){console.log(this.x)};
var obj = {x: 1};

f();  // 0
f.apply(obj);  // 1
```
**bind** создаёт такую же функцию с её облостью видимости, но к привязкой к указаному объекту:  
`const fn = f.bind(obj);`

**Контекст в стрелочныех функциях**  
В стрелочных функциях используется контекст окружение, а не само окружение
```
var x = 0;

var obj = {
    x: 1,
    print_x: ()=> console.log(this.x),
    print_x2: function(){
        let px = ()=> console.log(this.x);
        px();
    }
};

obj.print_x();   // 0
obj.print_x2();  // 1
```

Ещё пример (в print_var контекст замещается глобальным окружением):
```
var obj = {
    name03: 'Tires B2',
    various: [1, 1.2, 1.5],
    
    print_var(){
        this.various.forEach(function(v){
            console.log(this.name03, v)
        })
    },
    print_var_2(){
        let that = this;
        this.various.forEach(function(v){
            console.log(that.name03, v)
        })
    },
    print_var_3(){
        this.various.forEach((v)=>console.log(this.name03, v))
    },
};

obj.print_var();   // [undefined, 1] ...
obj.print_var_2(); // [Tires B2, 1] ...
obj.print_var_3(); // [Tires B2, 1] ...
```


### Копирование объектов
При обычном создании второго объекта из первого передаётся ссылка на первый объект и далее они оба ссылаются на один и те же свойства
```
const obj_1 = {
    name03: 'Tires B2',
    price: 6500,
};
const obj_2 = obj_1;
obj_2.name03 = 'Wheel';

console.log(obj_1);  // {name03: 'Wheel', price: 6500}
console.log(obj_2);  // {name03: 'Wheel', price: 6500}
```
Для **копирования** объекта применяется метод **Object.assign(target, ..sources)**, он позволяет создать новый объект и передать ему свойства указанных объектов
```
const obj_1 = {
    name03: 'Tires B2',
    price: 6500,
};
const obj_cnt = {count: 20}
const obj_2 = Object.assign({}, obj_1, obj_cnt);
obj_2.name03 = 'Wheel';

console.log(obj_1);  // {name03: 'Tires B2', price: 6500}
console.log(obj_2);  // {name03: 'Wheel', price: 6500, count: 20}
```
Если названия свойств совпадают, то берётся свойство из последнего указанного

Но при **вложенных объектах** будет работать такое копирование не будет
```
const obj_1 = {
    storage: {place: 'MSC'},
};

const obj_2 = Object.assign({}, obj_1);
obj_2.storage.place = 'SPB';

console.log(obj_1);  // storage: {place: 'SPB'}
console.log(obj_2);  // storage: {place: 'SPB'}
```

Для копирования с **вложенными объектами** можно использовать **рекурсивную функцию**:
```
function get_params(obj){
    const params = {}
    for(const param of Object.entries(obj)){
        if (typeof(obj[param[0]]) == 'object'){
            params[param[0]] = get_params(obj[param[0]])
        }else{
            params[param[0]] = param[1]
        }
    }
    return params
};

const product = {name03: 'Tire', price: 6500, storage: {place: 'MSC', address:{street: 'Red St.', house:5}}};
const product_2 = get_params(product)
product.storage.place = 'SPB'
product.storage.address.street = 'Green St.'
```

**Копирование с помощью spread-оператора**  
```
const obj_1 = {
    name03: 'Tires B2',
    price: 6500,
};
const obj_2 = {...obj_1, name03: 'Wheel'};

console.log(obj_1);  // {name03: 'Tires B2', price: 6500}
console.log(obj_2);  // {name03: 'Wheel', price: 6500}
```
Если нужно **переопределить свойства**, то можно сразу же их прописать, они заменятся


### Проверка на наличие методов и свойств в объекте
```
const obj_1 = {
    name03: 'Tires B2',
    print_info(){console.log(this.name03)},
};

console.log('count' in obj_1);  // false
console.log('print_info' in obj_1);  // true
```
альтернативный способ: `obj_1.count !== undefined`  
или `obj_1.hasOwnProperty('print_info')`

**Перебор всех свойств и методов**:
```
const obj_1 = {
    name03: 'Tires B2',
    print_info(){console.log(this.name03, this.price)},
};

for(const prop in obj_1){
    console.log(prop, '-', obj_1[prop])
}
// name03 - Tires B2
// print_info - ƒ print_info(){console.log(this.name03, this.price)}
```
Перебор в виде **_ключ: значение_**
```
for(const prop of Object.entries(obj_1)){
    console.log(prop)
}
// ['name03', 'Tires B2']
// ['print_info', ƒ]
```
**keys** и **values** для вывода ключей и значений:
```
console.log(Object.keys(obj_1))   // ['name03', 'print_info']
console.log(Object.values(obj_1)) // ['Tires B2', ƒ]
```


### Создание объекта с помощью функции
```
function create_product(name03, price){
    if(price <= 0){
        price = 100;
    };
    return {
        name03: name03,
        price: price,
        print_info() {console.log(this.name03, this.price)}
    };
};

const prod_2 = create_product('Tire B11', -999);
```

**Функции-конструкторы** и ключевое слово **new**:
```
function Product(name03, price){
    this.name03 = name03;
    this.price = price;
    this.print_info = function(){console.log(this.name03, this.price)};
}

const prod = new Product('Tire A19', 6500);
```
Оператор **instanceof** позволяет проверить с помощью какого конструктора создан объект:  
`console.log(prod instanceof Product);  // true`


### Прототипы объектов. Расширения
Получить прототип (шаблон) **объекта**:
```
const obj = {}
console.log(obj.__proto__);  // constructor: ƒ Object() ...
console.log(Object.getPrototypeOf(obj));  // constructor: ƒ Object() ...
```
Получить прототип **функции-конструктора**:
```
function Product(name03, price){
    this.name03 = name03;
    this.price = price;
}

const prod = new Product('Tire A19', 6500);
console.log(Product.prototype);  // constructor: ƒ Product(name03, price) ...
console.log(prod.__proto__);  // constructor: ƒ Product(name03, price) ...
console.log(Object.getPrototypeOf(prod));  // constructor: ƒ Product(name03, price) ...
```

Прототипу можно **добавлять свойства/методы**:
```
function Product(name03, price){
    this.name03 = name03;
    this.price = price;
}
Product.prototype.print_info = function(){console.log(this.name03, this.price)};

const prod = new Product('Tire A19', 6500);
prod.print_info();
```
**Переопределение свойств/методов** через прототип НЕ буду их менять:
```
function Product(){
    this.print_info = function(){console.log('constr')};
}
Product.prototype.print_info = function(){console.log('prot')};

const prod = new Product();
prod.print_info()  // constr
```

### Функция как объект
В конструкторе можно передавать аргументы и тело функции как строки
```
const f = new Function('x', 'return x*2')
console.log(f(3))
```
Свойства объекта функции:
- arguments - массив аргументов
- length - кол-во аргументов
- caller - определяет функцию, которая вызвала текущую функцию
- name - название функции
- prototype - прототип

Метод **call** задаёт текущий объект (**this**):
```
function Product(name03, price){
    this.name03 = name03;
    this.price = price;
};
function add_price(x){
    console.log(this.price + x);
}

const prod = new Product('Tire A19', 6500);
add_price.call(prod, 250)  // 6750
```
Метод **apply** то же, что и call, но аргументы передаются в виде массива:
`add_price.apply(prod, [250])  // 6750`


### Object.create
Вариант объектов. Передаётся прототип и свойства/методы, которые определяются через _value_ (по-умолчанию свойства после создания объекта **поменять нельзя**):
```
const prod = Object.create(Object.prototype, {
    name03: { value: 'Tier F2'},
    price: { value: 1200},
    print_info: { value: function(){console.log(this.name03, this.price)}},
});
```
Поля помимо value:
- writable - можно ли изменять значение (default: false)
- enumerable - можно ли перебирать атрибут (for...in). Перебор именно всех атрибутов объекта (default: false)
- configurable - можно ли менять свойства атрибута (enumerable, configurable, set, get, но **кроме _writable_**) (default: false)
- set - задаёт функцию, которая вызовется при изменении свойства
- get - задаёт функцию, которая вызовется при чтении свойства

```
const prod = Object.create(Object.prototype, {
    name03: { 
        value: 'Tier F2',
        writable: true,
        enumerable: true,
    },
    price: { 
        value: 1200,
        writable: false,
        enumerable: true,
    },
    print_info: { 
        value: function(){console.log(this.name03, this.price)},
        enumerable: false,
    },
});

prod.name03 = 'Tier B100';
prod.price = 900;
prod.print_info();  // Tier B100 1200
for(prop in prod){
    console.log(prop);  // name03, price
}
```
**Добавить/переопределить** свойство (**Object.defineProperty**):
```
const prod = Object.create(Object.prototype, {
    name03: { 
        value: 'Tier F2',
        writable: true,
        enumerable: true,
    },
});
Object.defineProperty(prod, 'price', { 
        value: 1200,
        writable: false,
        enumerable: true,
    })
```
или несколько свойств с помощью **Object.defineProperties**:
```
Object.defineProperties(prod, {
    name03: { 
        value: 'Tier F2',
        writable: true,
        enumerable: true,
    },
    price: {
        value: 1200,
        writable: false,
        enumerable: true,
    },
})
```

### Наследование прототипов
Создание объекта на основе прототипа:
```
const product_prot = {
    name03: '',
    price: 0,
};
const product = Object.create(product_prot);
console.log(product.__proto__)  // {name03: '', price: 0}
```
**Переопределение** метода с вызовом его **базового** функционала:
```
const product_prot = {
    name03: '',
    price: 0,
    get_info: function(){
        return this.name03 + this.price;
    },
};
const product = Object.create(product_prot);
product.name03 = 'Tire H5'
product.price = 1300
product.get_info = function(){
    return 'info: ' + this.__proto__.get_info.call(this)
    // return 'info: ' + Object.getPrototypeOf(this).get_info.call(this)  // альтернатива
}
console.log(product.get_info())  // info: Tire H51300
```

**Проверка** является ли объект прототипом другого объекта:  
`console.log(product_prot.isPrototypeOf(product))  // true`


### Наследование прототипов конструкторов
Пример, где в прототип конструктора **_добавляются новые методы уже после его объявления_** (иначе **_не получится их переопределить в дальнейшем_**), 
далее один объект наследуется от второго со всеми свойствами/методами и переопределяет один из методов:
```
function Product (name03, price) {
    this.name03 = name03;
    this.price = price;
    // this.get_info = function(){ ... }  // Если сразу объявить метод, то НЕ получится потом его переопределить

};
Product.prototype.get_info = function(){  // Добавление метода в прототип
        return this.name03 + ' ' + this.price;
    };

function ProductWH(name03, price, count){
    Product.call(this, name03, price);
    this.count = count;
}

ProductWH.prototype = Object.create(Product.prototype);  // Чтобы добавился метод add_percent
ProductWH.prototype.get_info = function(){return Product.prototype.get_info.call(this) + ' ' + this.count}  // Переопределение

ProductWH.prototype.constructor = ProductWH;  // Чтобы при создании можно было указать 3 параметра

const prod_1 = new ProductWH('Tire 8U', 1000, 17);
console.log(prod_1.get_info());  // Tire 8U 1000 17
```
**Тонкости**:  
- Если в родительский конструктор (Product) доабвить новый метод, то он появится даже в уже существующих дочерних объектах (ProductWH)
- Через прототип дочернего конструктора можно менять методы в родительском конструкторе: <br>`ProductWH.prototype.__proto__.add_percent = function(x) {this.price = this.price * x}`


### Инкапсуляция свойств
Запрет на доступ/редактирование свойств:
```
function Product (name03, price) {
    this.name03 = name03;
    let _price = price;
    this.get_info = function(){
        return this.name03 + ' ' + _price;
    };
};

const prod_1 = new Product('Tire 9R', 1900);
prod_1._price = -99;
console.log(prod_1.get_info());  // Tire 9R 1900
console.log(prod_1._price);  // -99
```
Тут у prod_1 создасться **новая** переменная _price, которая никак не повляет на ту, что в объекте


### Деструктизация
Позволяет разложить объект на переменные:
```
const product = {
    name03: 'Tire 3E',
    price: 1300,
}

const {name03, price} = product  // name03 = 'Tire 3E'
const {name03: name, price: price_rub} = product  // name = 'Tire 3E'
const {name03: name, price: price_rub = 0, count: count = 0} = product  // price_rub = 1300, count = 0
```
В последней строчке берётся свойство из объекта, иначе возвращается **значение по-умолчанию**

Получение **вложенных** объектов:
```
const product = {..., storage: {place: 'MSC'},}

const {name03, storage: {place}} = product;
console.log(place)  // MSC
```
**Отделить** все оставшиеся свойства в отдельный объект:
```
const {name03, ...etc} = product;
console.log(etc);  // {price: 1300, storage: {…}}
```
**Деструктизация массивов**:
```
const m = ['Ab', 'Cd', 'Ef'];
const [a, b, c] = m;
```
Если переменных **меньше**, чем в элементов в массиве _m_, то остальные элементы игнорируются  
Если **больше**, то _undefined_

**Игнорирование** некоторых элементов:
```
const m = ['Ab', 'Cd', 'Ef', 'Gh'];
const [,x2,,x4] = m;
```
**Деструктизация объектов массивов**:
```
const m = [
    {name03: 'A', count: 1},
    {name03: 'B', count: 2},
    {name03: 'C', count: 2},
];
const [,{name03}] = m;
console.log(name03)  // B
```
**Деструктуризация в цикле**:
```
for(let {name03: name_i} of m){
    console.log(`Имя: ${name_i}`)
}
```
Можно раскладывать **параметры функции** (при работе с объектами или массивами):
```
function f({name03: f_name}){ console.log(f_name); }

function f2([x, y]){
    console.log(x + y)
}
f2([1, 2, 3]) // 3
```

С помощью разложения легко **менять** значения переменных **местами**:
```
var x = 2;
var y = 3;
[x, y] = [y, x];
```


### Проверка на наличие свойств. Оператор ?.
```
const product = {
    name03: 'Tire 3E',
    price: 1300,
    storage: {place: 'MSC'},
    add_price(x){return this.price + x},
}

console.log(product?.name03)  // Tire 3E
console.log(product?.storage?.street)  // undefined
console.log(product.add_price?.(3))  // 1303  (если нет return, то выполнит функцию и возвратит undefined)
console.log(product.add_count?.(5))  // undefined
```

### Запрет на изменение объекта
**Object.preventExtensions** запрещает добавлять новые свойства к объекта:
```
const product = { name03: 'Tire 3E'}
Object.preventExtensions(product)
product.count = 10;
console.log(product.count)  // undefined
```
Чтобы проверить: является ли объект расширяемым?  
`console.log(Object.isExtensible(product))  //false` 

**Закрытие** объекта на **редактирование** **(Object.seal)**:
```
Object.seal(product);
product.count = 10;  // свойство НЕ добавится
Object.defineProperty(product, 'price', {writable: false})  // Изменит
product.price = 10;  // после запрета defineProperty НЕ изменится
Object.defineProperty(product, 'price', {writable: true})  // Uncaught TypeError: Cannot redefine property: price
```
Повторное **defineProperty** выдаст ошибку  
Проверка на закрытый объект: `console.log(Object.isSealed(product))  //true` 

**Заморозка** объекта **Object.freeze**.  
**const** только запрещает присваивать переменной новое значение (в случае с объектом нелья присвоить константе новый объект) 
```
Object.freeze(product);
product.count = 10;
product.price = 500;
console.log(product)  // {name03: 'Tire 3E', price: 1300}
```
Проверка: `console.log(Object.isFrozen(product))  // true`


### Классы
По сути классы в JS - это синтакситечкий сахар, просто более удобный способ создавать объекты

Создание класса: `class Product {}`  
Анонимный класс: `const Product = class{}`

Можно присвоить определение класса в константе и далее создавтаь объекты через неё: 
```
const ProductCreator = class Product{}
const prod_1 = new ProductCreator()
console.log(prod_1)  // Product {}
```

**Поля** класса (можно указать начальные значения):
```
class Product{
    name03;
    price = 0;
}
const prod_1 = new Product()
```
**Методы** класса:
```
class Product{
    name03 = 'None';
    price = 0;
    get_info(){
        return this.name + ' ' + this.price;
    }
};
```
**Конструктор** (если поля определяются в конструкторе, то их можно дополнительно не объявлять в начале):
```
class Product{
    constructor(pName, pPrice){
        this.name03 = pName;
        this.price = pPrice;
    };
}
const prod_1 = new Product('Tire A', 1400)
```

**Приватные поля** обозначаются символом **#**
```
class Product{
    #price;
    constructor(pName, pPrice){
        this.name03 = pName;
        this.#price = pPrice;
    };
}
```
**Приватные методы**:
```
class Product{
    #price;
    constructor(pName, pPrice){
        this.name03 = pName;
        this.#price = pPrice;
    };
    #check_price(){
        if(this.#price <= 0){
            console.log('Некорректная цена')
        }
    };
    test(){
        this.#check_price();
    };
}
```

**Статические поля**  
**static** поля хранят данные для всего класса, а не только для отдельных объектов:
```
class Product{
    static code = '1ABC';
    constructor(pName, pPrice){
        this.name03 = pName;
        this.price = pPrice;
    };
    get_info(){
        console.log(Product.code)
    }
}
console.log(prod_1.code)   // undefined
console.log(Product.code)  // 1ABC
```
Внутри класса к таким полям **нельзя** обращаться через **this**, только через **имя класса** 

**Статические методы** работают по аналогии со static полями.  
В static методах чтоб обратиться к static полю **класса** используется **this**
```
class Product{
    static code = '1ABC';
    static get_info(prod){
        console.log(this.code, prod.code)  // 1ABC 2CDE
    }
}
const prod_1 = new Product()
prod_1.code = '2CDE'
Product.get_info(prod_1)
```
Можно совмещать **static** и **private**: `static #code = '1ABC';`

### Геттеры и сеттеры
```
class Product{
    #name03;
    #priceValue;
    constructor(name03, price){
        this.#name03 = name03;
        this.#priceValue = price;
    }
    set price(value){
        if(value > 0){
            this.#priceValue = value;
        }
    }
    get price(){ return this.#priceValue; }
}

const prod_1 = new Product('Tire A7', 900);
prod_1.price = -99
```

### Наследование
Классы наследуются через ключевое слово **extends**:
```
class Product{ #name03; ...}

class ProductWH extends Product{
    count = 0;
}
```
Для обращения к базовому классу используется **super**
```
class ProductWH extends Product{
    count;
    constructor(name03, price, count){
        super(name03, price)
        this.count = count
    }
}
```
Обращаться к **прватным полям** родительского класса **нельзя**

**instanceof** используется для проверки к каким классам объект имеет отношение:
```
class Product{ #name03; ... }
class ProductWH extends Product{ count = 0; ... }
class Employee{}

const prod_1 = new ProductWH('Tire A7', 900, 14);
console.log(prod_1 instanceof Product)    // true
console.log(prod_1 instanceof ProductWH)  // true
console.log(prod_1 instanceof Employee)   // false
```


### Массивы
```
const m = []
const m2 = Array()
const m3 = Array.of('A', 'B'
```

**Array.from**

1. Создаёт массив из объекта со свойством _length_:  
`const m = Array.from('hi')  // ['h', 'i']`

2. Применяет к элементам массива лямбда функцию:  
```
const data = [2, 3, 1]
const m = Array.from(data, x => x * 2)  // [4, 6, 2]
```
3. Позволяет раскладывать элементы на значение и индекс в лямбда функцию:
```
const data = ['A', 'B', 'C']
const m = Array.from(data, (element, index) => {
	return index * 2
})
console.log(m)  // [0, 2, 4]
```
```
const m = Array.from({length:3, 0: "Ab", 1: "Cd", 2: "Ef"}, (element) => {
	return `${element}+`
})
console.log(m)  // ['Ab+', 'Cd+', 'Ef+']
```

**spread-оператор** позволяет разложить массив на значения:
```
const m = ['A', 'B', 'C']
const m2 = [...m]
const m3 = new Array(...m)
const m4 = Array.of(...m)
```
Объединение массивов:
```
const m = ['A', 'B']
const m2 = ['C', 'D']
const m3 = [...m, 'X', ...m2]
console.log(m3)  // ['A', 'B', 'X', 'C', 'D']
```


### Операции с массивами
**Добавление данных**  
- push - добавление данных в конец массива:
```
const m = ['A', 'B']
m.push('C')  // ['A', 'B', 'C']
```
- unshift - добавление в начало: `m.unshift('C')  // ['C', 'A', 'B']`
- splice - добавление по определённому индексу: `m.splice(1, 0, 'C')  // ['A', 'C', 'B']`
или добавить несколько элементов: `m.splice(1, 0, 'C', 'D')  // ['A', 'C', 'D', 'B']`

**Удаление данных**  
- pop - удаление последнего элемента, возвращает удалённый элемент: `const d_el = m.pop() // С`
- shift - удаляет первый элемент и возвращает его
- splice - удаляет элементы с определённого индекса и возвращает удалённый список
```
const m = ['A', 'B', 'C', 'D']
const dels = m.splice(2)
console.log(dels)  // ['C', 'D']
console.log(m)     // ['A', 'B']
```
Удалить с конца: `m.splice(-2)`  
Удалить срез элементов с n1 по n2: `m.splice(1, 2)`  

**Замена данных**  
```
const m = ['A', 'B', 'C', 'D']
m.splice(1, 2, 'Q', 'W', 'E')  // ['A', 'Q', 'W', 'E', 'D']
```


**Глубокое копирование slice**
```
const m = ['A', 'B', 'C']
const m2 = m.slice()
const m3 = m.slice(1)  // ['B', 'C']
const m4 = m.slice(-1)  // ['C']
const m5 = m.slice(0, 1)  // ['A']
const m6 = m.slice(0, -1)  // ['A', 'B']
const m7 = [...m]
```
Копирование элементов внутри массива **copyWithin**  
Элементы 2-5 начинают вставляться с индекса 1:
```
const m = ['A', 'B', 'C', 'D']
const m2 = m.copyWithin(1, 2, 5)
console.log(m2)  // ['A', 'C', 'D', 'D']
```
**toSpliced** возвращает объекты вне диапазона
```
const m = ['A', 'B', 'C', 'D', 'E']
const range = m.toSpliced(1, 3)
console.log(range) // ['A', 'E']
```
**concat** объединение массивов
```
const m = ['A', 'B', 'C']
const m2 = ['Q', 'W']
const m3 = m.concat(m2)  // ['A', 'B', 'C', 'Q', 'W']
```
**join** объединение массивов в строку
```
const m = ['A', 'B', 'C']
console.log(m.join())  // A,B,C
console.log(m.join('; '))  // A; B; C
```

**Сортировка**  
По-умолчанию сортировка происходит по алфавиту, поэтому:
```
var m = ['F', 'A', 'B', 'D']
console.log(m.sort())  // ['A', 'B', 'D', 'F']

var m = [5, 10, 45, 8, 0]
console.log(m.sort())  // [0, 10, 45, 5, 8]
```
В сортировку можно передать функцию для сортировки, которая принимает 2 соседних элемента:
```
var m = [5, 10, 45, 8, 10]
function f(a, b){
	return a - b
	// ИЛИ
	// if(a > b){
	// 	return 1
	// }else{
	// 	return -1
	// }
}
console.log(m.sort(f))  // [0, 10, 45, 5, 8]
```
или `m.sort( (a, b) => a - b )`

Сортировка sort **меняет** масив, чтобы изначальный массив не менялся есть **toSorted** (возвращает отсоритрованный массив):  
`console.log(m.toSorted( (a, b) => a - b ))`


Обратный порядок элементов **reverse** (меняет изначальный массив):
```
var m = ['Q', 'W', 'E']
console.log(m.reverse())  // ['E', 'W', 'Q']
```
**toReversed** возвращает новый массив и не меняет изначальный


**Поиск индекса элемента**
```
var m = ['A', 'B', 'C', 'A', 'B']
console.log(m.indexOf('A'))  	// 0
console.log(m.lastIndexOf('A')) // 3
console.log(m.indexOf('D'))		// -1
```
indexOf - первое вхождение  
lastIndexOf - последнее вхождение  
Если не найдено, то вернёт -1

Наличие элемента в массиве **includes** (вторым параметром принимает индекс с которого начинать искать):
```
var m = ['A', 'B', 'C', 'A', 'B']
console.log(m.includes('A'))    // true
console.log(m.includes('C', 3)) // false
```
Для поиска с конца (например, последние 2 элемента) берётся число с минусом


Проверка всех (**every**) элементов по условию. 
```
var m = [1, 2, 3]
console.log(m.every( x => x > 0))    // true
```
Проверка на соответствие условию хотя бы для одного элемента (**some**):
```
var m = [1, -2, -3]
console.log(m.some( x => x > 0))    // true
```

Применение **фильтра** для массива:
```
var m = [1, -2, 3, 0, -5]
console.log(m.filter(x => x > 0))    // [1, 3]
```
В фнукцию передаётся _элемент, индекс и ссылка на массив_ 

Применение функции ко всем элементам (**forEach**):  
`console.log(m.forEach(x => console.log(x * 2)))`

**map** применяет функцию ко всем элементам и возвращает новый массив:  
`console.log(m.map(x => x * 2))    // [2, 4, 6]`

Поиск _первого_ элемента, который удовлетворяет условия функции:  
`console.log([3, 7, 9].find(x => x > 5))    // 7`

Для поиска _последнего_ элемента:  
`console.log([3, 7, 9].findLast(x => x > 5))    // 9`

**findIndex** и **findLastIndex** аналогичны, но возвращают индекс

**flat** раскладывает массив (из многомерного делает одномерный массив):
```
var m = [3, 7, 9, [1, 2, [5, 6]]]
console.log(m.flat())           // [3, 7, 9, 1, 2, [5, 6]]
console.log(m.flat(2))          // [3, 7, 9, 1, 2, 5, 6]
console.log(m.flat(Infinity))   // [3, 7, 9, 1, 2, 5, 6]
```
По-умолчанию раскладывает только 1 уровень вложенности, но можно указать уровень (_Infinity_ для безлимита)


**with** изменяет элемент в массиве и возвращает новый массив
```
var m = ['A', 'B', 'C']
var m1 = m.with(1, 'D')
console.log(m)  // ['A', 'B', 'C']
console.log(m1) // ['A', 'D', 'C']
```

**reduce** сводит значения массива к одному значению. Параметры: (prev, current, index, array)
```
var m = ['A', 'B', 'C']
console.log(m.reduce((prev, cur) => prev += cur))               // ABC
console.log(m.reduceRight((prev, cur) => prev += cur))          // CBA
console.log(m.reduce((prev, cur) => prev += cur, 'reduce: '))   // reduce: ABC
```
Можно задать **начальное значение** как в последнем примере


Методы массивов можно **комбинировать**:
```
function Person(name, age){
        this.name = name;
        this.age = age;
}
const people = [
        new Person("Tom", 38), new Person("Kate", 31), 
        new Person("Bob", 42), new Person("Alice", 34), 
        new Person("Sam", 25)
    ];
var ageFilter = (x) => x.age > 31;
var namePrint = (x) => console.log(x.name);
people.filter(ageFilter).forEach(namePrint)
```

### Наследования массивов
Объект наследуется от Array, дополнительно к нему добавляется новое поле и переопределяется метод push:
```
class Orders extends Array{
    constructor(id, ...products){
        super(...products);
        this.id = id;
    }
    push(product){
        if(product.price > 0) super.push(product)
    }
};

var prod_1 = {name03: 'Tire F2', price: 500}
var prod_2 = {name03: 'Oil R10', price: 60}
const order_list = new Orders(15, prod_1, prod_2)
var prod_3 = {name03: 'new', price: 0}
order_list.push(prod_3)

console.log(order_list)  // Orders(2) [{…}, {…}, id: 15]

for(order of order_list){
    console.log(order)  // {name03: 'Tire F2', price: 500} ...
}
```



# Строки
Повторение строк **repeat**:
```
var s = 'qw '
console.log(s.repeat(3))  // qw qw qw 
```
Для перевода строки в **нижний**/**верхний** регистр - **toLowerCase**/**toUpperCase**

**Удаление пробелов**:
- trim - удаляет по краям
- trimStart - удаляет пробелы с **начала** (_зависит правосторонней и левосторонней системы_)
- trimEnd - удаляет пробелы с **конца** (_зависит правосторонней и левосторонней системы_)
- trimLeft - удаляет пробелы **слева**
- trimRight - удаляет пробелы **справа**

**concat объединяет** строки: `s1.concat(s2)`

**replace заменяет** первое вхождение подстроки в строке: `s1.replace('msg', 'message')`  
**replaceAll** заменяет все вхождения

**split разделяет** строку на массив: `s1.split(',')`

Поиск индексов вхождений подстроки (**indexOf**, **lastIndexOf**):
```
var s = 'test msg'
console.log(s.indexOf('s'))      // 2
console.log(s.indexOf('s', 7))   // -1
console.log(s.lastIndexOf('s'))  // 6
console.log(s.indexOf('x'))      // -1 если не найдено
```
Вторым параметром можно задать индекс с которого надо начинать поиск

Проверка на содержание подстраки (**includes**):
```
console.log(s.includes('s'))      // true
console.log(s.includes('s', 7))   // false
```
**startsWith**/**endsWith** - проверка: начинается/заканчивается ли строка на указанную подстроку  
Вторым параметром можно указать индекс с которого начинать поиск

Заполнение строки доп. символами:
```
var s1 = 'test'
console.log(`|${s1.padStart(7)}|`)        // |   test|
console.log(`|${s1.padEnd(7)}|`)          // |test   |
console.log(`|${s1.padStart(7, '_-')}|`)  // |_-_test|
```

### Получение подстроки
**substring** берёт указанную часть строки или часть с указанного индекса до конца строки:
```
var s = 'test msg'
console.log(s.substring(5, 9))  // msg
console.log(s.substring(5))     // msg
console.log(s.substring(9, 5))  // msg (порядок индексов не важен)
```
**slice** похож на substring, но передаваемые индексы должны идти по возрастанию, а ещё можно указывать отрицательные индексы (возьмёт с конца строки):
```
console.log(s.slice(5, 9))  // msg
console.log(s.slice(-3))    // msg
```
**substr** (_не является стандартом_) берёт с указанного индекса определённое кол-во символов или всё, до конца строки
```
console.log(s.substr(5, 3))  // msg
console.log(s.slice(5))      // msg
```
---

Получить символ массива и его код:
```
console.log(s.charAt(2))      // s
console.log(s.charCodeAt(2))  // 115
```

### Вставка html кода на страницу
```
const prod = {name03: 'Tire T6', price: 550}
const div_info = `<div>
<p>Название: ${prod.name03}</p>
<p>Цена: ${prod.price}</p>
</div>`;
document.body.innerHTML = div_info;
```
Пример с выводом значений из списка (но запятая между элементами выводится тоже как отдельный объект):
```
const prods = ['Tire T6', 'Tire H10']
const div_info = `<div>
${prods.map(p => `<p>Название: ${p}</p>`)}
</div>`;
document.body.innerHTML = div_info;
```

### Тег-функции
Используются как префиксы перед шаблонами, в **parts** передаются значения до переменной (_parts[0]_) и после (_parts[1]_)
```
function priceCheck(parts, product){
    if(product.price > 0) return `${parts[0]}${product.name03}${parts[1]}`
    else return `Ошибка цены у ${product.name03} [${product.price}]`
}

const prod_1 = {name03: 'Tire H4', price: 150}
const prod_2 = {name03: 'Tire Y7', price: 0}

console.log(priceCheck`Товар ${prod_1}.`)  // Товар Tire H4.
console.log(priceCheck`Товар ${prod_2}.`)  // Ошибка цены у Tire Y7 [0]
```

### Регулярные выражения
```
const rEx = /re/
const rEx2 = new RegExp('re')
```
**test** для проверки наличия подстроки в строке:
```
const part = /msg/;
const text = 'test msg';
console.log(part.test(text))  // true
```
**exec** возвращает найденную часть или _null_:  
`console.log(part.exec(text))  // ['msg', index: 5, input: 'test msg', groups: undefined]`

**Спец. символы**:
- **.** - обозначает любой символ
- **|** - или
- **[ab]** - любой из символов в скобках
- **[^ab]** - всё, кроме символов в скобках
- **[a-zA-Z0-9]** - диапазон
- **\d** - цифры
- **\D** - НЕ цифры
- **\w** - буква (англ) / цифра / символ **_**
- **\W** - инверсия w
- **\s** - пробел
- **\S** - НЕ пробел
- **^** - начало строки
- **$** - конец строки
- **\b** - начало или конец слова
- **\B** - НЕ граница слова

**Флаги выражений**:
- **g** - поиск всех подстрок
- **i** - игнорирование регистра
- **m** - поиск подстрок в многострочном тексте
- **s** - поиск подстроки без учёта переноса строк, оператор **.** заменяет **\n**

**Примеры**:
`const part = /(my|pg)sql/;`
пример с `\b` и `\B`:
```
const part1 = /my/;
const part2 = /my\b/;
const part3 = /my\B/;
const text1 = 'db=mysql';
console.log(part1.test(text1))  // true
console.log(part2.test(text1))  // false
console.log(part3.test(text1))  // true

const text2 = 'db=my sql';
console.log(part3.test(text2))  // false
```
Пример с флагами (тут совмещено 2 флага **s** и **i**):
```
const part = /m.y/si;
const text = 'db=M\nysql';
console.log(part.test(text))  // true
```









