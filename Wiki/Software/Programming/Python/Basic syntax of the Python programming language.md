---
authors:
  - "0x4248"
tags:
  - "#Software"
  - Programming
  - Python
aliases:
  - python syntax
  - Python syntax
---
>[!note]+ Subsection
> This page is a subsection of [[Python]].

Python has a simple programming syntax that is easy to learn. Python uses indentation to define code blocks instead of curly brackets like other languages like [[C]] and [[C++]]. 

## Contents
- [Contents](#contents)
- [Comments](#comments)
- [Variables](#variables)
- [Data types](#data-types)
- [Operators](#operators)
- [Control flow](#control-flow)
    - [If statements](#if-statements)
    - [For loops](#for-loops)
    - [While loops](#while-loops)

## Comments
Python uses the `#` symbol to mark comments. This is ignored by python and is used to explain what the code is doing. 

```python
# This is a comment
```

Comments can be used along with functions

```python
print("Hello World") # This is a comment
```

They can be also indented with code

```python
num = 5
for i in num:
    # This is a comment
    print(i) # This is also a comment
```

## Variables
*For main wiki page see: **[[Creating and using variables in Python]]***

Variables are used to store data in a program. Think of it like putting items into a box. The box is the variable and the items are the data. 

```python
x = 123 # Set variable x to 123
```

Variables can be used in functions

```python
x = 123 # Set variable x to 123

print(x) # Print the value of x
```

Variables can be also changed after they have been set

```python
x = 123 # Set variable x to 123

print(x) # Print the value of x

x = 456 # Set variable x to 456

print(x) # Print the value of x
```

## Data types
*For main wiki page see: **[[Python data types]]**

Python has many different data types. These are used to store different types of data. These are:

- [[String]] - Used to store text
- [[Integer]] - Used to store whole numbers
- [[Float]] - Used to store decimal numbers
- [[Boolean]] - Used to store true or false values
- [[List]] - Used to store multiple values
- [[Tuple]] - Used to store multiple values
- [[Dictionary]] - Used to store multiple values

You can cast data types to other data types

```python
x = 123 # Set variable x to 123
x = str(123) # Turn the x variable from a integer to a string
```

## Operators
*For main wiki page see: **[[Operators in Python]]**

There a operators in python to do mathematical and logical operations. These are:

| Operator |         Description       |
| -------- | ------------------------- |
|   `+`    | Addition                  |
|   `-`    | Subtraction               |
|   `*`    | Multiplication            |
|   `/`    | Division                  |
|   `%`    | Modulus                   |
|   `**`   | Exponentiation            |
|   `//`   | Floor division            |
|   `==`   | Equal                     |
|   `!=`   | Not equal                 |
|   `>`    | Greater than              |
|   `<`    | Less than                 |
|   `>=`   | Greater than or equal to  |
|   `<=`   | Less than or equal to     |
|   `and`  | Logical and               |
|   `or`   | Logical or                |
|   `not`  | Logical not               |

These can be used in functions

```python
x = 5
y = 10
print(x + y) # Add x and y
```

## Control flow

*For main wiki page see: **[[Python control flow]]**

Control flow is used to control the flow of a program. This is done with if statements, for loops and while loops.

### If statements

If statements are used to check if a condition is true. If the condition is true then the code inside the if statement will run. If the condition is false then the code inside the if statement will not run. 

```python
x = 5
if x == 5: # Check if x is equal to 5
    print("x is equal to 5") # Print if x is equal to 5
```

If statements can also have else statements. If the condition is true then the code inside the if statement will run. If the condition is false then the code inside the else statement will run. 

```python
x = 5
if x == 5: # Check if x is equal to 5
    print("x is equal to 5") # Print if x is equal to 5
else:
    print("x is not equal to 5") # Print if x is not equal to 5
```

If statements can also have elif statements. If the condition is true then the code inside the if statement will run. If the condition is false then the code inside the elif statement will run. 

```python
x = 5
if x == 5: # Check if x is equal to 5
    print("x is equal to 5") # Print if x is equal to 5
elif x == 10:
    print("x is equal to 10") # Print if x is equal to 10
else:
    print("x is not equal to 5 or 10") # Print if x is not equal to 5 or 10
```

### For loops

For loops are used to loop through a list or a range of numbers. 

```python
for i in range(10): # Loop through the numbers 0 to 9
    print(i) # Print the number
```

For loops can also be used to loop through a list

```python
fruits = ["Apple", "Banana", "Orange"] # Create a list
for fruit in fruits: # Loop through the list
    print(fruit) # Print the item
```

### While loops

While loops are used to loop through a list or a range of numbers. 

```python
i = 0
while i < 10: # Loop while i is less than 10
    print(i) # Print the number
    i += 1 # Add 1 to i
```
