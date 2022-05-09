### Задание 1 ###
Замените код скрипта из шага 4 выше на собственную реализацию простейшей игры «Угадай число», в соответствии со следующим алгоритмом:

загадать число, используя функцию Math.random(), сохранить его в переменную.

Примечание: для получения случайного целого числа в диапазоне от 0 до 999, можно использовать следующую конструкцию: let n = Math.floor(Math.random() * 1000);

для целей отладки вывести число в консоль, используя функцию console.log();

предложить пользователю ввести число, используя функцию prompt() и проверку, что введено числовое значение, используя функцию isNaN();

если введено не число, выдать соответсвующее сообщение с помощью функции alert();

сравнить введенное число с загаданным;

вывести пользователю результат угадывания в зависимости от сравнения с расшифровкой в случае не совпадения: «Больше» или «Меньше». Для вывода использовать функцию alert().

### Примечание ###
т.к. циклы мы будем изучать на следуюущем занятии, то достаточно реализовать одну итерацию игры. При желании вы можете посмотреть в онлайн-учебнике https://learn.javascript.ru/while-for описание простейшего цикла while, аналогичного уже известному вам в Python, и реализовать игру со множеством попыток.

### Правила приема работы ###
Задание можно сдавать, прикрепляя в личном кабинете файл index.html с кодом игры.
На дальнейших занятиях вам потребуется сдавать задание в виде ссылки на репозиторий в github, поэтому вы можете задание данного урока также сдавать в виде ссылки на репозиторий с кодом.
Критерии оценки:
К заданию прикреплен файл index.html либо ссылка на репозиторий в github, содержащий файл index.html.
В файле index.html должен содержаться код, который при запуске выполняет описанный в задании алгоритм игры.
