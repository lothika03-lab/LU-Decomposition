
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
Developed by: Lothika M
RegisterNumber: 212225040211
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
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
Program to find the L and U matrix.
Developed by: Lothika M
RegisterNumber: 212225040211
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
![lu decomposition]()

<img width="784" height="863" alt="Screenshot 2026-06-03 080308" src="https://github.com/user-attachments/assets/cc360a2c-114e-4b51-8766-a632e431454c" />

<img width="645" height="726" alt="Screenshot 2026-06-03 075757" src="https://github.com/user-attachments/assets/9147a7de-9bf5-4819-857d-741121c22177" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

