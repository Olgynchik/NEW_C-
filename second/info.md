// что бы написать программу надо, узнать на каком языке писать, на какой платформе будет работать эта программа
// откуда будет поступать информация,
// что с этой информацией делать 
// ЗАДАЧА найти сумму двух чисел
int numberA = 3 ; // напишем переменную, уточнив тип числа (в данном случае целое)
int numberB = 5 ; // int - указывает на то, что число целое
int result = numberA + numberB ; //
 Console.WriteLine(result) ; //-вывод суммы на экран

//найти частное  двух чисел

//найти вещественное число (деление с остатком)
double numberC = 20;
double numberD = 3;
Console.WriteLine(numberC / numberD);

//сложение целых чисел с используя рандомные числа
int number1 = new Random().Next(1,10) ; //- новое случайное число в диапазоне [MIN, MAX)
Console.WriteLine(number1) ;
int number2 = new Random().Next(1,10) ; // - [мин включено, макс -1)
Console.WriteLine(number2) ;
Console.WriteLine(number1 + number2) ;
