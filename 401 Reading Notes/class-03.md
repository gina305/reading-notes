# FileIO & Exceptions

## Read & Write Files in Python
Python provides inbuilt functions for creating, writing, and reading files. There are two types of files that can be handled in python, normal text files and binary files (written in binary language, 0s, and 1s).

* Text files: In this type of file, Each line of text is terminated with a special character called EOL (End of Line), which is the new line character (‘\n’) in python by default.
* Binary files: In this type of file, there is no terminator for a line, and the data is stored after converting it into machine-understandable binary language.

You can open the file in:

* r - read-only mode
* r+ - read and write mode
* w - write-only mode
* w+ - write and read mode
* a - append-only mode
* a+ - read-only mode

You can open a file using the open() method.
Here is an example of how to use th open method, using append-only mode:

```python
file1 = open("MyFile.txt","a")
```

## Exceptions in Python

A statement can be syntactically correct and still trow and exception.

Exception errors are detected during execution and vary in type. Some examples exceptions are ZeroDivisionError, NameError and TypeError - just to name a few.

You can  write programs that handle selected exceptions usinf the try-catch statements (See example below):

```python
try:
    x = int(input("Please enter your age: "))
    break
except ValueError:
    print("Oops!  That was not a valid number.  Try again...")
```
