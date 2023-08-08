// Задача 34: Задайте массив заполненный случайными положительными трёхзначными числами. 
// Напишите программу, которая покажет количество чётных чисел в массиве.
// [345, 897, 568, 234] -> 2


// int[] array = new int[5];
// int count = 0;

// for (int i = 0; i < array.Length; i++)
// {
//     array[i] = new Random().Next(0, 160);
//     Console.Write(array[i] + " ");

//     if (array[i] % 2 ==0)
//     {
//         count++;
//     }

// }
// System.Console.WriteLine();
// System.Console.WriteLine(count++);


// Задача 36: Задайте одномерный массив, заполненный случайными числами. 
// Найдите сумму элементов, стоящих на нечётных позициях.
// [3, 7, 23, 12] -> 19
// [-4, -6, 89, 6] -> 0

// System.Console.Write("Введите число");
// int num = Convert.ToInt32(Console.ReadLine());
// int[] array = new int[num];
// int count = 0;
// for(int i = 0; i < array.Length; i++)
// {
//     array[i] = new Random().Next(0, 100);
//     System.Console.Write(array[i] + " ");
//     if(i%2 != 0)
//     {
//         count += array[i];
//     }
// }
// System.Console.WriteLine("");
// System.Console.WriteLine(count);