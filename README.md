# python-calculator
A simple CLI calculator using Python (with operator logic, error handling)
"""
calculator.py
Author: Mohammed Arfat
Date: 27-Jun-2025
"""



num1 = float(input("Enter The First Number  =   "))
operator = input("Enter The Operator (+,-,*,/):")
num2 = float(input("Enter The Second Number  =   "))

if operator == "+":
    result = num1 + num2


elif operator == "-":
    result = num1 - num2

elif operator == "*":
    result = num1 * num2

elif operator == "/":
    result = num1 / num2

else:
    print("Invalid Operator")
    result = None

if result is not None:
    print("result:", result)
