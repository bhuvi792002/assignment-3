# assignment-3
task 4

# Task 2: Using the Math Module for Calculations

import math  # Import the math module

# Ask the user for a number
try:
    num = float(input("Enter a number: "))

    # Calculate using the math module
    sqrt_value = math.sqrt(num) if num >= 0 else "Square root is not defined for negative numbers."
    log_value = math.log(num) if num > 0 else "Logarithm is not defined for non-positive numbers."
    sine_value = math.sin(num)  # Sine function works for all real numbers

    # Display the results
    print(f"Square root of {num}: {sqrt_value}")
    print(f"Natural logarithm of {num}: {log_value}")
    print(f"Sine of {num} (radians): {sine_value}")

except ValueError:
    print("Invalid input! Please enter a valid number.")



    task 5


    # Task 2: Using the Math Module for Calculations

import math  # Import the math module

# Ask the user for a number
try:
    num = float(input("Enter a number: "))

    # Calculate using the math module
    sqrt_value = math.sqrt(num) if num >= 0 else "Square root is not defined for negative numbers."
    log_value = math.log(num) if num > 0 else "Logarithm is not defined for non-positive numbers."
    sine_value = math.sin(num)  # Sine function works for all real numbers

    # Display the results
    print(f"Square root of {num}: {sqrt_value}")
    print(f"Natural logarithm of {num}: {log_value}")
    print(f"Sine of {num} (radians): {sine_value}")

except ValueError:
    print("Invalid input! Please enter a valid number.")
