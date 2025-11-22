## Ex 2e:Functions in Python: Count digits in a number

## Aim
To write a Python program to count the number of digits in a given number.

## Algorithm
1.Start the program.

2.Read a number from the user as input.

3.Convert the number to a string.

4.Count the length of the string to get the number of digits.

5.Display the count.

6.End the program.
## Program
```
def count_digits(num):
    return len(str(abs(num)))
num=int(input())
digit_count=count_digits(num)
print("The number of digits in the number are:",digit_count)
```
## Output
<img width="871" height="210" alt="image" src="https://github.com/user-attachments/assets/838f8323-99a9-4000-8511-4dbdfdd99b4f" />

## Result
Thus, the program successfully counts and displays the number of digits in a given number.
