# Ex 2b:Functions: Check Perfect Number using Function

## Aim
To write a Python program to check whether a given number is a Perfect number using a user-defined function.
## Algorithm
1.Start the program.

2.Define a function that:
     Takes a number as input.
     Finds all its proper divisors.
     Adds them and returns the sum.

3.Read a number from the user.

4.Call the function and compare the sum of divisors with the number.

5.If both are equal, it is a Perfect number; otherwise, it is not.

6.Display the result.

7.End the program.

## Program
```
def is_perfect_number(num):
    if num <= 0:
        return False
    divisors_sum = sum(i for i in range(1, num) if num % i == 0)
    return divisors_sum == num

n = int(input())

if is_perfect_number(n):
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")
```

## Output
<img width="754" height="215" alt="image" src="https://github.com/user-attachments/assets/af8de547-8b6a-4150-9ed9-81d7f22c854d" />

## Result
Thus, the program successfully checks whether a given number is a Perfect number using the concept of functions.
