# Video Summaries

## 1. [VA Meetup: Pythonic code techniques for developers and data scientists](https://www.youtube.com/watch?v=e-56wLh30xc)

This is talk given by [Michael Kennedy](https://www.youtube.com/channel/UCB2z8yryU2efaHA74MoDN8w) teaching us different, very useful, Pythonic code techniques. He explains well with great examples which is easy to understand. The video is simple and fun to watch and Michael explains the concept really well and tells us exactly how pythoneers must code!

### 1.1. Key take aways

1. Use pythons string formatting options for concats
2. Don't try to loop over collections using index. It's not the pythonic way
3. Python uses EAFF error handling strategy

### 1.2. Timeline

* [05:04](https://youtu.be/e-56wLh30xc?t=304) strings
* [11:36](https://youtu.be/e-56wLh30xc?t=696) Merging dictionaries
* [18:37](https://youtu.be/e-56wLh30xc?t=1117) Tuples
* [25:48](https://youtu.be/e-56wLh30xc?t=1548) Error handling
* [31:27](https://youtu.be/e-56wLh30xc?t=1887) Lambdas
* [41:55](https://youtu.be/e-56wLh30xc?t=2515) Generators
* [58:54](https://youtu.be/e-56wLh30xc?t=3534) __slots__

## 2. [Transforming Code into Beautiful, Idiomatic Python](https://www.youtube.com/watch?v=OSGv2VnC0go)

This talk given by [Raymond Hettinger](https://twitter.com/raymondh), who is python core developer and has made significant contributions to the python project! He covers a range of functions, generators, python way of writing python code and more with a great style of teaching. All over the talk was very informative and funny. Do keep in mind that most of what he explained was originally for the older versions of python, so go back to the python docs and see what changed. Definitely take a look!

### 2.1. Key take aways

1. python `for` is not the same as other languages `for`. It is actually `foreach`
2. Use generators or iterables instead for looping through the entire collection
3. Don't try to create simple functions, use lambda instead
4. Try to use tuples packing and unpacking instead of temporary variables for swapping and other functionalities
5. Try to use list comprehensions and other python one liners

### 2.2. Timeline

* [03:04](https://www.youtube.com/watch?v=OSGv2VnC0go&t=184s) Looping over a range of functions  
* [04:47](https://www.youtube.com/watch?v=OSGv2VnC0go&t=287s) Looping over a collection  
* [05:28](https://www.youtube.com/watch?v=OSGv2VnC0go&t=328s) Looping backwards  
* [06:51](https://www.youtube.com/watch?v=OSGv2VnC0go&t=411s) Looping over a collection of indicies  
* [07:36](https://www.youtube.com/watch?v=OSGv2VnC0go&t=456s) Looping over two collections  
* [09:42](https://www.youtube.com/watch?v=OSGv2VnC0go&t=582s) Looping in sorted order  
* [10:04](https://www.youtube.com/watch?v=OSGv2VnC0go&t=604s) Custom sort order  
* [12:27](https://www.youtube.com/watch?v=OSGv2VnC0go&t=747s) Call a function until a sentinel value  
* [15:52](https://www.youtube.com/watch?v=OSGv2VnC0go&t=952s) Distinguishing multiple exit points in loops  
* [19:18](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1158s) Looping over dictionary keys  
* [21:10](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1270s) Looping over dictionary keys and values  
* [21:52](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1312s) Construct a dictionary from pairs  
* [23:15](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1395s) Counting with dictionaries  
* [25:30](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1530s) Grouping with dictionaries  
* [27:57](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1677s) Is a dictionary pop() atomic?  
* [29:12](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1752s) Linking dictionaries  
* [31:10](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1870s) Clarify function calls with keyword arguments  
* [32:17](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1937s) Clarify multiple return values with named tuples  
* [33:13](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1993s) Unpacking sequences  
* [34:01](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2041s) Updating multiple state variables  
* [36:15](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2175s) Simultaneous state updates  
* [38:24](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2304s) Concatenating strings  
* [38:41](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2321s) Updating sequences  
* [39:57](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2397s) Using decorators to factor-out administrative logic  
* [40:24](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2424s) Caching decorator  
* [41:19](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2479s) Factor-out temporary contexts for decimal  
* [42:01](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2521s) How to open and close files  
* [42:25](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2545s) How to use locks  
* [43:10](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2590s) Factor-out temporary contexts  
* [44:56](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2696s) Context manager: redirect_stdout()  
* [46:04](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2764s) Concise expressive one-liners

## 3. [Stop Writing Classes](https://www.youtube.com/watch?v=o9pEzgHorH0)

A talk by [Jack Diederich](https://twitter.com/jackdied) on problems of over usage of classes in out code. It has a different perspective and points out the mistakes made by us creating classes and sub-classes when in fact a function would just be fine. The talk gives examples of class overuse and how you can refactor the unnecessary classes, exception and modules away from your code, making it more readable to developers and even reduce total lines of code and hence increasing performance.

### 3.1. Key take aways

1. Classes are useful but not when it is not needed
2. Simple is always better
3. Practicality beats standard conventions
4. Don't try reinventing the wheel. Use the existing tools and save time
5. Make it readable
6. The proper way is not always the right way
7. Don't try to create empty class, functions, etc. as placeholders for future functionality. Code what is required for now and add in later

### 3.2. Timeline

* [1:03](https://youtu.be/o9pEzgHorH0?t=64) don't do hard things in the first place
* [3:48](https://youtu.be/o9pEzgHorH0?t=228) standard lib: functools.partial
* [3:58](https://youtu.be/o9pEzgHorH0?t=238) Classes give us lovely things
* [4:33](https://youtu.be/o9pEzgHorH0?t=273) Example of over usage of classes
* [9:27](https://youtu.be/o9pEzgHorH0?t=567) Namespaces
* [11:58](https://youtu.be/o9pEzgHorH0?t=718) Python standard library
* [12:48](https://youtu.be/o9pEzgHorH0?t=768) When to use class
* [20:33](https://youtu.be/o9pEzgHorH0?t=1233) QnA

## 4. [PEP 20 Presentation - Zen of Python](https://www.youtube.com/watch?v=PHSAVai7yx4)

This is a very short video teaching us the key coding methodology to remember when coding in python.

### 4.1. Key take aways

1. Beautiful code is achieved through a combination of explicit, simple sparse and flat attributes to ensure readability
2. Explicit is better than implicit
3. Simple is better than complex, complex is better than complicated
4. Sparse is better than dense
5. Errors should not be passed silently. Give message when it occurs
6. Guido Van Rossum is the creator of Python

## 5. [Practicality Beats Purity: The Zen of Python’s Escape Hatch?](https://www.youtube.com/watch?v=XU9_3AlCy84)

A very interesting perspective by [Christopher Neugebauer](https://twitter.com/chrisjrn) showing the other side of The Zen of Python and how it doesn't hold up to being truly pythonic.

### 5.1. Key take aways

1. Zen of python isn't prescriptive
2. Decorators doen't modify function behaviour, but rather changes the decorator of the function
3. `@property` is pythonic
4. In python types are not enforced so it needs to be tested and porting code is hard
5. Zen of python doesn't solve Type hints argument
6. Practicality beats purity
7. PEP 8 is a style guide which is better to follow

### 5.2. Timeline

* [03:15](https://youtu.be/XU9_3AlCy84?t=195) Zen of Python
* [05:15](https://youtu.be/XU9_3AlCy84?t=315) Decorators
* [10:16](https://youtu.be/XU9_3AlCy84?t=616) Type Hints
* [14:16](https://youtu.be/XU9_3AlCy84?t=856) Practicality beats purity
* [16:43](https://youtu.be/XU9_3AlCy84?t=1003) Python doesn't tell you how to do things
* [18:21](https://youtu.be/XU9_3AlCy84?t=1101) Switch statement and pattern matching
* [21:46](https://youtu.be/XU9_3AlCy84?t=1306) Never is often better than right now

## 6. [10 Python Tips and Tricks For Writing Better Code](https://www.youtube.com/watch?v=C-gEQdGVXbk)

A video by [Corey Schafer](https://www.youtube.com/channel/UCCezIgC97PvUuR4_gbFUs5g) giving us more pythonic ways of writing python code.

### 6.1. Key take aways

1. Use `_` as numerical separators or delims for long numbers
2. Use string formating to diplay numbers with commas `print(f"{number_var:,}')`
3. Use `with open('file.txt', 'r') as f` context managers to handle files, thread, connection or any resources that needs to be managed
4. Use `enumerate` to loop over lists.
5. In unpacking you can use `*<variable>` to take all/subset of the unpacked values into a list variable
6. Class can have dynamic attributes
7. Use `setattr()` to create the attribute in the class using a string as param
8. Use `getattr()` to get/find the attribute of the class via a string
9. For terminals if you want to hide your input (for passwords) use `getpass()` `from getpass import getpass`
10. In `python -m`, `-m` argument is for running a specific module
11. Use `help()`, `dir()` to know more about functions, datatypes, modules etc.

### 6.2. Timeline

* [00:34​](https://www.youtube.com/watch?v=C-gEQdGVXbk&t=34s) Ternary Conditionals
* [02:13​](https://www.youtube.com/watch?v=C-gEQdGVXbk&t=133s) Underscore Placeholders
* [04:25](https://www.youtube.com/watch?v=C-gEQdGVXbk&t=265s) Context Managers
* [06:50​](https://www.youtube.com/watch?v=C-gEQdGVXbk&t=410s) Enumerate
* [08:52​](https://www.youtube.com/watch?v=C-gEQdGVXbk&t=532s) Zip
* [13:02​](https://www.youtube.com/watch?v=C-gEQdGVXbk&t=782s) Unpacking
* [19:08​](https://www.youtube.com/watch?v=C-gEQdGVXbk&t=1148s) Setattr/Getattr
* [26:24​](https://www.youtube.com/watch?v=C-gEQdGVXbk&t=1584s) GetPass
* [29:18​](https://www.youtube.com/watch?v=C-gEQdGVXbk&t=1758s) Python dash m
* [33:17​](https://www.youtube.com/watch?v=C-gEQdGVXbk&t=1997s) Help/Dir

## 7. [25 Python Tips + Tricks](https://www.youtube.com/watch?v=y4I3VI1N_ts)

A very helpful video by [Caleb Curry](https://www.youtube.com/channel/UCZUyPT9DkJWmS_DzdOi7RIA) which covers all frequent use cases in python. The video is to the point and explained briefly.

### 7.1. Key take aways

1. Use itertools and generators
2. You can preserve all data when merging two lists with unequal number of elements using zip_longest

### 7.2. Timeline

* [00:00](https://www.youtube.com/watch?v=y4I3VI1N_ts) Introduction  
* [00:43](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=43s) Wrapping a Primitive to change within function  
* [02:09](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=129s) Compare identity with is  
* [02:27](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=147s) Add a method dynamically  
* [02:50](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=170s) Compare by Value  
* [03:20](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=200s)Class parenthesis optional but not function parenthesis  
* [03:46](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=226s) Get current date and time  
* [04:17](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=257s) Countdown  
* [04:55](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=295s) Elapsed time  
* [05:24](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=324s) Parentheses for operations with object members  
* [06:54](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=414s) Runtime error vs syntax error  
* [07:52](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=472s) Get a random number  
* [08:13](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=493s) Import with Alias  
* [05:58](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=358s) Generators and Yield  
* [11:09](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=669s) Infinite number  
* [12:11](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=731s) Infinite generator  
* [12:47](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=767s) list from generator  
* [13:37](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=817s) itertools for simple infinite generator  
* [14:48](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=888s) Iterate through custom type with iter  
* [16:00](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=960s) Falsey for custom types (not)  
* [17:13](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1033s) Combine two lists as a list of lists  
* [17:39](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1059s) Convert list of tuples to list of lists  
* [18:11](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1091s) Preserving all data when zipping with zip_longest  
* [18:55](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1135s) Default Arguments  
* [19:30](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1170s) Keyword Arguments  
* [20:14](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1214s) Get the Python version

## 8. [20 Python Tips and Tricks - Why We Love Python](https://www.youtube.com/watch?v=sbtbIqEG4nI)

A great video from [Tech with Tim](https://www.youtube.com/channel/UC4JX40jDee_tINbkjycV4Sg) which gives us more tips and tricks in python. It is useful and it is explained really well.

### 8.1. Key take aways

1. Create enums using `range()` unpacking
2. Use `f""` string for formating and concating.
3. Find different functions or properties of a class or type using `dir(<class_type>)`
4. Ignore unpacked variable using `_`
5. To get count of elements in `x` list just use `max(set(x), key = x.count)`
6. To repeat string multiple times use the `*` operator
7. To print each element in a list do `print(*x)`
8. Use `*` to get mutliple params in a function and `**` to pass a dictionary of arguments to the functions

### 8.2 Timeline

* [0:09](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=9s) this (module)  
* [0:52](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=52s) Enum (class)  
* [1:34](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=94s) multiline assignment  
* [2:20](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=140s) Fstrings  
* [3:19](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=199s) list enumeration  
* [4:14](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=254s) zip (function)  
* [5:51](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=351s) help (function)  
* [6:41](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=401s) DIR (function)  
* [7:42](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=462s) list comprehension  
* [9:23](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=563s) Anonymous variable  
* [10:28](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=628s) concatenation list elements to string  
* [11:16](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=676s) slicing  
* [11:40](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=700s)  _hello_ (module)  
* [11:49](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=709s) sys (module)  
* [12:27](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=747s) most frequent item in list  
* [13:48](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=828s) lambda (function)  
* [15:07](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=907s) antigravity (module)  
* [15:25](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=925s) string multiplication  
* [16:06](https://www.youtube.com/watch?v=sbtbIqEG4nI&t=966s) unpack (operator)

## 9. [10 Python Tips & Tricks That You Do Not Know || Python Clever Tips || Learn Python Shortcuts](https://www.youtube.com/watch?v=WEP3DVTjKCc)

A good video from [Programming Hero](https://www.youtube.com/channel/UCStj-ORBZ7TGK1FwtGAUgbQ) which gives us some everyday use tips and tricks with a great vibe.

### 9.1. Key take aways

1. For `if` you don't need to keep paranthesis like other languages
2. For many conditions, rather than listing them all in `if`, create a list of those conditions and give `if all(conditions)`. Using this we can even update our conditions easily in the list
3. You can remove duplicates in a list by converting it into a set. Set contains only unique values
4. To pass multiple values as arguments in your function use `def func(*a)`
5. You can reverse a string like so `string_var[::-1]`

### 9.2. Timeline

* [00:28](https://youtu.be/WEP3DVTjKCc?t=28) inputs
* [02:33](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=153s) use a list of conditions for if
* [06:44](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=404s) swapping using tuple unpacking
* [08:44](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=524s) remove duplicates using set
* [10:25](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=625s) get the value which is repeated most in a list
* [12:00](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=720s) list comprehension
* [14:47](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=887s) using `*` to pass multiple params in dunctions
* [16:56](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=1016s) reverse string with [::-1]
* [17:49](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=1069s) palindrome

## 10. [50 Python Tips and Tricks for Beginners](https://www.youtube.com/watch?v=F3T8tg2tVKM)

Another very helpful video by [Caleb Curry](https://www.youtube.com/channel/UCZUyPT9DkJWmS_DzdOi7RIA) with more extra tips and tricks in python.

### 10.1. Key take aways

1. To seperate digits in a number, use `_` which acts like `,` in numbers
2. To break a single line in python into multilines, use `\`
3. To create a string with line breaks, use `"""`
4. To check a substring in string you can use `in` or `find()`
5. `id()` gives you the address of a variable
6. `data = ['new']` creates a new list but `data[:] = ['new']` replaces the values inside the list without creating another one
7. Use `locals()` and `globals()` to get the alive variables
8. The is no `do... while()` in python, so you can use `while() if break`

### 10.2. Timeline

* [00:00](https://www.youtube.com/watch?v=F3T8tg2tVKM) Introduction  
* [00:41](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=41s) Assign Multiple Variables on One Line  
* [00:59](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=59s) Print Colored Text  
* [01:38](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=98s) Power operator  
* [01:55](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=115s) Banker’s Rounding  
* [02:36](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=156s) Underscores in numbers  
* [02:56](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=176s) Open a web browser  
* [03:10](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=190s) Concat without +  
* [03:28](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=208s) Split string on multiple lines  
* [04:06](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=246s) Multiline string  
* [04:25](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=265s) Multiline comment  
* [04:37](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=277s) Get last element of list  
* [05:05](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=305s) Reverse list with slicing  
* [05:32](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=332s) Reverse with method  
* [05:50](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=350s) Substring with in  
* [06:25](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=385s) single line if  
* [06:44](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=404s) get index with find  
* [07:23](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=443s) id to get identity  
* [07:48](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=468s) Aliases  
* [08:51](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=531s) Primitive types are immutable  
* [09:21](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=561s) in-place methods  
* [10:10](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=610s) Replace list vs replace list content  
* [12:33](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=753s) Copy list with slicing  
* [12:57](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=777s) Copy a list with method  
* [13:03](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=783s) Using deepcopy  
* [14:44](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=884s) concatenate lists  
* [14:59](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=899s) not data vs is none  
* [15:32](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=932s) Check empty list  
* [16:29](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=989s) Check if exists  
* [18:20](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1100s) Print end =" " to change ending  
* [18:49](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1129s) Print multiple elements with commas  
* [20:47](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1247s) String formatting for easy string making  
* [21:56](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1316s) Return multiple values and assign to multiple variables  
* [22:55](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1375s) Ternary conditional operator  
* [24:11](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1451s) Else can be used with loop  
* [26:58](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1618s) Use range to generate lists  
* [28:09](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1689s) Unpack operator  
* [29:10](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1750s) How to do nothing in Python with pass  
* [30:03](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1803s) Remove list duplicates  
* [30:51](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1851s) Using in instead of complex conditional - Check against list of values  
* [32:04](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=1924s) complex conditional - Evaluate against any condition  
* [33:21](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=2001s) complex conditional - Evaluate against all conditions  
* [33:28](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=2008s) Split from string to multiple variables  
* [34:43](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=2083s) Join data  
* [35:11](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=2111s) Removing certain elements from a list  
* [36:35](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=2195s) Iterate backwards with reversed  
* [37:19](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=2239s) No do-while loop in python  
* [38:46](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=2326s) Assigning a function to a variable - just don’t use ()  
* [39:53](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=2393s) Wait with time.sleep  
* [40:38](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=2438s) Get index with for loop  
* [41:23](https://www.youtube.com/watch?v=F3T8tg2tVKM&t=2483s) Flatten a list with nested list comprehension

## 11. [11 Tips And Tricks To Write Better Python Code](https://www.youtube.com/watch?v=8OKTAedgFYg)

A short video by [Python Engineer](https://www.youtube.com/channel/UCbXgNpp0jedKWcQiULLbDTA) channel on writing better python code

### 11.1. Key take aways

1. Iterate with enumerate instead or range(len(x))
2. Use list comprehension instead of raw for loops
3. Sort complex iterables with sorted()
4. Store unique values with Sets
5. Save memory with Generators
6. Define default values in Dictionaries with .get() and .setdefault()
7. Count hashable objects with collections.Counter
8. Format strings with f-Strings (Python 3.6+)
9. Concatenate strings with .join()
10. Merge dictionaries with {\*\*d1, \*\*d2} (Python 3.5+)
11. Simplify if-statements with if x in list

### 11.2. Timeline

* [00:20](https://youtu.be/8OKTAedgFYg?t=20) Iterate with enumerate instead or range(len(x))
* [01:03](https://youtu.be/8OKTAedgFYg?t=63) Use list comprehension instead of raw for loops
* [01:47](https://youtu.be/8OKTAedgFYg?t=107) Sort complex iterables with sorted()
* [02:58](https://youtu.be/8OKTAedgFYg?t=178) Store unique values with Sets
* [03:40](https://youtu.be/8OKTAedgFYg?t=220) Save memory with Generators
* [05:00](https://youtu.be/8OKTAedgFYg?t=301) Define default values in Dictionaries with .get() and .setdefault()
* [06:05](https://youtu.be/8OKTAedgFYg?t=365) Count hashable objects with collections.Counter
* [07:38](https://youtu.be/8OKTAedgFYg?t=458) Format strings with f-Strings (Python 3.6+)
* [08:21](https://youtu.be/8OKTAedgFYg?t=501) Concatenate strings with .join()
* [09:26](https://youtu.be/8OKTAedgFYg?t=566) Merge dictionaries with {\*\*d1, \*\*d2} (Python 3.5+)
* [09:58](https://youtu.be/8OKTAedgFYg?t=598) Simplify if-statements with if x in list

## 12. [Trey Hunner Readability Counts PyCon 2017](https://www.youtube.com/watch?v=knMg6G9_XCg)

A great talk by [Trey Hunner](https://twitter.com/treyhunner) during the PyCon 2017 conference. The talks explains really well different coding styles and techniques to make our program more readable.

### 12.1. Key take aways

1. Don't try to focus on code line length
2. Use verbose mode for regular expressions to make it more readable
3. Wrap our arguments in our function
4. Follow PEP 8 python style guide
5. Use PEP 8 as a reference not as a rule book
6. Use descriptive names not 2 letter variables in python
7. Don't arbitrary indexes but use tuple unpacking
8. Use another method that return boolean when your if statement is too long
9. Read code aloud and see if it feels easy to read
10. Refactor your code to make it more self documented
11. Insert empty line breaks to divide your code into code blocks
12. Instead of having huge chunks in a single function have multiple functions inside a single function each performing each chuck of code to make it more readable
13. Dunder methods are methods with `__<method>__`
14. Use list comprehension instead of using `for`
15. Try to use built in python operators
16. If your chain of functions are passing and returning the same variable, consider using class

### 12.2. TImeline

* [00:00](https://www.youtube.com/watch?v=knMg6G9_XCg) Introduction
* [03:21](https://youtu.be/knMg6G9_XCg?t=201) Structuring Code
* [05:01](https://youtu.be/knMg6G9_XCg?t=301) Regular Expressions
* [06:36](https://youtu.be/knMg6G9_XCg?t=396) Function calls
* [08:42](https://youtu.be/knMg6G9_XCg?t=522) PEP 8
* [09:59](https://youtu.be/knMg6G9_XCg?t=599) Naming things
* [16:02](https://youtu.be/knMg6G9_XCg?t=962) So many functions
* [18:23](https://youtu.be/knMg6G9_XCg?t=1103) Recap
* [18:53](https://youtu.be/knMg6G9_XCg?t=1133) Programming idioms
* [19:26](https://youtu.be/knMg6G9_XCg?t=1166) Clean up
* [21:04](https://youtu.be/knMg6G9_XCg?t=1264) Lists from lists
* [22:21](https://youtu.be/knMg6G9_XCg?t=1341) Operator overloading
* [24:10](https://youtu.be/knMg6G9_XCg?t=1450) Abstract base class
* [24:24](https://youtu.be/knMg6G9_XCg?t=1464) Shared Data
* [25:02](https://youtu.be/knMg6G9_XCg?t=1502) Recap 2

## 13. [Mariano Anaya: Clean code in Python](https://www.youtube.com/watch?v=n_Y-_7R2KsY)

A talk by [Mariano Anaya](https://twitter.com/rmarianoa)

### 13.1. Key take aways

1. We spend more time reading code than writing, so focus on readability
2. Duplicated code is hard to maintain and error prone
3. Use decorators to modify a function with changed logic
4. Differentiate business logic and implementation logic
5. Avoid writing getter and setter methods for classes use `@property`
6. Use context managers to maintain state of resources
7. Be pythonic
8. Use docstrings, PEP 8, unit tests, linters etc

### 13.2. Timeline

* [00:59](https://www.youtube.com/watch?v=n_Y-_7R2KsY&t=59s) Introduction  
* [04:19](https://www.youtube.com/watch?v=n_Y-_7R2KsY&t=259s) Don't Repeat yourself DRY  
* [05:38](https://www.youtube.com/watch?v=n_Y-_7R2KsY&t=338s) Decorators  
* [08:37](https://www.youtube.com/watch?v=n_Y-_7R2KsY&t=517s) Implementation Details  
* [10:37](https://www.youtube.com/watch?v=n_Y-_7R2KsY&t=637s) @property  
* [12:51](https://www.youtube.com/watch?v=n_Y-_7R2KsY&t=771s) Maintaining State using context managers  
* [14:52](https://www.youtube.com/watch?v=n_Y-_7R2KsY&t=892s) Pythonic  
* [15:26](https://www.youtube.com/watch?v=n_Y-_7R2KsY&t=926s) Summary  
* [19:12](https://www.youtube.com/watch?v=n_Y-_7R2KsY&t=1152s) QnA

## 14. [Readability Counts: Best Practices in Python Coding](https://www.youtube.com/watch?v=ubGeHQRjNog)

In this webinar, bootcamp instructor Alex Baransky discussed popular Python coding conventions and how you can incorporate them into your work to increase your code's readability. It is a very detailed webinar with a lot of tips and tricks.

### 14.1. Key take aways

1. `import this` to take a look at the "Zen of Python"
2. Try to avoid `l` (lowercase letter el), `O` (uppercase letter oh) or `I` (uppercase letter eye) as a single character and they are pretty hard to distinguish
3. Avoid using python keywords and built-in function/class names as variable names. Use an `_` if you have to use it
4. Modules should have short lowercase names
5. Constants should be created with UPPERCASE
6. Avoid single letter variable, it should only be used while representing index values.
7. Use descriptive variable and function names
8. Use docstring for documentation
9. In documentation don't describe how a function or class works, but what it does and how to use it
10. In docstring for params use `param: Description -> <object_type>`
11. In docstring for function in class doc use `<function_name>: Description`
12. In docstring functions tell what it does, the arguments it need and what it returns
13. For recursive functions, comment the base condition (exit condition) and where the function calls itself
14. Don't do this `func ()`
15. PEP 8 suggests ***not to have more than 79 characters*** on a single line
16. On splitting a mathematical statement make sure the ***operator preceeds the operand***
17. Make sure indentation is aligned
18. Break huge chunks of code into small separate functions
19. Write your code as explicitly as possible
20. Don't do `from <library> import *` as there can be conflicting names
21. For some packages like `pandas` use the standard alias typically used, here `pd`
22. Try to make code simple, but while doing so if it looks complicated, you rather have it complex to increase efficiency
23. For arrays each row should be in each line
24. Don't try to nest code, make it as flat as possible
25. Don't make deep packages
26. Don't try to explain every single thing
27. Errors should not pass silently, unless explicitly silenced
28. Raise errors to alert users for params/input validations
29. Don't make your code ambiguous, as not every programmer can read it
30. Implementation should be easy to explain
31. Don't go overboard trying to make code unreasonably robust. Solve immediate issues

### 14.2. Timeline

* [01:30](https://www.youtube.com/watch?v=ubGeHQRjNog&t=90s) Introduction  
* [04:25](https://www.youtube.com/watch?v=ubGeHQRjNog&t=265s) Why write Interpretable code?  
* [09:30](https://www.youtube.com/watch?v=ubGeHQRjNog&t=570s) Naming Conventions  
* [17:45](https://www.youtube.com/watch?v=ubGeHQRjNog&t=1065s) Names to avoid  
* [19:55](https://www.youtube.com/watch?v=ubGeHQRjNog&t=1195s) Modules and packages  
* [20:10](https://www.youtube.com/watch?v=ubGeHQRjNog&t=1210s) Variables and functions  
* [31:09](https://www.youtube.com/watch?v=ubGeHQRjNog&t=1869s) Classes, Class methods and arguments  
* [36:30](https://www.youtube.com/watch?v=ubGeHQRjNog&t=2190s) Documentation  
* [44:10](https://www.youtube.com/watch?v=ubGeHQRjNog&t=2650s) Commenting  
* [50:00](https://www.youtube.com/watch?v=ubGeHQRjNog&t=3000s) Beautiful code  
* [51:45](https://www.youtube.com/watch?v=ubGeHQRjNog&t=3105s) Spacing  
* [57:07](https://www.youtube.com/watch?v=ubGeHQRjNog&t=3427s) Maximum character in a line  
* [01:01:10](https://www.youtube.com/watch?v=ubGeHQRjNog&t=3670s) using keywords  
* [01:05:40](https://www.youtube.com/watch?v=ubGeHQRjNog&t=3940s) Helper functions  
* [01:13:29](https://www.youtube.com/watch?v=ubGeHQRjNog&t=4409s) Writing explicit code  
* [01:15:12](https://www.youtube.com/watch?v=ubGeHQRjNog&t=4512s) Calling objects from modules or packages  
* [01:18:26](https://www.youtube.com/watch?v=ubGeHQRjNog&t=4706s) Write simple code  
* [01:24:33](https://www.youtube.com/watch?v=ubGeHQRjNog&t=5073s) complex is better than complicated  
* [01:33:31](https://www.youtube.com/watch?v=ubGeHQRjNog&t=5611s) Flat is better than nested  
* [01:37:27](https://www.youtube.com/watch?v=ubGeHQRjNog&t=5847s) Modules and packages  
* [01:38:28](https://www.youtube.com/watch?v=ubGeHQRjNog&t=5908s) Sparse is better than Dense  
* [01:45:08](https://www.youtube.com/watch?v=ubGeHQRjNog&t=6308s) Error should never pass silently  
* [01:50:50](https://www.youtube.com/watch?v=ubGeHQRjNog&t=6650s) Raising errors  
* [01:52:20](https://www.youtube.com/watch?v=ubGeHQRjNog&t=6740s) Ambiguity  
* [01:56:36](https://www.youtube.com/watch?v=ubGeHQRjNog&t=6996s) Implementation should be easy to explain  
* [01:58:30](https://www.youtube.com/watch?v=ubGeHQRjNog&t=7110s) Now is better than never. Although, never is often better than right now  
* [02:01:33](https://www.youtube.com/watch?v=ubGeHQRjNog&t=7293s) Conclusion

## 15. [Trey Hunner Hands On Intro to Python for New Programmers PyCon 2017](https://www.youtube.com/watch?v=6zu8lrYn6t8)

Once again from [Trey Hunner](https://twitter.com/treyhunner), a great tutorial for absolute python beginners given at PyCon 2017. Do keep in mind the video is really long

### 15.1. Key take aways

1. strings
2. scripts
3. conditions
4. lists
5. `append()` and `pop()`
6. `for` `while`
7. files

### 15.2. Timeline

* [01:01](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=61s) Talk starts  
* [10:03](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=603s) Python 3.6  
* [20:00](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=1200s) Strings  
* [28:40](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=1720s) Variables  
* [40:30](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=2430s) Scripts  
* [01:12:26](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=4346s) break  
* [01:29:00](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=5340s) continue  
* [01:31:00](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=5460s) conditions  
* [01:39:00](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=5940s) if else  
* [01:58:54](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=7134s) lists  
* [02:47:47](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=10067s) Loops  
* [02:51:23](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=10283s) Slices  
* [02:53:00](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=10380s) QnA  
* [03:04:47](https://www.youtube.com/watch?v=6zu8lrYn6t8&t=11087s) Files

## 16. [Anand Chitipothu - Writing Beautiful Code](https://www.youtube.com/watch?v=QIRyr6qvGrY)

A talk by [Anand Chitipothu](https://twitter.com/anandology) on writing code that is pleasant to read and maintain during the EuroPython 2017 conference.

### 16.1. Key take aways

1. Choose meaningful names
2. Avoid generic names, abbreviations, using datatype as a name
3. Use nouns for variables and classes and verbs for functions
4. Use plural for a list
5. Avoid single letter variable, it should only be used while representing index values.
6. Never use similar names for completely different datatypes
7. In comments, don't say the obvious. Instead, explain why it was done
8. The length of the variable is proportional to the scope of the variable

### 16.2. Timeline

* [02:24](https://www.youtube.com/watch?v=QIRyr6qvGrY&t=144s) Choose meaningful names  
* [10:28](https://www.youtube.com/watch?v=QIRyr6qvGrY&t=628s) Comments  
* [12:43](https://www.youtube.com/watch?v=QIRyr6qvGrY&t=763s) Program Organization  
* [18:42](https://www.youtube.com/watch?v=QIRyr6qvGrY&t=1122s) Summary  
* [20:20](https://www.youtube.com/watch?v=QIRyr6qvGrY&t=1220s) QnA
