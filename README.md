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
```
#Program to find the solution for the given linear equations.
#Developed by: R.R.KAMESH
#RegisterNumber: 212223230095
import numpy as np
A = np.array([[5,-3,-10], [2,2,-3],[-3,-1,5]])
b = np.array([-9,4,-1])
x = np.linalg.solve(A, b)
print( x)
```
## Output:
![Screenshot 2024-03-18 193836](https://github.com/23002027/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/139752981/f1adfe3d-3015-47e5-8581-70dcf03da37f)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

