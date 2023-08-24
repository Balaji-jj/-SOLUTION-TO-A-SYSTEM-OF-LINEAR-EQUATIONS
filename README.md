# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
``
Program to find the solution for the given linear equations.
#Developed by: Balji j 
#RegisterNumber:212221243001
import numpy as np
num1=np.array([[1,-3],[3,1]])
num2=np.array([0,10])
result=np.linalg.solve(num1,num2)
print(result) 
```
## Output:
![image](https://github.com/Balaji-jj/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/142155013/15f4e3fe-4b27-44c5-9834-08f5a3fd67e4)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

