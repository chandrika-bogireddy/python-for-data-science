# python-for-data-science
# Python basics
Python is a high-level, interpreted programming language. Python is widely used in web development, data analysis, artificial intelligence, scientific computing, and more.

# 1. Data Types
Data types in Python specify the type of data that can be stored in a variable. Python has several built-in data types:
<br>Ex:-int,float,string,list,tuple, dictionary and etc</br>

# 2. Variables
Variable is the name of the memory location where the data is stored. In Python, you do not need to declare the type of a variable explicitly. Variable names must start with a letter or an underscore, followed by letters, digits, or underscores.

<br>x = 10          # integer</br>
<br>y = 3.14        # float</br>
<br>name = "Alice"  # string</br>

# 3. Operators
Operators are symbols that perform operations on variables and values. Python supports various types of operators:

<br>Arithmetic Operators: +, -, , /, %, * , //</br>
<br>Comparison Operators: ==, !=, >, <, >=, <=</br>
<br>Logical Operators: and, or, not</br>
<br>Assignment Operators: =, +=, -=, =, /=, %=, *=, //=</br>
<br>Bitwise Operators: & (AND), | (OR), ^ (XOR), ~ (NOT), << (left shift), >> (right shift)</br>

# 4. Strings
Anything that is present inside single or double quotes are strings. Strings are immutable.
<br>greeting = "Hello, World!"</br>
<br><h3>string operations:</h3></br>
<br>Concatenation: "Hello, " + "World!"</br>
<br>Slicing: greeting[0:5]</br>
<br>Methods: upper(),lower()...etc</br>
# 5. Lists
Lists are ordered, mutable collections of items. They can contain elements of different data types.
<br>fruits = ["apple", "banana", "cherry"]</br>
<br><h3>List operations:</h3></br>
<br>Accessing elements: fruits[0]</br>
<br>Modifying elements: fruits[1] = "blueberry"</br>
<br>Adding elements: fruits.append("date")</br>
<br>Removing elements: fruits.remove("banana")</br>
<br>Slicing: fruits[1:3]</br>
<br>Methods: fruits.sort(), fruits.reverse()</br>

# 6. Dictionaries
Dictionaries are unordered, mutable collections of key-value pairs. They are often used to store related data.
person = {
    "name": "Alice",
    "age": 30,
    "city": "New York"
}
<br>Examples:-</br>
<br>Accessing values: person["name"]</br>
<br>Modifying values: person["age"] = 31</br>
<br>Adding key-value pairs: person["email"] = "alice@example.com"</br>
<br>Removing key-value pairs: del person["city"]</br>
<br>Methods: person.keys(), person.values(), person.items()</br>
