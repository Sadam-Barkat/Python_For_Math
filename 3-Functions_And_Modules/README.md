# Functions and Modules in Python

## Overview
This guide provides an introduction to defining and calling functions, handling parameters and return values, and using modules in Python. It concludes with exercises and a mini-project to reinforce these concepts.

## Functions
Functions allow you to create reusable code blocks. Define a function using `def`, followed by its name and parameters.
```python
# Defining and calling a function
def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))  # Output: Hello, Alice!
Parameters and Return Values
Functions can accept parameters and return values:

python
Copy code
def add(a, b):
    return a + b

print(add(5, 3))  # Output: 8
Modules
Modules are files containing Python code that can be imported and used in other programs. Use built-in modules or create custom ones.

Using Built-in Modules
python
Copy code
import math
print(math.sqrt(25))  # Output: 5.0
Creating Custom Modules
Create my_module.py with:

python
Copy code
# my_module.py
def square(n):
    return n * n
Import and use:

python
Copy code
from my_module import square
print(square(4))  # Output: 16
Mini-Project: GCD Function
Implement a function to find the Greatest Common Divisor (GCD):

python
Copy code
def gcd(a, b):
    while b:
        a, b = b, a % b
    return a

print(gcd(48, 18))  # Output: 6
Conclusion
Understanding functions and modules helps create modular, maintainable code. Practice by defining functions, using modules, and building small projects.

vbnet
Copy code

This single-page `README.md` provides essential information with brief code snippets to copy and paste into your GitHub repository.





