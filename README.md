using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
 
namespace check1
{
    class Program
    {
        static void Main(string[] args)
        {
            double rent;
            Console.Write("How much do you owe for rent: ");
            rent = double.Parse(Console.ReadLine());
            double cable;
            Console.Write("How much do you owe for cable: ");
            cable = double.Parse(Console.ReadLine());
            double electric;
            Console.Write("How much do you owe for electricity: ");
            electric = double.Parse(Console.ReadLine());
            double total;
            total = rent + cable + electric;
            Console.Write("You owe: $" + total);


        }
    }
}
