# Variables and Simple Data Types

## Variables

Variables are used to store data that can be referenced and manipulated in a program. In Python, you can create a variable by simply assigning a value to it using the equals sign (`=`).

```python
message = "Hello, Python world!"
print(message)
```

### Naming and usage conventions
There are some rules and guidelines to be adhered tpo when using variables in Python:

- Variable names can contain only letters, numbers, and underscores (`_`). They can start with a letter or an underscore, but not with a number. An example of a valid variable name is `my_variable1` but not `1st_variable`.
- Spaces are not allowed in variable names, but underscores can be used to separate words (e.g., `my_variable`).
- Avoid using Python keywords and function names as variable names.
- Variable names should be short but descriptive. An example is `age` instead of `a`, `name` instead of `n`, and `total_price` instead of `tp`.
- Be careful when using the lowercase letter `l`, uppercase letter `O`, and the number `0` in variable names, as they can be easily confused with each other.

### Avoiding name errors when using variables

```python
message = "Hello, Python world!"
print(mesage)
```

In the code above, there is a typo in the variable name `mesage`, which will result in an error. However, the interpretor provides a traceback when a program cannot run successfully. A `traceback` is a record of where the interpretor ran into trouble when trying to execute your code.

```
Traceback (most recent call last):
    File "script.py", line 2, in <module>
        print(mesage)
NameError: name 'mesage' is not defined
```
The output indicates that the error occurred on line 2 of the script, and it specifies that the name `mesage` is not defined. This helps you identify and fix the typo in the variable name.

### Variables are labels

Variables are often described as boxes you can store values in. However, a more accurate description is that variables are labels that refer to values stored in memory. When you assign a value to a variable, you are creating a label that points to that value.

```python
message = "Hello, Python world!"
print(message)
```

In the code above, the variable `message` is a label that refers to the string value `"Hello, Python world!"`. When you print the variable, Python looks up the label and retrieves the value it points to.

Variables can be reassigned to refer to different values. For example:

```python
message = "Hello, Python world!"
print(message)
message = "Hello, Universe!"
print(message)
```

In the above program, the variable `message` is first assigned to the string `"Hello, Python world!"`. Later, it is reassigned to the string `"Hello, Universe!"`. When you print the variable after each assignment, it outputs the current value it refers to.

## Strings

A string is a sequence of characters. Anything inside quotes is considered a string in Python, and you can use either single quotes (`'`) or double quotes (`"`).

```python
"This is a string."
'This is also a string.'
```

This flexibility allows us to use quotes and apostrophes within strings.

```python
'I told my friend, "Python is my favorite programming language!"'
"The language 'Python' is named after Monty Python, not the snake."
"One of Python's strengths is its diverse and supportive community."
"I come from a village known as 'Mworoga'."
```

### Changing Case in a String with Methods
