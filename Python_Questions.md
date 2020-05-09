# Python Questions
#### Hossam Hassan
**1. What is Python?**
    Python is an interpreted, object - oriented, high- level programming language.
**2. What is a variable?**
	A variable in python is a reserved memory location to store values. 
**3. What is a namespace?**
    A namespace is a system to have a unique name for each and every object in python.
**4. What is the difference between list and tuple?**
    List are dynamic, and are mutable. Tuples are static, and are immuatable.
**5. How you can convert a number to a string?**
    Using the str() built in function.
**6. What are the rules for local and global variables?**
    If a variable is assigned a value anywhere within th function's body, it is assumed to be a local variable unless it is expliciltly declared as a global variable.
**7. Explain how to generate random numbers.**
    In python there is a standard library that provides a module called random that offers several functions for generating random numbers.
>Python [random](https://docs.python.org/3/library/random.html) documentation. 

**8. What is a dictionary?**
    A dictionary in python is an unordered collection of data values, values are held in a key:value pair.
**9. What is the self keyword?**
    Self representes the instance of the class. The self keyword is used to access the attributes and methods of the class in python. It binds the attributes with the given arguments.
**10. What are loop interruption statements?**
    Loop interruption statements can be used to return and pass statments to interrupt, skip, or stop the iteration.
**11. Explain List, Tuple, Set, and Dictionary and provide at least one instance where each of these collection types can be used.**
* Lists are mutable, can be used for any type of object,they are accessed like strings, and variables are declared by using brackets.
    >**List** = [A,B,C]

* Tuples are immutable, used to hold together multiple objects, tuple are delared by using parentheses.
    >**Tuple** = (A,B,C)

* Dictionarys are a key:value pair, declared by using curly brackets
    >**example_dictionary** = {1: 'A', 2: 'B', 3: 'C'}

**12. How is Exception Handling done?**
Exception handling is done by using a [try/except](https://docs.python.org/3/tutorial/errors.html) block.
**13. What does ‘#’ symbol do?**
The '#' symbol is a comment in python.
**14. Write the command to get all keys from a dictionary.**
  ```Syntax = dict.keys()```
**15. What is range()? Give an example to explain it.**
The [range()](https://docs.python.org/3/library/functions.html#func-range) function generates the integer numbers between the given start integer to the stop integer.  
>```print(range(5))```
>> Output: [0,1,2,3,4]  

**16. What does the // arithmetic operator do?**
An arthmetic operator takes two operands as input, performas a calculation and returns the result.
**17. What is a data type?**
Python [data types](https://www.w3schools.com/python/python_datatypes.asp) are the classification or categorization of data items. Data types represent a kind of value which determines what operations can be performed on that data.
**18. What are the basic data types that are supported by the language?**
Python data types include
- Text Type: ```str```
- Numeric Types:  ```int,``` ``` float,``` ``` complex```
- Sequence Types:  ```list,``` ``` tuple,``` ``` range```
- Mapping Type: ```dict```
- Set Types: ```set,``` ``` frozenset```
- Boolean Type: ```bool```
- Binary Types: ```bytes,``` ``` bytearray,``` ``` memoryview```

**19. How do you check whether the two variables are pointing to the same object?**
The 'is' [keyword](https://www.w3schools.com/python/python_ref_keywords.asp) is used to test if two variables refer to the same object. 
**20. What is for-else and while-else?**
[For](https://www.w3schools.com/python/python_for_loops.asp) and [While](https://www.w3schools.com/python/python_while_loops.asp) are loops in python. 
**21. What does immutable mean in the context of programming?**
An immutable object is an object whose state cannot be modified after it is created.
**22. What is a list in Python?**
* [Lists](https://www.w3schools.com/python/python_lists.asp) are mutable, can be used for any type of object,they are accessed like strings, and variables are declared by using brackets.
    >**List** = [A,B,C]

**23. What is a tuple in Python?**
* [Tuples](https://www.w3schools.com/python/python_tuples.asp) are immutable, used to hold together multiple objects, tuple are delared by using parentheses.
    >**Tuple** = (A,B,C)

**24. When do you choose a list over a tuple?**
Tuples are fixed size while a lists are dynamic. A tuple is immutable and a list is mutable. Tuples might be faster to use but you are unable to to append or extend a tuple. [List vs Tuple](https://www.programiz.com/python-programming/list-vs-tuples).
**25. How do you get the last value in a list or a tuple?**
>``` list[len - 1]```

**26. What is Index Out Of Range Error?**
An **Index out of range** error occurs in Python when trying to access an undefined element from the list. 
**27. Why should a program close a file when it is finished using it?**
A file must be closed because in some systems failure to close an output file can cause loss of data. 
**28. Assume the names variable references a list of strings. Write code that determines whether 'Dale' is in the names list. If it is, display the message 'Hello Dale'.  Otherwise, display the message 'No Dale'.**
**29. Write a program that opens a specified text file then displays a list of all the unique words found in the file. Hint: Store each word as an element of a set.**
**30. Write a program that reads the contents of a text file. The program should create a dictionary in which the keys are the individual words found in the file and the values are the number of times each word appears. For example, if the word "the" appears 128 times, the dictionary would contain an element with 'the' as the key and 128 as the value. The program should either display the frequency of each word or create a second file containing a list of each word and its frequency.**