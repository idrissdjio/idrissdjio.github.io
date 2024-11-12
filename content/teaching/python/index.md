---
title: Learn Python for Data Science
summary: Quickly learn the basics of Python and how to use it in data science in under 10 minutes!
date: 2023-10-24
type: docs
math: false
tags:
  - Python
  - Data Science
image:
  caption: 'Start coding with Python today!'
---

Python is one of the most popular languages in data science due to its simplicity and powerful libraries. This tutorial covers Python basics and introduces some essential tools for data science. Let’s get started!

## 1. Python Basics

### What is Python?
Python is a versatile programming language used for web development, automation, machine learning, and data science. Its simple syntax makes it beginner-friendly, while its vast ecosystem of libraries makes it ideal for data analysis.

### Running Python
You can run Python code in various environments, like Jupyter Notebooks, the terminal, or Python IDEs. To test it, open a Python interpreter by typing `python` in your terminal, or try online editors like [Repl.it](https://replit.com/).

Try the code below:
```python
print("Hello, Python!")
```
This code will output `Hello, Python!` to the console.

---

## 2. Variables and Data Types

### Declaring Variables
In Python, you create a variable simply by assigning a value to a name:
```python
name = "Alex"
age = 25
```

### Basic Data Types
Python has several core data types:
- **String**: Text, such as `"Hello, World!"`
- **Integer**: Whole numbers, e.g., `42`
- **Float**: Decimal numbers, e.g., `3.14`
- **Boolean**: `True` or `False`

```python
greeting = "Hello, Data Science!"
is_active = True
score = 98.6
```

### Type Conversion
You can convert data types using built-in functions like `str()`, `int()`, and `float()`:
```python
num = 10
num_str = str(num)  # Converts integer to string
```

---

## 3. Lists and Dictionaries

### Lists
Lists are ordered collections that can store multiple values:
```python
fruits = ["apple", "banana", "cherry"]
print(fruits[0])  # Outputs: apple
```

### Dictionaries
Dictionaries store data in key-value pairs and are useful for labeled data:
```python
person = {"name": "Alex", "age": 25}
print(person["name"])  # Outputs: Alex
```

---

## 4. Control Flow

### Conditionals
Conditionals let you execute code based on conditions:
```python
if age > 18:
    print("Adult")
else:
    print("Minor")
```

### Loops
Loops let you repeat code. Here’s a `for` loop and a `while` loop:

```python
# For loop
for fruit in fruits:
    print(fruit)

# While loop
count = 0
while count < 3:
    print(count)
    count += 1
```

---

## 5. Functions

Functions let you define reusable blocks of code. Here’s how to define a function:

```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Alex"))  # Outputs: Hello, Alex!
```

---

## 6. Introduction to Libraries

Python’s power in data science comes from its extensive libraries. Here are a few essential ones:

### Numpy
Numpy is a library for numerical operations in Python:
```python
import numpy as np
arr = np.array([1, 2, 3])
print(arr.mean())  # Outputs the mean of the array
```

### Pandas
Pandas is used for data manipulation and analysis:
```python
import pandas as pd
data = pd.DataFrame({
    "name": ["Alex", "Bob", "Clara"],
    "age": [25, 30, 35]
})
print(data.head())
```

---

## Summary

In this tutorial, you learned the basics of Python, including variables, data types, lists, dictionaries, functions, and essential libraries like Numpy and Pandas. Start exploring these concepts in your data science journey!

## Did you find this page helpful? Consider sharing it 🙌
