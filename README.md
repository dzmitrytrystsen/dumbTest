using System;

namespace Input
{
    class Program
    {
        static void Main()
        {
            Console.Write("Please enter any number between 1 and 10.\n");

            var input = Console.ReadLine();

            var number = Convert.ToInt32(input);

            if (number >= 1 && number <=10)
                {
                    Console.WriteLine("\nOh, you are genius!");
                }

            else
                {
                    Console.WriteLine("\nLOL! You are so dumb!");
                }

            Main();
        }
    }
}
