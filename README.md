# Lab-5_202001233
 
**Name:** Jainam M. Bhavsar  
**Student ID:** 202001233  
**Lab:** 5  
**Date:** 16/03/23  
## Static Analysis

**Language** : Python  
**Tool:** mypy  


**Link 1:** https://github.com/Mrinank-Bhowmick/python-beginner-projects/blob/main/projects/Hangman/main.py  
**Output**:  
![Screenshot (2)](https://user-images.githubusercontent.com/75676753/225574787-3d095668-87c0-425e-ba63-81a53ce2e5e4.png)  
Understanding of the errors:  
This error is indicating that the Python module "RandomWords" is either not installed or cannot be found by the MyPy static type checker.  

**Link 2:** https://github.com/Mrinank-Bhowmick/python-beginner-projects/blob/main/projects/Calculator/main.py  
**Output**:  
![Screenshot (3)](https://user-images.githubusercontent.com/75676753/225575188-4d24a860-654f-4b98-a508-2d6688737932.png)  
Understanding of the errors:  
This error is indicating that there is a type mismatch between a value of type "str" and a variable of type "int" in an assignment statement in line 46 of the "main.py" file.  

**Link 3:** https://github.com/Mrinank-Bhowmick/python-beginner-projects/blob/main/projects/Captcha_Genrator/Captcha_Genrator.py  
**Output**:  
![Screenshot (4)](https://user-images.githubusercontent.com/75676753/225575518-e8f6e5ba-d888-4057-a814-311aa0109d95.png)  
Understanding of the errors:  
The first error in line 13 is indicating that MyPy cannot find the implementation or library stub for the "captcha.image" module. This means that MyPy is not able to check the types of the functions and classes in this module because it does not have access to the necessary type information.  

The second error in line 22 is indicating that there is a type mismatch in an assignment statement. Specifically, the expression on the right-hand side of the assignment has type "str" but the variable on the left-hand side has type "Callable[[], float]".  

**Link 4:** https://github.com/Mrinank-Bhowmick/python-beginner-projects/blob/main/projects/Alarm%20Clock/alarm_clock.py  
**Output**:  
![Screenshot (5)](https://user-images.githubusercontent.com/75676753/225575899-11a0347e-f94a-4a8b-89da-40e024731f21.png)  
Understanding of the errors:  
The error message in line 5 is indicating that there is a type mismatch in the import statement for the "Event" class. Specifically, the import of "Event" from the "threading" module has a different type than the import of "Event" from the "tkinter" module.  

**Link 5:** https://github.com/Mrinank-Bhowmick/python-beginner-projects/blob/main/projects/ScreenRecorder/main.py  
**Output**:  
![Screenshot (6)](https://user-images.githubusercontent.com/75676753/225576325-58f38ef5-d846-4ccb-95cf-c26a8e74c62e.png)  
Understanding of the errors:  
1st Error indicates that the "cv2" module could not be found or does not have a type stub. This could be due to the module not being installed or due to missing type hints.  

2nd Error indicates that library stubs are missing for the "pyautogui" module.   

3rd Error indicates that library stubs are missing for the "win32api" module.  

4th Error indicates that the "numpy" module could not be found or does not have a type stub. 
