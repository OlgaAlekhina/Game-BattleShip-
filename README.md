Консольная реализации игры "Морской бой" для двух игроков или игрока с компьютером.

Игровая доска представляет собой сетку 6 х 6 ячеек. Пустые ячейки отображаются как '0', палуба корабля - черный квадратик, подбитая палуба - 'X', неудачный выстрел - 'T'.

На доске располагается 7 кораблей: 1 трехпалубный, 2 двухпалубных и 4 однопалубных. Корабли могут стоять в горизонтальном или вертикальном направлениях, обязательно минимум в одной клетке друг от друга.

Игрок расставляет свои корабли самостоятельно, задавая направление корабля и координаты первой палубы. При несоблюдении условий расстановки выбрасываются и обрабатываются исключения.

Корабли компьютера расставляются автоматически случайным образом, но с соблюдением всех условий.

Игрок задает координаты выстрела самостоятельно. При выстрелах мимо доски или в уже обстрелянные точки выбрасываются и обрабатываются исключения. 

Компьютер делает ходы наугад, но не стреляет в одни и те же ячейки.

При попадании в корабль игрокам и компьютеру предоставляется еще один ход.

Побеждает тот, кто первым разгромил корабли противника.

Игра реализована в двух вариантах:
1) для игрока и компьютера - в файле game_battleship.py
2) для двух игроков - в файле game_two_people.py

Игра написана на питоне по принципам ООП. Использовалась одна библиотека - random - для генерации доски и выстрелов компьютера.

Для работы программы необходим только интерпретатор Python. Разработка и тестирование проводились с помощью Python 3.8.