// Задача 47. Задайте двумерный массив размером m×n, 
// заполненный случайными вещественными числами.
// m = 3, n = 4.
// 0,5 7 -2 -0,2
// 1 -3,3 8 -9,9
// 8 7,8 -7,1 9


// int rows = ReadInt("Введите количество строк: ");
// int colums = ReadInt("Введите количество столбцов: ");
// double[,] numbers = new double[rows, colums];
// FillArray2D(numbers);
// PrintArray2D(numbers);

// void FillArray2D(double[,] array)
// {
//     for (int i = 0; i < array.GetLength(0); i++)
//     {
//         for (int j = 0; j < array.GetLength(1); j++)
//         {
//             array[i, j] = new Random().Next(-99, 100) / 10.0;
//         }
//     }
// }

// void PrintArray2D(double[,] array)
// {
//     for (int i = 0; i < array.GetLength(0); i++)
//     {
//         for (int j = 0; j < array.GetLength(1); j++)
//         {
//             Console.Write(array[i, j] + " ");
//         }
//         Console.WriteLine();
//     }
//     Console.WriteLine();
// }

// int ReadInt(string message)
// {
//     Console.Write(message);
//     return Convert.ToInt32(Console.ReadLine());
// }



// Задача 50. Напишите программу, которая на вход принимает позиции 
// элемента в двумерном массиве, и возвращает значение этого элемента 
// или же указание, что такого элемента нет.
// Например, задан массив:
// 1 4 7 2
// 5 9 2 3
// 8 4 2 4
// 17 -> такого числа в массиве нет


// Console.Write("Введите номер строки: ");
// int a = Convert.ToInt32(Console.ReadLine()) - 1;
// Console.Write("Введите номер столбца: ");
// int b = Convert.ToInt32(Console.ReadLine()) - 1;
// int n = 3; 
// int m = 4; 
// Random random = new Random();
// int[,] arr = new int[n, m];
// Console.WriteLine("Исходный массив: ");
// for (int i = 0; i < arr.GetLength(0); i++)
// {
//     for (int j = 0; j < arr.GetLength(1); j++)
// {
//     arr[i, j] = random.Next(1, 10);
// Console.Write("{0} ", arr[i, j]);
// }
// Console.WriteLine();
// }
//     if (a < 0 | a > arr.GetLength(0) - 1 | b < 0 | b > arr.GetLength(1) - 1)
// {
// Console.WriteLine("Элемент не существует  ");
// }
//     else
// {
//     Console.WriteLine("Значение элемента массива = {0}", arr[a, b]);
// }
// Console.ReadLine();



// Задача 52. Задайте двумерный массив из целых чисел. Найдите 
// среднее арифметическое элементов в каждом столбце.
// Например, задан массив:
// 1 4 7 2
// 5 9 2 3
// 8 4 2 4
// Среднее арифметическое каждого столбца: 4,6; 5,6; 3,6; 3.


// int rows = ReadInt("Введите количество строк: ");
// int colums = ReadInt("Введите количество столбцов: ");
// int[,] numbers = new int[rows, colums];
// FillArray2D(numbers);
// PrintArray2D(numbers);
// MiddleArithmeticColunsArray2D(numbers);

// void FillArray2D(int[,] array)
// {
//     for (int i = 0; i < array.GetLength(0); i++)
//     {
//         for (int j = 0; j < array.GetLength(1); j++)
//         {
//             array[i, j] = new Random().Next(1, 10);
//         }
//     }
// }

// void PrintArray2D(int[,] array)
// {
//     for (int i = 0; i < array.GetLength(0); i++)
//     {
//         for (int j = 0; j < array.GetLength(1); j++)
//         {
//             Console.Write(array[i, j] + " ");
//         }
//         Console.WriteLine();
//     }
//     Console.WriteLine();
// }

// void MiddleArithmeticColunsArray2D(int[,] array)
// {
//     for (int j = 0; j < array.GetLength(1); j++)
//     {
//         double sum = 0;
//         for (int i = 0; i < array.GetLength(0); i++)         
//         sum += array[i, j]; 
//         {             
//             Console.Write($"{ sum / array.GetLength(0)} ");
//         }
//     }    
//     Console.ReadLine();
// }
// int ReadInt(string message)
// {
//     Console.Write(message);
//     return Convert.ToInt32(Console.ReadLine());
// }
