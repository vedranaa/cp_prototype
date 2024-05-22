---
layout: default
---

# Try assignments
**EXERCISE. DURATION: 60min**

## Instruction

Programs are usually written to solve a specific problem. Before you can use programs to solve the problems, you need to understand how programs work. We will therefore start with a *Try-it* exercise, where we ask you to look at some code and either predict what it will do, or try it line-by-line.

In this exercise, you don't need to write any code. Instead, you need to carefully copy the code which we have provided. We strongly encourage you to copy the code by typing it, rather than copying and pasting.

You will probably experience that some commands you input cause Python to return an error message. Learning to read and understand these error messages is an important part of learning to program. 

When beginner programmers experience an error message, they lack the experience to understand what *exactly* is causing an error, and they get stuck. It is important that you practice figuring out what is causing an error. 

<details>
  <summary>Hint</summary>
  If in doubt, see hint.
</details>

## Exercise

TODO: Fix indentation of exercises.

* Following lines of code contain an error. What is the error? Try running this code in Python and see what happens. 

```python
first_number = 5
second_number = 7
print(first_number + second_number)
third number = 9
print(first_number + third number)
```

* There is something wrong with the following lines of code. Try running this code and see what happens.  

```python
print = 'Hello, World!'
print('Hello to you too!')
```

Understanding error messages is an important part of learning to program. In the example above, the error message stated that 'str' object is not callable. *Being callable* is a property of python objects which can be called like functions. We call a function when we write parentheses `()` after objects name, with or without something between parentheses. For example we call `print` function by writing  `print('Hello, World!')`. A string cannot be called. You can test this by writing `'Hello world'(7)` or just `'Hello world'()`.  
  
Now, the actual problem in the code above is in the line before the line throwing the error. The line `print = 'Hello, World!'` assigns a string to the variable name `print`. This is a problem because `print` is a name of a built-in function in Python. After we use `print` as a name of the string variable, we cannot use it as a function anymore.  

*  TODO, move to lists exercises. Following lines of code contain an error. What is the error? Try running this code in Python and see what happens. 

```python
name = "This is my name"
list = "This is my list: trees, bushes, flowers."
sequence = "This is my sequence: 1, 2, 3."
```










