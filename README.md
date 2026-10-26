\# PLP Python Week 6 Assignment



\## Files



\- `safe\_tools.py` - Contains three functions that handle division by zero, invalid number input, and missing dictionary keys.

\- `README.md` - Describes the assignment files and explains the use of error handling.



\## Why can't an if check catch abc on its own?



An `if` statement can check whether a condition is true or false, but it does not automatically catch errors during number conversion. For example, `int("abc")` raises a `ValueError`, so `try` and `except ValueError` are used to handle the invalid input without crashing the program.

