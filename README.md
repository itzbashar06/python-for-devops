### python-for-devops

# Most Important Topic in Python For DevOps Engineer Point of View

Use Python when,
1. Complex Logic
2. API Integration
3. Reusable Code
4. Error handing
5. Advanced Data Processing
   and many More .....

# Data Types
1. Numric Data Types
   1. Int:- Represents Integar (Whole Number)
   Ex- x = 5
   2. float:- Represents Floating- Point Numbers (Number With Decimal Point)
   Ex- y = 3.14

2. Sequence Data Types
   1. Str:- Represents String (Sequence Of Character)
   Ex- text = "Hello World"
   2. List:- Represents List (Ordered, Mutable)
   Ex- my_list = [1, 2, 3,] 
   3. Tuple:- Represents Tuple (Unordered, immutable)
   Ex- my_tuple = (1, 2, 3,)

3. Mapping Type
   1. Dict:- Represents Dictionary (Key Value Pairs)
   Ex- my_dict ={"name", "john", "age", "18"}

4. Set Types
   1. Set:- Represents Set (Unordered Collection or Unique Elements)
   Ex- my_set = {1, 2, 3}
   2. Frozenset:- Represents Immutable sets
   Ex- my_frozenset = ([1, 2, 3,])

5. Boolean Type
   1. Bool:- Represents Boolean (True Or False)
   Ex- is_valid = True

6. Binary Types
   1. Bytes:- represents immutable sequence of Bytes
   Ex- data = b'hello'
   3. Bytesarray:- Represents mutable sequence of bytes
   Ex- bytearray = (b'hello')

7. None Type
   1. none type:- Represents the none object which is used to indicate a null value

8. Custom Data Types:- you can also define your custom data types using class and objects


# strings
String Data Types in Python
* In python, a string is a sequence of characters, enclosed within single (' '), double (" "), or triple (''' ''') or (""" """) quotes.
* strings are immutable, meaning you cannot change the characters within a string directly. Instead, you create new strings.
* You can access individual characters in a string using indexing.
* strings support various built- in methods, such as len(), upper(), lower(), strip(), replcae() and more, for manipulation.

# String Manipulation and Formatting
* Concatenation:- You can combine strings using the + operator.
* Substring:- Use slicing to extract partions of a string, exmaple my_sring [2:5)] will extract characters from the 2nd to the 4th position.
* String Interpolation:- Python supports various ways to format strings, including f- dtrings, %-formatting and str-format().
* Escape sequence:- Special characters like newline tab and others are represented using escape sequences.
* String methods:- Python provides many bulit-in methods for string manipulation, such as split(), join() and startswith().

# Numric Data Types
Numric Data Types In Python (int, float):-
* python supports two primary numeric data types int for integar and float for floating- point numbers.
* Integars are whole number and float represents number with decimal point.
* You can perform arithmetic operations on those types, including addition, substraction, multiplication, division and more.

# Keywords in Python
Keywords are reserved words in python that have predefined meanings and cannot be used as variable names or identifiers. These words are used to define the structure and logic of the program. They are an integral part of the python language and are case- sensitive, which means you must use them exactly as specified. 
Here are some important python KEywords:-
 1. and:- It is a logical operator that returns Ture if both operands are True.
 2. or:- It is a logical operator that returns True if at least one of the operands true.
 3. not:- It is a logical operator that returns opposite of the operands truth value.
 4. if:- It is used to start a condition statement and is followed by a condition that determines whether the code block is executed.
 5. else:-It is used in conjuction with if define an alternative code block to execute when the if condition is false.
 6. elif:- short for 'else if', it is used to additional condition after an if statement and is used in combination with if and else.
 7. while:- it is used to create a loop that repeatedly executes a block of code as long as a specified condition is true.
 8. for:- It is also used to create a loop that iterates over a sequence and executes a block of code for each item in the sequence.
 9. in:- used with for in loop. it check if a value is present in a sequence.
 10. try:- it is a beggining of a block of code that is subject to exception handling. it is followed by except to catch and handle exceptions.
 11. except:- used with try, it defines a block of code to execute when an exception is raised in the corresponding try block.
 12. finally:- used with try, it defines a block of codes that is always executed, whether an exception is raised or not.
 13. def:- it is used to define a function.
 14. class:- it is used to define a class, which is a blueprint for creating objects in object oriented programming.
 15. return:- it is used within a function to specify the value that the function should return.
 16. import:- it is used to import a module or libraries to access their function, class or variables.
 17. from:- used with import to specify which specific components from a module should be imported.
 18. true:- it represents is boolean valur for true.
 19. false:- it represents a boolean valur for false.
 20. as:- used with import to create an alias for a module, making it easier to refrence in the code.
 21. none:- it represent a special null value or absence of value.
 22. is:- it is used to identity comparison checking if two variables refer to the same object in memory.
 23. lambda:- it is used to create small, anonymous functions.
 24. with:- it is used for content management ensuring thet certain operations are performed before and after a block of code.
 25. global:- it is used to declare a global variable within a functions scope.
 26. nonlocal:- it is used to declare a variable as nonlocal, which allows modifying a variable in an enclosing scope.


# Understanding Variables in Python
 In Python, a variable is a names storage location used to store data, varables are essential for programming as they allow us to work with data, manipulate it and make our code more flexible and reuseable.

# Variable Scope and Lifetime
* Variable Scoep:- In python, variables have different scopes, which determine where in the code the variable can be accessed. There are mainly two types of variable scopes.
1. Local Scope:- Variables defined within a function have local scope and are only accessible inside that function.
   Ex:- def my_function():
               x = 10  # Local Variable
               print(x)
2. Global Scope:- Variables defined outside of any fuction have global scope and can be accessed throuthout the entire code.
   Ex:- y = 20   # Global Scope
        def another_function():
                    print(y)

* Variable Lifetime:-The lifetime of a variable is determined by when it is created and when it is destroyed or goes out of scope. Local variables exist only while the function is being executed, while global variables exist for the entire duration of the program.

# Variables naming convention and best practices:

It's important to follow naming conventions and best practices for variables to write clean and maintanable code:-
 * Variable names should be descriptive and indicate their purpose.
 * Use lowercaes letters and separate words with underscores for variable names.
 * Avoid using reserved words (Keywords) for variable names.


# Functions
A function is a block of code that performs a specific task. Functions are defined using the def keywords and can take inputs, called arguments. They are a way to encapsuleate and reuse code.
Ex:- def greet(name):
         return f"Hello, {name}!"

    message = greet("Alice")
    print(message)


# Modules
A module is a python script contraining python code. It can define functions, classes and variables that can be used in other python scripts. Moduless help organize and modularize your code. making it more maintainable.
 Ex:- Suppose you have a python file named my_module.py:-
      # my_module.py
       def square (x):
           return x ** 2
      You can use this module in another script:-
        import my_module
        result = my_module.square(5)
        print(result)
        print(my_module.pi)
      In this case, my_module is a python module.

 # packages
 A package is a collection of modules organized in directories. packages help you organize related modules into a hierarchy. They contain a special file named ___init___.py, which indicates that the directory should be treated as a package.
 
           
 # Python workspaces
  Python workspaces can be local or virtual environments. A local environment is the system- wide python installation, while a virtual environment is an isolated environmentis the system- wide python installation, while a virtual environment is an isolated environment for a specific project. You can create virtual environment using tools like "virtualenv" or "venv".
  Ex:- # create a virtual environment
       python -m venv myenv
       # activate the virtual environment
       myenv\scripts\activate
 # introduction to operators in python
  Operators in python are special symbols or keywords that are used to perform operations on variables and values. Python supports a wide range of operators categorized into several types. These operators allow you to perform tasks such as arithmetic calculations, assign values to variables, compare values, perform logical operations and more.
  Here are the main types of operators in python:
  * Arithmetic Operators:- These Operators are used for performing basic mathematical operations such as addition, substraction, multiplication, division and more.
  * Assignment Operators:- Assignments operators are used to assign values to variables. They include the equal sign (=) and various compound assignment operators.
  * Relational Operators:- Relational operators are used to compare values and determine the relationship between them. They return a boolean result(True or false).
  * Logical Operators:- Logical operatrs are used to combine and manipulate boolean values they include "and", "or", and "not".
  * Identity Operators:- Identity operators are used to check if two variables point te the same object in memory. The identity operators in python are "is" and "is not".
  * membership operators:- membership operators are used are check if a value is present in a sequence or collection, such as a list, tuple or string. The membership operators in python are "in" and "not in"
  * 


