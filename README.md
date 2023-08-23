# Pattern

## Aim:
To write a C# program to draw a pattern.

## Equipment Required:
Microsoft Visual Studio 2022 (or Lower) or Any other C# compiler.

## Algorithm:
Step 1:
Create a class and declare a variable with string datatype

Step 2:
Use for loop to check whether the input is a palindrome or not.

Step 3:
Use if condition to check whether input is equal to the calculated number.

Step 4:
Display the results of the condition of the input using Console.WriteLine().



## Program:
Name : ARUN KUMAR SUKDEV CHAVAN

Reg.No : 212222230013
```
using System;
class HelloWorld
{
    static void Main()
    {
        int c = 0, rows = 6;
        for (int i = 0; i < rows; i++)
        {
            for (int s = 0; s < rows - i; s++)
            {
                Console.Write("  ");
            }
            for (int j = 0; j <= i; j++)
            {
                if (i == 0 || j == 0)
                {
                    c = 1;
                }
                else
                {
                    c = c * (i - j + 1) / j;
                }

                Console.Write("   " + c);

            }
            Console.WriteLine();

        }
    }
}
```



## Output:
![output](https://github.com/Akash020803/C-Pattern/raw/main/ss1.png)
## Result:
Hence, a C# program for a pascal's triangle is executed successfully.
