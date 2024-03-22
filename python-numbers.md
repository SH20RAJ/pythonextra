# Python Numbers

In Python, numbers are a fundamental concept and play a crucial role in various computational tasks. Python offers three primary numeric types:

1. **int (Integer)**: Integers are whole numbers, either positive or negative, without any decimal points. They can be of unlimited length, allowing for precise numerical representation.

```python
x = 1
y = 35656222554887711
z = -3255522
```

2. **float (Floating-Point)**: Floating-point numbers are real numbers that can include one or more decimals. They can be positive or negative and provide a means for representing non-integer values.

```python
x = 1.10
y = 1.0
z = -35.59
```

Floating-point numbers can also be used to represent scientific notation with an "e" to indicate the power of 10.

```python
x = 35e3
y = 12E4
z = -87.7e100
```

3. **complex**: Complex numbers are represented with a "j" as the imaginary part. They are used to work with complex mathematical operations and are essential in various scientific and engineering applications.

```python
x = 3+5j
y = 5j
z = -5j
```

You can verify the type of any object in Python using the `type()` function:

```python
print(type(x))
print(type(y))
print(type(z))
```

### Type Conversion

Python allows you to convert between different numeric types using the following methods:

* `int()`: Converts to an integer.
* `float()`: Converts to a floating-point number.
* `complex()`: Converts to a complex number.

For example:

```python
x = 1    # int
y = 2.8  # float
z = 1j   # complex

a = float(x)  # Convert from int to float
b = int(y)    # Convert from float to int
c = complex(x)  # Convert from int to complex

print(a)
print(b)
print(c)
```

Please note that you cannot directly convert complex numbers into other numeric types.

### Random Numbers

Python provides a built-in module called `random` for generating random numbers. While Python doesn't have a `random()` function, you can use the `random` module to create random numbers. Here's an example of generating a random number between 1 and 9:

```python
import random

print(random.randrange(1, 10))
```

Explore the `random` module further in our Random Module Reference to understand more about generating random numbers and using randomization in Python.

Understanding and working with Python numbers is vital for a wide range of applications, from scientific calculations to data analysis and beyond.
