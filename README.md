# 1 задание












# 2 задание












# 3 задание












# 4 задание












# 5 задание

На вход алгоритма подаётся натуральное число $N$. Алгоритм строит по нему новое число $R$ следующим образом:
1. Строится двоичная запись числа $\mathrm{N}$.
2. Далее эта запись обрабатывается по следующему правилу:
a) если число $N$ делится на 3, то к двоичной записи справа дописываются последние три цифры;
б) если число $N$ не делится на 3, то остаток от деления числа $N$ на 3 умножается на три, а затем полученный результат в двоичном виде приписывается справа к двоичной записи.

Полученная таким образом запись является двоичной записью искомого числа $R$.

*Например, для исходного числа $12_{10}=1100_2$ результатом является число $1100100_2=100_{10}$, а для исходного числа $4_{10}=100_2$ результатом является число $10011_2=1910$.*

Укажите минимальное число $N$, после обработки которого с помощью этого алгоритма получается число $R$, большее 76. В ответе запишите это число в десятичной системе счисления.

<details><summary><strong>Ответ</strong></summary>
   11
</details>
<br></br>





Автомат обрабатывает натуральное число N (128 ≤ N ≤ 255) по следующему алгоритму:

1. Строится восьмибитная двоичная запись числа N.

2. Все цифры двоичной записи заменяются на противоположные (0 на 1, 1 на 0).

3. Полученное число переводится в десятичную запись.

4. Из исходного числа вычитается полученное, разность выводится на экран.

<!-- Пример. Дано число N = 131. Алгоритм работает следующим образом:
1. Восьмибитная двоичная запись числа N: 10000011.
2. Все цифры заменяются на противоположные, новая запись: 01111100.
3. Десятичное значение полученного числа: 124 .
4. На экран выводится число: 131-124=7 -->

Какое число нужно ввести в автомат, чтобы в результате получилось 185?

<details><summary><strong>Ответ</strong></summary>
   220
</details>
<br></br>






На вход алгоритма подаётся натуральное число N. Алгоритм строит по нему новое число R следующим образом:
1. Строится двоичная запись числа $\mathrm{N}$.
2. Далее эта запись обрабатывается по следующему правилу:
a) если количество разрядов в числе чётное, тогда в центр записи числа дописывается 000.
б) если количество разрядов в числе нечётное, тогда к этой записи слева дописывается 1, а справа дописывается 01.

Полученная таким образом запись является двоичной записью искомого числа R.

*Например, для исходного числа $5_{10}=101_2$ результатом является число $110101_2=53_{10}$, а для исходного числа $810=1000_2$ результатом является число $1000000_2=64_{10}$*

Укажите минимальное число N, после обработки которого с помощью этого алгоритма получается число R, большее 100. В ответе запишите это число в десятичной системе счисления.

<details><summary><strong>Ответ</strong></summary>
   16
</details>
<br></br>






Автомат получает на вход трёхзначное число. По этому числу строится новое число по следующим правилам:

1. Из цифр, образующих десятичную запись N, строятся наибольшее и наименьшее возможные двузначные числа (числа не могут начинаться с нуля).

2. На экран выводится разность полученных двузначных чисел.

*Пример. Дано число N = 351. Наибольшее двузначное число из заданных цифр – 53, наименьшее – 13. На экран выводится разность 53 – 13 = 40.*

Чему равно количество чисел N на отрезке [300; 400], в результате обработки которых на экране автомата появится число 20?


<details><summary><strong>Ответ</strong></summary>
   12
</details>
<br></br>







На вход алгоритма подаётся натуральное число N. Алгоритм строит по нему новое число R следующим образом:

1. Строится двоичная запись числа $\mathrm{N}$.
2. Далее эта запись обрабатывается по следующему правилу:
a) если сумма цифр в двоичной записи числа чётная, то к этой записи справа дописывается 0, а затем два левых разряда заменяются на 10;
б) если сумма цифр в двоичной записи числа нечётная, то к этой записи справа дописывается 1, а затем два левых разряда заменяются на 11.

Полученная таким образом запись является двоичной записью искомого числа R.

*Например, для исходного числа $6_{10}=110_2$ результатом является число $1000_2=810$, а для исходного числа $4_{10}=100_2$ результатом является число $1101_2=1310$*

Укажите минимальное число N, после обработки которого с помощью этого алгоритма получается число R, большее 40. В ответе запишите это число в десятичной системе счисления.


<details><summary><strong>Ответ</strong></summary>
   16
</details>
<br></br>





Автомат получает на вход натуральное трёхзначное число. По этому числу строится новое число по следующим правилам:

1) Вычисляются суммы квадратов первой и второй, а также второй и третьей цифр исходного числа.

2) Полученные два числа записываются друг за другом в порядке невозрастания (без разделителей).

*Пример. Исходное число: 534. Суммы квадратов цифр: 52 + 32 = 34; 32 + 42 = 25. Результат 3425*

Укажите наименьшее число, при обработке которого автомат выдаст число 9010


<details><summary><strong>Ответ</strong></summary>
   139
</details>
<br></br>









# 6 задание












# 7 задание



Голосовое сообщение длительностью 90 секунд было закодировано в формате стерео с разрешением 16 бит и частотой дискретизации 48 000 измерений в секунду и передано по каналу связи. Сжатия данных не производилось. Пропускная способность канала связи равна 3200 бит/с. Определите, сколько секунд необходимо для передачи голосового сообщения. В ответе запишите только целое число.

<details><summary><strong>Ответ</strong></summary>
   43200
</details>
<br></br>




Для проведения эксперимента записывается звуковой фрагмент в формате квадро (четырёхканальная запись) с частотой дискретизации 32 кГц и 32-битным разрешением. Результаты записываются в файл, сжатие данных не производится; дополнительно в файл записывается служебная информация, необходимая для эксперимента, размер полученного файла 97 Мбайт. 
Затем производится повторная запись этого же фрагмента в формате моно (одноканальная запись) с частотой дискретизации 16 кГц и 16-битным разрешением. Результаты тоже записываются в файл без сжатия и со служебной информацией, размер полученного файла 7 Мбайт. Объём служебной информации в обоих случаях одинаков. Укажите этот объём в мегабайтах.


<details><summary><strong>Ответ</strong></summary>
   1
</details>
<br></br>





Изображение размером 315 × 3072 пикселей сохраняется в памяти компьютера. Для его хранения выделяется не более 735 Кбайт без учёта заголовка файла. Все пиксели кодируются одинаковым количеством бит и записываются в файл один за другим. Какое максимальное количество цветов можно использовать в изображении? В ответе запишите только число.

<details><summary><strong>Ответ</strong></summary>
   64
</details>
<br></br>





Автоматическая фотокамера с 200 Кбайт видеопамяти производит растровые изображения c фиксированным разрешением и 8-цветной палитрой. Сколько цветов можно будет использовать в палитре, если увеличить видеопамять до 400 Кбайт?

<details><summary><strong>Ответ</strong></summary>
   64
</details>
<br></br>


















# 8 задание















# 9 задание



Определите количество строк таблицы, содержащих числа, для которых выполнены оба условия:
- все числа в строке различны;
- удвоенная сумма максимального и минимального чисел из строки не меньше суммы трёх оставшихся.

[Ссылка на файл](https://kompege.ru/files/NWYIDefXW.xlsx)

<details><summary><strong>Ответ</strong></summary>
   15058
</details>
<br></br>





Определите количество строк таблицы, содержащих числа, для которых выполнены оба условия:
- в строке только одно число повторяется ровно два раза, остальные числа различны;
- среднее арифметическое неповторяющихся чисел строки не меньше суммы повторяющихся чисел.

В ответе запишите только число.

[Ссылка на файл](https://kompege.ru/files/tmnY6t7Dk.xls)

<details><summary><strong>Ответ</strong></summary>
   64
</details>
<br></br>





Определите количество строк таблицы, содержащих числа, для которых выполнены оба условия:
- наибольшее из четырёх чисел меньше суммы трёх других;
- среди четырёх чисел есть только одна пара равных чисел.

В ответе запишите только число. 

[Ссылка на файл](https://kompege.ru/files/nHHTtAPZE.xlsx)

<details><summary><strong>Ответ</strong></summary>
   133
</details>
<br></br>





Определите количество строк таблицы, содержащих числа, для которых выполнены оба условия:
- наибольшее из четырёх чисел меньше суммы трёх других;
- четыре числа можно разбить на две пары чисел с равными суммами.

[Ссылка на файл](https://kompege.ru/files/SvzIbNXS-.xlsx)

<details><summary><strong>Ответ</strong></summary>
   104
</details>
<br></br>





Определите количество строк таблицы, в которых квадрат максимального из трёх чисел больше удвоенного произведения двух других чисел в строке.


[Ссылка на файл](https://kompege.ru/files/ntjOw0Hf5.xlsx)

<details><summary><strong>Ответ</strong></summary>
   2715
</details>
<br></br>


















# 10 задание


Откройте один из файлов и определите, сколько раз встречается в тексте отдельное слово «солдаты» со строчной буквы. Другие формы этого слова учитывать не следует.

[Ссылка на файл](https://kompege.ru/files/YVVDi1KNx.docx)

<details><summary><strong>Ответ</strong></summary>
   26
</details>
<br></br>




Определите, сколько раз, не считая сносок, встречается слово «Онегин» в тексте романа в стихах А.С. Пушкина «Евгений Онегин». Другие формы слов, такие как «Онегина», «Онегину» и т.д., учитывать не следует.

[Ссылка на файл](https://kompege.ru/files/1oEMBtMim.docx)

<details><summary><strong>Ответ</strong></summary>
   12
</details>
<br></br>






Определи, сколько раз в тексте поэмы встречается слово «Мой» написанное с заглавной буквы. Другие формы слова «Мой», такие как «Мои», «Моего» и пр. не учитывать.

[Ссылка на файл](https://kompege.ru/files/Skfa4pIJF.doc)

<details><summary><strong>Ответ</strong></summary>
   5
</details>
<br></br>














# 11 задание












# 12 задание












# 13 задание















# 14 задание












# 15 задание












# 16 задание


Алгоритм вычисления значения функции F(n), где n – натуральное число, задан следующими соотношениями: 

- F(n) = 1 при n = 1;  

- F(n) = n × F(n − 1), если n > 1.  

 Чему равно значение выражения F(2023) / F(2020)?


<details><summary><strong>Ответ</strong></summary>
   8266912626
</details>
<br></br>






Алгоритм вычисления значения функции F(n), где n – натуральное число, задан следующими соотношениями:

- F(n) = 1 при n < 3;

- F(n) = 2 × F(n – 1) – F(n – 2), если n > 2 и при этом n чётно;

- F(n) = F(n − 1)  – 2 × F(n – 2) – 3, если n > 2 и при этом n нечётно.

Чему равно значение функции F(15)?

<details><summary><strong>Ответ</strong></summary>
   6
</details>
<br></br>


















# 17 задание


В файле содержится последовательность натуральных чисел. Элементы последовательности могут принимать целые значения от 1 до 10 000 включительно. Определите количество пар последовательности, в которых только одно число является двухзначным, а сумма элементов пары кратна максимальному двухзначному элементу последовательности. В ответе запишите количество найденных пар, затем максимальную из сумм элементов таких пар. В данной задаче под парой подразумевается два идущих подряд элемента последовательности.

[Ссылка на файл](https://kompege.ru/files/bLdMiRLC1.txt)

<details><summary><strong>Ответ</strong></summary>
   1 2970
</details>
<br></br>

















# 18 задание












# 19 задание












# 20 задание












# 21 задание












# 22 задание












# 23 задание



Исполнитель преобразует число на экране. У исполнителя есть три команды, которым обозначены латинскими буквами:

- Прибавить 1

- Умножить на 2

- Умножить на 3

Сколько существует программ, для которых при исходном числе 2 результатом является число 25, и при этом траектория вычислений содержит число 15, но не содержит число 11?

<details><summary><strong>Ответ</strong></summary>
   12
</details>
<br></br>






У исполнителя есть две команды:

1. Вычти 2

2. Найди целую часть от деления на 2

Первая из них уменьшает число на экране на 2, вторая заменяет число на экране на целую часть от деления числа на 2. 

Сколько существует программ, для которых при исходном числе 28 результатом является число 1, и при этом траектория вычислений содержит число 10?

<details><summary><strong>Ответ</strong></summary>
   36
</details>
<br></br>





















# 24 задание

Текстовый файл состоит из прописных символов латинских букв.
Определите максимальное количество подряд идущих символов в прилагаемом файле, среди которых не содержится два символа из набора букв X, Y и Z (с учётом повторений), стоящих рядом.

[Ссылка на файл](https://kompege.ru/files/2k6zlwlNP.txt)

<details><summary><strong>Ответ</strong></summary>
   786
</details>
<br></br>



Текстовый файл состоит из символов A, B, C, D и O. Определите максимальное количество идущих подряд пар символов вида
`согласная` + `гласная`
в прилагаемом файле.

[Ссылка на файл](https://kompege.ru/files/nkbV0RABS.txt)

<details><summary><strong>Ответ</strong></summary>
   174
</details>
<br></br>




Текстовый файл состоит не более, чем из 106 символов из набора A, B, C.
Найдите максимальное количество подряд идущих пар символов `АС` или `АВ`. Искомая подстрока может включать только пары `АВ`, только пары `АС` или содержать одновременно как пары `АС`, так и пары `АВ`.

[Ссылка на файл](https://kompege.ru/files/q_XBXiwyU.txt)

<details><summary><strong>Ответ</strong></summary>
   19
</details>
<br></br>





Текстовый файл состоит не более чем из 106 заглавных латинских букв. Определите символ, который чаще всего встречается в файле между буквами A и C, так что A стоит слева от него, а C – справа. В ответе запишите сначала этот символ, а потом сразу (без разделителя) сколько раз он встретился между буквами A и C. Если таких символов несколько, нужно вывести тот, который стоит раньше в алфавите.

[Ссылка на файл](https://kompege.ru/files/pcdxnaEwR.txt)

<details><summary><strong>Ответ</strong></summary>
   T72
</details>
<br></br>




Текстовый файл содержит строки различной длины. Общий объём файла не превышает 1 Мбайт. Строки содержат только заглавные буквы латинского алфавита (ABC…Z).
В строках, содержащих менее 25 букв G, нужно определить и вывести максимальное расстояние между одинаковыми буквами в одной строке.

*Исходный файл:
GIGA
GABLAB
NOTEBOOK
AGAAA
В этом примере во всех строках меньше 25 букв G. Самое большое расстояние между одинаковыми буквами  — в третьей строке между буквами O, расположенными в строке на 2-й и 7-й позициях. В ответе для данного примера нужно вывести число 5.*

[Ссылка на файл](https://inf-ege.sdamgia.ru/get_file?id=89338)

<details><summary><strong>Ответ</strong></summary>
   1001
</details>
<br></br>










# 25 задание












# 26 задание












# 27 задание