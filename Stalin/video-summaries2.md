# Video Summaries

## 1. ["Goodbye Print Statements, Hello Debugger!" - Nina Zakharenko (PyCon AU 2019)](https://www.youtube.com/watch?v=HHrVBKZLolg)

A talk by [Nina Zakharenko](https://twitter.com/nnja) telling us not to use print but to use debuggers instead!

### 1.1. Key take aways

1. `print()` doesn't give much information on your code or the error
2. Use breakpoints
3. pdp and ipdp are few debuggers you can use in CLI
4. Don't Leave breakpoints in production code

### 1.2. Timeline

* [04:38](https://youtu.be/HHrVBKZLolg?t=278) Introduction Demo app
* [09:28](https://youtu.be/HHrVBKZLolg?t=568) Types of Debuggers
* [10:37](https://youtu.be/HHrVBKZLolg?t=637) Breakpoints
* [14:09] CLI Debugger demo
* [18:45](https://youtu.be/HHrVBKZLolg?t=1125) IDEs Debugger demo
* [22:56](https://youtu.be/HHrVBKZLolg?t=1375) When to use what?
* [23:38](https://youtu.be/HHrVBKZLolg?t=1418) Tips & Tricks
* [27:56](https://youtu.be/HHrVBKZLolg?t=1676) Conclusion

## 2. [Python Quick Tip: Debugger and breakpoint()](https://www.youtube.com/watch?v=aZJnGOwzHtU)

A video from [Python Engineer](https://www.youtube.com/channel/UCbXgNpp0jedKWcQiULLbDTA) which briefly explains debugging quick tip.

### 2.1. Key take aways

1. You can just call `breakpoint()` to create breakpoints (>=Python 3.7)

## 3. [Debugging Python programs using pdb (the Python debugger)](https://www.youtube.com/watch?v=IzgSl-tkPPg)

A quick video from [redshiftzero](https://www.youtube.com/channel/UC_ChPWb8UjvkGKszdSomfeg) on using python debugger.

### 3.1. Key take aways

1. `n` is for stepping over and `s` is for stepping inside a function
2. `c` to continue
3. `b` to create breakpoint

## 4. [Visual Debugger for Jupyter Lab/IPython Notebooks | Installation, Code Examples & Debugging](https://www.youtube.com/watch?v=16DhtEOJwTA)

A video by [Venelin Valkov](https://www.youtube.com/channel/UCoW_WzQNJVAjxo4osNAxd_g) on getting started with new Visual Debugger for Jupyterlab, to set breakpoints, inspect variables and navigation of call stack.

### 4.1. Key take aways

1. install the JupyterLab extension `jupyter labextension install @jupyterlab/debugger`
2. You can navigate the stack, set breakpoints and inspect variables with this extension
3. The extension is still in preview

### 4.2. Timeline

* [03:04](https://youtu.be/16DhtEOJwTA?t=184) Installation
* [05:45](https://youtu.be/16DhtEOJwTA?t=345) Demo

## 5. [How to Use a Debugger - Debugger Tutorial](https://www.youtube.com/watch?v=7qZBwhSlfOo)

A video from [Tech with Tim](https://www.youtube.com/channel/UC4JX40jDee_tINbkjycV4Sg) where he teached us how to debug using vscode IDE.

### 5.1. Key take aways

1. Step over moves to the next line for code rfrom the current line
2. Step out will escape out of the function to the calling function in the call stack
3. Step into will go inside the function call on the current line
4. You can create a breakpoint and disable it rather than deleting it
5. Use "Watch" to create expressions or variables you want to monitor or watch while debugging
6. You place the breakpoint at the gutter. Gutter is the space/padding next to the line numbers in the editor

### 5.2. Timeline

* [04:35](https://youtu.be/7qZBwhSlfOo?t=275) The vscode debugger
* [06:06](https://youtu.be/7qZBwhSlfOo?t=368) Watch variable
* [07:51](https://youtu.be/7qZBwhSlfOo?t=368) Breakpoints
* [09:25](https://youtu.be/7qZBwhSlfOo?t=565) Navigating your code

## 6. [Amandine Lee Passing Exceptions 101 Paradigms in Error Handling PyCon 2017](https://www.youtube.com/watch?v=BMtJbrvwlmo)

A great talk by Amandine Lee during the PyCon 2017 conference, talking about exceptions and how to handle them and choose the way to handle them.

### 6.1. Key take aways

1. BaseException is the base class of all exceptions
2. Design our programs like contracts
3. Database connection, network issues, etc. are recoverable
4. Abandonment isolates at the process level
5. Self-heal cleanly, think about what is recoverable, clear out bad state and isolated components are helpful
6. `assert` is used for things that never supposed to happen
7. ValueError is used for making sure the value is correct
8. If the program is not supposed to run in a certain way, end it with exception rather than recovering it

### 6.2. Timeline

* [00:51](https://www.youtube.com/watch?v=BMtJbrvwlmo&t=51s) Introduction
* [03:17](https://www.youtube.com/watch?v=BMtJbrvwlmo&t=197s) Exception
* [06:35](https://www.youtube.com/watch?v=BMtJbrvwlmo&t=395s) Reasons for exceptions
* [09:52](https://www.youtube.com/watch?v=BMtJbrvwlmo&t=592s) Exception use cases
* [13:46](https://www.youtube.com/watch?v=BMtJbrvwlmo&t=826s) Design by Contract
* [17:42](https://www.youtube.com/watch?v=BMtJbrvwlmo&t=1062s) Recovering from errors
* [23:49](https://www.youtube.com/watch?v=BMtJbrvwlmo&t=1429s) Lessons Learned  
* [25:29](https://www.youtube.com/watch?v=BMtJbrvwlmo&t=1529s) QnA

## 7. [Mario Corchero - Exceptional Exceptions - How to properly raise, handle and create them.](https://www.youtube.com/watch?v=V2fGAv2R5j8)

A talk by Mario Corchero on the multiple ways to raise and capture exceptions. The talk explains the decisions needed to raise and capture exceptions.

### 7.1. Key take aways

1. `else` will trigger if no exception happen while `finally` means it will run no matter what
2. Errors should never pass silently, unless explicitly silenced
3. To print the exception use `%r` or `repr(e)` in string formatting
4. When you raise an exception inside an except (catch) block, you will get the error message "During handling of the above exception, another exception occured". Instead just using `raise` will give in except will just give the error that happened
5. Doing `raise Exception() from e` will will give a message saying "The above exception was the direct cause of the following exception" 
6. Don't use `raise NotImplemented` for  functions thathas not been implemented yet but kept for the future, as this causes an actual error exception
7. `BaseException` is not what you wanna catch, its `Exception`
8. Inherit from `Exception` not from `BaseException` for custom exceptions

### 7.2. Timelines

* [02:28](https://www.youtube.com/watch?v=V2fGAv2R5j8&t=148s) How to raise and capture an exception  
* [04:00](https://www.youtube.com/watch?v=V2fGAv2R5j8&t=240s) finally else  
* [04:50](https://www.youtube.com/watch?v=V2fGAv2R5j8&t=290s) order of execution of tray except else finally  
* [06:03](https://www.youtube.com/watch?v=V2fGAv2R5j8&t=363s) Logging exceptions  
* [10:25](https://www.youtube.com/watch?v=V2fGAv2R5j8&t=625s) Scoping of the except  
* [12:22](https://www.youtube.com/watch?v=V2fGAv2R5j8&t=742s) Raise Exceptions  
* [14:08](https://www.youtube.com/watch?v=V2fGAv2R5j8&t=848s) Chaining Exceptions  
* [19:01](https://www.youtube.com/watch?v=V2fGAv2R5j8&t=1141s) Exception Attributes  
* [20:52](https://www.youtube.com/watch?v=V2fGAv2R5j8&t=1252s) Custom Exception class  
* [23:28](https://www.youtube.com/watch?v=V2fGAv2R5j8&t=1408s) Error Codes

~## 8. [Code Refactoring: Learn Code Smells And Level Up Your Game!](https://www.youtube.com/watch?v=D4auWwMsEnY)

A talk by Sandi Metz on refactoring and fixing bad code.

### 8.1. Key take aways

1. Fixing one problem (data clump) at one time
2. If you want to refactor, you must have unit tests that run quickly
3. Reek is a static analysis tool for identifying code smells in your program

### 8.2. Timeline

## 17. [How to do coding peer reviews with Github](https://www.youtube.com/watch?v=8fx-EaOUK2E)

A video from [London App Developer](https://www.youtube.com/channel/UC3RtgbslbAvE-5FFBkSgpig) on coding peer reviews using GitHub to improve the quality of code.

### Key take aways

1. Peer reviews is a technique used in programming to improve the quality of the code
2. Helps to learn from other developers
3. Great for knowledge transfer between the team
4. Good practice to have a master branch, which has the latest changes, and a development branch, which has all the development changes in progress
5. In development branch you have feature branches and create a readme for each feature change
6. Create PR (Pull Request) for peer reviews. Explain the changes made, add the reviewers who will review your code and create PR. After review and if all are ok, the PR can be approved and merged
7. Once the features are updated and complete, the feature branch can be deleted for clean up

### 17.2. Timeline

* [00:00](https://www.youtube.com/watch?v=8fx-EaOUK2E&t=0s)​ Introduction
* [00:59](https://www.youtube.com/watch?v=8fx-EaOUK2E&t=59s)​ Main benefits of peer review
* [02:49](https://www.youtube.com/watch?v=8fx-EaOUK2E&t=169s)​ Demo of how to do peer reviews using GitHub