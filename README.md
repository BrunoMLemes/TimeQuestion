# TimeQuestion
Perguntador de horario simples.
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Horario
{
    class Program
    {
        static void Main(string[] args)
        {

            int horas;
            string sexo;


            Console.WriteLine("Você é um homem ou mulher?");
            sexo = (Console.ReadLine());


            Console.WriteLine("Que horas são ?");
            horas = int.Parse(Console.ReadLine());


            if (horas < 12) {
                if (sexo == "m")
                {
                    Console.WriteLine("Bom Dia meu consagrado !!");
                }
                else
                {
                    Console.WriteLine("Bom dia minha consagrada !!");
                }
                

            }
            else {
                if (horas < 18) {
                    if (sexo == "m")
                    {
                        Console.WriteLine("Bom tarde meu consagrado !!");
                    }
                    else
                    {
                        Console.WriteLine("Bom tarde minha consagrada !!");
                    }
                    

                }
                else {

                    if (sexo == "m") { 
                        Console.WriteLine("Boa noite meu consagrado !!"); 
                    }
                    else { 
                        Console.WriteLine("Boa noite minha consagrada!!"); 
                    }
                    
                        
                }
                    
            }

            Console.ReadLine();
        }
    }
}
