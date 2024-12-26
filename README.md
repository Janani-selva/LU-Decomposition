# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Find the l and u matrix by using numpy and linalg from scipy
2. Print the l matrix and u matrix 
3. find the lu decomposition by using numpy and lu_factor and lu_solve
4. Print the following matrix

## Program:
(i) To find the L and U matrix
'''
Program to find L and U matrix using LU decomposition.
Developed by: Janani S
RegisterNumber:24901127
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```


(ii) To find the LU Decomposition of a matrix
'''
Program to solve a matrix using LU decomposition.
Developed by:Janani S 
RegisterNumber:24901127 
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

## Output:
![Alt text](<Screenshot from 2024-12-26 18-56-37.png>)
![Alt text](<Screenshot from 2024-12-26 18-56-54.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

