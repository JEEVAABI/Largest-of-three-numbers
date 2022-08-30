# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
~~~
using System;
namespace MYAPP
{
    internal class program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("enter 3 numbers");
            int num1, num2, num3;
            Console.WriteLine("enter number 1");
            num1 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("enter number 2");
            num2 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("enter number 3");
            num3 = Convert.ToInt32(Console.ReadLine());
            if (num1 > num2 && num1>num3)
            {
                Console.WriteLine("number 1 is greater");  
            }
            else if(num2>num3)
                {
                Console.WriteLine("number 2 is is greater");
                }
            else
            {
                Console.WriteLine("number 3 is greater");
            }
            

        }

    }
}

~~~

## Output:
![output](out.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully
