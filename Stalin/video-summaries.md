# Video Summaries

## [VA Meetup: Pythonic code techniques for developers and data scientists](https://www.youtube.com/watch?v=e-56wLh30xc)

This is talk given by [Michael Kennedy](https://www.youtube.com/channel/UCB2z8yryU2efaHA74MoDN8w) teaching us different, very useful, Pythonic code techniques. He explains well with great examples which is easy to understand. The video is simple and fun to watch and Michael explains the concept really well and tells us exactly how pythoneers must code!

### Key take aways:

1. Use pythons string formatting options for concats
2. Don't try to loop over collections using index. It's not the pythonic way
3. Python uses EAFF error handling strategy

### Timeline

* [05:04](https://youtu.be/e-56wLh30xc?t=304) strings
* [11:36](https://youtu.be/e-56wLh30xc?t=696) Merging dictionaries
* [18:37](https://youtu.be/e-56wLh30xc?t=1117) Tuples
* [25:48](https://youtu.be/e-56wLh30xc?t=1548) Error handling
* [31:27](https://youtu.be/e-56wLh30xc?t=1887) Lambdas
* [41:55](https://youtu.be/e-56wLh30xc?t=2515) Generators
* [58:54](https://youtu.be/e-56wLh30xc?t=3534) __slots__

## [Transforming Code into Beautiful, Idiomatic Python](https://www.youtube.com/watch?v=OSGv2VnC0go)

This talk given by [Raymond Hettinger](https://twitter.com/raymondh), who is python core developer and has made significant contributions to the python project! He covers a range of functions, generators, python way of writing python code and more with a great style of teaching. All over the talk was very informative and funny. Do keep in mind that most of what he explained was originally for the older versions of python, so go back to the python docs and see what changed. Definitely take a look!

### Key take aways:

1. python `for` is not the same as other languages `for`. It is actually `foreach`
2. Use generators or iterables instead for looping through the entire collection
3. Don't try to create simple functions, use lambda instead
4. Try to use tuples packing and unpacking instead of temporary variables for swapping and other functionalities
5. Try to use list comprehensions and other python one liners

### Timeline

* [03:04](https://www.youtube.com/watch?v=OSGv2VnC0go&t=184s) -- Looping over a range of functions  
* [04:47](https://www.youtube.com/watch?v=OSGv2VnC0go&t=287s) -- Looping over a collection  
* [05:28](https://www.youtube.com/watch?v=OSGv2VnC0go&t=328s) -- Looping backwards  
* [06:51](https://www.youtube.com/watch?v=OSGv2VnC0go&t=411s) -- Looping over a collection of indicies  
* [07:36](https://www.youtube.com/watch?v=OSGv2VnC0go&t=456s) -- Looping over two collections  
* [09:42](https://www.youtube.com/watch?v=OSGv2VnC0go&t=582s) -- Looping in sorted order  
* [10:04](https://www.youtube.com/watch?v=OSGv2VnC0go&t=604s) -- Custom sort order  
* [12:27](https://www.youtube.com/watch?v=OSGv2VnC0go&t=747s) -- Call a function until a sentinel value  
* [15:52](https://www.youtube.com/watch?v=OSGv2VnC0go&t=952s) -- Distinguishing multiple exit points in loops  
* [19:18](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1158s) -- Looping over dictionary keys  
* [21:10](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1270s) -- Looping over dictionary keys and values  
* [21:52](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1312s) -- Construct a dictionary from pairs  
* [23:15](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1395s) -- Counting with dictionaries  
* [25:30](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1530s) -- Grouping with dictionaries  
* [27:57](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1677s) -- Is a dictionary pop() atomic?  
* [29:12](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1752s) -- Linking dictionaries  
* [31:10](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1870s) -- Clarify function calls with keyword arguments  
* [32:17](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1937s) -- Clarify multiple return values with named tuples  
* [33:13](https://www.youtube.com/watch?v=OSGv2VnC0go&t=1993s) -- Unpacking sequences  
* [34:01](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2041s) -- Updating multiple state variables  
* [36:15](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2175s) -- Simultaneous state updates  
* [38:24](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2304s) -- Concatenating strings  
* [38:41](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2321s) -- Updating sequences  
* [39:57](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2397s) -- Using decorators to factor-out administrative logic  
* [40:24](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2424s) -- Caching decorator  
* [41:19](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2479s) -- Factor-out temporary contexts for decimal  
* [42:01](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2521s) -- How to open and close files  
* [42:25](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2545s) -- How to use locks  
* [43:10](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2590s) -- Factor-out temporary contexts  
* [44:56](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2696s) -- Context manager: redirect_stdout()  
* [46:04](https://www.youtube.com/watch?v=OSGv2VnC0go&t=2764s) -- Concise expressive one-liners

## [Stop Writing Classes](https://www.youtube.com/watch?v=o9pEzgHorH0)

A talk by [Jack Diederich](https://twitter.com/jackdied) on problems of over usage of classes in out code. It has a different perspective and points out the mistakes made by us creating classes and sub-classes when in fact a function would just be fine. The talk gives examples of class overuse and how you can refactor the unnecessary classes, exception and modules away from your code, making it more readable to developers and even reduce total lines of code and hence increasing performance.

### Key take aways

1. Classes are useful but not when it is not needed
2. Simple is always better
3. Practicality beats standard conventions
4. Don't try reinventing the wheel. Use the existing tools and save time
5. Make it readable
6. The proper way is not always the right way
7. Don't try to create empty class, functions, etc. as placeholders for future functionality. Code what is required for now and add in later

### Timeline

* [1:03](https://youtu.be/o9pEzgHorH0?t=64) don't do hard things in the first place
* [3:48](https://youtu.be/o9pEzgHorH0?t=228) standard lib: functools.partial
* [3:58](https://youtu.be/o9pEzgHorH0?t=238) Classes give us lovely things
* [4:33](https://youtu.be/o9pEzgHorH0?t=273) Example of over usage of classes
* [9:27](https://youtu.be/o9pEzgHorH0?t=567) Namespaces
* [11:58](https://youtu.be/o9pEzgHorH0?t=718) Python standard library
* [12:48](https://youtu.be/o9pEzgHorH0?t=768) When to use class
* [20:33](https://youtu.be/o9pEzgHorH0?t=1233) QnA

## [PEP 20 Presentation - Zen of Python](https://www.youtube.com/watch?v=PHSAVai7yx4)

This is a very short video teaching us the key coding methodology to remember when coding in python.

### Key take aways

1. Beautiful code is achieved through a combination of explicit, simple sparse and flat attributes to ensure readability
2. Explicit is better than implicit
3. Simple is better than complex, complex is better than complicated
4. Sparse is better than dense
5. Errors should not be passed silently. Give message when it occurs
6. Guido Van Rossum is the creator of Python

## [25 Python Tips + Tricks](https://www.youtube.com/watch?v=y4I3VI1N_ts)

A very helpful video by [Caleb Curry](https://www.youtube.com/channel/UCZUyPT9DkJWmS_DzdOi7RIA) which covers all frequent use cases in python. The video is to the point and explained briefly.

### Key take aways

1. Use itertools and generators
2. You can preserve all data when merging two lists with unequal number of elements using zip_longest

### Timeline

* [00:00](https://www.youtube.com/watch?v=y4I3VI1N_ts) - Introduction  
* [00:43](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=43s) - Wrapping a Primitive to change within function  
* [02:09](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=129s) - Compare identity with is  
* [02:27](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=147s) - Add a method dynamically  
* [02:50](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=170s) - Compare by Value  
* [03:20](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=200s) -Class parenthesis optional but not function parenthesis  
* [03:46](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=226s) - Get current date and time  
* [04:17](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=257s) - Countdown  
* [04:55](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=295s) - Elapsed time  
* [05:24](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=324s) - Parentheses for operations with object members  
* [06:54](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=414s) - Runtime error vs syntax error  
* [07:52](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=472s) - Get a random number  
* [08:13](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=493s) - Import with Alias  
* [05:58](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=358s) - Generators and Yield  
* [11:09](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=669s) - Infinite number  
* [12:11](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=731s) - Infinite generator  
* [12:47](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=767s) - list from generator  
* [13:37](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=817s) - itertools for simple infinite generator  
* [14:48](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=888s) - Iterate through custom type with iter  
* [16:00](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=960s) - Falsey for custom types (not)  
* [17:13](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1033s) - Combine two lists as a list of lists  
* [17:39](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1059s) - Convert list of tuples to list of lists  
* [18:11](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1091s) - Preserving all data when zipping with zip_longest  
* [18:55](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1135s) - Default Arguments  
* [19:30](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1170s) - Keyword Arguments  
* [20:14](https://www.youtube.com/watch?v=y4I3VI1N_ts&t=1214s) - Get the Python version

## [10 Python Tips & Tricks That You Do Not Know || Python Clever Tips || Learn Python Shortcuts](https://www.youtube.com/watch?v=WEP3DVTjKCc)

A good video from [Programming Hero](https://www.youtube.com/channel/UCStj-ORBZ7TGK1FwtGAUgbQ) which gives us some everyday use tips and tricks with a great vibe.

### Key take aways

1. For `if` you don't need to keep paranthesis like other languages
2. For many conditions, rather than listing them all in `if`, create a list of those conditions and give `if all(conditions)`. Using this we can even update our conditions easily in the list
3. You can remove duplicates in a list by converting it into a set. Set contains only unique values
4. To pass multiple values as arguments in your function use `def func(*a)`
5. You can reverse a string like so `string_var[::-1]`

### Timeline

* [00:28](https://youtu.be/WEP3DVTjKCc?t=28) inputs
* [02:33](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=153s) use a list of conditions for if
* [06:44](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=404s) swapping using tuple unpacking
* [08:44](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=524s) remove duplicates using set
* [10:25](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=625s) get the value which is repeated most in a list
* [12:00](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=720s) list comprehension
* [14:47](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=887s) using `*` to pass multiple params in dunctions
* [16:56](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=1016s) reverse string with [::-1]
* [17:49](https://www.youtube.com/watch?v=WEP3DVTjKCc&t=1069s) palindrome

## [11 Tips And Tricks To Write Better Python Code](https://www.youtube.com/watch?v=8OKTAedgFYg)

A short video by [Python Engineer](https://www.youtube.com/channel/UCbXgNpp0jedKWcQiULLbDTA) channel on writing better python code

### Key take aways:

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
