# Resources to be used
- Andreases intro to topics
- https://docs.python.org/3/index.html
- https://docs.python.org/3/tutorial/index.
- https://www.w3schools.com/python/default.asp
- https://futurecoder.io/
- https://pythontutor.com/
- https://www.hackerrank.com/domains/python
- https://www.codecademy.com/learn/learn-python-3
- https://open.kattis.com/problems?order=difficulty_data

# And maybe used
- https://programming-24.mooc.fi/
- https://cholmcc.gitlab.io/nbi-python/index.en.html


# Addon
[codon tables](https://en.wikipedia.org/wiki/DNA_and_RNA_codon_tables#/media/File:Aminoacids_table.svg)
https://teaching.healthtech.dtu.dk/22101/index.php/Biological_knowledge_needed_in_the_course
https://kurser.dtu.dk/course/27002
https://teaching.healthtech.dtu.dk/22101/index.php/22101/22161_-_Introduction_to_programming_in_Life_Science_using_Python

  

# CS50
- https://cs50.harvard.edu/python/2022/
- https://www.youtube.com/cs50
- https://youtube.com/playlist?list=PLhQjrBD2T3817j24-GogXmWqO5Q5vYy0V&si=h4wk7j_RWoDEPAhg 
  

# Think Python
- https://greenteapress.com/thinkpython2/html/index.html The version we used in the 2023 course. 
- https://allendowney.github.io/ThinkPython/index.html With jupyter notebooks.
- https://www.openbookproject.net/thinkcs/python/english3e/index.html A version which uses pyscripter IDE.
- https://runestone.academy/ns/books/published/thinkcspy/index.html An interactive version with MCQs and exercises in pytutor.
- http://www.openbookproject.net/thinkcs/python/english2e/ This is python 2 version, and should NOT be linked to

# Other books 
- https://learnpythonthehardway.org/
- https://www.pythonlikeyoumeanit.com/intro.html


# Other courses
- https://sites.pitt.edu/~naraehan/python3/
- https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/
- https://www.cs.cornell.edu/courses/cs1110/2017sp/index.php.html
- https://runestone.academy/ns/books/published/thinkcspy/index.html
- https://teaching.healthtech.dtu.dk/22110/index.php/22110_-_Python_and_Unix_for_Bioinformaticians
- https://swcarpentry.github.io/python-novice-inflammation/
- http://swcarpentry.github.io/python-novicegapminder/
- https://www.annedawson.net/CSCI120.html
- https://www.dumas.io/teaching/2020/fall/mcs260/
- https://www.cs.cornell.edu/courses/cs1110/2016sp/lectures/index.php.html
  

# Other resources
- https://mljar.com/blog/jupyter-notebook-online/
- https://www.udemy.com/share/102Z6G/ (not free)
- https://www.annedawson.net/Python3Programs.txt
- 

# Quizzes inspiration
- https://www.w3schools.com/quiztest/quiztest.asp?qtest=PYTHON 
- https://huggingface.co/learn/nlp-course/chapter1/10
- https://www.w3schools.com/quiztest/default.asp
 

# Maybe other books
* Wes McKinney's - Data Analysis with Python (Data wrangling with Pandas, Numpy, and IPython)
* Führer, Solem, Verdier - Scientific Computing with Python 3
* https://ebookcentral-proquest-com.proxy.findit.dtu.dk/lib/DTUDK/detail.action?docID=4773881


# Literature on teaching and teaching programming
- https://dl-acm-org.proxy.findit.cvt.dk/doi/pdf/10.1145/2662412
- https://www.tandfonline.com/doi/full/10.11120/ital.2011.10010086
- https://www-tandfonline-com.proxy.findit.cvt.dk/doi/full/10.1080/03043797.2017.1301383


# Course outline by Andreas
The following is a brief overview of the material covered in each lecture. This is intended as a concise abstract which may be included on DTU Learn

### Lecture 1: Getting Started
Keywords: type, variable, expression, statement, output, course tools, interactive mode.

Overview:
In this lecture, we first introduce you to the basic tools: Python, the VS Code editor, and the zip file containing the assignments. Next, we introduce the notion of a variable and variable types. In particular, we cover how variables can be integers, floating point, or boolean. These three types represent the natural numbers, numbers with decimals, and true/false values, respectively. We discuss how the contents of variables are manipulated using statements which are the basic instructions that make up a computer program. Finally, we explain how to show output on the computer screen.

### Lecture 2: Structured code using functions
Keywords: functions, math, matplotlib, structured programming, script mode, mentally tracing through code.

Overview:
In the first lecture, we typed python statements and they were immediately executed. In this lecture, you will learn to program in script mode. This means that a computer program is written as a text document which is sometimes called a script. The simplest programs are just sequences of statements, but programs often become so long that a single sequence of statements is very hard to understand, let alone modify! Functions (in the computer science sense) help us make code much more manageable by offering a method for breaking a program into pieces. A function is a sequence of statements that can be called from the main program or even another function. Additionally, you will also be introduced to the math module and plotting points with matplotlib. In this lecture we also explain how you can mentally step through a program to understand what it does.

### Lecture 3: Conditionals and functions that return values
Keywords: conditionals, function return value,  good practices for program structure.

Overview:
Most of the time we want programs to behave differently depending on data. This is where conditionals come in. Conditionals allow us to make a program that executes certain statements only if a condition is met. In this lecture, we also introduce functions that return a value. Put differently, these functions send a message back to the place from which they were called. An important thing to consider as a programmer is how to divide your program into functions of appropriate size and with a clear purpose, and this is also discussed. In particular, if you have similar or identical lines of code in your program, you can get a much more manageable program by replacing all of those repetitions with a function call.

### Lecture 4: Iteration and text strings
Keywords: iteration, text strings, indexing, input.

Overview:
Often we want the same sequence of statements to execute a specific number of times. This is called iteration, and in this lecture we create programs that iterate. We also discuss text strings. A text string (or just string) is a sequence of letters which together make up some text. We will discuss how iteration can be used to make programs that perform operations on strings, such as transforming a string into a new one where all letters are upper case. This is possible because using a string we can easily get character n in the sequence of letters that make up the string. n is an integer called the index. Finally, we will discuss how to get input from the user while the program is running.

### Lecture 5: Lists
Keywords: lists, assignment operator, debugger.

Overview:
If we have several variables, we can store them in a list. Just as for strings, we can always get the list entry with index n.  While a list is a bit like a text string, each element in a list can be anything - even another list - and we can change each entry in a list. In this lecture we will also discuss assignment (i.e. the meaning of the ‘=’ symbol) in a Python program and how ‘a=b’ works slightly differently depending on whether b is a number or a list. Finally, we introduce the Debugger. The debugger works just like Python in interactive mode, which you remember from the first lecture, but now you will learn how to stop a program and use the functions and variables defined in the program directly from the command line.

### Lecture 6: Dictionaries
Keywords: dictionaries, keys and values, comments and clear coding.

Overview:
While lists allow us to store several variables and quickly retrieve the one with a given index, a dictionary solves a slightly harder problem: it maps any key to a value. This is a bit like having a list where the index can be anything … well almost: it must be a type that you cannot change. A list is not possible because you can change a list, but a text string, an integer or a floating point number is fine. You can think of dictionaries as very simple databases. In this lecture, we also discuss how to write clear code by choosing good names for variables and commenting in a useful fashion. 

### Lecture 7: Structured data
Keywords: tuples, structured data, random numbers.

Overview:
We discuss how data can be structured using tuples. At first sight, tuples are very similar to lists, but a tuple cannot be changed once it has been created. This makes tuples slightly more efficient and also means that they can be used as dictionary keys. Moreover, tuples are very powerful in combination with functions that return several values. 
In this lecture, we also cover pseudorandom numbers.

### Lecture 8: Storing data in files and debugging
Keywords: input and output, files, debugging and assertions.

Overview:
Lists, dictionaries, tuples, and strings are far more useful if the program can retrieve data from a file. Otherwise, our program can only deal with data that is either a part of the program or typed in by the user. In this lecture we discuss ways to read data from a file and then store it in tuples, lists, and dictionaries for easy use from within the program. We also have to own up to the fact that programs may contain bugs. In this lecture, we discuss how to fix bugs which is mostly a matter of finding them. Typically, this is done by inserting checks in the program until the point where it starts behaving oddly is found. Lastly, we cover assertions which are simply statements that must be true or the program stops. This is a useful tool for debugging.

### Lecture 9: Classes and objects
Keywords: classes, objects, object oriented programming.

Overview:
Classes are the core idea of object oriented programming. Classes combine data and functions. To be clear, a class does not itself contain any data, but it specifies what data must be contained in objects of the type that the class represents. In other words, classes are just types (like integer and float) but an object of the type of a given class usually consists of several member variables - much like a tuple. Now, the functions which are also members of a class operate on member variables that belong to the same object as the functions themselves. This is a structuring principle that is extremely helpful if you are writing larger programs, even if there is nothing that classes provide which cannot be done without classes.

### Lecture 10: Modules and packages
Keywords: modules, packages, importing.

Overview:
While classes (and object oriented programming) are crucial for developing bigger pieces of software, we can often get by without creating classes. However, almost all of the libraries of code that we use do contain classes, and this is the most important reason for learning about classes. Libraries of code are called packages in Python, and these packages contain modules that provide various functions and classes that we can use in our program. In this lecture, we will learn how to import functions and classes from modules and use them in our own programs.

### Lecture 11: Numerics 
Keywords: NumPy

Overview:
NumPy is a very common package that is used for numerics, and almost any Python programmer will come into contact with NumPy. In this lecture, we discuss how to use NumPy for linear algebra and efficient computations in general since an important benefit of using NumPy is that certain operations are much faster than if you code them from scratch. We will explain how NumPy arrays are different from lists and show how NumPy can be combined with Matplotlib, which was introduced earlier, to perform computations and visualize the results.

### Lecture 12: Algorithms
Keywords: algorithms, efficiency, run time.

Overview:
Often, the best way to design a computer program is to consider the problem that you want to solve and then break it into smaller subproblems and repeat this procedure until each subproblem is small enough that you know exactly how to code it. What you have designed in this way is, of course, an algorithm and once you have coded it up it becomes a program.
Unfortunately, not all algorithms (for solving the same problem) are equal and in this lecture we will discuss how some algorithms are much more efficient than others. This is a big topic, and the goal is only to provide you with a basic understanding of how to craft algorithms and some pitfalls to avoid.

### Lecture 13: Summary and discussion of the exam
Keywords: real-world programming, ChatGPT, evaluation, exam

Overview:
In this lecture, we will talk about how programming is used in DTU’s educations and provide examples of how it is necessary beyond your education in engineering work broadly. We will also discuss alternatives to programming such as using ready made programs or tools for code generation as well as the benefits and pitfalls when using automatic code generation. We also do an end-of-course evaluation and talk about the exam. Finally, all questions are answered to the best of your teacher’s ability.

