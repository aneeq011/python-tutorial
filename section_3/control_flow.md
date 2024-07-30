### Section 3: Control Flow

#### 1. Control Flow: Conditionals and Loops
Conditionals and loops are fundamental to controlling the flow of execution in Python programs.

##### Introduction to Conditionals
Conditionals (`if`, `else`, `elif`) allow you to make decisions in your code based on conditions.

```python
# Example of using if-else statement
weather = "sunny"
if weather == "rainy":
    print("Let's have some hot soup!")
elif weather == "sunny":
    print("Time for a beach picnic!")
else:
    print("Hmm... Let's order pizza!")
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
