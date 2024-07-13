# Tuples in Python

Tuples in Python are ordered collections of items, similar to lists. However, they are immutable, meaning their elements cannot be changed after creation.

## Creating Tuples
- Tuples are created by enclosing elements in parentheses (`()`), separated by commas.

### Example:
```python
# Creating tuples
coordinates = (3, 4)
```

## Tuple Operations

### Accessing Elements
- **Accessing Elements**: Retrieving elements from a tuple using indices.
```python
# Accessing elements in a tuple
x = coordinates[0]
```

### Slicing
- **Slicing**: Extracting a subtuple from a tuple using a specified range of indices.
```python
# Slicing a tuple
subtuple = coordinates[1:]  # Extract elements starting from index 1 to the end
```

### Tuple Operations
- **Tuple Operations**: Since tuples are immutable, operations are limited to accessing elements and slicing.
```python
# Concatenating tuples
combined_tuple = coordinates + (5, 6)

# Tuple unpacking
x, y = coordinates
```

Tuples are useful for representing fixed collections of items where immutability and integrity of data are required, such as returning multiple values from functions or as keys in dictionaries.
