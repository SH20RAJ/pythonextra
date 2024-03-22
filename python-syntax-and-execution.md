# Python Syntax and Execution

As we explored in the previous section, Python syntax can be executed in a couple of ways. Let's dive into these execution methods:

#### Interactive Command Line

You can directly execute Python syntax in the interactive command line, which allows you to experiment with code on the fly. Just open your command prompt or terminal and type the Python code:

```python
>>> print("Hello, World!")
Hello, World!
```

#### Running Python Files

Alternatively, you can create Python files with the `.py` extension and run them from the command line like this:

```shell
C:\Users\Your Name>python myfile.py
```

### Python Indentation

In Python, unlike many other programming languages where indentation is mainly for readability, it plays a crucial role in code structure. Python uses indentation to define code blocks. Here's an example:

```python
if 5 > 2:
    print("Five is greater than two!")
```

Python will raise an error if you neglect proper indentation:

**Syntax Error:**

```python
if 5 > 2:
print("Five is greater than two!")
```

The number of spaces you use for indentation is flexible, but consistency within a code block is essential. Common practice is to use four spaces, but at least one space is required:

```python
if 5 > 2:
    print("Five is greater than two!") 
if 5 > 2:
        print("Five is greater than two!")
```

Mismatched indentation within the same block will lead to errors:

**Syntax Error:**

```python
if 5 > 2:
    print("Five is greater than two!")
        print("Five is greater than two!")
```

### Python Variables

In Python, variables are created when you assign a value to them. There is no need for explicit variable declaration. Here's how you create variables in Python:

```python
x = 5
y = "Hello, World!"
```

Python is smart enough to determine the type of the variable based on the assigned value. You'll explore variables further in the Python Variables chapter.

### Comments

Python allows you to add comments to your code for in-code documentation. Comments begin with a `#` symbol, and Python will consider everything after it on the same line as a comment:

```python
# This is a comment.
print("Hello, World!")
```

Now you're ready to put your Python knowledge into practice with exercises and further exploration.

### Test Yourself With Exercises

**Exercise:** Insert the missing part of the code below to output "Hello, World".

```python
("Hello, World")
```

Start the Exercise

Explore more about Python and get certified to master this versatile language.
