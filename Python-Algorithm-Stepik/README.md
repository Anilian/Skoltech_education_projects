# Python-Algoritms-Stepik (Tasks solution)

 ![Python-Algorit-Stepik (Tasks solution)](https://github.com/mvgugaev/Python-Algorithm-Stepik/blob/master/media/rep_logo.png)
 
 Алгоритмы для задача из курса "Алгоритмы: теория и практика. Методы" на Stepik.org/
 URL курса: https://stepik.org/course/217/
 

#### **Глава 2 (Введение)**

| Наименование  | Условие | Реализация |
| ------------- | ------------- | ------------- |
| 1. Небольшое число Фибоначчи   | Дано целое число n от 1 до 40, необходимо вычислить n число Фибоначчи  | [fib.py](https://github.com/Anilian/my_education/blob/main/Python-Algorithm-Stepik/fib.py)  |
| 2. Последняя цифра большого числа Фибоначчи  | Дано число 1 < n < 10^7, необходимо найти последнюю цифру n-го числа Фибоначчи.  | [last_number_fib.py](https://github.com/Anilian/my_education/blob/main/Python-Algorithm-Stepik/last_number_fib.py)  |
| 3. Наибольший общий делитель   | По данным двум числам 1 <= a,b <= 2 * 10^9 найдите их наибольший общий делитель.  | [max_nod.py](https://github.com/Anilian/my_education/blob/main/Python-Algorithm-Stepik/max_nod.py)  |

#### **Глава 4 (Жадные алгоритмы)**

| Наименование  | Условие | Реализация |
| ------------- | ------------- | ------------- |
| 1. Покрыть отрезки точками   | По данным n отрезкам необходимо найти множество точек минимального размера, для которого каждый из отрезков содержит хотя бы одну из точек. В первой строке дано число 1 < n < 100 отрезков. Каждая из последующих n строк содержит по два числа 0 <= l <= r <= 10^9, задающих начало и конец отрезка. Выведите оптимальное число mm точек и сами mm точек. Если таких множеств точек несколько, выведите любое из них.  | [point_cover.py](https://github.com/Anilian/my_education/blob/main/Python-Algorithm-Stepik/point_cover.py)  |
| 2. Непрерывный рюкзак  | Первая строка содержит количество предметов 1 <= n <= 10^3 и вместимость рюкзака 0 <= W <= 2 * 10^6. Каждая из следующих nn строк задаёт стоимость 0 <= Ci <= 2 * 10^6 и объём 0 < Wi <= 2 * 10^6 предмета (n, W, Ci, Wi — целые числа). Выведите максимальную стоимость частей предметов (от каждого предмета можно отделить любую часть, стоимость и объём при этом пропорционально уменьшатся), помещающихся в данный рюкзак, с точностью не менее трёх знаков после запятой.  | [bag_folder.py](https://github.com/Anilian/my_education/blob/main/Python-Algorithm-Stepik/bag_folder.py)  |
| 3. Различные слагаемые   | По данному числу 1 <= n <=10^9 найдите максимальное число k, для которого nn можно представить как сумму k различных натуральных слагаемых. Выведите в первой строке число k, во второй — k слагаемых.  | [diff_number.py](https://github.com/Anilian/my_education/blob/main/Python-Algorithm-Stepik/diff_number.py)
| 4. Кодирование Хаффмана   | По данной непустой строке s длины не более 10^4, состоящей из строчных букв латинского алфавита, постройте оптимальный беспрефиксный код. В первой строке выведите количество различных букв k, встречающихся в строке, и размер получившейся закодированной строки. В следующих kk строках запишите коды букв в формате "letter: code". В последней строке выведите закодированную строку.  | [haffman_encode.py]()  |
| 5. Декодирование Хаффмана   | Восстановите строку по её коду и беспрефиксному коду символов. В первой строке входного файла заданы два целых числа k и l через пробел — количество различных букв, встречающихся в строке, и размер получившейся закодированной строки, соответственно. В следующих k строках записаны коды букв в формате "letter: code". Ни один код не является префиксом другого. Буквы могут быть перечислены в любом порядке. В качестве букв могут встречаться лишь строчные буквы латинского алфавита; каждая из этих букв встречается в строке хотя бы один раз. Наконец, в последней строке записана закодированная строка. Исходная строка и коды всех букв непусты. Заданный код таков, что закодированная строка имеет минимальный возможный размер.В первой строке выходного файла выведите строку s. Она должна состоять из строчных букв латинского алфавита. Гарантируется, что длина правильного ответа не превосходит 10^4.  | [haffman_decode.py]()  |
| 6. Очередь с приоритетами   | Первая строка входа содержит число операций 1 <= n <= 10^5. Каждая из последующих nn строк задают операцию одного из следующих двух типов: Insert x , где 0 <= x <= 10^9 — целое число; ExtractMax Первая операция добавляет число xx в очередь с приоритетами, вторая — извлекает максимальное число и выводит его.  | [priority_queue.py]()  |
