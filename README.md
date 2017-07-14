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
  - 
  
  2.8. Variable names
  - Since Python dont use type declaration, so it's helpful if use a name that meaningful so you don't forget type of variables
  - Python prefers underscore to camelCase
  - Avoid using keyword as variable name, it can cause syntax error
  - Using name like str or list don't cause error but it will override system varialbes
  
  2.9. More on modules and their namespaces
  
  2.10. Online help, help() and dir()
  
  
