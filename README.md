# Core-CodeWork
Tareas de Core-Code

Actividades del dia Martes

1. Watch this video about compilation and interpretation ✅

3. Search and answer the question: Java language is compiled or interpreted?
R = Java es un lenguaje hibrido lo cual primero es compilado bytecode por un programa llamado javac. 
Luego otro programa llamado java inicia el entorno de ejecución de java y puede complicar y/o interpretar el bytecode usando el Intérprete de Java/Compilador JIT.
Java se compila a bytecode, qu eluego entra en la maquina virtual de java, que lo interpreta.

4. Create an algorithm to calculate the equivalent of your local currencty to USD
R = 

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
namespace taller_56
{
 class Program
 {
 static void Main(string[] args)
 {
  float cord = 0, usd = 36.00, conversion = 0;
  
 Console.WriteLine("Digite el monto a convertir :\n");
 cord= float.parse(Console.ReadLine());
 
 conversion = cord * usd;
 Console.WriteLine("El monto digitado en dolar es: {0}", conversion);
 
 Console.ReadKey();
   }
  }
 }

  

6. Read about Pseudocode here, you can also find some examples here, anwser to the question: Why is pseudocode helpful?
R = 

8. Create a pseudocode to calculate the aproximated age of a user base on the year they born, (you can define a variable with the actual year if you need it, like for example i could define Y <-- 2022)
R = 

10. Read about flowcharts here answer to the question: Why are flowcharts important to us as developers? 
R = 

12. Search about High-level languages and Low-level languages, you can start with this video 


