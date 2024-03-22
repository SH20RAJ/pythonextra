# Python Strings

In Python, strings are a fundamental data type used to represent text. You can create strings by enclosing text in either single or double quotation marks. For example, `'hello'` and `"hello"` are both valid string representations, and they are considered equivalent.

#### Displaying Strings

You can display a string literal using the `print()` function. Here's an example:

```python
print("Hello")
print('Hello')
```

#### Assigning Strings to Variables

To store a string in a variable, you simply use the variable name followed by an equal sign and the string itself. For instance:

```python
a = "Hello"
print(a)
```

#### Multiline Strings

Python allows you to work with multiline strings easily by using triple quotes. You can use either triple double quotes or triple single quotes to create multiline strings. For example:

```python
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
```

or

```python
a = '''Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.'''
print(a)
```

#### Strings as Arrays

Strings in Python are treated as arrays of bytes representing Unicode characters. Unlike some other programming languages, Python doesn't have a character data type. Instead, a single character is represented as a string with a length of 1. You can access individual characters in a string using square brackets, and remember that indexing starts from 0.

```python
a = "Hello, World!"
print(a[1])  # This will print 'e'
```

#### Looping Through a String

You can loop through the characters of a string using a `for` loop:

```python
for x in "banana":
  print(x)
```

#### String Length

To determine the length of a string, you can use the `len()` function. For example:

```python
a = "Hello, World!"
print(len(a))  # This will print 13
```

#### Checking for Substrings

To check if a specific word or character is present in a string, you can use the `in` keyword. For instance:

```python
txt = "The best things in life are free!"
print("free" in txt)  # This will print True
```

You can also use the `not in` keyword to check if a word or character is NOT present in a string:

```python
txt = "The best things in life are free!"
print("expensive" not in txt)  # This will print True
```

These string operations allow you to manipulate and search for data within strings, making Python a versatile language for text processing.
