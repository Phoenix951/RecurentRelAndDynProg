# RecurentRelAndDynProg
Recurrence relations and dynamic programming (Excercises for MSU)


                  РЕКУРРЕНТНЫЕ СООТНОШЕНИЯ И
                ДИНАМИЧЕСКОЕ ПРОГРАММИРОВАНИЕ.

                            Задача 1.
     Вычислить значение суммы
                   S = 1/1! + 1/2! + ... + 1/k!

                            Задача 2.
     Написать программу   определения   количества    шестизначных
     "счастливых" трамвайных билетов,  у которых сумма первых трех цифр
     совпадает с суммой трех последних.

                            Задача 3.
     Написать программу определения количества 2N -значных "счаст-
     ливых" билетов,  у которых сумма первых N цифр равна сумме послед-
     них N цифр; N -произвольное натуральное число.
     
                           Задача 3.1.
     Найти сумму квадратов всех положительных целых чисел,  запись
     которых в десятичной системе счисления состоит ровно из k отличных
     от нуля цифр.
     
                           Задача 3.2.
     а). Найти  количество  n-значных  чисел  в десятичной системе
     счисления, у каждого из которых сумма цифр равна k. При этом в ка-
     честве n-значного числа мы допускаем и числа, начинающиеся с одно-
     го или нескольких  нулей.  Например,  000102  рассматривается  как
     шестизначное число, сумма цифр которого равна 3.
     b). Найти  количество  n-значных  чисел  в  m-ичной   системе
     счисления, у каждого из которых сумма цифр равна k. При этом в ка-
     честве n-значного числа мы допускаем и числа, начинающиеся с одно-
     го или нескольких нулей.

                            Задача 4.
     Фишка может двигаться по полю длины N  только  вперед.  Длина
     хода фишки  не  более K.  Найти число различных путей,  по которым
     фишка может пройти поле от начала до конца.
     Пример.  N=3, K=2
              Возможные пути:
                1,1,1
                1,2
                2,1
     Ответ: 3.

                            Задача 5.
     Покупатель имеет купюры достоинством A(1), ...,A(n), а прода-
     вец - B(1),  .. ,B(m). Необходимо найти максимальную стоимость то-
     вара Р, которую покупатель не может купить, потому что нет возмож-
     ности точно рассчитаться за этот товар с продавцом,  хотя денег на
     покупку этого товара достаточно.

                            Задача 6.
     Задан массив М [1:N] натуральных чисел, упорядоченный по неу-
     быванию, т.е.: M[1]<=M[2]<=...<=M[N].
     Найти первое натуральное число,  не представимое суммой ника-
     ких  элементов  этого массива,  при этом сумма может состоять и из
     одного слагаемого,  но каждый элемент массива может входить в  нее
     только один раз.

                            Задача 7.
     У покупателя есть n монет достоинством H(1),..., H(n). У про-
     давца есть m монет достоинством B(1),...,B(l). Может ли купить по-
     купатель  вещь  стоимости  S так,  чтобы у продавца нашлась точная
     сдача (если она необходима).

                            Задача 8.
     Задан массив М [1:N] натуральных чисел, упорядоченный по неу-
     быванию, т.е.: M[1]<=M[2]<=...<=M[N].
     Написать алгоритм выплаты заданной суммы S минимальным  коли-
     чеством купюp достоинством M(1), ..., M(N).

                            Задача 9.
     По матрице A(N,N) построить матрицу  B(N,N).  Элемент  B(I,J)
     равен  максимальному  из  элементов матрицы А принадлежащем части,
     ограниченной справа диагоналями, проходящими через A(I,J).

                     ┌──────────────────────┐
                     │******      .         │
                     │*******  .            │
                     │********              │
                     │******   .            │
                     │****       .          │
                     │**           .        │
                     │               .      │
                     │                 .    │
                     │                   .  │
                     └──────────────────────┘

                            Задача 10.
     Вводится матрица a(m,n) из 0 и 1. Найти в ней квадратную под-
     матрицу из одних единиц максимального размера.

                            Задача 11.
     Вводится матрица a(m,n) из 0 и 1. Найти в ней прямоугольную под-
     матрицу  из  одних единиц максимального размера (т.е.  с максимальным
     произведением высоты на длину).

                   Переформулировка задачи 11.
     Фермер хочет построить на своей земле как  можно  больший  по
     площади  сарай.  Но  на  его  участке есть деревья и хозяйственные
     постройки,  которые он не хочет никуда  переносить.  Для  простоты
     представим ферму сеткой размера MxN. Каждое из деревьев и построек
     размещается в одном или нескольких узлах сетки.  Прямоугольный са-
     рай не должен ни с чем соприкасаться (т.е.  в соседних с ним узлах
     сетки не может ничего быть).
     Найти максимально возможную площадь сарая и где он может раз-
     мещаться.

                            Задача 12.
     Дан массив A[N,M]. Необходимо найти максимальную сумму элементов
     прямоугольного подмассива по всем возможным  прямоугольным  подмасси-
     вам.

                            Задача 13.
     Задана матрица натуральных чисел A(n,m). За каждый проход че-
     рез клетку  (i,j) взымается штраф A(i,j).  Необходимо минимизировать
     штраф и
     а) Пройти из какой-либо клетки 1-ой строки в n-ую строчку,  при
     этом из текущей клетки можно перейти
        1) в любую из 3-х соседних, стоящих в стpоке с номеpом на
        1-цу большем;
        2) в любую из 8 соседних клеток;
     б) Реализовать пункт a) для перехода из клетки (1,1) в (n,m).

                            Задача 14.
     Дан выпуклый n-угольник, n=>3, своим обходом по контуру. Раз-
     бить его на треугольники (n-3)-мя  диагоналями,  непересекающимися
     кроме как по концам, таким образом чтобы
     а) Cумма их длин была минимальной;
     б) Максимальная из диагоналей имела наименьшую длину.

                            Задача 15.
     Задано число  А и два вектора b[1..n] и c[1..n].
     Найти множество I, являющееся подмножеством множества {1,...,n},
     такое, что

    SUM   C <=А, a   SUM   B  является максимальной из всех
    i из I  i        i из I  i           возможных

                            Задача 16.
     Пусть x=(a1,a2,...,am) и y=(b1,b2,...,bn) - две заданных строки
     символов.
     Определим d(x,y) как минимальное число вставок,  удалений и за-
     мен символа,  которое необходимо для преобразования x в y.
     Например:   d(ptslddf,tsgldds)=3

          удаление p       вставка g        замена f
          ptslddf---------->tslddf--------->tsglddf-------->tsgldds
          
     Для заданных x и y найти d(x,y).

                            Задача 17.
     Вводится три неотрицательных числа d,  i,  c и две строки X и
     Y.  Найти преобразование строки X в Y минимальной  стоимости.  До-
     пустимы следующие три операции:
    удалить любой символ из X (стоимость операции d);
    вставить любой символ в X (стоимость операции i);
    заменить символ в X на произвольный (стоимость операции e).

                            Задача 18.
     Даны две  строки  x и y.  Строка x состоит из нулей и единиц,
     строка y из символов A и B.  Можно ли  строку  x  преобразовать  в
     строку  y по следующему правилу:  цифра 0 преобразуется в непустую
     последовательность букв A,  а цифра 1 - либо в непустую последова-
     тельность букв A, либо в непустую последовательность букв B?

                            Задача 19.
     Пусть известно,  что для перемножения матрицы размера n*m  на
     матрицу  размера m*k требуется n*m*k операций.  Необходимо опреде-
     лить, какое минимальное число операций потребуется для  перемноже-
     ния  n матриц А1,...Аn,  заданных своими размерами n(i)*m(i).  При
     этом можно перемножать любые две рядом стоящие матрицы,  в резуль-
     тате чего   получается   матрица   нужного   размера.
     Замечание:
          n(i) - число строк в матрице Ai
          m(i) - число столбцов в матрице Ai
          n(i)=m(i)+1.

                            Задача 20.
     а) Из последовательности,  состоящей из N чисел, вычеркнуть ми-
     нимальное количество  элементов  так,  чтобы  оставшиеся  образовали
     строго возрастающую последовательность.
     б) Из  заданной  числовой последовательности A[1..N] вычеркнуть
     минимальное число элементов так,  чтобы в  оставшейся  подпоследова-
     тельности  каждый  последующий элемент был больше предыдущего кроме,
     быть может, одной пары соседних элементов ( одного "разрыва" возрас-
     тающей подпоследовательности).
     Например: A=(1,2,3,2,4,3,4,6);
               Искомая подпоследовательность (1,2,3,2,3,4,6)
               Разрыв подчеркнут.                   ---
     б) Из  заданной  числовой последовательности A[1..N] вычеркнуть
     минимальное число элементов так,  чтобы в  оставшейся  подпоследова-
     тельности  каждый  последующий элемент был больше предыдущего кроме,
     быть может,  m  пар  соседних элементов ( возрастающая подпоследова-
     тельность с m "разрывами").

                            Задача 21.
     В заданной последовательности целых чисел  найти  максимально
     длинную подпоследовательность чисел такую,  что каждый последующий
     элемент подпоследовательности делился нацело на предыдущий.

                            Задача 22.
     Возвести число  А  в натуральную степень n за как можно меньшее
     количество умножений.

                            Задача 23.
     Заданы z и y -  две  последовательности.  Можно  ли  получить
     последовательность z вычеркиванием элементов из y.

                            Задача 24.
     Найти максимальную по длине последовательность z, полученную
     вычеркиванием элементов как из x, так и из y.

                            Задача 25.
     Пусть x и y - две бинарных последовательности (т.е.  элементы
     последовательностей - нули и единицы);  x и y можно  рассматривать
     как запись в двоичной форме некоторых двух натуральных чисел.
     Найти максимальное  число  z,  двоичную запись которого можно
     получить вычеркиванием цифр как из x,  так и из y.  Ответ выдать в
     виде бинарной последовательности.
