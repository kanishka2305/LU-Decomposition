# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import numpy library using import statement.

Step 2:
From scipy package import lu().

Step 3:
Get input from user and pass it as an array.

Step 4:
Get P, L, U matrix using lu()

Step 5:
Print L and U matrix 


## Program:
(i) To find the L and U matrix
```python
Program to find L and U matrix using LU decomposition.
Developed by: kanishka.v.s
RegisterNumber: 22003409

# To print L and U matrix
import numpy as np
from scipy.linalg import lu
S=eval(input()) 
P,L,U=lu(S) 
print(L) 
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
Program to solve a matrix using LU decomposition.
Developed by:kanishka.v.s 
RegisterNumber: 22003409

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input()) 
B=eval(input()) 
lu, piv=lu_factor(A) 
x=lu_solve((lu, piv),B) 
print(x) 
```

## Output:
![lu decomposition](/lu%20output%201.png)

![OUT](/lu%20output%202.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

