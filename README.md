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
