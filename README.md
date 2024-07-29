# Modules-Regular-Expressions-and-Recurrsion
assignmenmt
import math

1. Finding the Square Root of number using math function
 import math

number = 64
sqrt_number = math.sqrt(number)
print(f"The square root of {number} is {sqrt_number}")



2. Calculate the floor and ceiling of 4.3 using math function

import math

number = 4.3
floor_number = math.floor(number)
ceil_number = math.ceil(number)
print(f"The floor of {number} is {floor_number}")
print(f"The ceiling of {number} is {ceil_number}")




3. Calculate the power of a number using math function

import math

base = 2
exponent = 3
power = math.pow(base, exponent)
print(f"{base} to the power of {exponent} is {power}")





4. Write a Python program that uses regular expressions to validate whether an input string    is a valid email address or not.(try to do and understand this)

import re

def is_valid_email(email):
    pattern = r'^[a-zA-Z0-9_.+-]+@[a-zA-Z0-9-]+\.[a-zA-Z0-9-.]+$'
    return re.match(pattern, email) is not None

email = "example@example.com"
print(f"Is '{email}' a valid email? {is_valid_email(email)}")

email = "invalid-email.com"
print(f"Is '{email}' a valid email? {is_valid_email(email)}")






5. Find Factorial of a number using Recurssion.

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

number = 5
print(f"The factorial of {number} is {factorial(number)}")





