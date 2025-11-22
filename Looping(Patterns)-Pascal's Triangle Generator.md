# Ex 2d:Looping(Patterns)-Pattern printing using a character

## Aim

To write a Python program that takes a character as input and prints a pattern of the same character.

## Algorithm

1.Start the program.

2.Read a single character from the user.

3.Use a loop from 1 to 5.

4.In each iteration, print the character repeated i times with spaces.

5.End the program.

## Program
```
char = input()

rows = 5  

for i in range(1, rows + 1):
    print(" ".join([char] * i))
```

## Sample Output
<img width="405" height="458" alt="image" src="https://github.com/user-attachments/assets/5a8a2d9b-30d3-4e84-8b5f-9ca14d2c1c6b" />

## Result
Thus, the program successfully prints a pattern using the same character entered by the user.
