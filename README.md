# Задание 2. Простой класс
### Классы на выбор:
- Геометрическая фигура. Задание сторон, координат на плоскости.
Вычисление площади и периметра.
- Комплексное число. Операторы сложения, вычитания, умножения (на
комплексное и действительное число). Вычисление аргумента и модуля.
- Кватернион. Аналогично комплексному числу.
- Вектор. Задаётся своими компонентами. Вычисление длины, углов между
осями; операторы сложения и вычитания, умножения на число.
- Время. Сложение, вычитание. Добавление минут, секунд, часов и т.п.
Перевод времени в секунды, часы, минуты. Преобразование в строку.
- Дата. Реализовать то же самое, что и для времени.
- Обыкновенная дробь. Операции сложения, вычитания, умножения,
деления, сравнения.
- Другой класс по согласованию с преподавателем.

Рекомендуется сдавать лабораторную по частям. Допускается изменение АДТ
и UML диаграммы на этапе кодирования.


## Задание
1. Описать ADT -- Abstract Data Type
  - описание в pdf или markdown
2. Представить класс в виде UML диаграммы.
  - сохранить в виде изображения и в файле пригодном для редактирования. Например как ссылку на draw.io или в qmodel. 
3. Описать класс на С++.
  - в отдельно модуле, имямодуля должно совпадать с именем класса
  1. Создать геттеры и сеттеры (рекомендуется начать с описания простых
операций в UML и ADT)
  2. Реализовать методы для доступа и изменения данных, контроль
постоянства, конструктор с параметрами. Операторы (в том числе
проверки на равенство) и генерирование исключительных ситуаций если
необходимо
  4. Продемонстрировать работу с классом, с основными методами, операторами.
Динамическое создание объекта. Программа не обязательна должна
взаимодействовать с пользователем, главная цель — показать пример
использования класса.
  5. Создать массив из объектов. Выделить память для массива из объектов.
Создать массив из указателей на объекты.
  6. Записать состояние объектов в файл, загрузить из файла.
4. Для класса привести документацию для класса описав его назначение,
принципы использования, смысл методов и их параметров. Если необходимо
привести пример использования класса в документации.
  - Дополнительно (не обязательно): кратко описать документацию в markdow. Markdown
отображается на github.com, а редактировать можно в Visual Studio Code, Atom и др с
одновременным просмотром готового документа.

[//]: # (Дополнительно: загрузить код на github или другой подобный сервис.)
  
Для проверки корректности всех методов класса можно использовать юнит-тест.
см. «Задание 8. Юнит-тест» из второй части курса.

Дополнительно: подключить класс к проекту на QtCreator


## Вопросы
1. Что такое АДТ?
2. Что такое предусловия? Для чего нужны? Что такое постусловия?
3. Что такое класс? Что такое объект?
4. Что такое абстрагирование?
5. Что такое инкапсуляция? Что такое метод? Что такое поле класса? Что такое
конструктор?
6. Что такое принцип сокрытия? Что такое «чёрный ящик»?
7. Что такое оператор?
8. Как вызвать метод конкретного объекта находящегося в массиве?
9. Чем отличаются обращения к методам в С++ с использованием объекта,
ссылки на объект и указателя на объект?
10. Что такое равенство объектов? Когда объекты идентичны?
11. Чем отличается присваивание объектов от присваивания указателей на
объекты?
12. Как обратится к методу или полю объекта находящегося в массиве?
13. Что такое поведение? Что такое состояние?
14. Что такое markdown?
15. Какими функциями среды программирования, облегчающими разработку, вы
пользовались? Что такое рефакторинг?
