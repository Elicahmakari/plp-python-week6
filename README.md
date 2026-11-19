Week 6 Assignment: Error Handling in Python

Assignment Description

This project demonstrates how to handle errors in Python using try and except.

Files Included

1. safe_tools.py

Contains three functions:

- safe_divide(): Divides two numbers and handles division by zero.
- safe_number(): Converts text into an integer and handles invalid input.
- get_field(): Retrieves information from a dictionary and handles missing keys.

2. README.md

Provides an overview of the assignment and explains the Python concepts used.

Question: Why can the if check not catch abc on its own?

An if statement cannot automatically determine whether text such as "abc" can be converted into an integer. The int() function raises a ValueError when it receives invalid text. Therefore, try and except are used to catch the error and prevent the program from crashing.

Expected Output

5.0
Cannot divide by zero
42
Not a number
82
Field not found

Concepts Practiced

- try and except
- ValueError
- ZeroDivisionError
- KeyError
- Python functions
- Error handling
