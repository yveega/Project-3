# Генератор задач про карточки
Заказчик: Илья Осипов

Руководитель: Илья Осипов

Консультант: Илья Осипов

Итоговая программа будет "придумывать" колоду карт и ряд для задачи, описанной в ТЗ
## Тех. Задание
Задача: имеется колода карт, для каждого вида карты задана постоянная вероятность вытаскивания именно этой карты (сумма
вероятностей всех видов карт равна 1). Есть некоторый набор свойств, по которым карты разного вида могут различаться или
совпадать, например, цвет, фигуга, штриховка. Также имеется ряд из карт, отличающихся или совпадающих по таким же свойствам.
За один ход можно совершить одно из двух действий:
1) Взять одну карту из колоды в руку
2) "Проехать" по картам

Поездка по картам работает по следующим правилам: игрок выбирает карту из руки, далее перемещает свою позицию влево в ряду,
пока карта справа от позиции игрока имеет ровно одно совпадающее свойство с выбранной картой. После совершения поездки
выбранная игроком карта сбрасывается.
Изначальная позиция игрока - слева от первой карты в ряду, цель - оказаться в позиции ровно перед последней картой в ряду
с наименьшим математическим ожиданием количества ходов.

Программа генерирует колоду карт - набор видов карт с вероятностями вытягивания и ряд карт. Требование: для решения задачи
не должна подходить такая стратегия: постоянно вытягивать карты из колоды, как только в руке появится набор карт, достаточный
для решения задачи, сразу ехать.

Интерфейс: консоль: диалог программы с пользователем производится в текстовом виде

Входные данные: количество карт в ряду, количество свойств, количество задач, которые нужно сгенерировать

Выходные данные: В текстовом виде набор карт и ряд (каждая карта описана набором признаков для каждого свойства)

Технические особенности:

ОС: Windows, Linux, MacOS

Тип программы: desktop-приложение

Работает оффлайн
