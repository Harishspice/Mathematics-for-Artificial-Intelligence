# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix




```
## Output:
### 1-Norm of a Matrix
![norm1](https://user-images.githubusercontent.com/117935868/215326779-c8767a00-a3fd-494f-ac88-5eef310c7f3c.png)


### 2-Norm of a Matrix
![norm2](https://user-images.githubusercontent.com/117935868/215326898-e3d6c332-4e09-416a-beb4-2bcf17cc9aac.png)


### Infinity Norm of a Matrix
![inf norm](https://user-images.githubusercontent.com/117935868/215326880-950326a0-d1a7-435f-aac5-77bf4ea2c0e3.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
