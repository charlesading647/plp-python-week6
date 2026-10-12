# Week 6 Assignment: Safe Functions

This project demonstrates error handling in Python using try and except.

## Files

- `safe_tools.py` - Contains safe_divide, safe_number, and get_field functions.
- `README.md` - Describes the assignment and explains why an if check alone cannot catch invalid integer conversion.

## Why can't an if check catch abc on its own?

An if statement can check whether text meets a condition, but it cannot reliably determine whether every possible string can be converted to an integer. Using int() inside a try block and catching ValueError handles invalid input such as "abc" safely.