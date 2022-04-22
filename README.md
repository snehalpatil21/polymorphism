# polymorphism
using System;
Namespace CSharp_Shell
{     Public class Program 
    	{
    	Void add(int a,int b)
    	{
    	Int c=a+b;
    	Console.WriteLine(“Addition of a and b=”+c);
    	}
    	Void add(int a,int b,int c)
    	{
    	Int c1=a+b+c;
    	Console.WriteLine(“Addition of a.b and c=”+c1);
    	}
        Public static void Main(string [] args)
        {			Program p=new Program();
			p.add(10,20);
			p.add(10,20,30);
			Console.ReadLine();
        }    }   }
