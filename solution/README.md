# FinalTask
## Задача
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
## Описание алгоритма решения
Создаем непосредственно логический метод программы ***ArrayWithIF(string[]array1, string[] array2)***. Суть такова: в ходе логических операций, отработанных на двух ранее созданных массивах ***array1*** и ***array2*** в методе ***main()*** образуется новый результирующий массив ***resultArray***, который с помощью выхода данного массива в методе ***main()*** присваивается к массиву ***result*** в методе ***main()***.
## Логические операции в методе **ArrayWithIF**
Cоздается переменная ***count***, которая сначала будет служить
счетчиком для работы второго массива ***array2*** с первым ***array1***. В перменную ***stop***
присваивается 3 - максимальное количество элементов в строке. Далее в цикле **for** происходит сортировка элементов на основании проверки на ***stop***. Для того, чтобы в массиве было фиксированного количество элементов, соответствующее количеству элементов, отвечающих проверке в предыдущем цикле, создается новый результирующий массив ***resultArray***, в котором переменная ***count*** уже выполняет функцию длины массива. Здесь (во втором цикле **for**) происходит присваивание элементов массива ***array2*** массиву ***resultArray***. Ниже расположен метод вывода на консоль ***PrintArray*** и метод ***main()*** в котором происходит использование всех методов и само решение.

## Блок-схема 
![Блок-схема метода](/finalTaskDia1.jpg)