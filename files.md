# FileIO & Exceptions

<br><br>


## What Is a File?

> A data that is organized in a specific format and can be anything


## What does a file contains?

<p> 

Files on most modern file systems are composed of three main parts: <br>

1. Header: metadata about the contents of the file (file name, size, type, and so on) <br>
2. Data: contents of the file as written by the creator or editor <br>
3. End of file (EOF): special character that indicates the end of the file <br>



</p>

## Where files located?

> When you access a file on an operating system, a file path is required <br>

> The file path is a string that represents the location of a file <br>


<p> 

> A file path consist of three parts

1. Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash / (Unix) or backslash \ (Windows)  <br>
2. File Name: the actual name of the file <br>
3. Extension: the end of the file path pre-pended with a period (.) used to indicate the file type <br>

</p>


## Opening and Closing a File in Python

<br>

> When you want to work with a file, the first thing to do is to open it. <br>

> file = open('File_path') <br>

> file.close() <br>

<br>

> Files can be opend with different modes : <br>

<p>

1.  open('File_path', r) for reading (default one) <br>

2.  open('File_path', w) for writing <br>

3.  open('File_path', a) for appending <br>

</p>


## Exceptions Vs Syntax Errors

<br>

> Syntax errors occur when the parser detects an incorrect statement <br>

> Exception errors occurs whenever syntactically correct Python code results in an error <br>


## Handling Exceptions

<br>

> The try and except block in Python is used to catch and handle exceptions. Python executes code following the __try__ statement as a “normal” part of the program <br>

> This exception error will crash the program if it is unhandled. The __except__ clause determines how your program responds to exceptions. <br>

> Using the __else__ statement, you can instruct a program to execute a certain block of code only in the absence of exceptions. <br>

> Using the __finally__ statement, does not matter if you encounter an exception somewhere in the try or else clauses, it will always be executed <br>

> Using __raise__, allows you to throw an exception at any time <br>

> __Assert__ enables you to verify if a certain condition is met and throw an exception if it isn’t.