# GOOGLE-PYTHON-CLASS

1. Setup
2. Introduction
  2.1. Prelude
  - This course using Python 2
  - Books : http://www.informit.com/articles/article.aspx?p=1849069
  - Interactive exercises: https://stackoverflow.com/questions/3217222/beginner-python-practice/3226704#3226704
  
  2.2. Language introduction
  - Python is interpreted language
  - There is no type declaration of variables, methods, parameters, functions... -> short, flexible
  - No compiled-time checking, Python checks our code during run-time
  - Like C or Java, variable name is case-sensitive. It means that a is different with A
  - Unlike C or Java, statement in Python ending at the end of the line, not by semicolons
  
  2.3. Python source code
  - Is file .py, also called module
  - Run this file by calling python interpreter: python xyz.py. Code is read line by line : 1, 2, 3 ...
  
  2.4. Import, Command-line arguments, and len()
  - Python code can either read directly like above or imported somewhere
  - If code is run directly, use special variable __name__ and set to "__main__"
  - argv contains command-line arguments, argv[0] is program itself, argv[1] is the first argument
  - argc is the number of arguments
  - len() function return the number of element of array, tupple, dictionary, string...
  
  2.5. User-defined functions
  - function and if is grouped by identations, it can take arguments and return to the caller
  - '+' or '*' using for repeated string , but * is faster because size is computed only one time. 
  - They are overloaded operators because it means different to different types
  
  
  2.6. Identation
  - Unusual feature of Python
  - Identation have to be the same for all the statements of a function 
  - Avoid using TAB for identation 
  - How many space is enough : 4 or 2
  
  2.7. Code checked at run-time
    
  2.8. Variable names
  - Since Python dont use type declaration, so it's helpful if use a name that meaningful so you don't forget type of variables
  - Python prefers underscore to camelCase
  - Avoid using keyword as variable name, it can cause syntax error
  - Using name like str or list don't cause error but it will override system varialbes
  
  2.9. More on modules and their namespaces
  - A module (*.py) can be imported to other module by : import nameModule.py
  - Think Namespace as a containter of names. Name here can be function, variable. Name is connected with a namespace by '.'
  - We can explicitly specify what name from namespace we want to import by : from namespaceX import name1, name2
  - Then we can call these name by short names but it is not recommended, we want to know what name from what namespace
  
  2.10. Online help, help() and dir()
  - Google
  - help : describe what function do
  - dir : attributes
  
3. String
  - 2 ways to enclose a string : double quotes or single quotes
  - Using blackslash \ if there's double quote or single quote somewhere in string
  - Blackslash can be used to span string in multiple lines
  - Otherwise, tripple quotes is alternative way
  - IMPORTANT : STRING IN PYTHON IS IMMUTABLE (same as JAVA) ? -> How it works?
  - len() is a built-in function return the number of elements (avoid using for variable name)
  - In Python, '+' doesnt automatically convert number to string like Java
  
  3.1 String methods
    - Method running on object (OOP idea)
    - Some common methods:
    s.lower(), s.upper()
    s.strip() -> removes space at top and end
    s.isalpha(), s.isdigit(), s.isspace()
    s.startswith('sth'), s.endswith('sth') -> checks if string starts or ends with a given string, return true or false
    s.find('sth') -> checks if string contains a particular given string, return index of first character, or -1 if not found
    s.replace('old', 'new') -> return new string where all old chars is replaced by new chars
    s.split() -> return a array of substring is seperated by what is specified in argument
    s.join(arr) -> opposite of split, it joins elements in the list (s here is what seperated between elements)
  
  3.2 String slices
    - Work for string and list
    - Explicit way: s[a:b] -> from index of a , extending up but not including b
    Some variants: 
    s[a:] -> from index of a up to the end
    s[:b] -> from start up to but not including b
    s[:] -> all
    s.[:a] + s[a:] is actually s
    - a,b can be negative numbers, last char is -1 and so on
    
    
  3.3 String %
    - Works same as printf in C, string can take in arguments at where % is specified, like parameters
    - %d is integer, %s is string, %f is float
    - Trick : To span the who expression in multiple lines, use a addiitonal outer paretheses
  
  3.4 i18n Strings (Unicode)
    - Differentiate between normal string and unicode
    - Use u prefix ahead of string to specify this is a unicode string
    - Share many same functions with normal string
    -> Research more on this
  
  3.5 If statement
    - Different from C/Java
    - Using ':' and identation to group statements
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
