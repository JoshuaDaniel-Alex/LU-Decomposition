# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Joshua Daniel A  
RegisterNumber: 212225040161 (25017654)
*/


import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Joshua Daniel A
RegisterNumber: 212225040161 (25017654)
*/

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)


```

## Output:
<img width="1232" height="474" alt="Screenshot 2026-02-07 082355" src="https://github.com/user-attachments/assets/ebe81f15-f308-4a29-b47b-29137f112f9b" />
<img width="1220" height="211" alt="Screenshot 2026-02-07 082413" src="https://github.com/user-attachments/assets/b27a2c93-e2bc-47eb-80a9-95a1b4cd7e17" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

