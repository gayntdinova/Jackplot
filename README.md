# Jackplot
Рисование графика многочлена с помощью языка jack.

## Как пользоваться:
* Ввсети многочлен в формате ax^n1 + bx^n2 + ... + cx + d. Слагаемые с 0 коэффициентом можно не писать
* Нажать ENTER
* Чтобы стереть график надо нажать 'DEL'
* Чтобы завершить программу нужно нажать 'ESC'

## Что можно делать после отрисовки графика:
* Можно использовать 'wasd', 'WASD' или клавиши стрелок, чтобы перемещаться по экрану
* Можно использовать '+' и '-' для изменения масштаба

## Что было использовано:
* класс Parser для парсинга многочлена в ModifiedArray коэффициентов
* класс ModifiedArray - обёртка над Array, у которого можно взять длину
* класс Calculator - принимает ModifiedArray в конструкторе и имеет метод calculateYInScale, вычисляющий значение p(x) в масштабе scale
* класс Plot - класс графика с методами отрисовки, перемещения и изменения масштаба

## Что можно улучшить:
* Доработать вычисления, чтобы повысить точность и бороться с переполнением.