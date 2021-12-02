#Лабораторная работа №1
Написать программу, которая имеет следующие возможности.
##1. Может принимать на вход:
1. матрицу смежности графа;
2. матрицу инцидентности графа;
3. список рёбер вершин вида Edges{i(a, k, l), . . .}, где i — номер
ребра, a — вес ребра, k и l — номера или имена вершин;
4. список вершин также может быть задан с привязкой по координатам в следующем виде: Vertex{v(x, y)}, где v — имя
или номер вершины, x и y — координаты в пикселях;
5. если список вершин не указан, то их координаты могут задаваться произвольно;
6. в файле могут быть комментарии начинающиеся с %.
##2. Позволяет задать граф графическим способом, с помощью мыши
и клавиатуры:
1. можно устанавливать вершины мышью;
2. можно мышью связать вершины между собой с указанием
веса на на клавиатуре или с помощью элементов управления;
3. можно выбирать направление рёбер или оставлять их ненаправленными через контекстное меню у рёбер;
4. можно менять форму рёбер с помощью мыши;
5. можно делать петли, через контекстное меню у вершин;
6. можно мышью двигать вершины, за ними соответственно передвигаются инцидентные им рёбра;
7. можно строить мультиграф, то есть несколько рёбер, между
парами вершин, при этом рёбра не должны накладываться
друг на друга.
##3. В процессе работы сохраняются 10 последних состояний графа,
также в интерфейсе есть соответствующие функции «Undo» и
«Redo».
##4. Позволяет сохранить полученный граф в тех же форматах, что
и входные данные, а также в виде изображения.
##5. Показывает в реальном времени матрицу смежности графа.
##6. При изменении матрицы смежности графа сразу меняются рёбра
графа (вес или наличие ребра).
##7. У приложения должен быть графический интерфейс:
1. должно быть меню с пунктами «Файл», «Задачи теории графов», «?»;
2. в пункте файл должны быть пункты открытия и графа из
файла, сохранения графа в файла и выход из программы;
3. для открытия и закрытия файла используются стандартные
диалоги;
4. если пользователь редактировал или создал граф и не сохранил его, то перед выходом программа должна предложить
сохранить граф в файл;
5. в пункте меню должны быть следующие пункты:
• «О программе» с исчерпывающими инструкциями по использованию вашей программой;
• «Об авторе» с ФИО автора, его группе, кафедре, факультете и университете.
##8. Дальнейшие лабораторные работы используют инфраструктуру
данной лабораторной и добавляются в пункты её меню, в раздел
«Задачи теории графов»
