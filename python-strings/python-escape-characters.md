# Python - Escape Characters

In Python, you can use escape characters to insert special characters or symbols into strings. Escape characters are preceded by a backslash (`\`) and are used to represent characters that are either illegal or have special meanings within strings.

### Common Escape Characters

Here are some common escape characters used in Python:

* `\'`: Represents a single quote.
* `\\`: Represents a backslash.
* : Represents a new line.
* : Represents a carriage return.
* : Represents a tab.
* `\b`: Represents a backspace.
* `\f`: Represents a form feed.
* `\ooo`: Represents an octal value (replace "ooo" with the octal value).
* `\xhh`: Represents a hex value (replace "hh" with the hex value).

#### Example

```python
txt = "This is a single quote: \' and this is a new line:\nSee the tab\tand backslash: \\."
print(txt)
```

In this example, escape characters are used to include a single quote, a new line, a tab, and a backslash within the string.

Escape characters are essential when you need to include special characters or formatting within your strings. They allow you to include characters that might otherwise be interpreted differently.
