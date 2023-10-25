# python-intro-notes

In Python, variables are used to store and manipulate data. 
Python is a dynamically typed language, which means you don't need to declare the data type of a variable explicitly. 
Here's an introduction to variables in Python:

## Comments

In Python, comments are used to include explanatory notes or remarks within your code that are not executed by the Python interpreter. Comments are useful for documentation, clarifying code, and making it more understandable to both yourself and other developers. There are two common ways to add comments in Python:

### Single-Line Comments: 
Single-line comments are used to add a brief comment on a single line. They start with a # character and continue until the end of the line.

```
# This is a single-line comment
variable = 42  # You can also add comments at the end of a line of code

```

## Multi-Line Comments 
(Docstrings): For longer comments, especially when documenting functions, classes, or modules, multi-line comments are often used as docstrings. A docstring is enclosed in triple-quotes (single or double) and can span multiple lines.

```
"""
This is a multi-line comment or a docstring.
It can be used for documentation purposes.
For example, documenting a function.
"""

def my_function():
    """This is a docstring for a function."""
    # Function code here

```

### WHat are variables?
Variables are a temporary storage space in a computer’s memory. When a variable’s value changes the program’s current state also changes. A variable acts as a container to hold a different number of data items or values. 

### Every variable is created with an initial value. A variable can be in three states:

Variable creation (Declaration)
Variable assignment (Initialization)
Variable changed (Execution)


### Variable Declaration:

### Here are a few examples of valid variable names:

c
ref_number
admin
aVeryLongName
##Here are a few examples of invalid variable names:

True
$name
12Graph

In Python, you declare a variable simply by assigning a value to it. There's no need to specify the data type. For example:

```
my_variable = 42
```
In this example, my_variable is declared and assigned the integer value 42.

### Variable Names:
Variable names in Python should follow these rules:

They must start with a letter (a-z, A-Z) or an underscore (_).
The rest of the name can contain letters, digits, and underscores.
Variable names are case-sensitive, meaning my_variable and My_Variable are considered different variables.

### Data Types:
Python supports several data types, including:

int: Integer data type (e.g., 42).
float: Floating-point data type (e.g., 3.14).
str: String data type (e.g., "Hello, World!").
bool: Boolean data type (True or False).
Reassigning Variables:
You can change the value of a variable simply by assigning it a new value. For example:

```
my_variable = 42
my_variable = "Hello, World!"
```
In this case, my_variable first holds an integer and then a string.

### Dynamic Typing:
Python is dynamically typed, meaning a variable can change its type during the program's execution. For instance, you can initially assign an integer to a variable and later assign a string to it, and Python will handle the change without any issues.

### Using Variables:
You can use variables in various ways, including performing calculations, string operations, and passing them as arguments to functions. Here's an example of performing a calculation with variables:

```
x = 5
y = 10
result = x + y
print(result)  # This would print 15
```
### Variable Scope:
Variables in Python have a scope, which determines where in the code they can be accessed. Global variables are accessible throughout the entire program, while local variables are confined to a specific function or code block.

### Best Practices:

Use descriptive variable names to make your code more readable.
Follow naming conventions, like using lowercase letters and underscores for variable names (e.g., my_variable).

### Casting

In Python, casting refers to the process of converting one data type into another. 
This is also known as type conversion or typecasting.

Here are some of the most commonly used casting functions in Python:

1.    int(): This function is used to convert a value to an integer.
```
x = int(3.14)  # x will be 3
```

2.    float(): Use this function to convert a value to a floating-point number.
```
y = float("3.14")  # y will be 3.14
```
3.    srt(): It comverts a value to a string.
```
s = str(42)  # s will be the string "42"
```
4.    bool(): This function converts a value to a boolean.
```
b = bool(0)  # b will be False
```
5.   list(): Converts a sequence (e.g., a string or tuple) into a list. 
```
my_list = list("hello")  # my_list will be ['h', 'e', 'l', 'l', 'o']
```
6.    ord() and chr(): These functions are used to convert characters to their Unicode code points
```
and vice versa.
code = ord('A')  # code will be 65
char = chr(65)   # char will be 'A'
```
#### In Python, some operations might not work as intended if you mix incompatible data types, so typecasting can be a useful tool to manage data effectively.
