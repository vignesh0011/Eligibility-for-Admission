# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithm:
### Step 1:
Create new class

### Step 2:
Initiate the variables for maths, physics and chemistry and get the value from the user.

### Step 3:
Convert the values to integer values.

### Step 4:
Calculate the sum of all three subjects and maths-physics total.

### Step 5:
Check for the given criteria for eligibility using if-else statements.

### Step 6:
Display whether the person is eligible for admission or not based on the given criteria.

### Step 7;
Exit the Program.

## Program:
```c#
using System;
    class Eligibility
    {
        static void Main(string[] args)
        {
            int math, phy, chem;
            Console.Write("Enter Maths Marks:");
            math = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter Physics Marks:");
            phy = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter Chemistry Marks:");
            chem = Convert.ToInt32(Console.ReadLine());
            int Sum = math + phy + chem;
            int MP = math + phy;
            if (math >= 65 && phy >= 55 && chem >= 50)
            {
                if (Sum >= 180 || MP >= 140)
                    Console.WriteLine("Student is eligible.");
                else
                    Console.WriteLine("Student is not eligible.");
            }
            else
                Console.WriteLine("Student is not eligible.");
        }
    }

```

## Output:
![image](https://github.com/vignesh0011/Eligibility-for-Admission/assets/53014593/47af91eb-911d-46e6-9b44-d07a332d4ce1)


## Result:

Thus a C# program to check eligibility for admission is executed successfully.
