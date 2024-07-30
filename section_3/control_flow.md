### Section 3: Control Flow

#### 1. Control Flow: Conditionals and Loops
Conditionals and loops are fundamental to controlling the flow of execution in Python programs.

##### Introduction to Conditionals
Conditionals (`if`, `else`, `elif`) allow you to make decisions in your code based on conditions.

```python
# Example of using if-else statement
age = 20
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```

##### Another Example of Conditionals
```python
# Example of using if-else statement to check if a number is positive, negative, or zero
num = 0

if num > 0:
    print("The number is positive.")
elif num < 0:
    print("The number is negative.")
else:
    print("The number is zero.")
```

##### Types of Loops
Loops (`for` and `while`) are used to iterate over sequences or execute blocks of code repeatedly.

```python
# Example of using for loop
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

# Example of using while loop
num = 1
while num <= 5:
    print(num)
    num += 1
```

#### More Examples and Explanation

##### Nested Conditionals
You can nest conditionals within each other to create more complex decision-making structures.

```python
# Example of nested conditionals
num = 10
if num > 0:
    if num % 2 == 0:
        print("Positive even number.")
    else:
        print("Positive odd number.")
elif num < 0:
    print("Negative number.")
else:
    print("Zero.")
```

##### Loop Control Statements
Python provides `break`, `continue`, and `pass` statements to control the flow within loops.

```python
# Example of using break and continue
for i in range(1, 10):
    if i % 3 == 0:
        continue  # Skip current iteration
    if i == 7:
        break  # Exit the loop
    print(i)
```

##### Using Range
The `range()` function generates a sequence of numbers, which is commonly used in loops.

```python
# Example of using range in a for loop
for i in range(5):  # Generates numbers from 0 to 4
    print(i)

# Using range with start and end values
for i in range(2, 6):  # Generates numbers from 2 to 5
    print(i)

# Using range with step value
for i in range(1, 10, 2):  # Generates odd numbers from 1 to 9
    print(i)
```

##### Using Pass
The `pass` statement is a null operation; it is used when a statement is required syntactically but you do not want any command or code to execute.

```python
# Example of using pass
for i in range(5):
    if i == 3:
        pass  # Do nothing
    else:
        print(i)
```
