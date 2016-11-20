Tutorial
--------
Los arreglos en C# son muy similar a los arreglos en C. Ellos estan definidos usando corchetes  `[]`, y
se inicializan usando una lista definida con llaves `{}`. Por ejemplo:

    int[] nums = { 1, 2, 3, 4, 5 };

Tambien podemos definir un arreglo vacio como esta:

    int[] nums = new int[10];

Para obtener el tamaño de un arrego, use el metodo `Length`.

    int[] nums = new int[10];
    Console.WriteLine(nums.Length);

Para acceder a un elemento especifico en el arreglo, usamos los corchetes:

    int[] nums = new int[10];
    int primerNumero = nums[0];
    int segundoNumero = nums[1];
    nums[2] = 10;

Observe que c# usa indices basados en cero.

### Arreglos Multidimensionales / Matrices

C# soporta matrices, definidas en la siguiente manera:

    int[,] matrix = new int[2,2];

    matrix[0,0] = 1;
    matrix[0,1] = 2;
    matrix[1,0] = 3;
    matrix[1,1] = 4;

    int[,] predefinedMatrix = new int[2,2] { { 1, 2 }, { 3, 4 } };

Ejercicio
---------

Defina un arreglo llamado `frutas` que contenga las siguientes cadenas: "manzana", "banano" y "naranja".

Tutorial Code
-------------

    using System;

    public class Tutorial
    {
       public static void Main()
       {
          // Escriba su codigo aqui

          // Codigo de prueba
          Console.WriteLine(frutas[0]);
          Console.WriteLine(frutas[1]);
          Console.WriteLine(frutas[2]);
       }
    }

Expected Output
---------------

    manzan
    banano
    naranja

Solution
--------

    using System;

    public class Tutorial
    {
       public static void Main()
       {
          // Escriba su codigo aqui
          string[] frutas = new string[] { "manzana", "banano", "naranja" };

          // Codigo de prueba
          Console.WriteLine(frutas[0]);
          Console.WriteLine(frutas[1]);
          Console.WriteLine(frutas[2]);
       }
    }


