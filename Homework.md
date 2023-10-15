// Напишите программу, которая принимает на вход три числа
// и выдает максимальное из этих чисел.
Console.WriteLine("Введите первое число: ");
int numberA=Convert.ToInt32(Console.ReadLine()!);
Console.WriteLine("Введите второе число: ");
int numberB=Convert.ToInt32(Console.ReadLine()!);
Console.WriteLine("Введите третье число: ");
int numberC=Convert.ToInt32(Console.ReadLine()!);
int max = numberA;
if (max < numberB); max = numberB;
if (max < numberC); max = numberC;
Console.WriteLine($"Max= " + max);

// Напишите программу, которая на вход принимает число (N), 
// а на выходе показывает все чётные числа от 1 до N.
Console.WriteLine("Введите число: ");
int n=Convert.ToInt32(Console.ReadLine()!);
for (int i=1; i <= n; i++)
{
    if (i%2 == 0)
    Console.Write(i+", ");
}

// Напишите программу, которая на вход принимает два числа
// и выдает, какое число большее, а какое меньшее.
Console.WriteLine("Введите первое число: ");
int numberA=Convert.ToInt32(Console.ReadLine()!);
Console.WriteLine("Введите второе число: ");
int numberB=Convert.ToInt32(Console.ReadLine()!);
if (numberA > numberB)
{
    Console.WriteLine($"max: {numberA}, min: {numberB}");
}
else
{
    Console.WriteLine($"max: {numberB}, min: {numberA}");
}

// Напишите программу, которая на вход принимает число и выдает,
// является ли число четным (делится ли оно на два без остатка).
Console.WriteLine("Введите число: ");
int number = Convert.ToInt32(Console.ReadLine()!);
if (number%2 == 0)
{
    Console.WriteLine($"Число: {number} четное, да");
}
else
{
    Console.WriteLine($"Число: {number} нечетное, нет");
}
