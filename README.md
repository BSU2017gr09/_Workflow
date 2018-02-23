## Не надо исправлять или дописывать что-то в файлы проверенных работ.     
Комментарии преподавателя **в cpp файле** - для Вашего лучшего понимания проблем и ошибок!

|Прозвішча               |  ДЗ0|ДЗ1  | ДЗ2 | ДЗ3 | ДЗ4 | ДЗ5 |Диктант| ДЗ6 |КР1 | КР2| iтог |комментарии |
|:-----------------------|:---:|----:|:---:|----:|----:|----:|:-----:|----:|---:|---:|-----:|-----------:|
|Боровик Роман           |  6  |     |     |     |     |     |       |     |    |    |      |            |
|Желток Мария            |  8  |     |     |     |     |     |       |     |    |    |      |            |
|Зенов Иван              |  7  |     |     |     |     |     |       |     |    |    |      |            |
|Клыс Анастасия          |  9  |     |     |     |     |     |       |     |    |    |      |            |
|Козаченко Диана         |  7  |     |     |     |     |     |       |     |    |    |      |            |
|Крисевич Денис          |  -1 |     |     |     |     |     |       |     |    |    |      |            |
|Крицкий Алексей         |  9  |     |     |     |     |     |       |     |    |    |      |            |
|Молосай Михаил          |  -1 |     |     |     |     |     |       |     |    |    |      |            |
|Петрик Сергей           |  9  |     |     |     |     |     |       |     |    |    |      |            |
|Пискунов Юрий           |  -1 |     |     |     |     |     |       |     |    |    |      |            |
|Роговский Владислав     |   9 |     |     |     |     |     |       |     |    |    |      |            |
|Сивенков Егор           |  7  |     |     |     |     |     |       |     |    |    |      |            |
|Устинов Михаил          |  -1 |     |     |     |     |     |       |     |    |    |      |            |
|Шаталов Всеволод        |  9  |     |     |     |     |     |       |     |    |    |      |            |

# Обязательные требования ко всем лабам:

• Текст задания, которое выполняется надо продублировать в первых строках решения как комментарий       
также стоит реализовать вывод условия задачи как один из пунктов в меню (если создание меню есть в условии задачи)     
• в main() только объявления переменных и вызовы функций. Вся реализация функций ОТДЕЛЬНО.      
• имена переменных и функций должны соответствовать общепринятым нормам.

## Задание на 28.02 (указатели, одномерные массивы в heap )
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  3 файла с именами 0-1.cpp (тут решение 1-й задачи), 0-2.cpp (тут решение второй задачи), 0-3.cpp)`

•	Размер массива N запрашивать у пользователя;      
•	выделение и контроль динамической памяти прямо в  main;      
•	в зависимости от задания создать одну или несколько функций для обработки массивов, которые передавать туда через указатели; 
•	организация циклов **с использованием указателей**, а не с помощью A[i];     

1. В массиве размера N, заполненного случ.числами от 0 до 10, подсчитать количество элементов, встречающихся более одного раза.     
2. В массиве размера N, заполненного случ.числами от 0 до 10, определить максимальную длину последовательности равных элементов.     
3. Массив чисел размера N проинициализировать случайными числами из промежутка от -N до N. Написать функцию циклического сдвига элементов массива вправо на k элементов.

## Задание на 24.02 (функции для работы с одномерными массивами в heap )
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  4 файла с именами 1-1.cpp (тут решение 1-й задачи), 1-2.cpp (тут решение второй задачи), 1-3.cpp, 1-4.cpp)`

Разработать программу для работы с одним или несколькими одномерными массивами в heap, предусмотрев в ней:     
•	Размер массива N запрашивать у пользователя;      
•	выделение и контроль динамической памяти **в отдельной функции**, а не в main;      
•	организация циклов **с использованием указателей**, а не с помощью A[i];     
•	функции для инициализации, для ввода, для вывода массивов в heap;      
•	удаление динамической памяти после её использования;      
•	в зависимости от варианта задания одну или несколько функций для обработки массивов (для сортировки новый массив не создавать);     

1. Расположить в порядке возрастания элементы массива А(N), начиная с k-го элемента.
2. Даны точки плоскости своими координатами в виде двух одномерных массивов. Точки плоскости рассортировать по возрастанию расстояния до прямой ax + by + c = 0.
3. Положительные элементы массива А(N) переставить в конец массива, сохраняя порядок следования. Отрицательные элементы расположить в порядке убывания. Дополнительный массив не использовать.
4. Элементы массива А(N), значения которых – простые числа, расположить в порядке возрастания, не нарушая порядка следования других элементов.


## Задание "на будущее" ;-) (функции для работы с двумерными массивами в heap )
1. Подготовить для работы в аудитории функции для выделения памяти для **двумерного массива**, функции для инициализации...      
**Прототипы функций:**     

* void give_memory(int**&, int, int)//первый способ. Подумайте, почему обязательно надо тут &
* int** give_memory(int, int)//второй способ
* void init_array(int **,int,int)
* void print_array(int **,int,int)
* void free_array(int **,int,int)

2. Транспонировать **"на месте"** (т.е. в том же массиве) случайную квадратную матрицу (n,n)
3. Найти в случайной матрице минимум в каждом столбце и записать этот минимум в новый массив. 
4. Найти в случайной матрице седловую точку если она там есть. Седловой точкой называется элемент матрицы который является минимумом в строке и максимумом в столбце. 
5. В матрице (n,m) найти те строки и вывести их номера, элементы которых образуют возрастающую последовательность.
6. В матрице (n,m) удалить нулевые строки (из одних нулей), "подтянув" все остальные вверх.
