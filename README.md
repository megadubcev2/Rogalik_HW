# Rogalik_HW

# 1 Стародубцев Андрей Евгеньевич

# 2 Генерация комант:
Сначала определяется количество комнат всего от 6 до 10
BP_GameLevelState создает первую пустую комнату
После ждет события когда игрок подойдет к одной из двух дверей (Observer Pattern)
После этого он создает следующую комнату слева или справа в зависмости от двери и открывает саму дверь 
После этого когда игрок выходит из комнаты дверь за ним закрывается и он оказывается в новой комнате
Если игрок выбрал правую дверь, то сложность комнаты увеличилась на 1

# 3 Изменение сложности:
В первой комнтате пусто
В последней скамейка обозначающая конец игры 
В остальных комнатах находятся Бафф (шар, который восполняет HP) и препеятсвие (куб, который движется вокруг Баффа и при столкновении с игроком отнимает HP)
При увелечении сложности комнаты бафф прибавляет больше HP, а препятсвие больше снимает. Также при увелечении сложности увеличивается угловая скорость препятсвия 
Радиус, по которому движется препятсвие задается рандомно в каждой комнате


# 4 Доп механики
Реализовал подпрыгивание персонажа при столкновении c препятсвием 

# 5 Референсы
Взял готовый шаблон от 3 лица в Unreal Engine

 