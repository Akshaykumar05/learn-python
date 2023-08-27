
# learn-python
![](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/python-logo-with-scribbled-python-functions-3.jpg)

### Topics need to cover in Python
1. Operators
2. Boolean Exp
3. if...else
4. loops
5. Functions
6. Lists
7. Tuple
8. Object Oriented Programming- Classes & objects
9. Constructor

### Pthon's features:
* Easy to learn, read, maintain, interactive.
* Interpreted language
* A broad standard library
* Free and Open Surce
* Interactive Mode: Debugging
* Databases
* GUI Programming.

  ### Who uses Python
  * Google
  * PBS
  * NASA
  * Librariy of Congress
  * Instagram
 
### Others features:
* Easy-to-learn.
* Code is 3-5 times shorter than Java.
* 5-10 times shorter than C++.
* Since it allows you to express very powerful ideas in very few lines of code while being very readable.
* Not only a Scripting language, also support Web Development and Database Connectivity.
* Rising Demand for Python Programmers.
* Google, Nokia, Disney, Yahoo, IBM use Python.

### Installing Python:
* Download Python from www.python.org
* IDLE: Integrated Development and Learning Environment.

#### Python
* A variale can refer to an object of any type.
* Main drawback: type errors are only cought at runtime.

#### Indentation in Python:
* Use identation for blocks, instead of curly bracket.
* The delimiter followed in Python is a colon (:) and indent spaces or tabs.
#### Others
* The Print() Function
* Assigning values to a variable
* Multiple assignment
* Comments
* Unary & Binary operations
* Division(/) Opreataor and floor Division Operators
* Module (%) Operator
* The exponent operator 
  
#### User Input
##### Program execution Cycle:
* Source Code => Byte Code => PVM

#### Input:
* The input (string) method returns a line of user input as a string.
* The string can be converted by using the conversion methods int(string) converts to int, float(string) converts to float or eval(string) converts and evaluates expressions etc.

##### Arithmetic Questions:
1. Read two integers from STDIN and print three lines where:
   * The first line contains the sum of the two numbers.
   * The second line contains the difference of the two numbers.
   * The third line contains the product of the two numbers.
  
2. Read two integers and print two lines.
   * The fisrt line should contain integer division.
   * The seconf line contain float division.

3. Calculate an average marks of 5 students.

#### Tokens in Python:
| Tokens                                                              | Meanings and Examples                                                                                      |
| :------------------------------------------------------------------ | :----------------------------------------------------------------------------------------- |
| Keywords| Reserved words (ex:, if, else, for)
| Identifiers | Name used to defines/find variables
| Operators | Used to perform operators.(<,>,+,* etc)
| Delimeters | Symbols to perform operators. (:, ',', ;, etc
|Literals | Can be anything number of string(78, '21.90')

#### Python Core Types (Data Types)
| Types                                                               | Examples                                                                                      |
| :------------------------------------------------------------------ | :----------------------------------------------------------------------------------------- |
| 1. Integer | 10, 20, -2, etc
| 2. Float | 12.34, 45.21, 12.766, etc
| 3. Complex | 1 + 4j, 2 - 8j
| 4. Boolean | True, False
| 5. String | 'Hello World', "bye"

#### Object Characterisation:
| Types                                                               | Examples                                                                                      |
| :------------------------------------------------------------------ | :----------------------------------------------------------------------------------------- |
| 1. Identity | id(x)
| 2. Type | type(x)
| 3. Value |

#### Expressions in Python
1. A data value or set of operation to compute a value.
* Example: 1+4*3

2. Arithmetic Operator:
* = - * /
* %
* (multiply) **

3. Precedence: Order in which operators are computed.
   * / % ** have a higher predence than +, -
   * Parenthesis can be used to force a certain evaluation.
   * (1+3) * 4 is 16

#### Operators
| Types                                                               | Examples                                                                                      |
| :------------------------------------------------------------------ | :----------------------------------------------------------------------------------------- |
| 1. Arithmetic Operators | (+, -, /, **, //, %)
| 2. Relational Operators | (==, <,>, <=, >=, !=)
| 3. Assignment Operators | (=, +=, -=, *=, //=, %=, **=)
| 4. Bitwise Operators | (&,|,^,~, <<,>>)
| 5. Logical Operators | (and, or, not)
| 6. Membership & Identity | in, not in, is, is not)

#### Decision Making Statement: (Conditional Statement)
* if
* if-else
* if-elif-else
* Nested if

#### Data Structure in Python
* Some of the Data Structures (built-in container types) available in Python are:
1. Strings
2. List
3. Tuples
4. Sets
5. Dictionaries

2. Lists
* Dynamic arrays, **mutable** collection of data.
* A list is the Python equivalent of an array, but is resizeable.
* Can contain element of different types.
* An ordered group of sequences enclosed inside square brackets andseparated by symbol comma(,)
* list1 = [] # creation of empyy list
* list2 = list() # empty list using list funtion
* list3 = [sequence1, Sequence2]
  * Examples
    * country = ['India'
    * Lists of strings
    * states = ['tamilnadu','Gujrat','Mizoram']
    * array = [2,3,4,5,7,19,23,15,20] # list of integers
    * L = [7575, 'Shyam', 25067.56] # list of mixed data
    * # Following is a Nested 2-D list
    * L = [[7575,''Join",25067.56], [7541,"Joe", 5678.2], [7832, "Jill", 43565.23]]
   
  * Basic List Operatons
    * list= [2,34,53,12,9]
    * len(list)  # length of list is 5
    * Print([1,3,9]+[8,6,5]) # Concatenation of two lists
    * ['Hello']*3  #['Hello','Hello','Hello']
    * [5]*3  #[5,5,5]
    * print97in[1,3,7]) # Membership,
    * for n in[1,3,7]:
      * print(n) #print1,3,7
     
  * Accessing values in Lists
    * To access values in lists, use the square brackets for slicing along with the index or indices to obtain value available at that indes.
    * list1=['physics','chemistry',1995,2000]
    * list2=[9,3,8,4,5,7,1,6]
    * print("first element: ", list1[0])      
4. Tuples
* A tuple is a sequence of immutable Python objects. Tuples are sequences, just like lists. The differences between tuples and lists are, the tuples canm not be changed unlike lists and tuples use parentheses, whereas lists use square brackets.
* Creating a tuple is as simple as putting different comma-separated values. Optionally you can put these comma-separated values between parenthese also. For example-
  * tup1 = ('physics', 'chemistry', 1997, 2000);
  * tup2 = (1, 2, 3, 4, 5 );
  * tup3 = "a", "b", "c", "d" ;

* The empty tuple is written as two parentheses containing nothing-
  * tup1 = ();

* To write a tuple containing a single value you have to include a comma, even though there is only one value -
  * tup1 = (50, );

## Python Libraries
### 1. NumPy
* NumPy (Numerical Python) is an open source Python library that’s used in almost every field of science and engineering. It’s the universal standard for working with numerical data in Python, and it’s at the core of the scientific Python and PyData ecosystems. NumPy users include everyone from beginning coders to experienced researchers doing state-of-the-art scientific and industrial research and development.
* It is used for working with arrays.
* It is used for compulsion and processing of single and multi dimentional array of element.
* Smaller memoory consumption and better runtime behavior.
  #### To instal the Library
  * pip start numpy
  * imort numpy
  #### Basic Operations
  * "import numpy as np"
    
     #### Some Popular Python Packages for Data Science/Big Data/Machine Learning You Get Pre-compiled – with ActivePython
     * pandas (data analysis)
     * NumPy (multi-dimensional arrays)
     * SciPy (algorithms to use with numpy)
     * HDF5 (store & manipulate data
     * Jupyter (research collaboration)
     * PyTables (managing HDF5 datasets
     * HDFS (C/C++ wrapper for Hadoop)
     * pymongo (MongoDB driver)
     * SQLAlchemy (Python SQL Toolkit)
   
### 2. Pandas
## OOPs Concepts in Python
 * Class, Object and Method
 * Constructor
 * Encapsulation
 * Inheritance
 * Polymorphism

