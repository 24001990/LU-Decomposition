# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1: Import the numpy module to use the built-in functions for calculation

Step 2: Prepare the lists from each linear equations and assign in np.array()

Step 3: Using scipy.linalg import lu ,we can find L and U matix.

Step 4: By using lu_factor ,lu_solve .we can find lu decomposition matrix.

Step 5: End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: DODLA SUSMITHA
RegisterNumber: 212224110016
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
P,L,U=lu(matrix)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: DODLA SUSMITHA
RegisterNumber: 212224110016
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot = lu_factor(A)
result = lu_solve((lu,pivot),B)
print(result)

*/
```

## Output:
![lu decomposition]()
<img width="1229" height="946" alt="Screenshot 2025-09-29 221248" src="https://github.com/user-attachments/assets/bbcfd055-0519-475e-834b-54a2ca10628d" />
<img width="1209" height="771" alt="Screenshot 2025-09-29 221441" src="https://github.com/user-attachments/assets/6b7b2fb6-7984-4730-90cd-ecb8594629d2" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

