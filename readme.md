# Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Пример:

> ["hello", "2", ";-)"] -> ["2", ";-)"]

> ["1234", "1567", "-2", "computer secience"] -> ["-2"]

> ["Russia", "Denmark", "Kazan"] -> []


# Алгоритм решения:
1. Объявляем два масива одинаковой длинны;
2. Объявляем метод;
3. Вносим цикл в метод для проверки условия <=3:

    * В случае выполнения условия элемент первого массива записывается во второй массив;
    * В случае не выполенения условия, приступаем к проверки следующего элемента первого массива;
4. Проверка осуществляется до тех пор, пока не счетчик не будет равен количеству элементов массива;
5. Полученный результат во втором массиве выводится на экран.
    



