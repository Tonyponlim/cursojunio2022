# cursojunio2022
REPOSITORIO DE TAREAS DEL CURSO JUNIO 2022 DESARROLLO DE SOFTWARE
using System;

namespace ConsolaAplication5
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!!!!");
            Console.ReadKey();
            int num1 = 5;
            int nuero2 = 6;
            double numero3 = 2.57;
            double suma;
            suma = num1 + numero3;

            Console.WriteLine(suma);
            string valor1 = Console.ReadLine();
            Console.WriteLine("El número introducido es: " + valor1);
            int valorint = Convert.ToInt32(valor1);
            Console.ReadKey();
        }
    }
}
