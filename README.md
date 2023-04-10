# Ex05-Rec-JaggedArray
## Aim:
To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.
## Algorithm:
### Step 1:
Start the C# program in visual studio 2022.

### Step 2:
Declare a Jagged Array for four element.

### Step 3:
Initialize the elements.

### Step 4:
Accessing the elements.

### Step 5:
Finish the program and Run the prgram

### Step 6:
Take the screenshot of the output of the program.



## Program:
```
using System;
class exp02
{
    public static void Main(String[] args)
    {
        int[][] cpu = new int[4][];
        cpu[0] = new int[3];
        cpu[1] = new int[5];
        cpu[2] = new int[6];
        cpu[3] = new int[4];
        for (int i = 0; i < 4; i++)
        {
            for (int j = 0; j < cpu[i].Length; j++)
            {
                cpu[i][j] = i * j + 70;
            }
        }
        for (int i = 0; i < cpu.Length; i++)
        {
            for (int j = 0; j < cpu[i].Length; j++)
            {
                Console.WriteLine("CPU usage at node" + i + " is " + cpu[i][j] + "%");
            }
            Console.WriteLine();
        }
    }
}
```

## Output:
![img1](https://user-images.githubusercontent.com/94508142/230871133-6d00ab5c-5d0c-4330-973a-e83474a1e34e.jpg)


## Result:
A C# program to create a sample CPU usage on a network with 4 nodes using a jagged array is successfully executed.
