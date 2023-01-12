# Python Programming Language
Python is a high-level, general-purpose programming language. It was created by Guido van Rossum in 1991 and is known for its readability and simple syntax. Python is widely used in a variety of applications, such as web development, scientific computing, data analysis, artificial intelligence, and more.

One of the key features of Python is its flexibility and ease of use, making it a popular choice for beginners and experienced developers alike. Python code is often described as "readable" and "easy to learn," which makes it a great choice for learning how to program.

Additionally, Python has a large and active community that creates and maintains a wealth of libraries and frameworks. These tools make it easy to perform complex tasks and greatly speed up development time.

Python is also platform-independent, meaning that it can run on any operating system, such as Windows, MacOS, and Linux. This means that once you learn Python, you can apply your skills to a wide range of projects and systems.

## Advantages of Python
- **Dynamic Typing**: Python is a dynamically typed language, which means that the data type of a variable is determined at runtime, rather than at the time of declaration. This allows for greater flexibility in the way you write code, and it makes it easier to work with complex data types.

- **Interpreted Language**: Python is an interpreted language, which means that the code is executed line by line, rather than being compiled into machine code. This makes it easier to debug and test your code, and it also allows for interactive development.

- **Large Standard Librar**: Python has a large standard library that provides a wide range of modules and functions for a variety of tasks such as web scraping, data manipulation, text processing, and more. This makes it easy to perform common programming tasks without having to write your own code.

- **Object-Oriented Programming**: Python is an object-oriented programming language, which means that you can use classes and objects to organize and structure your code. This allows for encapsulation and abstraction of data and methods, making it easier to understand, maintain, and extend the code.

- **Easy to Learn**: Python is designed to be easy to read and write, with a simple and consistent syntax that is easy to understand. This makes it a great language for beginners and for those who are new to programming.

- **High-level language**: Python is a high-level programming language, which means that it is closer to human language than machine code. This allows for more efficient and less error-prone coding, as well as easier code maintenance.

## Difference between Interpreted and Compiled Languages

A compiled language is a programming language that is converted into machine code (binary code that can be executed by a computer) before it is run. The code is translated from the source code (the code written by the programmer) into machine code by a compiler. Once the code is compiled, it can be run directly on the target machine without the need for any additional software. Examples of compiled languages include C, C++, and C#.

An interpreted language, on the other hand, is a programming language that is executed by an interpreter, rather than being compiled into machine code. The interpreter reads the source code line by line and converts it into machine code on the fly, while the program is running. This means that interpreted languages do not need to be compiled before they are run. Examples of interpreted languages include Python, JavaScript, and Ruby.

There are pros and cons to both compiled and interpreted languages. Compiled languages are generally faster and more efficient, as the code is optimized for the target machine before it is run. They also offer more control over the underlying hardware and can be used to write low-level system software such as operating systems. However, they can be more difficult to learn and debug, and the compilation process can be slow.

Interpreted languages, on the other hand, are generally easier to learn and debug, as the code is executed line by line and errors can be identified as they occur. They also offer more flexibility and are well-suited for rapid development and scripting tasks. However, they are generally slower and less efficient than compiled languages, as the code is not optimized for the target machine before it is run.

In summary, compiled languages are translated into machine code before they are executed and are generally more efficient, while interpreted languages are executed by an interpreter, are generally slower and more flexible.

# Contents
- **Variables and data types**: understanding how to store and manipulate data in Python, including strings, integers, and lists.
- **Control flow**: using if/else statements and loops to control the flow of a program and make decisions based on the data.
- **Functions**: creating and calling reusable blocks of code that can accept parameters and return values.
- **Object-oriented programming**: understanding how to define and work with classes and objects to create modular, reusable code.
- **Libraries and modules**: learning how to import and use pre-built libraries and modules to add functionality to your programs.
- **Error handling**: understanding how to handle and raise exceptions to prevent errors and make your code more robust.
- **File handling**: reading, writing and manipulating files in python.
- **Debugging**: using tools such as the pdb module and print statements to troubleshoot code and fix bugs.

## Variables and data types
A variable is a name that refers to a value. Variables are used to store data in a program, and they can be used to store different types of data.

Here are some examples of how to create variables and assign different data types to them in Python:

### Numbers (integers and floating-point numbers):
```python
age = 25  # integer
height = 1.75  # floating-point number
```
### Strings:
```python
name = "John Smith"  # string enclosed in double quotes
address = '123 Main St.' #string enclosed in single quotes
```
### Booleans:
```python
is_student = True  # boolean value
is_working = False  # boolean value
```
### Lists:
```python
numbers = [1, 2, 3, 4, 5] # list of integers
words = ["apple", "banana", "cherry"] # list of strings
```
### Tuples:
```python
coordinates = (4, 5) # tuple of integers
```
### Dictionaries:
```python
person = {'name': 'John', 'age': 25, 'address': '123 Main St.'} # dictionary with keys and values
```
### Set:
```python
colors = {"red", "green", "blue"} # set of strings
```
### None:
```python
empty = None # None value
```

## Print
The *print()* statement in Python is used to output text or other data to the console or terminal. It is a built-in function that can be used to print strings, numbers, variables, and other types of data. The basic syntax for the print() function is as follows:
```python
print(data, ..., sep=' ', end='\n', file=sys.stdout, flush=False)
```
The *data* parameter is the value or values that you want to print. You can pass multiple values to the *print()* function by separating them with commas.

The *sep* parameter is used to specify a separator between the values. The default separator is a space.

The *end* parameter is used to specify the end character for the printed text. The default end character is a newline ('\n'), which causes the cursor to move to the next line after the text is printed.

The *file* parameter is used to specify the file or device that the data should be printed to. The default is *sys.stdout*, which prints to the console or terminal.

The *flush* parameter is used to specify whether the output should be flushed (i.e., written immediately) or buffered (i.e., held in memory until the buffer is full or the program exits). The default is *False*, which means that the output is buffered.

Here's an example of how to use the *print()* function to print a string:
```python
print("Hello, World!")
```
Here's an example of how to use the *print()* function to print multiple values:
```python
name = "John"
age = 30
print("My name is", name, "and I am", age, "years old.")
```
In python 3.6 and above, f-strings (formatted string literals) is another way to print variable values.

```python
name = "John"
age = 30
print(f"My name is {name} and I am {age} years old.")
```
The *print()* function is one of the most commonly used functions in Python and is a powerful tool for debugging and testing your code. It can be used to display the results of calculations, to print messages to the user, and to display the values of variables and other data.



## Lists
A list is a collection of items that are ordered and changeable. Lists are used to store multiple items in a single variable. The items in a list are separated by commas and enclosed in square brackets [].

Here's an example of how to create a list in Python:
```python
fruits = ["apple", "banana", "cherry"]
```

You can access individual items in a list using their index (the position of the item in the list). The index starts at 0 for the first item, and it increases by 1 for each subsequent item. Here's an example of how to access the first item in the list "fruits":
```python
print(fruits[0])  # Output: "apple"
```

You can also use negative indexing to access the items from the end of the list.
```python
print(fruits[-1])  # Output: "cherry"
```

Lists are mutable, meaning you can change the content of the list after it is created. You can add, remove and modify the items in the list. Here are some examples of how to modify a list:
```python
fruits.append("orange")  # add "orange" to the end of the list
fruits.insert(1, "mango")  # insert "mango" at index 1
fruits.remove("banana")  # remove "banana" from the list
fruits[1] = "kiwi"  # change the second item to "kiwi"
```

You can also use various built-in methods and functions to perform operations on lists such as sort, reverse, clear etc.
Additionally, you can also use list comprehension and other ways of creating lists as well.

Lists are one of the most commonly used data types in Python, and they are useful for organizing and manipulating large amounts of data.

### List functions and methods
lists have several built-in functions and methods that can be used to manipulate and work with the data stored in them. Here are a few examples of commonly used list functions and their uses:

- **append(x)**: Adds an item (x) to the end of the list.
```python
fruits = ["apple", "banana"]
fruits.append("cherry")
print(fruits)  # Output: ["apple", "banana", "cherry"]
```
- **extend(iterable)**: Adds all the items from an iterable (e.g. list, tuple, etc.) to the end of the list.
```python
fruits = ["apple", "banana"]
new_fruits = ["cherry", "orange"]
fruits.extend(new_fruits)
print(fruits)  # Output: ["apple", "banana", "cherry", "orange"]
```
- **insert(i, x)**: Inserts an item (x) at a given index (i) in the list.
```python
fruits = ["apple", "banana", "cherry"]
fruits.insert(1, "orange")
print(fruits)  # Output: ["apple", "orange", "banana", "cherry"]
```
- **remove(x)**: Removes the first item from the list that has the value x.
```python
fruits = ["apple", "banana", "cherry", "banana"]
fruits.remove("banana")
print(fruits)  # Output: ["apple", "cherry", "banana"]
```
- **pop([i])**: Removes and returns the item at the given index (i) in the list. If no index is specified, it removes and returns the last item.
```python
fruits = ["apple", "banana", "cherry"]
removed_fruit = fruits.pop(1)
print(fruits)  # Output: ["apple", "cherry"]
print(removed_fruit)  # Output: "banana"
```
- **index(x)**: Returns the index of the first item in the list that has the value x.
```python
fruits = ["apple", "banana", "cherry"]
banana_index = fruits.index("banana")
print(banana_index)  # Output: 1
```
- **count(x)**: Returns the number of times x appears in the list.
```python
fruits = ["apple", "banana", "cherry", "banana"]
banana_count = fruits.count("banana")
print(banana_count)  # Output: 2
```
- **sort()**: Sorts the items in the list in ascending order.
```python
numbers = [3, 1, 4, 1, 5, 9, 2]
numbers.sort()
print(numbers)  # Output: [1, 1, 2, 3, 4, 5, 9]
```
- **reverse()**: Reverses the order of the items in the list.
```python
numbers = [1, 2, 3, 4, 5]
numbers.reverse()
print(numbers)  # Output: [5, 4, 3, 2, 1]
```

## Tuples
 A tuple is a collection of items that are ordered and immutable. Similar to lists, tuples are used to store multiple items in a single variable. However, unlike lists, tuples cannot be modified once they are created. The items in a tuple are separated by commas and enclosed in parentheses ().

 Here's an example of how to create a tuple in Python:
```python
fruits = ("apple", "banana", "cherry")
```
You can access individual items in a tuple using their index (the position of the item in the tuple). The index starts at 0 for the first item, and it increases by 1 for each subsequent item. Here's an example of how to access the first item in the tuple "fruits":
```python
print(fruits[0])  # Output: "apple"
```
You can also use negative indexing to access the items from the end of the tuple.
```python
print(fruits[-1])  # Output: "cherry"
```
Tuples are useful when you want to store a collection of items that should not be modified throughout the program. For example, you might use a tuple to store the RGB values of a color, or the x and y coordinates of a point.

Tuples are also useful when you want to use a collection of items as a key in a dictionary. Since lists are mutable, they cannot be used as keys, but tuples can be used because they are immutable.

You can also use various built-in functions and methods on tuples such as len, min, max, index, count etc.
You can also convert a tuple to a list and vice versa.

It's important to note that once a tuple is created, you can't change its values. If you need to change the values of a tuple, you can create a new tuple and assign it to the same variable.

### Tuple functions and methods
Tuples have several built-in functions and methods that can be used to manipulate and work with the data stored in them. Here are a few examples of commonly used tuple functions and their uses:

- **len(x)**: Returns the length of the tuple x.
```python
fruits = ("apple", "banana", "cherry")
print(len(fruits))  # Output: 3
```

## Sets
A set is a collection of items that are unordered and unindexed. Sets are used to store multiple items in a single variable. However, unlike lists and tuples, sets are unordered, meaning that the items in a set do not have a defined order. You cannot access items in a set by referring to an index or a key.

Here's an example of how to create a set in Python:
```python
fruits = {"apple", "banana", "cherry"}
```

You can also create a set using the set() constructor. Here's an example of how to create a set using the set() constructor:
```python
fruits = set(("apple", "banana", "cherry"))
```

You can access items in a set using a for loop, or by checking if a specified value is present in a set, by using the in keyword.
```python
fruits = {"apple", "banana", "cherry"}
for x in fruits:
  print(x)
```
You can add items to a set by using the add() method. Here's an example of how to add an item to a set:
```python
fruits = {"apple", "banana", "cherry"}
fruits.add("orange")
print(fruits)  # Output: {"apple", "banana", "cherry", "orange"}
```

You can add multiple items to a set by using the update() method. Here's an example of how to add multiple items to a set:
```python
fruits = {"apple", "banana", "cherry"}
fruits.update(["orange", "mango", "grapes"])
print(fruits)  # Output: {"apple", "banana", "cherry", "orange", "mango", "grapes"}
```

You can get the number of items in a set by using the len() method.
```python
fruits = {"apple", "banana", "cherry"}
print(len(fruits))  # Output: 3
```

You can remove an item in a set by using the remove(), or the discard() method.
```python
fruits = {"apple", "banana", "cherry"}
fruits.remove("banana")
print(fruits)  # Output: {"apple", "cherry"}
```
You can also use the pop(), method to remove an item, but this method will remove the last item. Remember that sets are unordered, so you will not know what item that gets removed.
```python
fruits = {"apple", "banana", "cherry"}
x = fruits.pop()
print(x)  # Output: "apple" or "banana" or "cherry"
print(fruits)  # Output: {"banana", "cherry"} or {"apple", "cherry"} or {"apple", "banana"}
```
The clear() method empties the set:
```python
fruits = {"apple", "banana", "cherry"}
fruits.clear()
print(fruits)  # Output: set()
```
The del keyword will delete the set completely:
```python
fruits = {"apple", "banana", "cherry"}
del fruits
print(fruits)  # This will raise an error because the set no longer exists
```
You can join two sets by using the union() method.
```python
set1 = {"a", "b" , "c"}
set2 = {1, 2, 3}
set3 = set1.union(set2)
print(set3)  # Output: {1, 2, 3, "a", "b", "c"}
```
The update() method inserts the items in set2 into set1:
```python
set1 = {"a", "b" , "c"}
set2 = {1, 2, 3}
set1.update(set2)
print(set1)  # Output: {1, 2, 3, "a", "b", "c"}
```
The set() constructor also takes an iterable object (like a list, tuple, string etc.) and converts it into a set.
```python
set1 = set(("apple", "banana", "cherry")) # note the double round-brackets
print(set1)  # Output: {"apple", "banana", "cherry"}
```
## Dictionaries
A dictionary is a collection which is unordered, changeable and indexed. In Python dictionaries are written with curly brackets, and they have keys and values.

Here's an example of how to create a dictionary in Python:
```python
car = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
```
You can access the items of a dictionary by referring to its key name, inside square brackets:
```python
x = car["model"]
```
You can change the value of a specific item by referring to its key name:
```python
car["year"] = 2018
```
You can loop through a dictionary by using a for loop. When looping through a dictionary, the return value are the keys of the dictionary, but there are methods to return the values as well.
```python
for x in car:
  print(x)
```
You can also use the values() method to return values of a dictionary:
```python
for x in car.values():
  print(x)
```
You can use the items() method to return each item in a dictionary, as tuples in a list:
```python
for x, y in car.items():
  print(x, y)
```
You can check if a specified key is present in a dictionary by using the in keyword:
```python
if "model" in car:
  print("Yes, 'model' is one of the keys in the car dictionary")
```
You can determine how many items (key-value pairs) a dictionary has by using the len() method:
```python
print(len(car))
```
You can add an item to the dictionary by using a new index key and assigning a value to it:
```python
car["color"] = "red"
```
You can remove an item from the dictionary by using the pop() method:
```python
car.pop("model")
```
The popitem() method removes the last inserted item (in versions before 3.7, a random item is removed instead):
```python
car.popitem()
```
The del keyword removes the item with the specified key name:
```python
del car["model"]
```
The del keyword can also delete the dictionary completely:
```python
del car
```
The clear() keyword empties the dictionary:
```python
car.clear()
```
You can also use the dict() constructor to make a new dictionary:
```python
car = dict(brand="Ford", model="Mustang", year=1964)
```
### Difference between list, tuple, set and dictionary
| List | Tuple | Set | Dictionary |
| --- | --- | --- | --- |
| Ordered | Ordered | Unordered | Unordered |
| Changeable | Unchangeable | Unchangeable | Changeable |
| Allows duplicate members | Allows duplicate members | Does not allow duplicate members | Does not allow duplicate members |
| Indexes have meaning | Indexes have meaning | Indexes have no meaning | Keys have meaning |
| Written with square brackets | Written with round brackets | Written with curly brackets | Written with curly brackets |
| Can be accessed with index | Can be accessed with index | Can be accessed with index | Can be accessed with key |

# Control Flow
## If statement
***run this code in python shell to see the output***

An if statement is written by using the if keyword.
```python
if 5 > 2:
  print("Five is greater than two!")
```
You can add an else statement to an if statement, which executes a block of code when the condition is not true.
```python
if 5 > 2:
  print("Five is greater than two!")
else:
  print("Five is not greater than two.")
```
You can add an elif statement, which is short for else if. It allows you to check for multiple expressions.
```python
if 5 > 2:
  print("Five is greater than two!")
elif 4 > 3:
  print("Four is greater than three!")
else:
  print("Five is not greater than two.")
```
## While loop
With the while loop we can execute a set of statements as long as a condition is true.
```python
i = 1
while i < 6:
  print(i)
  i += 1
```
With the break statement we can stop the loop even if the while condition is true:
```python
i = 1
while i < 6:
  print(i)
  if i == 3:
    break
  i += 1
```
With the continue statement we can stop the current iteration, and continue with the next:
```python
i = 0
while i < 6:
  i += 1
  if i == 3:
    continue
  print(i)
```
With the else statement we can run a block of code once when the condition no longer is true:
```python
i = 1
while i < 6:
  print(i)
  i += 1
else:
  print("i is no longer less than 6")
```
## For loop
A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).
```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
```
With the break statement we can stop the loop before it has looped through all the items:
```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "banana":
    break
```
With the continue statement we can stop the current iteration of the loop, and continue with the next:
```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    continue
  print(x)
```
With the range() function we can loop through a set of code a specified number of times:
```python
for x in range(6):
  print(x)
```
The range() function defaults to 0 as a starting value, however it is possible to specify the starting value by adding a parameter: range(2, 6), which means values from 2 to 6 (but not including 6):
```python
for x in range(2, 6):
  print(x)
```
The range() function defaults to increment the sequence by 1, however it is possible to specify the increment value by adding a third parameter: range(2, 30, 3):
```python
for x in range(2, 30, 3):
  print(x)
```
A nested loop is a loop inside a loop.
```python
adj = ["red", "big", "tasty"]
fruits = ["apple", "banana", "cherry"]

for x in adj:
  for y in fruits:
    print(x, y)
```
With the else statement we can run a block of code once when the loop is finished:
```python
for x in range(6):
  print(x)
else:
  print("Finally finished!")
```
## Pass statement
The pass statement is a null operation; nothing happens when it executes. The pass statement is also useful in places where your code will eventually go, but has not been written yet (e.g. in stubs for example).
```python
for x in [0, 1, 2]:
  pass
```
## enumerate()
The enumerate() function takes a collection (e.g. a tuple) and returns it as an enumerate object. The enumerate() function adds a counter as the key of the enumerate object.
```python
for i, v in enumerate(['tic', 'tac', 'toe']):
  print(i, v)
```
## zip()
The zip() function takes iterables (can be zero or more), aggregates them in a tuple, and return it.
```python
questions = ['name', 'quest', 'favorite color']
answers = ['lancelot', 'the holy grail', 'blue']
for q, a in zip(questions, answers):
  print('What is your {0}?  It is {1}.'.format(q, a))
```
## reversed()
The reversed() function returns a reversed iterator.
```python
for i in reversed(range(1, 10, 2)):
  print(i)
```
## sorted()
The sorted() function returns a sorted list from the items in an iterable.
```python
basket = ['apple', 'orange', 'apple', 'pear', 'orange', 'banana']
for f in sorted(set(basket)):
  print(f)
```
## map()
The map() function executes a specified function for each item in an iterable. The item is sent to the function as a parameter.
```python
def fahrenheit(T):
  return ((float(9)/5)*T + 32)
def celsius(T):
    return (float(5)/9)*(T-32)
temp = (36.5, 37, 37.5,39)
F = map(fahrenheit, temp)
C = map(celsius, F)
print(list(F))
print(list(C))
```
## filter()
The filter() function returns an iterator were the items are filtered through a function to test if the item is accepted or not.
```python
def f(x):
  return x % 2 != 0 and x % 3 != 0
print(list(filter(f, range(2, 25))))
```

# List Comprehensions
List comprehension is a concise and efficient way to create a new list in Python. It is a way to create a new list by applying an expression to each item in an existing list (or other iterable), and optionally filtering the items. It is an elegant way to perform common list operations in a single line of code.

Here's an example of how to use list comprehension to create a new list that contains the squares of the numbers in an existing list:
```python
numbers = [1, 2, 3, 4, 5]
squares = [n**2 for n in numbers]
print(squares) # Output: [1, 4, 9, 16, 25]
```
You can also use *if* statements inside list comprehension to filter the items that are included in the new list.
```python
numbers = [1, 2, 3, 4, 5]
even_squares = [n**2 for n in numbers if n % 2 == 0]
print(even_squares) # Output: [4, 16]
```
List comprehension can also be used with other data types such as sets and dictionaries.

Here's an example of using a set comprehension:
```python
numbers = [1, 2, 3, 4, 5, 1, 2, 3]
unique_numbers = {n for n in numbers}
print(unique_numbers)  # Output: {1, 2, 3, 4, 5}
```
Here's an example of using a dictionary comprehension:

```python
numbers = [1, 2, 3, 4, 5]
squared_numbers = {n:n**2 for n in numbers}
print(squared_numbers)  # Output: {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
```
List comprehension can be a more readable and efficient way to perform common list operations, but it's important to use it judiciously. When the logic of the operation becomes too complex, it's often better to use a for loop or another method to perform the operation, as list comprehension can become hard to read and understand. Additionally, if the operation is too computationally expensive, it's also better to use a regular loop as it will be more memory efficient.

## Excersice
- Write a program that prints the numbers from 1 to 10.
- Write a program that prints the numbers from 1 to 10, but skips the number 5.
- Write a program that prints the numbers from 1 to 10, but stops when it reaches the number 5.
- Write a program that prints the even numbers from 1 to 10.
- Write a program that prints the odd numbers from 1 to 10.
- Write a program that takes a number as input and prints whether it is positive, negative, or zero.
- Write a program that takes a number as input and prints whether it is even or odd.
- Write a program that takes two numbers as input and prints the larger number.
- Write a program that takes a list of numbers as input and prints the second largest number.
- Write a program that takes a list of numbers as input and prints all the prime numbers in the list.

# Functions
## Function definition  
A function is a block of code which only runs when it is called. You can pass data, known as parameters, into a function. A function can return data as a result.
```python
def my_function():
  print("Hello from a function")
```
## Calling a function
To call a function, use the function name followed by parenthesis:
```python
def my_function():
  print("Hello from a function")

my_function()
```
## Arguments
Information can be passed into functions as arguments.
```python
def my_function(fname):
  print(fname + " Refsnes")

my_function("Emil")
my_function("Tobias")
my_function("Linus")
```
## Parameters or Arguments?
From a function's perspective:
- A parameter is the variable listed inside the parentheses in the function definition.
- An argument is the value that is sent to the function when it is called.
```python
def my_function(fname):
  print(fname + " Refsnes")

my_function("Emil")
my_function("Tobias")

# Arguments are often shortened to args in Python documentations.
```
## Arbitrary Arguments, *args
If you do not know how many arguments that will be passed into your function, add a * before the parameter name in the function definition.
```python
def my_function(*kids):
  print("The youngest child is " + kids[2])

my_function("Emil", "Tobias", "Linus")
```

## Keyword Arguments
You can also send arguments with the key = value syntax.
```python
def my_function(child3, child2, child1):
  print("The youngest child is " + child3)

my_function(child1 = "Emil", child2 = "Tobias", child3 = "Linus")
```

## Arbitrary Keyword Arguments, **kwargs
If you do not know how many keyword arguments that will be passed into your function, add two asterisk: ** before the parameter name in the function definition.
```python
def my_function(**kid):
  print("His last name is " + kid["lname"])

my_function(fname = "Tobias", lname = "Refsnes")
```

## Default Parameter Value
The following example shows how to use a default parameter value. If we call the function without argument, it uses the default value:
```python
def my_function(country = "Norway"):
  print("I am from " + country)

my_function("Sweden")
my_function("India")
my_function()
my_function("Brazil")
```

## Passing a List as an Argument
You can send any data types of argument to a function (string, number, list, dictionary etc.), and it will be treated as the same data type inside the function.
```python
def my_function(food):
  for x in food:
    print(x)

fruits = ["apple", "banana", "cherry"]

my_function(fruits)
```

## Return Values
To let a function return a value, use the return statement:
```python
def my_function(x):
  return 5 * x

print(my_function(3))
print(my_function(5))
print(my_function(9))
```

## The pass Statement
function definitions cannot be empty, but if you for some reason have a function definition with no content, put in the pass statement to avoid getting an error.
```python
def myfunction():
  pass
```

## Recursion
Python also accepts function recursion, which means a defined function can call itself.
```python
def tri_recursion(k):
  if(k > 0):
    result = k + tri_recursion(k - 1)
    print(result)
  else:
    result = 0
  return result

print("\n\nRecursion Example Results")
tri_recursion(6)
```

## Anonymous Functions
Anonymous functions are also called lambda functions because they are not declared with the standard def keyword. You can use the lambda keyword to create small anonymous functions.
```python
x = lambda a : a + 10
print(x(5))
```

## Why Use Lambda Functions?
The power of lambda is better shown when you use them as an anonymous function inside another function.
You can use the same function definition to make both functions, because lambda functions are just syntactic sugar for a normal function definition. They have the same name and behave as normal functions.
```python
def myfunc(n):
  return lambda a : a * n

mydoubler = myfunc(2)

print(mydoubler(11))
```

## Exercise
- Write a function that takes two numbers as input and returns their sum.
- Write a function that takes a string as input and returns the number of vowels in the string.
- Write a function that takes a list of numbers as input and returns the largest number.
- Write a function that takes a list of numbers and a target number as input and returns the number of times the target number appears in the list.
- Write a function that takes a list of strings as input and returns a new list that contains only the strings that have a length greater than 5.
- Write a function that takes a list of numbers as input and returns a new list that contains only the prime numbers from the original list.
- Write a function that takes a string as input and returns a new string that contains the original string with all vowels removed.

