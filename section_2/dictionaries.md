# Dictionaries in Python

Dictionaries are collections of key-value pairs. They are unordered, iterable, and mutable.

## Creating Dictionaries
- Dictionaries are created by enclosing key-value pairs in braces (`{}`), with each pair separated by a comma. Keys are unique within a dictionary.

## Example:
```python
# Examples of dictionary operations
person = {'name': 'John', 'age': 25, 'city': 'New York'}
phone_book = {'Alice': '123-456-7890', 'Bob': '987-654-3210'}
```

## Dictionary Operations

### Accessing Values
- **Accessing Values**: Retrieving values from a dictionary using keys.
```python
# Accessing values in a dictionary
person_name = person['name']
```

### Adding and Updating Elements
- **Adding and Updating Elements**: Modifying or adding new key-value pairs in a dictionary.
```python
# Adding and updating elements in a dictionary
person['email'] = 'john@example.com'
person['age'] = 31  # Updating existing value
```

### Removing Elements
- **Removing Elements**: Deleting key-value pairs from a dictionary.
```python
# Removing elements from a dictionary
del person['city']
```

### Checking Existence of Keys
- **Checking Existence**: Verifying if a key exists in a dictionary.
```python
# Checking existence of keys in a dictionary
has_age = 'age' in person
```

### Iterating Over Keys and Values
- **Iterating**: Looping through keys, values, or key-value pairs in a dictionary.
```python
# Iterating over keys and values in a dictionary
for key in person:
    print(key, person[key])
```

Dictionaries are useful for storing data that needs to be accessed quickly using a unique key.

