# Python-Fundamentals-for-Data-Science

## In this repository , we are looking at the basics of the Python . The topics covered here are :- 

### 1. Identifiers and Variables 

- A python identifier is a name used to identify a variable , function, class , module or other object.
- An identifier starts with a letter A to Z or a to z or an underscore (_) followed by zero or more letters, underscores and digit(0 to 9)
- Python is a case sensitive programming language.
- Python does not allow special characters as @, $ and % within identifiers.
- An identifier should follow a snake_case or camelCase for variables ,or functions ‘PascalCase’ for classes. 
- Valid Identifiers 
a) y
b) new_variable
c) MIN_VALUE
d) _new_var
e) myAddFunc
f) MyClass
- Invalid Identifiers 
a) 3y (starts with a number)
b) if (a keyword)
c) new-variable (contains a hyphen)
d) new.variable (contains a period)
-  Variables are nothing but reserved memory locations to store values. This means that when we create a variable, we reserve some space in memory.
Let’s take an example 
y= 10 
When the above code gets executed , the interpreter creates the variable named y and assigns the value 10 to it.
-  The Memory block is divided into two parts ,the first part stores the metadata of the variable ( data type and other info) and the second part stores the actual value of the variable. 
+----------------------+
|  Memory allocated for |
|    integer variable   |
|          y           |
+----------------------+
|          10          |
+----------------------+


### 2. Conditional Statements 
- Conditional statements are used to execute a statement or a group of statements , when some condition is true 
- Type of Conditional statements If, Elif , Else 


### 3. Loop Statements
- A loop statement helps us to execute a statement or a group of statement multiple times
- Types of loops While , for and Nested
- While” loops are known as indefinite or conditional loops. They will keep iterating until certain conditions are made. There is no guarantee ahead of time regarding how many times the loop will iterate.
- For loop in Python is which repeats a group of statements a specified number of times. The for loop provides a syntax where the following information is present :
    - Boolean condition
    - The initial value of the counting variable
    -  Incrementation of the counting variable
- Loop control statements change the execution from its normal sequence. When execution leaves a scope, all automatic objects that were created in that scope are destroyed.
    - break statement: The break statement is used to exit a loop prematurely. When the break statement is encountered inside a loop, the loop is terminated and control is passed to the next statement outside the loop. 
    - continue statement: The continue statement is used to skip over a particular iteration of a loop. When the continue statement is encountered inside a loop, the current iteration is skipped, and control is passed to the next iteration of the loop. 
    - The pass statement is used as a placeholder when you need a statement in your code, but you don't want it to do anything. The pass statement is effectively a null operation - it doesn't do anything at all.

### 4. Operators
- In python , operators are special symbols or keywords that allow you to perform operations on values or variables. Some of the most commonly used operators are :- 
Comparison, Logical, Assignment, Bitwise, Identity and  Membership operators 
- Arithmetic operators: These operators are used to perform arithmetic operations such as addition, subtraction, multiplication, division, floor division , exponent and modulus.
- Assignment operators: These operators are used to assign a value to a variable. Sometimes it also assign the value to a variable which has undergone certain mathematical calculations.
- Comparison operators : These operators are used to compare two values and return a boolean value (True or False) based on the comparison. 
Examples are Equal to , not equal to , greater than , less than , greater than or equal to or less than equal to
- Logical Operators: These operators are used to perform logical operations such as AND, OR, and NOT. It also returns results in the form of true and false.
- Bitwise Operators :These operators are used to perform bitwise operations on binary numbers. Examples include binary and , binary or , binary Xor , binary not and binary right and left shift.
- Identity Operators :These operators are used to compare the identity of two objects. Examples include is and is not.
           - Is evaluates to true , if the variables on either side of the operator point to the same object and false otherwise.
           - Is not evaluates to False, if the variables on either side of the operator point to the same object and True otherwise.

- Membership Operator :These operators are used to check if a value is a member of a sequence or collection. Examples include in and not in.
           - In evaluates to true , if it finds a variable in the specified sequence and otherwise false
           - Not in evaluates to true, if it does not find a variable in the speacified sequence and otherwise false.

### 5. Lists 
- List is the most versatile data type available in Python, which can be written as a list of comma-separated values(items)between square brackets.
- Lists are often used to store related data together. For example, a list of employee names or a list of employee salaries.
- Lists are iterable, meaning we can loop over the elements of a list using a for loop. This makes lists useful when we need to perform the same operation on each element.
- Sorting data :Lists have a built-in sort method that allows you to sort the elements in ascending or descending order. This makes lists useful when you need to sort data.
- Because lists are mutable, we can change the contents of a list after creation. This makes lists useful when you need to modify data.
- Lists preserve the order of elements, so if you need to store data in a specific order, a list may be a good choice.
- Lists can contain elements of different types, so if you need to store data of different types together, a list may be a good choice.
- Lists can contain duplicate elements, so if you need to store multiple copies of the same element, a list may be a good choice.

### 6. Tuples 
- A tuple is a sequence of immutable Python Objects. Tuples are sequences , just like lists.
- The execution speed of tuples is  must faster as compared to lists. So, if we need to accomplish a task over a short period of time, then tuple can be used.
- Tuples are immutable which means that the values inside cannot be modified. If you need to store a sequence of elements that should not be changed, a tuple may be a better choice than a list.
- Tuples are ordered sequence which means that they preserve the order of their elements. 
- Overall, tuples are a useful data structure in Python that can be used in a variety of situations where you need an ordered sequence of elements that should not be changed.

### 7. Strings 
In Python, String is a sequence of characters enclosed in single or double quotes . In the figure we can see , python is an example of string which is enclosed within double quotes. String can contain any combinations of letters, numbers, and symbols, including whitespace characters such as spaces and tabs. Strings are also immutable, which means that we cannot modify a string once it is created. Since String is a type of sequence it supports operations like slicing , updating , concatenation , repetition, membership and as well as sorting. 
- Strings are amongst the most popular types in python.
- Single, double or triple quotes can be used to show strings.

### 8. Sets 
- A set is an unordered collection of unique items. Set is defined by values separated by comma inside braces {} . If we wish to collect unique things or integers from sequences.
- For example , school administration faces problem because during the information feeding many kids enters the same password and ID. Sets supports unique elements, we can convert the list of ID’s and password into sets and can get only Unique values. 

### 9. Dictionaries 
- In python , a dictionary is a built-in data structure that allows us to store and retrieve data using key-value pairs. A dictionary is like a list or a tuple which means  that it is a collection of items, but it is more flexible because we can access the items using keys instead of integer indices. A dictionary is created using curly braces {} or the dict() constructor. Each key-value pair is separated by a colon : and individual pairs are separated by commas.
- Dictionaries are a powerful tool for storing and manipulating data in Python. They are commonly used in many types of programs, including web applications, data analysis, and machine learning. Suppose Annie works in the municipality's office. And she has to create records of the people of that region. She can create a dictionary where the person's name will be key and BSN number will be the value. 

### 10. Numpy 
Numpy is a python library used for scientific computing and data analysis. The library is written in C and Python, and it provides a fast and efficient way to work with numerical data in Python.
We can consider numpy as one of the powerful python library that provides various features for scientific computing :- 

- Numpy supports multi dimensional array . It provides a powerful array object called ndarray (N-dimensional array), which is a collection of elements of the same data type. Ndarrays are fast, efficient, and provide a variety of methods for performing mathematical operations on arrays.

- NumPy provides a broadcasting feature that allows for the computation of operations between arrays with different shapes and sizes. This feature eliminates the need for explicit looping over arrays and improves the performance of code. So, the processing of the arrays becomes easy and efficient.

- NumPy provides powerful indexing and slicing capabilities for ndarrays. Indexing and slicing allow us to access and manipulate specific elements or subsets of an array.

- NumPy provides a powerful set of functions for performing linear algebra operations, including matrix multiplication, determinant calculation, and eigenvalue/eigenvector computation.


### 11. Pandas

In Python, Pandas is a popular open-source library for data manipulation and analysis. It provides high-performance, easy-to-use data structures and data analysis tools for handling and analyzing structured data. The name pandas is derived from “Panel Data “ – an econometric term for multidimensional data. 
 Pandas supports different kinds of data :- 

- Any kind of tabular data with hetergeneous columns. Columns can be categorical , numerical in nature. 
- It supports times series data which can be ordered and unordered.
- Matrix data with rows and column labels
- Any other observational/statistical data . It can be unlabeled or mixed data which can be placed into a pandas data structure.

