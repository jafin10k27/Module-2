# Exp.No:2e  
## SEB - Python Program to find the sum of series 1+3+5+7.......+N 

### AIM  
To write a Python program to find the sum of the series 1+3+5+7+…+N.

### ALGORITHM
1.Start the program.

2.Input a number n (upper limit of the series) from the user.

3.Initialize a variable sum to 0.

4.Use a for loop:

5.Start from 1 and go up to n (inclusive), incrementing by 2 each time (to pick odd numbers only).

6.In each iteration, add the current number i to sum.

7.After the loop ends, print the value of sum.

8.End the program.

### PROGRAM

```
# Reg.No-212223020018
# Name-Mohamed Jafin S
n=int(input())
sum=0
for i in range (1,n+1,2):
    sum=sum+i
print(f"The sum of the series =  {sum}")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/b27f3500-3723-46a4-b46b-f39eb22c60cb)

### RESULT
The program correctly calculates the sum of the series of odd numbers up to N and displays it.

