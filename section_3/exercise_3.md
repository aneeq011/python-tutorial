\### Exercise: Odd or Even Checker

Create a Python program that checks if a given number is odd or even.

\#### Instructions:

1. Prompt the user to enter a number using `input()`.

2. Convert the user input from string to an integer.

3. Use an `if-else` statement to check if the number is odd or even:
   - Print "Even number!" if the number is even (i.e., divisible by 2).
   - Print "Odd number!" if the number is odd (i.e., not divisible by 2).

4. Implement error handling to ensure the program handles invalid inputs gracefully (e.g., non-numeric inputs).

\#### Example:

\```python
\# Prompt the user to enter a number
number_str = input("Enter a number: ")

try:
    \# Convert user input to an integer
    number = int(number_str)
    
    \# Check if the number is odd or even
    if number % 2 == 0:
        print("Even number!")
    else:
        print("Odd number!")
    
except ValueError:
    print("Invalid input. Please enter a valid number.")
\```

\#### Task:

- Implement the above code in a Python file named `odd_even_checker.py`.
- Test the program with various numbers (both odd and even) to verify correct functionality.
- Ensure to handle cases where the user enters invalid inputs gracefully.

This exercise focuses on using basic control flow (`if-else` statements) to create a simple interactive program, making it suitable for beginners to practice conditional statements in Python.
