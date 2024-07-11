# Python Programs

This repository contains several small Python programs for various tasks.

## 1. String Reverse

### Description
This program takes a string and returns it in reverse order. It uses Python's slicing feature to reverse the string.

### Example
For the input `"val"`, the output will be `"lav"`.

### Code Explanation

def backward_string(val: str) -> str:
    return val[::-1]  # This line uses slicing to reverse the string

### Usage Example
To run this program, save the code to a file named `backward_string.py` and execute it:

$ python backward_string.py

## 2. Remainder of Division

### Description
This program takes two integers and returns the remainder when the first number is divided by the second. It uses the modulo operator `%` to find the remainder.

### Example
For the input `10` and `3`, the output will be `1`.

### Code Explanation

def find_remainder(dividend: int, divisor: int) -> int:
    return dividend % divisor  # This line calculates the remainder of the division

### Usage Example
To run this program, save the code to a file named `find_remainder.py` and execute it:

$ python find_remainder.py

## 3. Determine the Sign of a Number

### Description
This program takes an integer and returns a string indicating whether the number is "positive", "negative", or "zero". It uses simple conditional statements to determine the sign of the number.

### Example
For the input `-5`, the output will be `"negative"`.

### Code Explanation

def determine_sign(num: int) -> str:
    if num > 0:  # Checks if the number is positive
        return "positive"
    elif num < 0:  # Checks if the number is negative
        return "negative"
    else:  # If the number is neither positive nor negative, it is zero
        return "zero"

### Usage Example
To run this program, save the code to a file named `determine_sign.py` and execute it:

$ python determine_sign.py

## 4. Check if a Number is Even

### Description
This program takes an integer and returns `True` if the number is even, and `False` otherwise. It uses the modulo operator `%` to check if the number is divisible by 2.

### Example
For the input `4`, the output will be `True`.

### Code Explanation

def is_even(num: int) -> bool:
    return num % 2 == 0  # Checks if the number is divisible by 2

### Usage Example
To run this program, save the code to a file named `is_even.py` and execute it:

$ python is_even.py

## 5. Sum and Product

### Description
This program calculates the sum and product of two given numbers and displays the results. It uses basic arithmetic operations to find the sum and product.

### Example
For the inputs `2` and `5`, the sum will be `7` and the product will be `10`.

### Code Explanation

a = 2  # First number
b = 5  # Second number

add = a + b  # Calculates the sum of a and b
multi = a * b  # Calculates the product of a and b

print(f"Sum of a and b: {add}")  # Displays the sum
print(f"Product of a and b: {multi}")  # Displays the product

### Usage Example
To run this program, save the code to a file named `add_multiply.py` and execute it:

$ python add_multiply.py

This `README.md` file contains detailed descriptions of each program, examples of their usage, explanations of the code, and instructions on how to run them.
