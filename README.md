# test_02

### 0.0.1
Дана посследовательность чисел. Нужно реализовать алгоритм разворота последовательности. Функция разворота должна использовать `std::swap`.

### Входные данные
Во входных данных заданы 2 строки. Первая строка содержит размер последовательности. Вторая строка содержит элементы последовательности, разделенные пробелом.

### Выходные данные
Строка, содержащая элементы развернутой последовательности или строка, сведетельствующая о возникновении ошибки ввода.

### Примеры
#### входные данные
```
10
1 2 3 4 5 6 7 8 9 10
```
#### выходные данные
```
10 9 8 7 6 5 4 3 2 1
```
#### входные данные
```
10
1 2 3 4 5 6 7 8 9
```
#### выходные данные
```
An error has occurred while reading input data
```
#### входные данные
```
-10
1 2 3 4 5 6 7 8 9 10
```
#### выходные данные
```
An error has occurred while reading input data
```
#### входные данные
```
10
1 2 3 4 5 6 7 8 9 10 11
```
#### выходные данные
```
An error has occurred while reading input data
```

### 0.0.2
Дана посследовательность чисел. Нужно реализовать алгоритм сдвига последовательности **вправо**. Алгоритм сдвига состоит из 3 шагов:
// 1 2 3 4 5 -> 3
- разделить последовательность A на две подпоследовательности B, C. // 1 2 3 4 5 -> 1 2 | 3 4 5
- развернуть последовательности B, C. // 1 2 | 3 4 5 -> 2 1 | 5 4 3
- развернуть исходную последовательность A. // 2 1 5 4 3 -> 3 4 5 1 2

### Входные данные
Во входных данных заданы 3 строки. Первая строка содержит размер последовательности. Вторая строка содержит элементы последовательности, разделенные пробелом. Третья строка содержит количество элементов, на которое необходимо сдвинуть последовательность.

### Выходные данные
Строка, содержащая элементы сдвинутой последовательности или строка, сведетельствующая о возникновении ошибки ввода.

### Примеры
#### входные данные
```
10
1 2 3 4 5 6 7 8 9 10
2
```
#### выходные данные
```
3 4 5 6 7 8 9 10 1 2
```
#### входные данные
```
10
1 2 3 4 5 6 7 8 9
2
```
#### выходные данные
```
An error has occurred while reading input data
```
#### входные данные
```
-10
1 2 3 4 5 6 7 8 9 10
```
#### выходные данные
```
An error has occurred while reading input data
```
#### входные данные
```
10
1 2 3 4 5 6 7 8 9 10 11
2
```
#### выходные данные
```
An error has occurred while reading input data
```
#### входные данные
```
10
1 2 3 4 5 6 7 8 9 10
```
#### выходные данные
```
An error has occurred while reading input data
```

### 0.0.3
Написать программу сдвига **внешней** спирали матрицы.

### Входные данные
Во входных данных заданы строки, следующего формата:
```
кол-во строк, кол-во столбцов
элементы матрицы
сдвиг
```
### Выходные данные
Строки, содержащие элементы сдвинутой матрицы или строка, сведетельствующая о возникновении ошибки ввода.

### Примеры
#### входные данные
```
3, 3
1 2 3
8 9 4
7 6 5
2
```
#### выходные данные
```
7 8 1
6 9 2
5 4 3
```
#### входные данные
```
3, 
```
#### выходные данные
```
An error has occurred while reading input data
```
#### входные данные
```
3, 3
1 2 3
6 5 4
2
```
#### выходные данные
```
An error has occurred while reading input data
```

### 0.0.4
Написать программу вывода матрицы в форме улитки.
### Входные данные
Во входных данных заданы размеры матрицы:
```
кол-во строк, кол-во столбцов
```
### Выходные данные
Улиточная матрица или строка, сведетельствующая о возникновении ошибки ввода.

### Примеры
#### входные данные
```
3, 3
```
#### выходные данные
```
1 2 3
8 9 4
7 6 5
```
#### входные данные
```
3, 
```
#### выходные данные
```
An error has occurred while reading input data
```
#### входные данные
```
2, 3
```
#### выходные данные
```
1 2 3
6 5 4
```
#### входные данные
```
4, 4
```
#### выходные данные
```
1  2  3  4
12 13 14 5
11 16 15 6
10 9  8  7
```

### 0.0.5
Написать программу сдвига **всех** спиралей матрицы.

### Входные данные
Во входных данных заданы строки, следующего формата:
```
кол-во строк, кол-во столбцов
элементы матрицы
сдвиг
```
### Выходные данные
Строки, содержащие элементы сдвинутой матрицы или строка, сведетельствующая о возникновении ошибки ввода.

### Примеры
#### входные данные
```
3, 3
1 2 3
8 9 4
7 6 5
2
```
#### выходные данные
```
7 8 1
6 9 2
5 4 3
```
#### входные данные
```
3, 
```
#### выходные данные
```
An error has occurred while reading input data
```
#### входные данные
```
3, 3
1 2 3
6 5 4
2
```
#### выходные данные
```
An error has occurred while reading input data
```
