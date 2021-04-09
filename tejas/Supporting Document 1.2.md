# **Supporting Document 1.2**

## **#1. *"Goodbye Print Statements, Hello Debugger!" - Nina Zakharenko (PyCon AU 2019)***

**Link** - https://www.youtube.com/watch?v=HHrVBKZLolg

In this video which is approximately 30 mins long, the author Nina Zakharenko speaks on how to level up your ability to troubleshoot complex code situations by using the power of a fully-featured debugger.

**Pointers**,

 1. Print statements don't give you much context
 2. A debugger helps you examine the state of a running program
 3. Have a new method breakpoint() in python 3.7
 4. PDB debugger is included in the standard library
 5. Call the debugger by calling the breakpoint() function
 6. Types of CLI debuggers - **pdb** (In standard library), **ipdp** (via pip install)
 7. Types of graphical debuggers - **pudb**, **vs code**, **pycharm**
 8. A breakpoint - stops the flow of execution in your program
 9. Set env variable PYTHONBREAKPOINT=0 in your cmd line to skip all the debug breakpoints in python 3.7 or use import pdb or import ipdb for older versions and call pdb.set_trace() or ipdb.set_trace
 10. 5 most important commands
l (list) or ll (long list)
n (next line)
s (step into)
c (continue until next breakpoint)
h (help) (optional command)
j (jump, if your debugger is stuck in a loop)
11. Never leave breakpoints in production code

<br>

## **#2. *Python Quick Tip: Debugger and breakpoint()***

**Link** - https://www.youtube.com/watch?v=aZJnGOwzHtU

In this video which is approximately 6 mins long, the author teaches how to use the Python Debugger using the breakpoint() function. A more descriptive video on using the basic debugging commands.

**Pointers**,

 1. Commands for debugging
h : help
w : where
n : next (steps over function)
s : step (steps into function)
c : continue
p : print
l : list
ll : longlist
q : quit
2. Use "s" instead of "n" for entering a function
3. Find yourself in the code with the "w" command

<br>

## **#3. *Debugging Python programs using pdb (the Python debugger)***

**Link** - https://www.youtube.com/watch?v=IzgSl-tkPPg

In this video which is approximately 6 mins long, the author teaches on how to invoke pdb debugger and some of the pdb commands.

<br>

## **#4. *Visual Debugger for Jupyter Lab/IPython Notebooks | Installation, Code Examples & Debugging***

**Link** - https://www.youtube.com/watch?v=16DhtEOJwTA

In this video which is approximately 15 mins long, the author teaches how to set breakpoints, inspect variables and navigate the call stack right into your notebooks.

<br>

> Additional resources

 - Hacker's guide to machine learning with python - https://leanpub.com/Hackers-Guide-to-Machine-Learning-with-Python
 - A visual debugger for jupyter - https://blog.jupyter.org/a-visual-debugger-for-jupyter-914e61716559

<br>

## **#5. *How to Use a Debugger - Debugger Tutorial***

**Link** - https://www.youtube.com/watch?v=7qZBwhSlfOo

In this video which is exactly 17 mins long, the author teaches us how to debug and walks us through the VS Code debugger.

**Pointers**,

 1. Only use the debugger when things are complicated
 2. Place your break points in the gutter in VS Code. Gutter is the space that appears before the line numbers in your editor
 3. Have to place at least one breakpoint for the debugger to work
 4. step over moves you to the next line of code
 5. step into moves you into a function or method
 6. step out takes you out of the current scope
 7. Debugger will go through multiple files if you are using more than one

<br>

## **#6. *Amandine Lee Passing Exceptions 101 Paradigms in Error Handling PyCon 2017***

**Link** - https://www.youtube.com/watch?v=BMtJbrvwlmo

In this video which is exactly 17 mins long, the author talks about exception and error handling.

**Pointers**,

 1. BaseException is the first level of exception
 2. Reasons for exception - control flow, unexpected error, bugs in code
 3. Use MyPy for static analysis
 4. Writing components of program as if they are a contract
 5. Contract elements include - i/o elements, errors and exceptions raised, side effects, preconditions, postconditions, invariants


<br>

> Additional resources

 - PyCon slides - https://speakerdeck.com/pycon2017

<br>

## **#7. *Mario Corchero - Exceptional Exceptions - How to properly raise, handle and create them***

**Link** - https://www.youtube.com/watch?v=V2fGAv2R5j8

In this video which is exactly 17 mins long, the author talks about the decisions needed to raise and capture exceptions when creating a library. You will look at how to translate and handle errors, create your own exceptions, and make exceptions clear and easy to troubleshoot, while also understanding how they actually work, common pitfalls.

**Pointers**,

 1. Always raise exception from Exception class not BaseException class

<br>

> Additional resources

 - PyCon slides - https://speakerdeck.com/pycon2019

<br>

## **#8. *Code Refactoring: Learn Code Smells And Level Up Your Game!***

**Link** - https://www.youtube.com/watch?v=D4auWwMsEnY

In this video which is approximately 36 mins long, the author talks about how to take a pile of perplexing code, identify the "smells", and surgically apply the curative refactorings. It breaks a messy problem into clear-cut pieces, and proves that you can fix anything without being forced to understand everything. This video takes some time to soak in.

**Pointers**,

 1. Fixing one problem (data clump) at one time
 2. If you want to refactor, you must have unit tests that run quickly
 3. Reek is a static analysis tool for identifying code smells in your program

<br>

## **#9. *Kyle Knapp - Automating Code Quality - PyCon 2018***

**Link** - https://www.youtube.com/watch?v=G1lDk_WKXvY

In this video which is exactly 17 mins long, the author talks about code quality and how it would become easy and faster if a machine takes care of monitoring code quality.

**Pointers**,

 1. Reduce the number of manual code quality checks that does not require a human to perform
 2. Keep docstrings to one line
 3. Make sure you're not using internal methods outside of a class. Methods / variables that start with _ is an internal method / variable
 4. Automating code quality makes development faster and safer
 5. Tools for improving code quality - flake8, pylint, coverage, mypy

<br>

> Additional resources

 - PyCon slides - https://speakerdeck.com/pycon2018
 - Python code quality authority - https://github.com/PyCQA

<br>

## **#10. *Nina Zakharenko - Code Review Skills for Pythonistas***

**Link** - https://www.youtube.com/watch?v=6L3ZVLtSeo8

In this video which is approximately 40 mins long, the author mentions as teams and projects grow, code review becomes increasingly important to support the maintainability of complex codebases.

**Pointers**,

 1. Design flaws and bugs can be identified and remedied before the code is complete
 2. Code reviews can decrease bugs by 80% and increase productivity by 15%
 3. A good code is like a good joke, it needs no explanation
 4. Stages of review
0 : Before PR submission
1 : PR submitted
2 : (Optional)  work in progress PR (30% - 50%)
3 : Review almost done (90% - 100%)
4 : Review completed

<br>

> Additional resources

 - Pre-commit - A framework for managing and maintaining multi-language pre-commit hooks https://pre-commit.com/

<br>

## **#11. *Erik Rose Constructive Code Review PyCon 2017***

**Link** - https://www.youtube.com/watch?v=iNG1a--SIlk

In this video which is approximately 45 mins long, the author looks at “tact hacks” that nudge communication in a friendly direction, anti-patterns to avoid, the pesky human emotions that can tempt us into reviewing poorly, and techniques for levelling up newcomers without losing all your coding time.

**Pointers**,

 1. Building an excellent product
 2. Building people
 3. Building yourself

<br>

## **#12. *Anthony Shaw - Wily Python: Writing simpler and more maintainable Python - PyCon 2019***

**Link** - https://www.youtube.com/watch?v=dqdsNoApJ80

In this video which is approximately 30 mins long, the author talks about code complexities and to what measure they can get complicated and the remedies to simplify code.

**Pointers**,

 1. Wily python is a tool that helps you manage the process from handling complicated code to its simplification
 2. About maintainability index for code
M = 171 - 5.2ln(V) - 0.23(C) - 16.2ln(L)
where,
V is Halstead volume
C is Cyclomatic complexity
L is Lines of code
Measure :
0 - 25 : Unmaintainable
25 - 50 : Cause for concern
50 - 75 : Needs improvement
75 - 100 : Super hero code
Package is radon (pip install radon)
e.g. radon cc main.py -s, radon mi main.py -s, radon hal main.py

<br>

> Additional resources

 - For python refactoring - https://realpython.com/python-refactoring/

<br>

## **#13. *How To Publish A Package On PyPI***

**Link** - https://www.youtube.com/watch?v=QgZ7qv4Cd0Y

In this video which is approximately 30 mins long, the author talks about publishing packages on PyPI. A must watch video on how to push your packages to PyPI.

<br>

## **#14. *Thea Flowers - Break the Cycle: Three excellent Python tools to automate repetitive tasks***

**Link** - https://www.youtube.com/watch?v=-BHverY7IwU

In this video which is approximately 24 mins long, the author talks about using python tools to automate repetitive tasks

**Pointers**,

 1. Tox - aims to automate and standardize python package testing
e.g. of a tox.ini file in your root directory
[tox]
envlist=py27,py37
[testenv]
deps = 
-r requirements.txt
pytest
commands = 
pytest
2. Nox - Flexible test automation
3. Invoke - Python task execution and library

<br>

## **#15. *Carol Willing - Practical Sphinx - PyCon 2018***

**Link** - https://www.youtube.com/watch?v=0ROZRNZkPS8

In this video which is approximately 27 mins long, the author talks about the best way to document your work. This video gets you started with Sphinx.

<br>

## **#16. *Dougal Matthews - MkDocs: Documenting projects with Markdown***

**Link** - https://www.youtube.com/watch?v=pzoOQg6BNG4

In this video which is approximately 22 mins long, the author talks about the easiest way to documentation i.e. using a tool called MkDocs.

<br>

## **#17. *How to do coding peer reviews with Github***

**Link** - https://www.youtube.com/watch?v=8fx-EaOUK2E

In this video which is approximately 12 mins long, the author talks about peer reviews which is a technique used in programming to improve the quality of the code. Every single change that’s done on the codebase gets reviewed by another developer to see if any improvements can be made.


## Thank you for reading 🙂
