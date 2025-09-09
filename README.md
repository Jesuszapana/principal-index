 {

     int A, B, opcion;



     Console.WriteLine("=== OPERADORES RELACIONALES ===");



     Console.WriteLine("1. 7 Menor que 9 (<)");



     Console.WriteLine("2. 10 Mayor que 8 (>)");



     Console.WriteLine("3. 6 Igual a 6 (==)");



     Console.WriteLine("4. 5 No igual a 10 (!=)");



     Console.WriteLine("5. 4 Menor o igual 4 (<=)");



     Console.WriteLine("6. 12 Mayor o igual 10 (>=)");







     opcion = int.Parse(Console.ReadLine());







     Console.Write("\nIngresa el valor de A: ");



     A = int.Parse(Console.ReadLine());







     Console.Write("Ingresa el valor de B: ");



     B = int.Parse(Console.ReadLine());















     switch (opcion)



     {



         case 1:



             if (A < B)



                 Console.WriteLine("7 es menor que 9");



             else



                 Console.WriteLine("7 no es menor que 9");



             break;







         case 2:



             if (A > B)



                 Console.WriteLine("10 es mayor que 8");



             else



                 Console.WriteLine("10 no es mayor que 8");



             break;







         case 3:



             if (A == B)



                 Console.WriteLine("6 es igual a 6");



             else



                 Console.WriteLine("6 no es igual a 6");



             break;







         case 4:



             if (A != B)



                 Console.WriteLine("5 no es igual a 10");



             else



                 Console.WriteLine("5 es igual a 10");



             break;







         case 5:



             if (A <= B)



                 Console.WriteLine("4 es menor o igual a 4");



             else



                 Console.WriteLine("4 no es menor o igual a 4");



             break;







         case 6:



             if (A >= B)



                 Console.WriteLine("12 es mayor o igual a 10");



             else



                 Console.WriteLine("12 no es mayor o igual a 10");



             break;











     }




