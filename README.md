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



## Datatypes:

Python is a dynamically-typed language, which means that you don't need to declare the data type of a variable explicitly. Python infers the data type based on the value assigned to the variable. Python supports a wide range of data types, including:

1.    Integers	 These represent numbers in an unlimited range. This is only limited by a machine’s      
 memory.
2.    Booleans: Evaluate to ‘True or False’, 1 or 0 respectively.
3.    Floating point numbers: Floating-point numbers represent double-precision numbers.
4.    Complex numbers: Complex numbers represent numbers as a pair of double-precision numbers.
5.    Strings: A sequence of Unicode characters e.g. a word or a sentence that can be             manipulated.

## Manipulating booleans

```
 Syntax	 Description
 a or b	 
If either a or b is True, then the result will be True. 

If both a and b are False then the result will be False.
 a and b	 If a and b are True, then the result will be True. Otherwise, the result will be False.
 not a	 If a is True, False is returned. If a is False, True is returned.

```
# WEEK 3 day 1 - 5
## Here are all of the methods of list objects:  

### list.append(x)
: Adds an item x to the end of the list.

### list.extend(iterable)
: Extends the list by appending all the items from the iterable.

### list.insert(i, x)
: Inserts an item x at the given position i. The first argument is the index of the element before which to insert.

### list.remove(x)
: Removes the first item in the list whose value is equal to x. Raises a ValueError if there is no such item.

### list.pop([i])
: Removes and returns the item at the given position i in the list. If no index is specified, a.pop() removes and returns the last item.

### list.clear()
: Removes all items from the list.

### list.index(x[, start[, end]])
: Returns the zero-based index of the first item in the list whose value is equal to x. Optional start and end arguments limit the search to a specific subsequence.

### list.count(x)
: Returns the number of times x appears in the list.

### list.sort(key=None, reverse=False)
: Sorts the items of the list in place. Optional arguments key and reverse can be used for sort customization.

### list.reverse()
: Reverses the elements of the list in place.

### list.copy()
: Returns a shallow copy of the list, equivalent to a[:].

  ##  Here are code examples for each of the listed list methods in Python:

  ```
    # Initialize a sample list for demonstration
my_list = [1, 2, 3, 4]

# list.append(x): Adds an item to the end of the list.
my_list.append(5)

# list.extend(iterable): Extends the list by appending all items from the iterable.
my_list.extend([6, 7])

# list.insert(i, x): Inserts an item x at a given position.
my_list.insert(1, 10)

# list.remove(x): Removes the first item equal to x.
my_list.remove(3)

# list.pop([i]): Removes and returns an item at the given position.
popped_item = my_list.pop(2)

# list.clear(): Removes all items from the list.
my_list.clear()

# Reinitialize the list for further examples
my_list = [3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5]

# list.index(x[, start[, end]]): Find the first index of an item x.
index = my_list.index(5)

# list.count(x): Count the number of occurrences of x in the list.
count = my_list.count(5)

# list.sort(key=None, reverse=False): Sort the list.
my_list.sort()

# list.reverse(): Reverse the list in place.
my_list.reverse()

# list.copy(): Create a shallow copy of the list.
copy_of_list = my_list.copy()

# Print the results
print("After append:", my_list)
print("After extend:", my_list)
print("After insert:", my_list)
print("After remove:", my_list)
print("Popped item:", popped_item)
print("After clear:", my_list)
print("Index of 5:", index)
print("Count of 5:", count)
print("Sorted list:", my_list)
print("Reversed list:", my_list)
print("Shallow copy:", copy_of_list)


  ```
# Using Lists as a Stack (Last-In, First-Out):

Lists can work like a stack, where the last item added is the first one retrieved (Last-In, First-Out or LIFO).
To add an item to the top of the stack, use the append() method.
To retrieve an item from the top of the stack, use pop() without specifying an index.

## Example

```
stack = [3, 4, 5]
stack.append(6)
stack.append(7)
stack.pop()  # Retrieves and removes the top item.

```
## Using Lists as a Queue (First-In, First-Out):

Lists can also mimic a queue, where the first item added is the first to be retrieved (First-In, First-Out or FIFO).
However, lists are not efficient for this because adding or removing items from the beginning requires shifting other elements.
For efficient queue operations, use collections.deque which allows fast appends and pops from both ends.

## Example using collections.deque:

```
from collections import deque
queue = deque(["Eric", "John", "Michael"])
queue.append("Terry")  # Adding an item to the end.
queue.popleft()  # Removing the first item efficiently.

```
In summary, lists can serve as both stacks and queues, but for efficient queue operations, it's recommended to use collections.deque. Stacks follow Last-In, First-Out (LIFO) while queues follow First-In, First-Out (FIFO).

-------------------------------------------------------------------------------------------------

# LIST COMPREHENSIONS

List comprehensions are a concise way to create lists in Python. They are often used to generate new lists by applying operations to each element of an existing sequence or iterable. List comprehensions can also be used to filter elements based on certain conditions. Here's an informative breakdown of how list comprehensions work:

## Creatin a list of squares:
You can creat a list of square using a 'for' loop:
```
    squares = []
    for x in range(10):
    squares.append(x**2)

```

Alternatively, use a list comprehension for a more concise and readable approach:
```
squares = [x**2 for x in range(10)]
```

2.    List Comprehension Structure:

A list comprehension consists of square brackets [...] containing an expression followed by one or more for or if clauses.
The result is a new list generated by evaluating the expression in the context of the following for and if clauses.

3.    Combining Elements from Two Lists:
You can use list comprehensions to combine elements from two lists based on certain conditions:

```
[(x, y) for x in [1, 2, 3] for y in [3, 1, 4] if x != y]

```

4.    Order of for and if Statements:

Note that the order of for and if statements in a list comprehension matches the structure of equivalent for loops.
5.    Handling Tuples in Expressions:

If the expression is a tuple (e.g., (x, y)), it must be parenthesized.

6.    Examples of List Comprehensions:

-    Creating a new list with doubled values, filtering out negative numbers, applying a         function to elements, and stripping whitespace from strings.
-    Creating a list of 2-tuples (number, square) and flattening a nested list.
-    Complex expressions and nested functions can be used in list comprehensions.

7.    Error Handling:

If the tuple is not parenthesized, it can result in a syntax error.

8.    Advanced Example:

Using the math module to round the value of pi to different decimal places for a list.
In 

summary, list comprehensions provide a concise and expressive way to create lists, apply operations, and filter elements from existing sequences or iterables. They are a powerful feature for Python programmers and can simplify code while making it more readable.


## Nested List Comprehensions:

-    List comprehensions can be nested, allowing for more complex transformations and operations.
## Example: Transposing a Matrix:

-    Consider a 3x4 matrix represented as a list of lists.
-    The goal is to transpose the matrix, switching rows and columns.

## List Comprehension Approach:

-    A nested list comprehension can achieve matrix transposition elegantly:

```
[[row[i] for row in matrix] for i in range(4)]

```
## Equivalent for Loop Approach:

-    The nested list comprehension is equivalent to a series of for loops:
  
  ```
transposed = []
for i in range(4):
    transposed.append([row[i] for row in matrix])
```
## Further Expanded Approach:

-    The equivalent for loop approach can be broken down into more detail:

```
transposed = []
for i in range(4):
    transposed_row = []
    for row in matrix:
        transposed_row.append(row[i])
    transposed.append(transposed_row)
```

## Using Built-In Function zip():

-    In real-world scenarios, built-in functions are preferred for readability and efficiency.
-    The zip() function transposes the matrix efficiently:

```
list(zip(*matrix))
```
## The del statement / Tuples and Sequences


# WEEK 4: INHERITANCE

Inheritance in Python is a fundamental object-oriented programming (OOP) concept that allows a new class (the derived or child class) to inherit attributes and behaviors from an existing class (the base or parent class). This promotes code reuse and establishes a hierarchy of classes, enabling the creation of more specialized classes based on existing ones.

## Key Points about Inheritance in Python:
1.    Class Definition:

-    Inheritance is implemented using a syntax that defines a derived class by specifying its base class.
-    Syntax: class DerivedClassName(BaseClassName):

```   

class BaseClassName:
    def base_method(self):
        print("Base class method")


class DerivedClassName(BaseClassName):
    def derived_method(self):
        print("Derived class method")


# Instantiating the derived class
obj = DerivedClassName()

```

2.    Attribute and Method Access:

-    A derived class inherits attributes and methods from its base class.
Attributes not found in the derived class are searched in the base class, following a specific order known as the Method Resolution Order (MRO).

```
# Accessing attributes and methods from the base class
obj.base_method()       # Output: Base class method
obj.derived_method()    # Output: Derived class method
```

3.    Instantiation:

-    Instances of the derived class can be created, and they inherit the properties of the base class.
Syntax: obj = DerivedClassName()

```
class BaseClassName:
    def overridden_method(self):
        print("Base class method")


class DerivedClassName(BaseClassName):
    def overridden_method(self):
        print("Derived class method (overridden)")


# Creating an instance of the derived class
obj = DerivedClassName()

# Calling the overridden method
obj.overridden_method()    # Output: Derived class method (overridden)
```

4.    Method Overriding:

-    The derived class can provide its own implementation of a method, effectively overriding the method inherited from the base class.
-    This allows customization of behavior in the derived class.
  
```
class BaseClassName:
    def overridden_method(self):
        print("Base class method")


class DerivedClassName(BaseClassName):
    def overridden_method(self):
        print("Derived class method (overridden)")


# Creating an instance of the derived class
obj = DerivedClassName()

# Calling the overridden method
obj.overridden_method()    # Output: Derived class method (overridden)
```

5.    Super Function:

-    The super() function is commonly used to call methods from the base class. It ensures that the correct method in the inheritance hierarchy is called.

```
class BaseClassName:
    def some_method(self):
        print("Base class method")


class DerivedClassName(BaseClassName):
    def some_method(self):
        super().some_method()  # Calling the base class method using super()
        print("Derived class method")


# Creating an instance of the derived class
obj = DerivedClassName()

# Calling the method in the derived class
obj.some_method()
```

6.    Dynamic Ordering (MRO):
-    Python uses a dynamic ordering mechanism known as Method Resolution Order (MRO) to determine the sequence in which base classes are searched for attributes and methods.
-    MRO resolves complexities in multiple inheritance scenarios and ensures a consistent order.
```
class A:
    def method(self):
        print("Method in class A")


class B(A):
    def method(self):
        print("Method in class B")


class C(A):
    def method(self):
        print("Method in class C")


class D(B, C):
    pass


# Creating an instance of the derived class
obj = D()

# Calling the method, MRO is used to determine the order
obj.method()  # Output: Method in class B
```
7.    Multiple Inheritance:

-    Python supports multiple inheritance, allowing a class to inherit from more than one base class.
-    The order of base classes matters, as it influences the MRO.
```
class Base1:
    def method(self):
        print("Method in Base1")


class Base2:
    def method(self):
        print("Method in Base2")


class Derived(Base1, Base2):
    pass


# Creating an instance of the derived class
obj = Derived()

# Calling the method, order of base classes matters
obj.method()  # Output: Method in Base1
```
8.    Built-in Functions:

-    The isinstance() function checks if an object belongs to a particular class or its derived classes.
The issubclass() function checks if a class is a subclass of another class.
```
# isinstance() function
print(isinstance(obj, Derived))     # Output: True
print(isinstance(obj, Base1))       # Output: True

# issubclass() function
print(issubclass(Derived, Base1))   # Output: True
print(issubclass(Derived, Base2))   # Output: True
```
9.    Use Cases:

-    Inheritance is beneficial for code organization, promoting reusability and extensibility.
-    It facilitates the creation of specialized classes without duplicating code.
```
# Code organization and reusability
class Animal:
    def speak(self):
        pass


class Dog(Animal):
    def speak(self):
        print("Woof!")


class Cat(Animal):
    def speak(self):
        print("Meow!")
```
10.    Dynamic Nature:

-    Inheritance in Python is dynamic, allowing modifications and extensions to classes during runtime.
-    This dynamic nature contributes to the flexibility and adaptability of Python programs.
In summary, inheritance in Python is a powerful mechanism that fosters code reuse, extensibility, and the creation of well-organized class hierarchies. It is a cornerstone of object-oriented programming in Python, enabling the construction of complex and modular software systems.

```
# Adding new method dynamically to a class
class MyClass:
    def existing_method(self):
        print("Existing method")


# Creating an instance
obj = MyClass()

# Adding a new method dynamically
def new_method(self):
    print("Dynamically added method")

MyClass.new_method = new_method

# Calling the dynamically added method
obj.new_method()  # Output: Dynamically added method
```
## In summary, the provided examples demonstrate how to transpose a matrix using both nested list comprehensions and the 'zip()' function. While list comprehensions are a powerful tool, built-in functions like 'zip()' are often preferred for more complex operations due to their readability and efficiency.



