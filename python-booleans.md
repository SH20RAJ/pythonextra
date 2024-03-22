# Python Booleans



Booleans are a fundamental data type in Python that represent one of two values: `True` or `False`. They are primarily used for logical operations, conditional statements, and control flow in Python.

### Boolean Values

In Python, you often need to determine whether an expression is `True` or `False`. You can evaluate expressions, and Python will return either `True` or `False` as the result.

#### Comparing Values

When you compare two values, Python evaluates the expression and returns the corresponding Boolean value:

```python
print(10 > 9)  # True
print(10 == 9) # False
print(10 < 9)  # False
```

#### Using Booleans in `if` Statements

In conditional statements, Python evaluates conditions to determine whether they are `True` or `False`. Based on the result, it executes the appropriate block of code:

```python
a = 200
b = 33

if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a")
```

#### Evaluating Values and Variables

The `bool()` function allows you to evaluate any value or variable and return `True` or `False`:

```python
print(bool("Hello"))  # True
print(bool(15))       # True

x = "Hello"
y = 15
print(bool(x))         # True
print(bool(y))         # True
```

### Most Values Are `True`

In Python, most values are considered `True` if they contain some content. For example:

* Any non-empty string is `True`.
* Any number is `True` unless it's 0.
* Any non-empty list, tuple, set, or dictionary is `True`.

```python
print(bool("abc"))                         # True
print(bool(123))                           # True
print(bool(["apple", "cherry", "banana"])) # True
```

### Some Values Are `False`

There are very few values that evaluate to `False`. These include:

* Empty values like `()`, `[]`, `""`, `{}`, and `0`.
* The special value `None`.
* The value `False`.

```python
print(bool(False))   # False
print(bool(None))    # False
print(bool(0))       # False
print(bool(""))      # False
print(bool(()))      # False
print(bool([]))      # False
print(bool({}))      # False
```

Additionally, objects created from classes with a `__len__` function that returns 0 or `False` will evaluate to `False`.

```python
class myclass:
  def __len__(self):
    return 0

myobj = myclass()
print(bool(myobj))  # False
```

### Functions Can Return a Boolean

You can create functions that return Boolean values. These functions can be used to execute code based on the returned value:

```python
def myFunction():
  return True

print(myFunction())  # True
```

You can use the result of a function in conditional statements:

```python
def myFunction():
  return True

if myFunction():
  print("YES!")
else:
  print("NO!")
```

Python also provides built-in functions that return Boolean values. For example, the `isinstance()` function can be used to check if an object is of a specific data type:

```python
x = 200
print(isinstance(x, int))  # True
```

Booleans are a fundamental part of Python, enabling you to make decisions and control the flow of your programs based on conditions and logic.
