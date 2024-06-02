# Задания, которые выполнялись на крусе лш от Барс Групп

## Задание 1. 

1. Создайте страницу с несколькими кнопками. Каждая кнопка должна выводить в консоль сообщение о том, что она была нажата.
Требования:
- Использовать метод addEventListener для привязки обработчиков событий.
- Каждая кнопка должна иметь уникальное сообщение.

2. Создайте страницу с кнопкой, которая при нажатии меняет цвет фона страницы на случайный цвет.
Требования:
- Использовать событие click.
- Цвет должен генерироваться случайным образом.

3. Создайте список элементов <ul>, содержащий несколько <li>. Добавьте обработчик события на <ul>, который будет выводить в консоль текст элемента <li>, по которому был выполнен клик.
Требования:
- Использовать всплытие.
- Обработчик должен быть привязан к родительскому элементу <ul>.

4. Создайте страницу, которая реагирует на ввод определенного набора клавиш (например, секретного кода). При правильном вводе отображается скрытое сообщение.
Требования:
- Использовать событие keydown.
- Хранить последовательность введенных клавиш и сравнивать с заданным кодом.

## Задание 2

1. Сделать ссылку (элемент <a>), у которой:
    - Цвет по умолчанию - черный, если ссылка была открыта - серый
    - При наведении на ссылку появляется нижнее подчеркивание и цвет становится зеленым
    - При нажатии на ссылку текст становится синим

2. Сделать при помощи изменения DOM TODO-приложение со следующим функционалом:
    - Для добавления задачи используется текстовое поле и кнопка "Добавить"
    - Если текстовое пустое - кнопка "Добавить" заблокирована
    - После нажатия на кнопку "Добавить" создается задача с названием которое было введено в текстовом поле, текстовое поле очищается
    - Задача состоит из названия задачи и чекбокса
    - Если чекбокс активен (в значении true), то текст задачи должен быть зачеркнут
