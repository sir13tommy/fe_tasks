# Условия и циклы

Напишите решения на javascript для следующих задач

1. Перепишите пример ниже, используя if.
```javascript
var color = prompt("Введите цвет","");
switch (color){
    case "red": document.write("<div style='background-color: red;'>красный</div>");
    case "black": document.write("<div style='background-color: black; color: white;'>черный</div>");
                break;
    case "blue": document.write("<div style='background-color: blue;'>синий</div>");
    case "green": document.write("<div style='background-color: green;'>зеленый</div>");
                break;
    default: document.write("<div style='background-color: gray;'>Я не понял</div>");
}
```

2. Спросите у пользователя сколько ему лет используя prompt(). Проверте ввел ли он корректное значение (число от нуля до 100). Выведите в консоль мессадж с ошибкой если неправильное

3. Напишите switch который выводит колличество дней в месяце указаном в переменной(jan, fab, march ...).

4. Напишите код который приветсвует пользователя в зависимости от того сколько ему лет. Приветсвия придумайте сами. Например: 'Привет сопля', 'Привет', 'Приветсвую', 'Здравствуйте', 'Здравствуйте многоувожаемый старый мурдый человек'.

5. Рассширьте предыдущий код добавив к привествию фразу про погоду(или время дня). 'Привет. Хороший день сегодня', 'Привет. Хороший вечер сегодня'

6. Сделайте декларативную JSON структура для html кода ниже
```html
<body>
    <div>
        <span>Enter a data please:</span><br/>
        <input type='text' id='name'>
        <input type='text' id='surname'>
    </div>
    <div>
        <button id='ok'>OK</button>
        <button id='cancel'>Cancel</button>
    </div>
</body>
```
* каждый тэг будет объектом
* имя тэга будет полем tagName
* вложенные тэги будут в поле subTags
* текст в тэге будет в поле text
* набор аттрибутов тэга будет в поле attrs.

7. Организуйте заполнение полей в объекте через prompt() и confirm()
```javascript
var notebook = {
    brand: "HP",
    type:  "440 G4",
    model: "Y7Z75EA",
    ram: 4,
    size: "14",
    weight: 1.8,
    resolution: {
        width: 1920,
        height: 1080,
    },
};

var phone = {
    brand: "meizu",
    model: "m2",
    ram: 2,
    color: "black",
};

var person = {
    name: "Donald",
    surname: "Trump",
    married: true,
}
```
Например:
```javascript
var person = {
    name: prompt("Enter a name"),
    surname: prompt("Enter a surname"),
}
```

8. Сделайте цикл с confirm, который продолжается по Отмена и заканчивается по ОК.

9. Спросите пользвователя про любое положительное число. С помощью цикла выведите все простые числа до него в консоль.

10. Создайте бесконечный цикл, который прерывается с помощью конструкции break, когда Math.random() > 0.9. Код должен подсчитывать количество итераций и вывести это число с помощью alert.

11. Сформировать строку " # # # # # " с помощью цикла for. Длина строки может быть четной и нечетной, и указывается в одном месте в коде.

12. Сформируйте массив из N элементов, содержащий в себе кубы индексов
```javascript
[0,1,8,27,64...]
```
