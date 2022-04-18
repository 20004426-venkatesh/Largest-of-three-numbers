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
```c#
using System;
namespace lg
{
    class LargeNo
    {
        static void Main(string[] args)
        {
            
            int num1,num2,num3;
            Console.WriteLine("Enter The Values :");
            num1=Convert.ToInt32(Console.ReadLine());
            num2=Convert.ToInt32(Console.ReadLine());
            num3=Convert.ToInt32(Console.ReadLine());

            
            if(num1>num2 && num1>num3)
            {
                Console.WriteLine("num1 Is Greater");
            }
            else if(num2>num1 && num2>num3)
            {
                Console.WriteLine("num2 Is Greater");
            }
            else
                Console.WriteLine("num3 Is Greater");
        }
    }
}
```

## Output:
![image](https://github.com/20004426-venkatesh/Largest-of-three-numbers/blob/main/exp1%20c%23.jpg)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully
