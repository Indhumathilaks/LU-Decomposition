# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
   
## Algorithm

1. Define the package as scipy.linalg import lu.

2. Get input from user and print L and U matrix by 'print' . 

3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable 

4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
# Program to find L and U matrix using LU decomposition.
# Developed by: INDHUMATHI L
# RegisterNumber: 212224220037

import numpy as np
from scipy.linalg import lu

A = np.array(eval(input()))
P,L, U = lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
# Program to solve a system using LU decomposition.
# Developed by: INDHUMATHI L
# RegisterNumber: 212224220037

import numpy as np
from scipy.linalg import lu
A = np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
b = np.array([4, 5, 7])
P, L, U = lu(A)
y = np.linalg.solve(L, np.dot(P, b))
x = np.linalg.solve(U, y)
print(x)
```

## Output:

<img width="1056" height="853" alt="image" src="https://github.com/user-attachments/assets/efeda02d-713a-4393-b02b-6e0e60f23735" />

<img width="1001" height="781" alt="image" src="https://github.com/user-attachments/assets/3502d911-40ae-4d70-bb7d-5520d324e259" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

