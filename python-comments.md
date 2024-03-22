# Python Comments

Comments in Python serve several important purposes. They enhance code readability, provide explanations, and allow for code testing without execution. Let's explore how to create comments in Python.

### Creating a Comment

In Python, comments are denoted by the `#` symbol, and Python will disregard them during execution. You can use comments for various purposes:

| **Comment Type**      | **Usage**                                                                        |
| --------------------- | -------------------------------------------------------------------------------- |
| Explanation of Code   | Comments explain the purpose of your Python code, making it more understandable. |
| Enhancing Readability | Comments improve code readability by providing context and clarifications.       |
| Preventing Execution  | Comments temporarily disable code execution when testing or debugging.           |

#### Explanation of Code

Comments can be used to explain the purpose of your Python code, making it more understandable:

**Example:**

```python
# This is a comment
print("Hello, World!")
```

#### Enhancing Readability

Comments can also be employed to improve code readability by providing context and clarifications.

**Example:**

```python
print("Hello, World!")  # This is a comment
```

#### Preventing Execution

You can use comments to temporarily disable code execution when testing or debugging:

**Example:**

```python
# print("Hello, World!")
print("Cheers, Mate!")
```

### Multiline Comments

Python does not have a specific syntax for multiline comments like some other programming languages. However, you can achieve multiline comments in a couple of ways.

#### Multiple `#` Lines

To create multiline comments, you can use multiple `#` symbols, one on each line:

**Example:**

```python
# This is a comment
# written in
# more than just one line
print("Hello, World!")
```

#### Multiline String (Triple Quotes)

Alternatively, you can use a multiline string enclosed in triple quotes, even though it's not a traditional comment. Python will ignore string literals that aren't assigned to a variable, essentially treating them as comments:

**Example:**

```python
"""
This is a comment
written in
more than just one line
"""
print("Hello, World!")
```

As long as the multiline string is not assigned to a variable, Python will parse the code but ignore it, effectively creating a multiline comment.

Comments are a valuable tool for code documentation and communication, helping you and others understand the code's purpose and functionality.
