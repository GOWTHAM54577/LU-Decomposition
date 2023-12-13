# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Import the numpy module to use the built-in functions for calculation

## Step 2:
Prepare the lists from each linear equations and assign in np.array()

## Step 3:
Using the np.linalg.solve(), we can find the solutions.

## Step 4:
End the program
## Program:
(i) To find the L and U matrix
```
/*
Program to find L and U matrix using LU decomposition.
Developed by: GOWTHAM N
RegisterNumber: 23013437
import numpy as np
from scipy.linalg import lu
A=eval(input())
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu=lu_factor(A)
x=lu_solve(lu,B)
print(x)
*/
```

## Output:
![OUTPUT](https://github.com/GOWTHAM54577/LU-Decomposition/assets/144589420/9b5e8bcf-475a-4277-92be-2c89be100f35)
![OUTPUT](https://github.com/GOWTHAM54577/LU-Decomposition/assets/144589420/466e7a22-1b44-44a7-b202-d79c3f4a2b4c)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

