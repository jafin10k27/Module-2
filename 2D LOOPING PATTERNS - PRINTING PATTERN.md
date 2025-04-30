# Exp.No:2d
## LOOPING PATTERNS - Create a Python program to print the  simple number pattern using a for loop.Get the input for the number of rows 

### AIM  
To write a Python program to print a simple number pattern based on the given number of rows using for loops.

### ALGORITHM
1.Start the program.

2.Input the number of rows n from the user.

3.Use an outer for loop to repeat from i = 1 to n:

4.For each row i, use an inner for loop from j = 1 to i:

5.Print the value of i followed by a space (end=" ").

6.After inner loop ends, print a newline to move to the next row.

7.End the program.

### PROGRAM
```
#Reg.No:212223020018
#Name:Mohamed Jafin S
n=int(input())
for i in range (1,n):
    for j in range (1,i+1):
        print(i,end=" ")
    print(" ")     

```

### OUTPUT
![image](https://github.com/user-attachments/assets/845fb71c-8206-4af1-8efd-e10137f1526a)

### RESULT
The program successfully prints a simple number pattern based on the number of rows entered by the user.

