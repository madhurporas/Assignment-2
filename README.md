# Assignment-2
#Task 1
# Even or Odd Number Checker

This is a simple Python program that checks whether a given integer is **even** or **odd**.

## 📌 Code

```python
n = int(input("Enter an integer: "))

if n % 2 == 0:
    print(n, "is an even integer")
else:
    print(n, "is an odd integer")
```
The program takes an integer input from the user.

It uses the modulo operator (%) to check divisibility by 2.

If the number is divisible by 2 (remainder 0), it is even.

Otherwise, it is odd.

output
```
Enter an integer: 10
10 is an even integer
Enter an integer: 7
7 is an odd integer
```


#Task 2
# Sum of Numbers from 1 to 50

This Python program calculates the sum of all integers from **1 to 50**.

## 📌 Code

```python
sum = 0
for i in range(1, 51):
    sum += i
print("sum of numbers from 1 to 50 is =", sum)
```

Initialize sum = 0.

Loop through numbers from 1 to 50 using for i in range(1, 51).

Add each number to the running total (sum += i).

Print the final result.

Output
```sum of numbers from 1 to 50 is = 1275```
