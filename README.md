# Modules-Regular-Expressions-and-Recurrsion
assignmenmt
import math

number = 16
square_root = math.sqrt(number)
print(square_root)


import math

number = 4.3
floor_value = math.floor(number)
ceiling_value = math.ceil(number)
print(f"Floor: {floor_value}, Ceiling: {ceiling_value}")


import math

base = 2
exponent = 3
power_value = math.pow(base, exponent)
print(power_value)


import re

def is_valid_email(email):
    pattern = r'^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$'
    return re.match(pattern, email) is not None

email = "example@example.com"
print(is_valid_email(email))  # True or False


import re
def is_valid_email(email):
    pattern = r'^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$'
    return re.match(pattern, email) is not None

email = "example@example.com"
print(is_valid_email(email))  # True or False



def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)

number = 5
print(factorial(number))
