# **Python**

[W3 Schools Python Introduction](https://www.w3schools.com/python/python_intro.asp "python introduction")

Prototyping on Python can be very quick

Python can be treated in a procedural way, an object-oriented way or a functional way.

* Python was designed for readability, and has some similarities to the English language with influence from mathematics.


The number of spaces is up to you as a programmer, the most common use is four, but it has to be at least one.

You have to use the same number of spaces in the same block of code, otherwise Python will give you an error:

Python has no command for declaring a variable.

- - -
## **Comments**

Comments can be placed at the end of a line

```python
    print("Hello, World!") #This is a comment
```

Python does not really have a syntax for multi line comments.

Not quite as intended, you can use a multiline string.

Since Python will ignore string literals that are not assigned to a variable, you can add a multiline string (triple quotes) in your code, and place your comment inside it:

```python
    """
    This is a comment
    written in
    more than just one line
    """
    print("Hello, World!")
```

As long as the string is not assigned to a variable, Python will read the code, but then ignore it, and you have made a multiline comment.

- - -

## **Variables**

Variables are containers for storing data values.

### Creating Variables

Python has no command for declaring a variable.

A variable is created the moment you first assign a value to it.

Variables do not need to be declared with any particular type, and can even change type after they have been set.

```python
    x = 4       # x is of type int
    x = "Sally" # x is now of type str
    print(x)
```

### Casting

If you want to specify the data type of a variable, this can be done with casting.

```python
    x = str(3)    # x will be '3'
    y = int(3)    # y will be 3
    z = float(3)  # z will be 3.0
```
### Get the Type

You can get the data type of a variable with the type() function.

```python
    x = 5
    y = "John"
    print(type(x))
    print(type(y))
```

String variables can be declared either by using single or double quotes:

Variable names are case-sensitive.

---

## **Python Variable Names**

### Variable Names

A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:
* A variable name must start with a letter or the underscore character
* A variable name cannot start with a number
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Variable names are case-sensitive (age, Age and AGE are three different variables)

### Multi Words Variable Names

Variable names with more than one word can be difficult to read.

There are several techniques you can use to make them more readable:

**Camel Case**

Each word, except the first, starts with a capital letter:

```python
    myVariableName = "John"
```

**Pascal Case**

Each word starts with a capital letter:

```python
    MyVariableName = "John"
```

**Snake Case**

Each word is separated by an underscore character:

```python
    my_variable_name = "John"
```

---

## **Python Variables - Assign Multiple Values**

### Many Values to Multiple Variables

Python allows you to assign values to multiple variables in one line:

```python
    x, y, z = "Orange", "Banana", "Cherry"
    print(x)
    print(y)
    print(z)
```

*Note: Make sure the number of variables matches the number of values, or else you will get an error.*

