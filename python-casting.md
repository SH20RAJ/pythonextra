# Python Casting

In Python, you can specify a variable type using casting. Casting is the process of converting a variable from one data type to another. Python, being an object-oriented language, uses constructor functions for casting. These functions allow you to explicitly define the data type of a variable.

Here are some commonly used casting functions in Python:

1.  `int()`: Constructs an integer from an integer literal, a float literal (by removing all decimals), or a string literal (if the string represents a whole number).

    Example:

    ```python
    x = int(1)    # x will be 1
    y = int(2.8)  # y will be 2
    z = int("3")  # z will be 3
    ```
2.  `float()`: Constructs a float number from an integer literal, a float literal, or a string literal (if the string represents a float or an integer).

    Example:

    ```python
    x = float(1)      # x will be 1.0
    y = float(2.8)    # y will be 2.8
    z = float("3")    # z will be 3.0
    w = float("4.2")  # w will be 4.2
    ```
3.  `str()`: Constructs a string from a wide variety of data types, including strings, integer literals, and float literals.

    Example:

    ```python
    x = str("s1")   # x will be 's1'
    y = str(2)      # y will be '2'
    z = str(3.0)    # z will be '3.0'
    ```

Casting allows you to manipulate and transform data as needed, making Python a flexible and versatile language for handling different types of variables.

Whether you need to convert numbers to strings or vice versa, casting functions in Python help you work with data seamlessly.
