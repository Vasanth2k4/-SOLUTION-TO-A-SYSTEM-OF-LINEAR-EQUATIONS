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
#Developed by: VASANTHARAJ J
#RegisterNumber:23012935
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
result=np.linalg.solve(a,b)
print(result)
```

## Output:
![output](https://github.com/Vasanth2k4/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/147139769/f4cc7865-e7f6-4c97-b602-14c0146d0426)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

