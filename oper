# Act_POO
using System;

namespace Aerolinea
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("BIENVENIDOS A LA AEROLINEA");


            string lugar = "USA";
            string lugar2 = "Mexico";
            string lugar3 = "Espana";

            int freviaj = 15000;

            long tiq_costo = 3200000;

            int cap_aviones = 400;

            int num_empleados = 4000;
            long salario = 2800000;




            var selepais = new Operaciones(){

                pais_num = lugar,
                pais_num2 = lugar2,
                pais_num3 = lugar3

            };

            selepais.pais(selepais.pais_num, selepais.pais_num2, selepais.pais_num3);

            var viajfre = new Operaciones(){

                viajeros_frecuentes = freviaj
            };

            viajfre.frecuentes_via(viajfre.viajeros_frecuentes);

            var costiq = new Operaciones(){

                costo_tiquetes = tiq_costo
            };

            costiq.tiquete(costiq.costo_tiquetes);

            var aviocap = new Operaciones(){

                capacidad_aviones = cap_aviones
            };

            aviocap.capaviones(aviocap.capacidad_aviones);

            var empleados = new Operaciones(){

                numero_empleados = num_empleados,
                sueldo = salario
            };

            empleados.numempleados(empleados.numero_empleados, empleados.sueldo);


            System.Console.WriteLine("¿Cual es tu nombre?");
            string nombre = Console.ReadLine();
            System.Console.WriteLine("¿Cual es tu edad?");
            int edad = Convert.ToInt32(Console.ReadLine());
            System.Console.WriteLine("¿Cuántas veces has vijado con nosotros?");
            int numviajes = Convert.ToInt32(Console.ReadLine());

            var preguntas = new Operaciones(){

                Nombre = nombre,
                edad_ = edad,
                vecesviaj = numviajes

            };

            preguntas.sistemadeviaje(preguntas.Nombre, preguntas.edad_, preguntas.vecesviaj);










           


        }
    }
}
