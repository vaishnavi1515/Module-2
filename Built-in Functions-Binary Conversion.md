# Ex 2a:Iterative functions -Print natural numbers from 1 to n

## Aim
To write a Python program to print natural numbers from 1 to a given number n.

## Algorithm
1.Start the program.

2.Read an integer n from the user.

3.Print a message “Natural Numbers are :”.

4.Use a loop from 1 to n and print each number.

5.End the program.
## Program
```
def print_natural_numbers(n):
    print("Natural Numbers are :")
    for i in range(1, n + 1):
        print(i)
n = int(input())
print_natural_numbers(n)
```
## Output
<img width="573" height="508" alt="image" src="https://github.com/user-attachments/assets/d9a592e4-70d7-4322-aaaf-8d80c88c3838" />

## Result
Thus, the program successfully prints natural numbers from 1 to n.
