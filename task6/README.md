## Задача 30
параметр: | значение:
------------ | -------------
Имя входного файла: |  input.txt
Имя выходного файла: | output.txt
Ограничение по времени: |  1 с
Ограничение по памяти: | нет

### Условие
На столе выложены доминошки. Каждая доминошка состоит из двух частей, на каждой из которых изображено некоторое число точек (от 0 до 6). Доминошки могут выкладываться в ряд одна за другой по следующему правилу: число точек на примыкающих частях соседних в ряду доминошек должно совпадать. Необходимо определить, можно ли выстроить цепочку, в которой каждая доминошка встречается ровно один раз, причём число точек на свободных концах доминошек, которые являются крайними в цепочке, должно совпадать.

### Формат входного файла
В первой строке находится число n доминошек (1 <= n <= 10000). Следующие n строк содержат данные о доминошках (два числа через пробел): число точек на верхней и нижней части доминошки.

### Формат выходного файла
В единственной строке выведите Yes, если можно составить цепочку из всех доминошек, или No, если цепочку составить нельзя.

## Пример
input.txt | output.txt
------------ | -------------
4 <br> 3 5 <br> 2 3 <br> 5 1 <br> 1 2 <br> | Yes

