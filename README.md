# Lab-5_202001192
# Author - Vikaskumar Patni
# Static Analysis


## 1 github.com/quatrope/ProperImage/blob/master/setup.py
   Static analysis using pylint tool
   Here is output message  
   
  ![image](https://user-images.githubusercontent.com/103668123/225579646-9ed2246f-3069-42b0-a496-6df9cf89d317.png)


### Analysis:  
 Pylint -(code analysis tool) that has detected various issues in a Python script's setup.py file.  
 These issues include missing a final newline character,   
 Importing a module that cannot be found  
 Not explicitly specifying an encoding when using the open() function &  
 Missing function or method docstrings.   
 These issues can cause problems with the code's readability, maintainability, and compatibility.   
 Addressing these issues will help to improve the code's quality and reduce the potential for errors.



##  2 github.com/quatrope/ProperImage/blob/master/ez_setup.py
  Static analysis using pylint tool  
  Here is output message  
  
 ![image](https://user-images.githubusercontent.com/103668123/225579733-887181fc-2559-4320-bf19-8b8dcba7b81f.png)


### Analysis:  
Pylint has given few  warnings and errors related to the above file.  
The warnings include missing final newline, self-import, unspecified encoding for the open function, missing function or method docstrings, and incorrect import order.  The suggested solutions include adding a final newline character, removing self-imports, explicitly specifying the encoding used with the "open" function, adding missing docstrings, and fixing the import order.    
To address these warnings and errors, you can add a newline character at the end of the file to resolve the missing-final-newline error.   
Then, remove any unnecessary self-imports to resolve the import-self warning. File should explicitly specify the encoding used with the "open" function to resolve the unspecified-encoding warnings.  
Add docstrings to any functions or methods that are missing them.   
Finally, move the "import setuptools" import before the "from ez_setup import use_setuptools" import to resolve the wrong-import-order error.



