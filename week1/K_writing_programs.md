---
layout: default
---

# Writing and executing programs
**STATUS: DRAFT. PLAN: TEXT AND VIDEOS. DURATION: 30min**

There are many ways to write and execute programs. Experienced programmers will use advanced tools (code editors), which are usually highly customizable and have a lot of features. For beginners, such tools can be overwhelming. (You can again think of the car analogy: when just learning to drive, you may be distracted by auto pilot and navigation systems, despite those being useful features for experienced drivers.)

As most students in this course are complete beginners, we will start with simple tools. Around the middle of the course we will also introduce more advanced tools, and you will be able to choose the tool that suits you best.

## Code editors
Code editors are programs designed to help you write code. They have features that make writing code easier and more efficient. To explain what code editors provide, let's compare them to text editors. A text editor, for example Microsoft Word, can make writing process much easier. It provides spelling check, copy and paste, searching and replacing, treasuries, and many other features. Clearly, you **could** write a book without a text editor, but it would be much harder. Code editors provide similar features, but they are tailored for writing code.

Apart from helping you to write the code, most code editors have features that help you to run the code. Such editors are called Integrated Development Environments (IDEs). Some popular IDEs for Python are Visual Studio Code, Sypder, and PyCharm. In this course, we will start with a simple code editor, IDLE, which comes with Python installation. Later, you may switch to Visual Studio Code.

### Idle
[Idle](https://docs.python.org/3/library/idle.html)

## Other ways of running python code
Executing python `.py` files from a command line or from IDE is a direct way of running python code. Python code may be used in other ways, and it has become popular to run python code from a so-called *Jupyter notebook*. Jupyter notebook is a web-based interactive environment for writing and running code. It is widely used in data science and machine learning. It is also used for teaching because it allows to combine code, text, and images in one document.

Jupyter notebooks may be run on your computer, but there are also online services that allow you to run Jupyter notebooks without installing anything on your computer.

The focus of this course is on writing and running python code, regardless of whether it is run from a `.py` file, from an IDE or in a Jupyter notebook. To solve assignments in the course you will need to write python code in a `.py` file. We will not be using Jupyter notebooks, but you might want to try them.

### Running python code online (or in browser)
TODO: What requires internet and what does not? And when? When loading, when running?

In this course, we expect you to get python installed and run python code it on your computer. If you can't running python on your computer (for example, before installing python in the first weeks of the corse, or when using another computer), you may use one of the following services. However, remember that this will not be possible for the exam. And also note that online tools might have limitations (e.g. getting user input, loading files).  

- [W3Scohools try-it editor](https://www.w3schools.com/python/trypython.asp?filename=demo_default) is a very simple online python editor provided by W3Schools. No account needed, and only a discrete ad at the top of the page. Requires internet connection to run the code.
- [Online-python](https://www.online-python.com/) has a few more features than W3Schools (saving the file, sharing the file), but also more prominent ads.
- [Jupyter lite](https://jupyter.org/try-jupyter/lab/), supports running jupyter notebooks in-browser, but can also be used to run python code. For this: under 'Other' chose 'Python File'. Right-click inside the file text, select 'Create Console for Editor', and then select Python (Pyodide) kernel. Now *go back* to the file text (that is, click in the file text). You can now run the code by clicking the 'Run' button in the top menu, and selecting 'Run All Code'. This is a bit more complicated than the other options, but allows working with files and folders similar to how you would work with files on your computer. 
- [Code skulptor](https://py3.codeskulptor.org/) implements a subset of python in the browser with the focus on interaction and graphical libraries. Nice and simple look with no ads. Despite focusing on gui, code skulptor can easily be used to run simple python code from the first weeks of our course.
- [Brython](https://brython.info/tests/editor.html?lang=en), yet another way to run python code in the browser.


**Advanced** Some of those are related, while some use very different technologies. Fore example, Jupyter lite uses [pyodide](https://pyodide.org/en/stable/), which translates python code to web assembly code. Code skulptor uses [skulpt](https://skulpt.org/) which translates python to JavaScript. Brython also translates to JavaScript. There are also services requiring the user to create a free account:  
[Pyscript](https://pyscript.com/) where you can maintain several projects; has focus on web development.
[Python anywhere](https://www.pythonanywhere.com/) also with focus on web development. [Replit](https://replit.com/), a more advanced tool resembling desktop editor.

## Additional resources (optional):
- [w3school python get started](https://www.w3schools.com/python/python_getstarted.asp)
- [Python tutorial Whetting Your Appetite](https://docs.python.org/3/tutorial/appetite.html)
- [Python tutorial Using the Python Interpreter](https://docs.python.org/3/tutorial/interpreter.html)



