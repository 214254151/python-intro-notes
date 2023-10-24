# python-intro-notes

In Python, variables are used to store and manipulate data. 
Python is a dynamically typed language, which means you don't need to declare the data type of a variable explicitly. 
Here's an introduction to variables in Python:

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

