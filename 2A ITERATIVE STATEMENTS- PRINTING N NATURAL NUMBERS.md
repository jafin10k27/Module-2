# Exp. No: 2a  
## ITERATIVE STATEMENTS – Write a python program to compute the factorial for a Given Number

###  Aim
To write a Python program to compute the factorial of a given number using a while loop.

###  Algorithm
1.Start the program.

2.Input a number (num) from the user.

3.Assign f = num and n = f - 1.

4.Use a while loop:

5.While n > 0, multiply f = f * n.

6.Decrease n by 1 in each iteration.

7.After the loop, print the value of f.

8.End the program.

### Program

```python
#Reg.NO:212223020018
#Name:Mohamed Jafin S
num = int(input())
f=num
n=f-1
while n>0:
    f=f*n
    n=n-1
print(f"Factorial of the given number {num} is {f}")    

```
### OUTPUT
![image](https://github.com/user-attachments/assets/eba6c92d-7688-44ce-8554-70044f49d909)

### RESULT
The program successfully computes and prints the factorial of a given number.
