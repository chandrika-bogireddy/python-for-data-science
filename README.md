# python-for-data-science
# Python basics
Python is a high-level, interpreted programming language. Python is widely used in web development, data analysis, artificial intelligence, scientific computing, and more.

# 1. Data Types
Data types in Python specify the type of data that can be stored in a variable. Python has several built-in data types:
Ex:-int,float,string,list,tuple, dictionary and etc

# 2. Variables
Variable is the name of the memory location where the data is stored. In Python, you do not need to declare the type of a variable explicitly. Variable names must start with a letter or an underscore, followed by letters, digits, or underscores.

x = 10          # integer
y = 3.14        # float
name = "Alice"  # string

# 3. Operators
Operators are symbols that perform operations on variables and values. Python supports various types of operators:

<br>Arithmetic Operators: +, -, , /, %, * , //</br>
Comparison Operators: ==, !=, >, <, >=, <=
Logical Operators: and, or, not
Assignment Operators: =, +=, -=, =, /=, %=, *=, //=
Bitwise Operators: & (AND), | (OR), ^ (XOR), ~ (NOT), << (left shift), >> (right shift)

# 4. Strings
Anything that is present inside single or double quotes are strings. Strings are immutable.

greeting = "Hello, World!"
string operations:

Concatenation: "Hello, " + "World!"
Slicing: greeting[0:5]
Methods: upper(),lower()...etc

# 5. Lists
Lists are ordered, mutable collections of items. They can contain elements of different data types.

fruits = ["apple", "banana", "cherry"]
List operations:
Accessing elements: fruits[0]
Modifying elements: fruits[1] = "blueberry"
Adding elements: fruits.append("date")
Removing elements: fruits.remove("banana")
Slicing: fruits[1:3]
Methods: fruits.sort(), fruits.reverse()

# 6. Dictionaries
Dictionaries are unordered, mutable collections of key-value pairs. They are often used to store related data.

person = {
    "name": "Alice",
    "age": 30,
    "city": "New York"
}
dictionary operations:

Accessing values: person["name"]
Modifying values: person["age"] = 31
Adding key-value pairs: person["email"] = "alice@example.com"
Removing key-value pairs: del person["city"]
Methods: person.keys(), person.values(), person.items()
