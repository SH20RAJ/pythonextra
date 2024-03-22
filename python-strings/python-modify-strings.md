# Python - Modify Strings

In Python, you can manipulate strings using various built-in methods. These methods enable you to change the case, remove whitespace, replace parts of the string, and split it into substrings.

#### Upper Case

The `upper()` method transforms a string into uppercase:

```python
a = "Hello, World!"
print(a.upper())  # This will print "HELLO, WORLD!"
```

#### Lower Case

The `lower()` method converts a string to lowercase:

```python
a = "Hello, World!"
print(a.lower())  # This will print "hello, world!"
```

#### Remove Whitespace

Whitespace at the beginning or end of a string can often be undesirable. You can use the `strip()` method to remove any leading or trailing whitespace:

```python
a = " Hello, World! "
print(a.strip())  # This will print "Hello, World!"
```

#### Replace String

The `replace()` method replaces a specified substring with another string:

```python
a = "Hello, World!"
print(a.replace("Hello", "Hi"))  # This will print "Hi, World!"
```

#### Split String

The `split()` method divides a string into substrings based on a specified separator and returns them as a list:

```python
a = "Hello, World!"
print(a.split(","))  # This will print ['Hello', ' World!']
```

These string manipulation methods make it easy to perform various operations on text data in Python.
