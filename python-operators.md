# Python Operators

Operators in Python are used to perform various operations on variables and values. Python provides a wide range of operators, categorized into different groups. Here, we will explore the main groups of Python operators.

### Arithmetic Operators

Arithmetic operators are used to perform mathematical operations on numeric values:

| Operator | Name           | Example  | Description                                                            |
| -------- | -------------- | -------- | ---------------------------------------------------------------------- |
| +        | Addition       | x + y    | Adds two values                                                        |
| -        | Subtraction    | x - y    | Subtracts the second value from the first                              |
| \*       | Multiplication | x \* y   | Multiplies two values                                                  |
| /        | Division       | x / y    | Divides the first value by the second                                  |
| %        | Modulus        | x % y    | Returns the remainder of the division of the first value by the second |
| \*\*     | Exponentiation | x \*\* y | Raises the first value to the power of the second                      |
| //       | Floor Division | x // y   | Returns the floor of the division of the first value by the second     |

### Assignment Operators

Assignment operators are used to assign values to variables:

| Operator | Example   | Same As      |
| -------- | --------- | ------------ |
| =        | x = 5     | x = 5        |
| +=       | x += 3    | x = x + 3    |
| -=       | x -= 3    | x = x - 3    |
| \*=      | x \*= 3   | x = x \* 3   |
| /=       | x /= 3    | x = x / 3    |
| %=       | x %= 3    | x = x % 3    |
| //=      | x //= 3   | x = x // 3   |
| \*\*=    | x \*\*= 3 | x = x \*\* 3 |
| &=       | x &= 3    | x = x & 3    |
| \|=      | x \|= 3   | x = x        |
| ^=       | x ^= 3    | x = x ^ 3    |
| >>=      | x >>= 3   | x = x >> 3   |
| <<=      | x <<= 3   | x = x << 3   |

### Comparison Operators

Comparison operators are used to compare two values:

| Operator | Name             | Example | Description                                                              |
| -------- | ---------------- | ------- | ------------------------------------------------------------------------ |
| ==       | Equal            | x == y  | Returns `True` if both values are equal                                  |
| !=       | Not Equal        | x != y  | Returns `True` if the values are not equal                               |
| >        | Greater Than     | x > y   | Returns `True` if the first value is greater than the second             |
| <        | Less Than        | x < y   | Returns `True` if the first value is less than the second                |
| >=       | Greater or Equal | x >= y  | Returns `True` if the first value is greater than or equal to the second |
| <=       | Less or Equal    | x <= y  | Returns `True` if the first value is less than or equal to the second    |

### Logical Operators

Logical operators are used to combine or modify conditional statements:

| Operator | Description                                                  | Example               |
| -------- | ------------------------------------------------------------ | --------------------- |
| and      | Returns `True` if both statements are `True`                 | x < 5 and x < 10      |
| or       | Returns `True` if at least one of the statements is `True`   | x < 5 or x < 4        |
| not      | Reverses the result, returns `False` if the result is `True` | not(x < 5 and x < 10) |

### Identity Operators

Identity operators are used to compare objects' memory locations:

| Operator | Description                                            | Example    |
| -------- | ------------------------------------------------------ | ---------- |
| is       | Returns `True` if both variables are the same object   | x is y     |
| is not   | Returns `True` if both variables are different objects | x is not y |

### Membership Operators

Membership operators are used to test if a sequence is present in an object:

| Operator | Description                                                                        | Example    |
| -------- | ---------------------------------------------------------------------------------- | ---------- |
| in       | Returns `True` if a sequence with the specified value is present in the object     | x in y     |
| not in   | Returns `True` if a sequence with the specified value is not present in the object | x not in y |

### Bitwise Operators

Bitwise operators are used to compare binary numbers:

| Operator | Name | Description                                     |
| -------- | ---- | ----------------------------------------------- |
| &        | AND  | Sets each bit to 1 if both bits are 1           |
| \|       | OR   | Sets each bit to 1 if one of two bits is 1      |
| ^        | XOR  | Sets each bit to 1 if only one of two bits is 1 |
| \~       | NOT  | Inverts all the bits                            |
| <<       |      |                                                 |

```
   | Left Shift    | Shifts left by pushing zeros in from the right |
```

\| >> | Right Shift | Shifts right by pushing copies of the leftmost bit in from the left |

### Operator Precedence

Operator precedence describes the order in which operations are performed. Operators with higher precedence are evaluated first. In case of operators with the same precedence, the expression is evaluated from left to right. Parentheses have the highest precedence.

Some of the key operator precedences are:

1. Parentheses `()`
2. Exponentiation `**`
3. Unary plus `+`, unary minus `-`, bitwise NOT `~`
4. Multiplication `*`, division `/`, floor division `//`, modulus `%`
5. Addition `+`, subtraction `-`
6. Bitwise left shift `<<`, bitwise right shift `>>`
7. Bitwise AND `&`
8. Bitwise XOR `^`
9. Bitwise OR `|`
10. Comparisons, identity, and membership operators
11. Logical NOT `not`
12. Logical AND `and`
13. Logical OR `or`

Understanding operator precedence is crucial for writing correct and efficient Python code.

Remember that you can always use parentheses to explicitly control the order of evaluation in complex expressions.

```python
result = (6 + 3) - (6 + 3)  # Evaluate the inner parentheses first
```

### Practice

Now, try the following exercise:

**Exercise:** Multiply 10 by 5 and print the result.

```python
print(10 * 5)
```

Operators play a fundamental role in Python, allowing you to perform various operations on values, make decisions, and control the flow of your programs. Understanding how to use operators and their precedence is essential for effective programming in Python.
