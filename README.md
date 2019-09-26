# algorithms

Задача 1.
Вывести квадраты натуральных чисел от 1 до n, используя только O(n) операций сложения и
вычитания (умножением пользоваться нельзя).
n ≤ 1000.

Задача 2.
Вычислить площадь выпуклого nугольника, заданного координатами своих вершин. 
Вначале вводится количество вершин, затем последовательно целочисленные 
координаты всех вершин в порядке обхода против часовой стрелки.
n < 1000, координаты < 10000.
Указание.
Для вычисления площади nугольника можно посчитать сумму 
ориентированных площадей трапеций под каждой стороной многоугольника.

Задача 3.
Даны два массива неповторяющихся целых чисел, упорядоченные по возрастанию. A[0..n-1] и B[0..m-1].
n >> m. Найдите их пересечение. Требуемое время работы: O(m * log k), где k - позиция элементта B[m-1] в
массиве A.. В процессе поиска очередного элемента B[i] в массиве A пользуйтесь результатом поиска
элемента B[i-1].
n, k ≤ 10000.

Задача 4.
Формат входных данных.
В первой строке количество команд n. n ≤ 1000000.
Каждая команда задаётся как 2 целых числа: a b.
a = 1 - push front
a = 2 - pop front
a = 3 - push back
a = 4 - pop back
Если дана команда pop*, то число b - ожидаемое значение.Если команда pop вызвана для пустой структуры
данных, то ожидается “-1”.
Формат выходных данных.
Требуется напечатать YES - если все ожидаемые значения совпали. Иначе, если хотя бы одно ожидание не
оправдалось, то напечатать NO.
Реализовать дек с динамическим зацикленным буфером.

Задача 5.
Дано N кубиков. Требуется определить каким количеством способов можно выстроить из этих кубиков
пирамиду.
Формат входных данных:
На вход подается количество кубиков N.
Формат выходных данных:
Вывести число различных пирамид из N кубиков.
Высокая пирамида. Каждый вышележащий слой пирамиды должен быть не больше нижележащего.
N ≤ 200.

Задача 6.
Заявки на переговоры.
В большой IT-фирме есть только одна переговорная комната. Желающие посовещаться заполняют заявки с
желаемым временем начала и конца. Ваша задача определить максимальное количество заявок, которое
может быть удовлетворено.
Число заявок n ≤ 100000. 
Формат входных данных:
Вход содержит только пары целых чисел  a b начала и конца заявок.
Формат выходных данных:
Выход должен содержать натуральное число  m — максимальное число заявок.


