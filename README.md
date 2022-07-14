using System;

public class Class1
{
	public Class1()
	{
	}
}
using System;
namespace LogicalPrograms
{
    public class Program
    {
        public static void Main()
        {
            int number1 = 10, number2 = 20;
            Console.WriteLine($"Before SWapping number1= {number1}, number2 = {number2}");
            number1 = number1 + number2; //number1=30 (10+20)      
            number2 = number1 - number2; //number2=10 (30-20)      
            number1 = number1 - number2; //number1=20 (30-10)    
            Console.WriteLine($"After swapping number1= {number1}, number2 = {number2}");
            Console.ReadKey();
        }
    }
}