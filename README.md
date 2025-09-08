# Julopaulo
Sujets TD
// Online C# Editor for free
// Write, Edit and Run your C# code using C# Online Compiler

using System;

public class HelloWorld
{
    public static void func(int count)
    {
        for(; count<10; count++)
        {
            Console.WriteLine (count);

        }     
    }
    public static void Main(string[] args)
    {
        Console.WriteLine ("Hello");
        int x = 10;
        char c = 'a';
        double i = 0.1;
        bool t =true;
        if(x>5)
        {
            Console.WriteLine ("More than 5");
        }
        
        int count=1;
        func(count);

        
Console.WriteLine (x);
        
    }
}



using System;

class Program
{
    static void Main()
    {
        Console.Write("Entrez un nombre entier n : ");
        int n = int.Parse(Console.ReadLine());

        int somme = 0;
        Console.WriteLine("\nLes {0} premiers nombres naturels :", n);
        for (int i = 1; i <= n; i++)
        {
            Console.Write(i + " ");
            somme += i;
        }

        Console.WriteLine("\n\nLa somme des {0} premiers nombres naturels est : {1}", n, somme);
    }
}


using System;

class Program
{
    static void Main()
    {
        Console.Write("Entrez un nombre entier pour calculer sa factorielle : ");
        int n = int.Parse(Console.ReadLine());

        long factorielle = 1;

        for (int i = 1; i <= n; i++)
        {
            factorielle *= i;
        }

        Console.WriteLine("La factorielle de {0} est : {1}", n, factorielle);
    }
}


