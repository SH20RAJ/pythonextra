# Python - Format Strings

In Python, you can format strings to include variables or values using the `format()` method. This allows you to create dynamic strings with placeholders that are replaced by specific values at runtime.

### Basic String Formatting

To use the `format()` method, define a string with placeholder braces `{}` where you want to insert values, and then call `format()` on that string, passing the values as arguments.

#### Example

```python
age = 36
txt = "My name is John, and I am {}"
print(txt.format(age))
```

In this example, `{}` serves as a placeholder for the `age` variable. The `format()` method replaces the placeholder with the value of `age`.

### Multiple Placeholders

You can use multiple placeholders within the same string and pass multiple values to the `format()` method.

#### Example

```python
quantity = 3
itemno = 567
price = 49.95
myorder = "I want {} pieces of item {} for {} dollars."
print(myorder.format(quantity, itemno, price))
```

In this example, three placeholders are used to format the `myorder` string, and three values are passed to `format()` to replace these placeholders.

### Index Numbers

If you want to ensure that the arguments are placed in the correct placeholders, you can use index numbers within the placeholders.

#### Example

```python
quantity = 3
itemno = 567
price = 49.95
myorder = "I want to pay {2} dollars for {0} pieces of item {1}."
print(myorder.format(quantity, itemno, price))
```

By specifying index numbers within the placeholders (e.g., `{2}`), you can control the order of argument insertion.

String formatting with `format()` is a powerful way to create dynamic and flexible strings that include variables, numbers, and other values.
