---
layout: default
---

# Variables and assignments
**STATUS: DRAFT. PLAN: TEXT AND VIDEOS. DURATION: 60min**


**Ressources** The content of this week is corresponds roughly to the first two chapters of the book [Think Python](https://allendowney.github.io/ThinkPython/index.html), Chapter 1 [Programming as a way of thinking](https://allendowney.github.io/ThinkPython/chap01.html) and Chapter 2 [Variables and statements](https://allendowney.github.io/ThinkPython/chap02.html), but we also include a few elements from Chapter 5. In the text, we will link to the relevant passages of this book, which you can read for more details. We also link to relevant pages in [w3schools Python tutorial](https://www.w3schools.com/python/).

**TODO: DECIDE WHETHER TO FOLLOW THE BOOK MORE CLOSELY.**


## A program

A program is a text with a sequence of instructions given to a computer. The computer executes the instructions one line at a time, starting from the top. You have already seen a simple program in the previous week, containing a command to print some text.

```python
print("Hello, world!")
```
Here, `print` is a command to the computer to print the text "Hello, world!" on the screen. We will later see that `print` is an example of a programming *function*. For now it is enough to know that it will print whatever it is given on the screen. 


Programs are written for the computer to perform some task. But programs are also read by humans, and to assist humans in understanding the program, we use [*comments*](https://www.w3schools.com/python/python_comments.asp), also covered [here](https://allendowney.github.io/ThinkPython/chap02.html#comments). Comments are text in the program that is ignored by the computer. In Python, comments start with the `#` symbol. 

```python
# This is a comment
print("Hello, world!") # This is also a comment
```



## Assignment

[*Variables*](https://allendowney.github.io/ThinkPython/chap02.html#variables) are used to store values. A variable has a *name*, and a *value* of a certain *type*. The name is used in the program text to access the variable.  The value is the actual content of the variable snd the type says what kind of variable it is.

Variables are created by assigning a value to a name using an *assignment statement*. In programming, the word *statement* is used for a command to perform some action. 

Here is an example of assigning the value `13` of type `int` to the variable `my_favorite_number`:

```python 
my_favorite_number = 8 + 5
```

To say to the computer that we want to perform assignment, we use the *assignment operator* `=`. In programming, the word *operator* is used for a symbol (often borrowed from mathematics) used in the text of the program.

On the left side of the `=` is the name of the variable. There are [rules for the names of variables](https://allendowney.github.io/ThinkPython/chap02.html#variable-names ) (also listed [here](https://www.w3schools.com/python/python_variables_names.asp)). The variable name should start with the letter and contain only letters, numbers or underscore.

On the right side of the `=` is the value that we want to assign to the variable. In the example above, tha value is an [*expression*](https://allendowney.github.io/ThinkPython/chap01.html#expressions) `8 + 5`. In programming, the word *expression* is used for some text that the computer can evaluate to a single value. In this specific example the expression evaluates to the value `13`.

In this specific example, both values in the expression are of type `int`, which is used for integers (positive and negative whole numbers). 
The sum of two `int` types is also `int`, so the variable `my_favorite_number` will be of type `int`. You can check the type of a variable using the `type` function:

```python
print(type(my_favorite_number))
```

In the expression above, the '+' is an *operator* used for addition of two integers. There are many [mathematical operators](https://allendowney.github.io/ThinkPython/chap01.html#arithmetic-operators) in Python, and they can be used with different types of values.

Apart from operators, the expressions may also contain [*mathematical functions*](https://allendowney.github.io/ThinkPython/chap01.html#arithmetic-functions). We will formally introduce functions later in the course, but when used in expressions, functions are somehow taking some input and returning some output. For example in expression `abs(-5)` the `abs` takes a value `-5` as input and returns the `5` as output.

For now we will work with four types of variables: `int`, `float`, `str`, and `bool`. The `float` type is used for numbers with a decimal point, called *floating-point numbers*. The `str` type is used for text, called [*strings*](https://allendowney.github.io/ThinkPython/chap01.html#strings). Read more about those three [values and types](https://allendowney.github.io/ThinkPython/chap01.html#values-and-types) in the book and try the examples. 

As for the `bool` type, it is used for boolean values, which can be either `True` or `False`. Boolean values and [boolean expressions](https://allendowney.github.io/ThinkPython/chap05.html?highlight=bool#boolean-expressions) which evaluate to `True` or `False` are very important in programming. Unexperienced programmers often experience problems when working with booleans, so we introduce them now such that you have more time to practice using them. Boolean expressions use [logical operators](https://allendowney.github.io/ThinkPython/chap05.html?highlight=bool#logical-operators) (also called Boolean operators) to be combined into more complex expressions.

Python has several more data types which we will cover later. If you are interested, you find the four types we learned now in the list of all built-in  [Python data type](https://www.w3schools.com/python/python_datatypes.asp).

## Reassignment
Once a variable is assigned a value, it the same variable name can be assigned a new value. This can be a different value of the same type, or a value of a different type. 

For example consider the statements:

```python
my_favorite_number = 13
my_favorite_number = my_favorite_number + 3.14
```
Here, the second statement reuses the variable name `my_favorite_number` on the left side of the `=`. The value assigned to this variable is  `my_favorite_number + 3.14`, which evaluates to `16.14`.  The variable `my_favorite_number` is now of type `float`.

## Casting
[Variables and casting](https://www.w3schools.com/python/python_variables.asp). TODO text.



## Using assignments when programming

Assignments may look easy, but you should nevertheless invest time practicing them. Many programming tasks might be simplified by using well-chosen assignments. 

The coder needs to consider all these aspects: appropriate type, appropriate name, and a value which is suitable for the task.

TODO elaborate and give example.



# Resources (optional)

- [Python tutorial introduction](https://docs.python.org/3/tutorial/introduction.html#) explains  assignments of numbers of and strings. It also explains the concept of indexing, and lists. We will cover those topics in the later. 


# Advanced topics (optional)
* Any and all functions
* Floating-point representation