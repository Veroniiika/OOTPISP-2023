# Отчет по лабораторной работе №4

## Создание интерфейса простых приложений

## Вариант №6

Зеленков Константин Игоревич

Напишите программу, которая преобразует температуру в целых числах по Фаренгейту от 0 до 212 градусов к значениям с плавающей запятой температуры по Цельсию с точностью до 3 знаков и к значениям абсолютной температуры с точностью до 1 знака. Используйте для вычислений формулы. Создайте интерфейс программы: выходные данные должны быть отпечатаны в таблице с выравниванием по правой границе поля, причем значения температуры по Цельсию должны содержать знак и перед положительными, и перед отрицательными температурами. Отрицательные значения Тс в таблице указать синим шрифтом, а положительные – красным.

## Код программы

- [main.cpp](./src/main.cpp)
- [mainwindow.cpp](./src/mainwindow.cpp)
- [mainwindow.h](./src/mainwindow.h)

А также файл формы

- [mainwindow.ui](./src/mainwindow.ui)

## Пример работы программы

Основное окно:

![image1](./images/1.png)

Проверка на диапозон числа по Фаренгейту:

![image2](./reamde_imgs/2.png)

При нажатии на Convert либо сочетание клавишь ctrl+Q расчитывается температура в Цельсий и Кельвин, плюсовая температура - красная:

![image3](./reamde_imgs/3.png)

То же самое, только минусовая температура - синяя:

![image4](./reamde_imgs/4.png)