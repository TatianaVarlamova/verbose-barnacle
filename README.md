 Итоговая работа: программа, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам.
 Console.WriteLine("Введите числа или слова через пробел: "); - Задаем текст в консоль
 string inputText = Console.ReadLine()!; - Вводим текст в консоль
 string[] stringArray = inputText.Split(' '); - Разбитие первоначального массива по пробелам на отдельные массивы строк