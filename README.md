# C++ example

```g++ -g -std=c++11 example-**N**.cpp -o example.exe```

### Парочка задач на многопоточность.

1. Имеется массив целых чисел длины N и два потока. Первый поток записывает в массив целые числа по кругу (записал N чисел, перешел к первому элементу и начал записывать заново). Второй поток читает из этого массива по такому же алгоритму и выводит числа на экран. Обеспечить потокобезопасное чтение из массива и запись в массив.

2. Спроектировать потокобезопасный класс для массива (реализовать потокобезопасные функции чтения и записи, чтение и запись работают по алгоритму из задачи 1) ииспользовать его в задаче 1.

3. Применить класс из задачи 2 в ситуации с произвольным количеством потоков чтения и записи.

### Вот несколько задач на изучение STL

1. Поменять слова в строке местами: последнее с первым и т.д. ```std::string str("who is on duty today?");```

2. Дана дата в виде трех переменных типа int. Перевести в строку формата **dd/mm/yyyy**, используя ```std::stringstream```.

3. Считать строку с пробелами из потока ввода.

4. Отсортировать вектор строк по длине. От меньшей к большей

5. Реализовать операторы скалярного и векторного произведения векторов.

6. Реализовать чтение из файла в карту вида ```map<string, string>```

    Файл
    ```
    Name Vasya
    Surname Pupkin
    City Moscow
    ```