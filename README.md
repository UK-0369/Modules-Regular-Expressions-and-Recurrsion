# Modules-Regular-Expressions-and-Recurrsion
assignmenmt

excercise 1
import math

number = 16
square_root = math.sqrt(number)
print(square_root)



excercise 2
import math

number = 4.3
floor_value = math.floor(number)
ceiling_value = math.ceil(number)
print(f"Floor: {floor_value}, Ceiling: {ceiling_value}")



Excercise 3
import math

base = 2
exponent = 3
power_value = math.pow(base, exponent)
print(power_value)




Excercise 4
import re

def is_valid_email(email):
    pattern = r'^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$'
    return re.match(pattern, email) is not None

email = "example@example.com"
print(is_valid_email(email))  # True or False





Excercise 5
def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)

number = 5
print(factorial(number))
