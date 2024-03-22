# Python Variables

Variables are fundamental elements in Python used for storing and managing data. They act as containers for data values and play a critical role in any Python program. In this section, we'll explore various aspects of Python variables, including their creation, casting, and data types.

### Creating Variables

In Python, you don't need to explicitly declare variables. A variable is created at the moment you first assign a value to it. Here's an example:

```python
x = 5
y = "John"
print(x)
print(y)
```

Variables can change their type after being set, as demonstrated in the following example:

```python
x = 4       # Initially, x is an integer
x = "Sally" # Now, x is a string
print(x)
```

### Casting

Casting allows you to specify the data type of a variable explicitly. Here's an example:

```python
x = str(3)    # x will be a string '3'
y = int(3)    # y will be an integer 3
z = float(3)  # z will be a float 3.0
```

### Get the Type

You can determine the data type of a variable using the `type()` function:

```python
x = 5
y = "John"
print(type(x))
print(type(y))
```

This function is useful for data type checks and debugging.

### Single or Double Quotes

String variables can be declared using either single or double quotes. Both forms are valid:

```python
x = "John"
# is equivalent to
x = 'John'
```

### Case-Sensitive

Variable names in Python are case-sensitive. This means that variables with different letter cases are considered distinct:

```python
a = 4
A = "Sally"
# 'A' does not overwrite 'a'
```

### Python - Global Variables

#### Global Variables

Variables created outside of a function, as shown in the examples above, are known as global variables. They can be accessed and modified by all parts of the code, both inside and outside of functions.

#### Example

```python
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()
```

If you create a variable with the same name inside a function, it will be treated as a local variable and can only be used within that function. The global variable with the same name will remain unaffected.

#### Example

```python
x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)
```

To create a global variable inside a function or to modify a global variable within a function, you can use the `global` keyword.

#### Example

```python
x = "awesome"

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)
```

Global variables can be used effectively but should be handled with caution to avoid unintentional modifications or confusion in larger codebases.

### Variable Naming

In Python, there are specific rules and best practices for naming variables. These guidelines ensure clarity and maintainability in your codebase.

| **Rules for Python Variables**                                                              |
| ------------------------------------------------------------------------------------------- |
| A variable name must start with a letter or the underscore character                        |
| A variable name cannot start with a number                                                  |
| A variable name can only contain alphanumeric characters and underscores (A-z, 0-9, and \_) |
| Variable names are case-sensitive (age, Age, and AGE are three different variables)         |
| A variable name cannot be any of the Python keywords.                                       |

### Multi Words Variable Names

Variable names with multiple words can sometimes be challenging to read. To enhance readability, various conventions can be used, such as Camel Case, Pascal Case, and Snake Case.

#### Camel Case

Each word, except the first, starts with a capital letter:

```python
myVariableName = "John"
```

#### Pascal Case

Each word starts with a capital letter:

```python
MyVariableName = "John"
```

#### Snake Case

Each word is separated by an underscore character:

```python
my_variable_name = "John"
```

### Python Variables - Assign Multiple Values

Python allows you to assign multiple values to multiple variables in one line.

#### Example

```python
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)
```

Ensure that the number of variables matches the number of values, or else you will encounter an error.

You can also assign the same value to multiple variables in one line:

#### Example

```python
x = y = z = "Orange"
print(x)
print(y)
print(z)
```

### Unpack a Collection

If you have a collection of values in a list, tuple, etc., Python enables you to extract the values into variables. This process is known as unpacking.

#### Example

```python
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)
```

### Python - Output Variables

The `print()` function in Python is often used to output variables.

#### Example

```python
x = "Python is awesome"
print(x)
```

In the `print()` function, you can output multiple variables separated by a comma.

#### Example

```python
x = "Python"
y = "is"
z = "awesome"
print(x, y, z)
```

You can also use

the `+` operator to output multiple variables.

#### Example

```python
x = "Python "
y = "is "
z = "awesome"
print(x + y + z)
```

Keep in mind that if you concatenate a string and a number using the `+` operator, Python will raise an error.

#### Example

```python
x = 5
y = "John"
print(x + y)
```

The best way to output multiple variables in the `print()` function is to separate them with commas, which even support different data types.

#### Example

```python
x = 5
y = "John"
print(x, y)
```

These concepts are crucial in working with variables effectively in Python, allowing you to store, manipulate, and display data as needed in your programs.Python Variables

Variables are fundamental elements in Python used for storing and managing data. They act as containers for data values and play a critical role in any Python program. In this section, we'll explore various aspects of Python variables, including their creation, casting, and data types.

### Creating Variables

In Python, you don't need to explicitly declare variables. A variable is created at the moment you first assign a value to it. Here's an example:

```python
x = 5
y = "John"
print(x)
print(y)
```

Variables can change their type after being set, as demonstrated in the following example:

```python
x = 4       # Initially, x is an integer
x = "Sally" # Now, x is a string
print(x)
```

### Casting

Casting allows you to specify the data type of a variable explicitly. Here's an example:

```python
x = str(3)    # x will be a string '3'
y = int(3)    # y will be an integer 3
z = float(3)  # z will be a float 3.0
```

### Get the Type

You can determine the data type of a variable using the `type()` function:

```python
x = 5
y = "John"
print(type(x))
print(type(y))
```

This function is useful for data type checks and debugging.

### Single or Double Quotes

String variables can be declared using either single or double quotes. Both forms are valid:

```python
x = "John"
# is equivalent to
x = 'John'
```

### Case-Sensitive

Variable names in Python are case-sensitive. This means that variables with different letter cases are considered distinct:

```python
a = 4
A = "Sally"
# 'A' does not overwrite 'a'
```

### Python - Global Variables

#### Global Variables

Variables created outside of a function, as shown in the examples above, are known as global variables. They can be accessed and modified by all parts of the code, both inside and outside of functions.

#### Example

```python
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()
```

If you create a variable with the same name inside a function, it will be treated as a local variable and can only be used within that function. The global variable with the same name will remain unaffected.

#### Example

```python
x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)
```

To create a global variable inside a function or to modify a global variable within a function, you can use the `global` keyword.

#### Example

```python
x = "awesome"

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)
```

Global variables can be used effectively but should be handled with caution to avoid unintentional modifications or confusion in larger codebases.

### Variable Naming

In Python, there are specific rules and best practices for naming variables. These guidelines ensure clarity and maintainability in your codebase.

| **Rules for Python Variables**                                                              |
| ------------------------------------------------------------------------------------------- |
| A variable name must start with a letter or the underscore character                        |
| A variable name cannot start with a number                                                  |
| A variable name can only contain alphanumeric characters and underscores (A-z, 0-9, and \_) |
| Variable names are case-sensitive (age, Age, and AGE are three different variables)         |
| A variable name cannot be any of the Python keywords.                                       |

### Multi Words Variable Names

Variable names with multiple words can sometimes be challenging to read. To enhance readability, various conventions can be used, such as Camel Case, Pascal Case, and Snake Case.

#### Camel Case

Each word, except the first, starts with a capital letter:

```python
myVariableName = "John"
```

#### Pascal Case

Each word starts with a capital letter:

```python
MyVariableName = "John"
```

#### Snake Case

Each word is separated by an underscore character:

```python
my_variable_name = "John"
```

### Python Variables - Assign Multiple Values

Python allows you to assign multiple values to multiple variables in one line.

#### Example

```python
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)
```

Ensure that the number of variables matches the number of values, or else you will encounter an error.

You can also assign the same value to multiple variables in one line:

#### Example

```python
x = y = z = "Orange"
print(x)
print(y)
print(z)
```

### Unpack a Collection

If you have a collection of values in a list, tuple, etc., Python enables you to extract the values into variables. This process is known as unpacking.

#### Example

```python
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)
```

### Python - Output Variables

The `print()` function in Python is often used to output variables.

#### Example

```python
x = "Python is awesome"
print(x)
```

In the `print()` function, you can output multiple variables separated by a comma.

#### Example

```python
x = "Python"
y = "is"
z = "awesome"
print(x, y, z)
```

You can also use

the `+` operator to output multiple variables.

#### Example

```python
x = "Python "
y = "is "
z = "awesome"
print(x + y + z)
```

Keep in mind that if you concatenate a string and a number using the `+` operator, Python will raise an error.

#### Example

```python
x = 5
y = "John"
print(x + y)
```

The best way to output multiple variables in the `print()` function is to separate them with commas, which even support different data types.

#### Example

```python
x = 5
y = "John"
print(x, y)
```

These concepts are crucial in working with variables effectively in Python, allowing you to store, manipulate, and display data as needed in your programs.
