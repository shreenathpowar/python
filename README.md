# Python


## 1. Modules and Pip

**Modules**: Modules are code libraries used to borrow someone else's code. basically use code written by some other person(s) in our code. 
Also other people can use our code in thier code with the help of modules.

**Types of Module**:
  1. **Built in modules:** Modules which comes out of the box with Python Interpreter and ready to use. e.g. Math, Random, os, Shutil
  2. **External Modules:** Modules which are created by someone else(third party) that we can install in our machine and then use e.g. Pandas, Cryptography

**Why Modules?**

to purely focus on functionality we are working on and not to repeat ourself writing code for something which is already written so that we can save our time and efforts. Also Modules are used by lots of programmers hence they are well tested.

**REPL - Read Evaluate Print Loop**

When we run python/python3 on shell, we get a prompt which is called as REPL. it can be used to run python statements one by one but we don't use it. We use python script to write code and then run this script by giving it to python/python3 as an argument.

**Installing External Module using Pip:**

>```cmd
>pip install pandas

**Usage**

>```python
>import pandas
>
># Read 'hello.csv' file
>csv_file = pandas.read_csv('hello.csv')
>
># display first few rows from the 'hello.csv'
>print(csv_file) 


## Hello World!

>```python
>print("Hello World!")
>

## Print

The print() function prints the specified message to the screen, or other standard output device. The message can be a string, or any other object, the object will be converted into a string before written to the screen.

>```python
>print("hey")
>print("number", 7)
>
output:
```
hey
number 7
```

