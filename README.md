# -Zadanie3
using System;
namespace lab3
{
    class Program
    {
        static void Zadanie1() 
        {

            double[] mas = new double[] { 10, -3, -5, 2, 5 };
            double d = double.MaxValue;
            int index = 0;
            for (int i = 0; i < mas.Length; ++i)
            {
                double temp = Math.Abs(mas[i]);
                if (d > temp)
                {
                    d = temp;
                    index = i;
                }
            }
            Console.WriteLine(index);          

        }
        static void Zadanie2(int[] arr)
        {
            Random rand = new Random();

            for (int i = 0; i < arr.Length; i++)
