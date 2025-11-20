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
#Developed by: BALAMURUGAN.K
#RegisterNumber: 25017932

import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
x=np.linalg.solve(A,B)
print(x)

```
Screenshot:
<img width="1467" height="692" alt="Screenshot 2025-11-20 100731" src="https://github.com/user-attachments/assets/73234492-6692-4be7-ad55-f12f4753625d" />

## Output:
<img width="1284" height="200" alt="Screenshot 2025-11-20 100747" src="https://github.com/user-attachments/assets/e9f3939d-4980-4e95-9f3a-93ab83154c0e" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

