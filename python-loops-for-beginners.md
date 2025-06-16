# Getting Started with Python Loops for Beginners

Loops are one of the foundational building blocks of programming. In Python, loops help us execute a block of code repeatedly. This tutorial introduces you to two main types of loops in Python: `for` and `while`.

---

## Why Use Loops?

Imagine you want to print a message 10 times. Instead of writing the print statement 10 times, a loop can do that for you in just a few lines.

---

## 1. The `for` Loop

The `for` loop is used to iterate over a sequence like a list, tuple, string, or range.

### Example:

```python
for i in range(5):
    print("Hello, world!")

This prints "Hello, world!" five times.

---

## 2. The `while` Loop

The `while` loop keeps running as long as a condition is True.

### Example:

```python
count = 0
while count < 3:
    print("Learning loops!")
    count += 1

This prints "Learning loops!" three times.

---

## Loop Control Statements

    break: Stop the loop prematurely.

    continue: Skip the current iteration.

    pass: Placeholder for future code.

### Example:

```python
for i in range(5):
    if i == 3:
        break
    print(i)

---

## Practice Exercise

# Print numbers from 1 to 10 using a for loop
for num in range(1, 11):
    print(num)

---

Summary

Loops help simplify repetitive tasks and make your code cleaner. Practice writing different loops until you feel confident. Python makes loops easy to understand and fun to use!

    “The more you loop, the more you learn!”
