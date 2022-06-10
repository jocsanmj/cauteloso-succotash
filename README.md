using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Informacion_de_los_usuarios_consumidores_
{
    class Program
    {
        static void Main(string[] args)
        {
            string nombre, apellidos;
            int numdecedula, numdetelefono;
            Console.Write("De su nombre: ");
            nombre = Console.ReadLine();
            Console.Write("De su apellido: ");
            apellidos = Console.ReadLine();
            Console.Write("De su numero de cedula: ");
            numdecedula = int.Parse(Console.ReadLine());
            Console.Write("De su numero de telefono: ");
            numdetelefono = int.Parse(Console.ReadLine());
            Console.WriteLine("Nombre: "+nombre);
            Console.WriteLine("Apellidos: "+apellidos);
            Console.WriteLine("Numero de cedula: " + numdecedula);
            Console.WriteLine("su numero de telefono: " + numdetelefono);


            Console.ReadKey();
                


        }
    }
}
