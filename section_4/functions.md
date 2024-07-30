# Functions

Functions are reusable blocks of code that perform a specific task. They help in organizing code, making it more readable and maintainable.

## Defining Functions

To define a function in Python, use the `def` keyword followed by the function name and parentheses.

### Syntax

`python
def function_name():
    # Code to execute
`

### Example

`python
def greet():
    print("Hello, World!")
`

### Explanation

Functions allow you to group code into reusable blocks. This is useful for organizing and reusing code.

## Arguments and Parameters

Functions can accept inputs called parameters. When you call a function, you provide arguments to these parameters.

### Syntax

`python
def function_name(parameter1, parameter2):
    # Code to execute
`

### Example

`python
def greet(name):
    print(f"Hello, {name}!")
`

### Explanation

Parameters are variables that hold the values of the arguments passed during the function call.

## Return Values

Functions can return a value using the `return` keyword.

### Syntax

`python
def function_name():
    return value
`

### Example

`python
def add(a, b):
    return a + b
`

### Explanation

Returning a value allows the function to produce output that can be used elsewhere in the code.

## Scope

Scope refers to the visibility of variables. Variables defined inside a function are local to that function.

### Example

`python
def my_function():
    local_variable = 10
    print(local_variable)

my_function()
# print(local_variable)  # This will cause an error
`

### Explanation

Local variables are only accessible within the function in which they are defined.

## Lambda Functions

Lambda functions are small anonymous functions defined using the `lambda` keyword.

### Syntax

`python
lambda arguments: expression
`

### Example

`python
add = lambda x, y: x + y
print(add(2, 3))
`

### Explanation

Lambda functions are useful for short, simple functions that are used only once or twice in the code.

