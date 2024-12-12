# Python ZeroDivisionError Bug
This repository demonstrates a common Python error: ZeroDivisionError. The bug occurs when attempting to divide a number by zero.  The solution shows how to handle this exception using a try-except block.

## Bug
The `bug.py` file contains a function `my_function` that divides two numbers. However, it doesn't handle the case where the second number is zero.  When called with `my_function(10, 0)`, it raises a `ZeroDivisionError`.

## Solution
The `bugSolution.py` file demonstrates how to gracefully handle this error using a `try-except` block. This approach prevents the program from crashing and allows you to handle the error in a more controlled way.