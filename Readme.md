1. _Создать репозиторий на GitHub_
2. _Нарисовать блок-схему алгоритмa (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)_
3. _Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)_
4. _Написать программу, решающую поставленную задачу_
5. _Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)_

**Описание решения задачи**

Создаём метод PrintArray для вывода значений массива Путем ввода значения size, задаём размер массива Объявляем массив arrayStrings Циклом for (int i = 0; i < size; i++) наполняем массив значениями, которые вводим с клавиатуры: Объявляем массив arrayFinal, такой же длины как и arrayStrings Объявляем две переменные length и count. length - количество символов в элементе, count - счетчик для определения длины финльного массива Выполняем цикл for (int i = 0; i < size; i++) Цикл выполняется столько раз, сколько элементов в массиве, при этом, при каждой итерации проверяется условие: if (arrayStrings[i].Length <= length) в котором проверяется сколько символов в текущем элементе массива, и если количество символов меньше или равно заданному количеству length, то значение записывается в элемент массива. Делаем отступ строки Console.WriteLine() и методом PrintArray выводим массив arrayFinal на экран.