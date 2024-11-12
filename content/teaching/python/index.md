---
title: Learn Python
summary: Easily learn Python in 10 minutes!
date: 2024-10-28
type: docs
math: false
tags:
  - Python
image:
  caption: 'Embed rich media such as videos and LaTeX math'
---

This tutorial is designed to help you get started with Python quickly and effectively. In just 10 minutes, you'll learn essential concepts and be able to write basic Python code.

## Getting Started with Python

Python is a versatile programming language known for its simplicity and readability. Follow these examples to understand its syntax and capabilities.

### Variables and Data Types

In Python, variables are used to store data values. You don’t need to declare a variable type; Python infers it automatically.

```python
# Integer
age = 25

# Float
height = 5.9

# String
name = "John"

# Boolean
is_student = True
```

### Basic Operations

Python supports basic arithmetic operations like addition, subtraction, multiplication, and division.

```python
# Addition
a = 10
b = 5
result = a + b

# Subtraction
result = a - b

# Multiplication
result = a * b

# Division
result = a / b
```

### Control Structures

#### If-Else Statements

Control the flow of your program using conditional statements.

```python
age = 18

if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```

#### Loops

Use loops to execute a block of code multiple times.

```python
# For loop
for i in range(5):
    print("Iteration", i)

# While loop
count = 0
while count < 5:
    print("Count is:", count)
    count += 1
```

### Functions

Functions in Python help organize code into reusable blocks.

```python
def greet(name):
    return "Hello, " + name

message = greet("Alice")
print(message)
```

### Working with Lists

Lists in Python allow you to store multiple items in a single variable.

```python
fruits = ["apple", "banana", "cherry"]
print(fruits[0])  # Output: apple

# Add an item
fruits.append("orange")

# Remove an item
fruits.remove("banana")
```

### Dictionaries

Dictionaries store data in key-value pairs.

```python
person = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}

print(person["name"])  # Output: Alice
```

### Simple Math Operations

Python can handle mathematical calculations directly.

```python
import math

# Square root
print(math.sqrt(16))  # Output: 4.0

# Pi constant
print(math.pi)  # Output: 3.141592653589793
```

---

With these basics, you're ready to start exploring Python. Practice by writing small programs to reinforce these concepts. Happy coding!
