---
layout: default
---

# Files, folders, paths and command line interface

**STATUS: DRAFT. PLAN: TEXT AND VIDEOS. DURATION: 30min**

Computers have become integral to almost every professional and personal activity, making them accessible to people of all backgrounds. For many, the computer serves as a tool for browsing the internet, managing bank accounts, and organizing documents, such as texts, photographs, and music. These activities are user-friendly and typically require minimal knowledge of the computer's underlying organization.

However, when it comes to programming, gaining insight into the computer's inner workings becomes essential. In this text we will cover the basic concepts of the computer's file system and the command line interface (CLI). These concepts are fundamental to understanding how to write and execute programs.

In the text, we give examples for Windows and MacOS, which are the most commonly used operating systems. If some students use Linux, they should be able to adapt the examples.

## Files and folders
The information in the computer is organized into files and folders (also called directories). Usually, you will be interacting with files and folders through a file manager such as Windows Explorer or Mac Finder, which can be customized to visualize the folder structure in different ways. File manager allows you to create, move, rename, delete and copy files and folders. 

TODO SCREENSHOTS

The root of the file system is the folder that contains all other folders and files. In Windows, the root is represented by a single character, such as `C:`. In MacOS, the root is represented by `/` .

**File extensions.** Files have extensions which indicate the type of the file, and how to open it. For example, the extension `.docx` is used for Microsoft Word documents, and the extension `.jpg` is used for JPEG-compressed images. Depending on your settings, the file manager may or may not show the file extensions. Python files have the extension `.py`. 

The operative system of the computer and the installed programs are also stored in files on your computer, often in folders that are not visible from file manager. 

**Downloading files.** When you download files from the internet, your browser will either ask you where to save the file, or it will save the file in the predefined folder, the *download folder*. You show always know where the file is saved, as you may need to access it later.

## Paths
A path indicates how the file can be located on the computer. Starting from the root of the file system, the path describes the sequence of folders that lead to the file. The path that starts from the root is called an *absolute path*. Sometimes we need to describe the path starting from a certain folder which is not a root, such path is called a *relative path*. In relative paths, we may need to move up one level in the folder structure and we use `..` to indicate that.

Knowing the correct path ensures that you, or your program, can locate the necessary resources. If you don't provide a full path of the resource which you expect your program to use, your computer will try to find it according to some rules.

## Command line interface

An interface is a way to interact with a computer. A command line interface (CLI) allows you to interact with the computer by writing text. You are probably more familiar with the graphical user interface (GUI), where you interact with the computer by clicking on icons, buttons, and menus. However, the CLI is still widely used, especially in programming and system administration.

CLI will often gives you more control over the computer than GUI. For example, you can see the hidden files and folders, and perform operations not accessible via GUI. Using CLI requires caution, as you can accidentally delete or modify important files.

It is possible to learn to program in Python without using the CLI, but it is recommended to learn the basics of CLI, as it will give you a better understanding of how the computer works.

### Basic commands
We are only going to cover two features of CLI: navigating the file system and executing programs.

| Command |  Windows| MacOS|
|---|---|---|
|list files and folders in the current directory |`dir`|`ls`| 
|print the full path of the current (working) directory |`cd`|`pwd`|
|change directory to foldername |`cd foldername`|`cd foldername`| 
|change directory up one level |`cd ..`|`cd ..`|

TODO CHECK ALL WRITTEN HERE. TODO MAKE VIDEOS FOR THESE EXAMPLES.

CLI also allows you to execute (start) utilities and programs. For example, a video [link TODO] shows a Windows computer, and CLI opened in a folder containing a file called `myprogram.exe`. This type of files is executable and one can start it by typing `myprogram` in the CLI as shown in the video

You are only able to execute programs that your computer can find in the current folder, or the special list of folders where the computer looks for programs to execute. This list is updated when you install new programs. For example, after installing Microsoft Word in a Windows computer, you will be able to start it by typing `winword` in the CLI, regardless of your current folder. To open a specific file in Word, you can type `winword filename.docx`. This is show in a video [link TODO].

In general, the commands given to CLI are of the format
```bash
prompt command param1 param2 param3 ...
```
Here, `prompt` is the text that the CLI shows to indicate that it is ready to accept a command. The `command` is the name of the utility or program that you want to start. The parameters `param1 param2 param3 ...` are additional information that the command needs to execute.

If you have python installed on your computer, you can start it by typing `python` in the CLI. A python program stored in a file `filename.py` can be executed by typing `python filename.py`. There are some variations of this command, depending on the version of Python you have installed. We will cover this in detail later.

The video [link TODO] shows how to start Python in CLI, and how to execute a Python program.


## Additional resources (optional)
Internet is packed with resources for introductory programming. Throughout the course, we have selected a few resources that we believe might be useful for beginners. Whenever possible, we will write a remark if the resource in some way deviates from the course content. 

If you want more information about files, folders, paths, and the command line interface, you can check the following resources:
- [CLI at w3schools](https://www.w3schools.com/whatis/whatis_cli.asp). Educational website [w3schools](https://www.w3schools.com/) is excellent for learning coding and web development. In this course, we will use often link to w3school as an additional resource. W3schools is run by a Norwegian company. 
- [CLI at Django Girls tutorial](https://tutorial.djangogirls.org/en/intro_to_command_line/). An international non-profit organization [Django Girls](https://djangogirls.org/en/) introduces girls to programming. Their tutorials are excellent for all beginners. 


TODO maybe add additional additional resources:
- https://www.redhat.com/sysadmin/navigating-filesystem-linux-terminal with focus on Linux, so it is the same on MacOS



