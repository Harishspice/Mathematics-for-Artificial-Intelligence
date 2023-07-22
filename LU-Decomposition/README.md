# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np
2. From scipy.linalg import lu ,lu_factor,lu_solve respectively
3. Get the input of matrix values from user using eval
4. Using P,L,U=lu(A) we can find L and U matrix . Using res=lu_factor(A)
,solution=lu_solve(res,B) we can find LU Decomposition of a matrix. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Harish R
RegisterNumber: 22005828
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Harish R
RegisterNumber: 22005828
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
*/
```

## Output:
## LU matrix
![lu](https://user-images.githubusercontent.com/117935868/215327196-b116db90-9f89-414f-b4e8-b6e392503817.png)

## LU decomposition
![lu dec](https://user-images.githubusercontent.com/117935868/215327253-4eebb2ca-ebb9-471d-91af-590956cf17b2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
