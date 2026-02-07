# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the np.linalg.solve(), we can find the solutions.

Step 4:
End the program
## Program:
(i) To find the L and U matrix
```
import numpy as np
from  scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
/*
Program to find the L and U matrix.
Developed by: TAMIZHAN B
RegisterNumber: 25018064
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: TAMIZHAN B
RegisterNumber: 25018064
*/
```

## Output:
(i)
![WhatsApp Image 2026-02-07 at 8 46 05 AM](https://github.com/user-attachments/assets/a2119e79-5717-4221-8d56-63ddb38ded7b)
(ii)
![WhatsApp Image 2026-02-07 at 8 46 23 AM](https://github.com/user-attachments/assets/0522a641-e363-4187-ae24-afad53bd29a6)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

