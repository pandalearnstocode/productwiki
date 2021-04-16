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

## 8. [Code Refactoring: Learn Code Smells And Level Up Your Game!](https://www.youtube.com/watch?v=D4auWwMsEnY)

A talk by Sandi Metz on refactoring and fixing bad code by mapping [code smells](http://www.industriallogic.com/wp-content/uploads/2005/09/smellstorefactorings.pdf) to refactorings The talk is on Rails but the principles holds for all.

### 8.1. Key take aways

1. Fixing one problem (data clump) at one time
2. If you want to refactor, you must have unit tests that run quickly
3. Reek is a static analysis tool for identifying code smells in your program for rails
4. Using code smells you can curate a refactoring recipe
5. The test cases need not be real or have real queries running as it can slow down things

### 8.2. Timeline

* [00:00](https://www.youtube.com/watch?v=D4auWwMsEnY&t=0s) Introduction (Bloaters, Abusers, Preventers, Dispensables, Couplers)
* [10:28](https://www.youtube.com/watch?v=D4auWwMsEnY&t=628s) Refactoring
* [18:07](https://www.youtube.com/watch?v=D4auWwMsEnY&t=1087s) Data Clump
* [20:19](https://www.youtube.com/watch?v=D4auWwMsEnY&t=1219s) Message Chain
* [24:21](https://www.youtube.com/watch?v=D4auWwMsEnY&t=1461s) How real test cases should be?
* [30:47](https://www.youtube.com/watch?v=D4auWwMsEnY&t=1847s) Duplicated Code
* [34:23](https://www.youtube.com/watch?v=D4auWwMsEnY&t=2063s) Reek

## 9. [Kyle Knapp - Automating Code Quality - PyCon 2018](https://www.youtube.com/watch?v=G1lDk_WKXvY)

A talk by [Kyle Knapp](https://twitter.com/thekyleknapp) on writing python code with a general design, different quality aspects etc. which can all be done using automated tools and thus improving code quality

### 9.1. Key take aways

1. Styling standards like PEP 8 and safe standards can be automated
2. pylint is more strict and opinionated than flake8
3. pylint covers all style, bugs, documentation and usability
4. Code must pass quality checks to be merged
5. Automated quality checks does not gaurantee code quality

### 9.2. Timeline

* [06:38](https://www.youtube.com/watch?v=G1lDk_WKXvY&t=398s) flake8  
* [10:21](https://www.youtube.com/watch?v=G1lDk_WKXvY&t=621s) pylint  
* [14:54](https://www.youtube.com/watch?v=G1lDk_WKXvY&t=894s) coverage  
* [16:53](https://www.youtube.com/watch?v=G1lDk_WKXvY&t=1013s) Code quality tools ecosystem  
* [18:50](https://www.youtube.com/watch?v=G1lDk_WKXvY&t=1130s) Automating for local environment  
* [21:22](https://www.youtube.com/watch?v=G1lDk_WKXvY&t=1282s) Automating for a team/project environment  
* [23:24](https://www.youtube.com/watch?v=G1lDk_WKXvY&t=1404s) Benefits of automated quality check setup  
* [24:20](https://www.youtube.com/watch?v=G1lDk_WKXvY&t=1460s) Best practices  
* [27:30](https://www.youtube.com/watch?v=G1lDk_WKXvY&t=1650s) Recap

## 10. [Nina Zakharenko - Code Review Skills for Pythonistas](https://www.youtube.com/watch?v=6L3ZVLtSeo8)

A talk by [Nina Zakharenko](https://twitter.com/nnja) on reviewing code as team and projects grow and how support maintainability of complex code bases. In this talk she covers guidelines for writing consistent python code beyond PEP 8 standards, the tools to automate them, etc.

### 10.1. Key take aways

1. Code reviews gives a sense of shared owenership and knowledge
2. Lottery factor is the measurement of how much concentrated specialized knowledge belongs to one individual. Using code review we can avoid that
3. Code should fit your company's style and expectations. Reviews should encourage consistency for code longevity
4. Code review should be done by your peers, not management
5. The code submitted for review should be small and relevant as it makes the reviewer overwhelmed
6. Use linter
7. Use vulture.py to find dead or unreachable code
8. Be objective, avoid condescending terms, have clear feedback and offer suggestions and compliments while revieweing
9. Try to do reviews in 24-48 hours

### Timeline

* [04:18](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=258s) Why code review?  
* [05:00](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=300s) Code review benefits  
* [07:05](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=425s) Code review guidelines  
* [10:06](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=606s) Consistent code  
* [13:20](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=800s) Stages of review  
* [13:32](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=812s) Stage 0: Before Submission  
* [15:40](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=940s) Stage1: Submitted  
* [16:08](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=968s) Stage 2: Work in progress  
* [17:04](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=1024s) Stage 3: Almost Done  
* [18:22](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=1102s) Automated tools  
* [22:18](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=1338s) Testing  
* [24:25](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=1465s) Stage 4: Review Complete  
* [28:07](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=1687s) Being a great Reviewer  
* [39:11](https://www.youtube.com/watch?v=6L3ZVLtSeo8&t=2351s) Summary

## 11. [Erik Rose Constructive Code Review PyCon 2017](https://www.youtube.com/watch?v=iNG1a--SIlk)

A talk by [Erik Rose](https://twitter.com/ErikRose) on have to make constructive code reviews and not sound like a condescending prick! A great talk on being encouragin, boosting skills and quality of developers by being a good reviewer. Coding is creative work and creative work is powered by enthusiasm.

### 11.1. Key take aways

1. Coding is creative work and creative work is powered by enthusiasm
2. Our review comments must be descriptive, objective and durable
3. Use "we" or "this" rather than "you" when it comes to giving advise or reviews
4. Add compliments to ease in and make the developers feel comfortable, but don't be sarcastic
5. When submitting long code blocks for review, give an overview of the path, use long commit messages but short commits and use comments, docstrings, proper naming to make it easier for reviewers
6. When coding long code blocks, its not easy to make small commit, so stage them and then commit them
7. Do not nitpick
8. Do not take it too hard when someone reviews your code and room for improvement was suggested
9. Organize your mailbox with proper filter to increase productivity
10. For new comers:
    1. Provide them with docs to refer and learn by themselves
    2. After they are finished with the basics, ask them to look at code and fix them and learn code reviews
    3. They write the tests themselves and they code themselves now

11. Articulate emotions
12. Be sincere and never talk down to people
13. Ask questions rather than pointing things out

### 11.2. Timeline

* [05:35](https://www.youtube.com/watch?v=iNG1a--SIlk&t=335s) Clarity of Explanation  
* [08:29](https://www.youtube.com/watch?v=iNG1a--SIlk&t=509s) Tact hacks  
* [12:33](https://www.youtube.com/watch?v=iNG1a--SIlk&t=753s) Antipatterns  
* [23:14](https://www.youtube.com/watch?v=iNG1a--SIlk&t=1394s) Emotional Issues  
* [41:22](https://www.youtube.com/watch?v=iNG1a--SIlk&t=2482s) Review Checklist  
* [41:47](https://www.youtube.com/watch?v=iNG1a--SIlk&t=2507s) QnA

## 12. [Anthony Shaw - Wily Python: Writing simpler and more maintainable Python - PyCon 2019](https://www.youtube.com/watch?v=dqdsNoApJ80)

A talk by [Anthony Shaw](https://twitter.com/anthonypjshaw) on wily python and using complexity metric to measure complexity in code and refactor and maintain them.

### 12.1. Key take aways

1. Code must be easy to understand
2. Fewer lines doesn't mean less complexity, readability counts
3. Cyclomatic complexity is when you have to understand all the decisions which are made, while reading the code. This is caused by over nesting
4. Halstead Metrics is a metric used to measure complexity in code
5. Maintainability Index = 171 - 5.2ln(Halstead Volume) - 0.23(Cyclomatic Complexity) - 16.2ln(Line of Code). Higher the score, the better
6. Radon is used for calculating these metrics
7. Wily is a python library tool that looks at the way the maintainability and complexity of your code changes at every revision
8. While refactoring your code, make sure spread complexity around your code and ensure the single responsibility principle
9. The single responsibility principle is making sure that every function or a piece of code, should only have one single responsibility. No code should try to achieve everything as it becomes more difficult to maintain
10. While refactoring, there should be high test covereage
11. Complexity measure is long term
12. Refactor your code often. While refactoring, don't try to refactor the entire code. Do it one by one

### 12.2 Timeline

* [05:12](https://www.youtube.com/watch?v=dqdsNoApJ80&t=312s) Cyclomatic Complexity  
* [10:12](https://www.youtube.com/watch?v=dqdsNoApJ80&t=612s) Halstead Metrics  
* [13:18](https://www.youtube.com/watch?v=dqdsNoApJ80&t=798s) Maintainability Index  
* [14:56](https://www.youtube.com/watch?v=dqdsNoApJ80&t=896s) Radon  
* [16:12](https://www.youtube.com/watch?v=dqdsNoApJ80&t=972s) Wily  
* [16:54](https://www.youtube.com/watch?v=dqdsNoApJ80&t=1014s) Demo  
* [20:08](https://www.youtube.com/watch?v=dqdsNoApJ80&t=1208s) Gravity of Complexity  
* [21:36](https://www.youtube.com/watch?v=dqdsNoApJ80&t=1296s) Testing and refactoring  
* [24:01](https://www.youtube.com/watch?v=dqdsNoApJ80&t=1441s) Summary  
* [26:40](https://www.youtube.com/watch?v=dqdsNoApJ80&t=1600s) QnA

## 13. [How To Publish A Package On PyPI](https://www.youtube.com/watch?v=QgZ7qv4Cd0Y)

A talk by [Mark Smith](https://twitter.com/judy2k) on building a package from scratch and publishing it on PyPI with the best practices.

### 13.1. Key take aways

1. Copying and pasting is not how you share code
2. To create a package, you need a `setup.py` and the code is kept inside the packar directory named `src`
3. You create a package using `bdist_wheel` which can be then used to installed
4. `pip install -e` the `-e` allows you to link the source files rather copying them into the python packages directory
5. In `readme` file, include title, description, installation instructions and usage instructions
6. `setup.py` is for production dependencies and `pipfile` is for development requirements
7. Production dependencies should be as relaxed as possible and development requirements must be fixed/locked
8. You can use cookie cutter to build and test packages

### 13.2. Timeline

* [03:58](https://youtu.be/QgZ7qv4Cd0Y?t=238) Making a package
* [08:08](https://youtu.be/QgZ7qv4Cd0Y?t=488) Housekeeping and Licensing
* [09:46](https://youtu.be/QgZ7qv4Cd0Y?t=586) Documentation
* [11:43](https://youtu.be/QgZ7qv4Cd0Y?t=703) Testing (pytest)
* [12:12](https://youtu.be/QgZ7qv4Cd0Y?t=732) Creating a Pipfile
* [14:13](https://youtu.be/QgZ7qv4Cd0Y?t=853) Setup vs Pipfile
* [15:12](https://youtu.be/QgZ7qv4Cd0Y?t=912) Running tests
* [15:41](https://youtu.be/QgZ7qv4Cd0Y?t=941) Source Distribution
* [17:56](https://youtu.be/QgZ7qv4Cd0Y?t=1076) Publish
* [19:39](https://youtu.be/QgZ7qv4Cd0Y?t=1179) Production
* [25:20](https://youtu.be/QgZ7qv4Cd0Y?t=1520) Cookie cutter

## 14. [Thea Flowers - Break the Cycle: Three excellent Python tools to automate repetitive tasks](https://www.youtube.com/watch?v=-BHverY7IwU)

A talk by [Thea Flowers](https://twitter.com/theavalkyrie) discussing 3 open-source tools that help in automating mundane tasks. It doesn't explain it in depth but it is a great starting point.

### 14.1. Key take aways

1. [tox](https://pypi.org/project/tox/) tool aims to standardize python package testing
2. [nox](https://pypi.org/project/nox/) is for flexible test automation
3. [invoke](https://pypi.org/project/invoke/) is a tool framework for python task execution tool
4. invoke is very flexible since it uses tasks

### 14.2. Timeline

* [08:28](https://www.youtube.com/watch?v=-BHverY7IwU&t=508s) tox tool  
* [13:07](https://www.youtube.com/watch?v=-BHverY7IwU&t=787s) Nox tool  
* [18:45](https://www.youtube.com/watch?v=-BHverY7IwU&t=1125s) invoke tool  
* [23:10](https://www.youtube.com/watch?v=-BHverY7IwU&t=1390s) summary

## 15. [Carol Willing - Practical Sphinx - PyCon 2018](https://www.youtube.com/watch?v=0ROZRNZkPS8)

A talk by [Carol Willing](https://twitter.com/WillingCarol) on sphinx so integrate documentation into everyday development workflow and applying best practices

### 15.1. Key take aways

1. Different people use different formats for documentation, so you can use Sphinx to compile it
2. pandoc is great for converting to and from different text file formats
3. Write drafts, just normal important content and worry about quality of documentation later
4. toctree gives structure to your documentation

### 15.2. Timeline

* [5:00](https://www.youtube.com/watch?v=0ROZRNZkPS8&t=300s) Basics: install sphinx, create a project, file structures, build and serve  
* [8:22](https://www.youtube.com/watch?v=0ROZRNZkPS8&t=502s) Words: source format (reStructuredText, Markdown, Notebooks, pandoc), content first, quality latter, spelling check tools  
* [13:50](https://www.youtube.com/watch?v=0ROZRNZkPS8&t=830s) Visuals: images, directives (warning, see also, code, etc.)  
* [15:43](https://www.youtube.com/watch?v=0ROZRNZkPS8&t=943s) Structure: toctree, caption  
* [17:00](https://www.youtube.com/watch?v=0ROZRNZkPS8&t=1020s) Workflow: testing, automate, host, monitoring, feedback  
* [19:43](https://www.youtube.com/watch?v=0ROZRNZkPS8&t=1183s) Extensions: autodoc, generating documentation by docs strings  
* [22:00](https://www.youtube.com/watch?v=0ROZRNZkPS8&t=1320s) Sphinx, JavaScript and Beautiful Design: pros of Sphinx, communities, comparison with JavaScripts tools, themes, customization

## 16. [Dougal Matthews - MkDocs: Documenting projects with Markdown](https://www.youtube.com/watch?v=pzoOQg6BNG4)

A talk by [Dougal Mathews](https://twitter.com/d0ugal) on documenting projects with MkDocs. It covers about markdown documents, how and why the project started and who uses MkDocs today.

### 16.1. Key take aways

1. You can create documents easily using `.md` and `.yaml` in MkDocs
2. You don't need any major python coding and it is very easy to deploy and integrate

### 16.2. Timeline

* [00:00](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=0s) Introduction  
* [01:44](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=104s) Project Goals  
* [03:13](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=193s) Who uses MkDocs  
* [04:36](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=276s) Why use MkDocs  
* [05:33](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=333s) MkDocs Overview  
* [07:05](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=425s) Getting started  
* [13:12](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=792s) Interlinking  
* [14:11](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=851s) Configuration  
* [14:00](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=840s) Deploying  
* [15:25](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=925s) Themes  
* [16:22](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=982s) Future developments  
* [18:02](https://www.youtube.com/watch?v=pzoOQg6BNG4&t=1082s) QnA

## 17. [How to do coding peer reviews with Github](https://www.youtube.com/watch?v=8fx-EaOUK2E)

A video from [London App Developer](https://www.youtube.com/channel/UC3RtgbslbAvE-5FFBkSgpig) on coding peer reviews using GitHub to improve the quality of code.

### 17.1. Key take aways

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
