# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each rows and columns and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Harish R
#RegisterNumber:22005828
import numpy as np

A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
result=np.linalg.inv(A)
print(result)
```
## Output:
![Screenshot (21)](https://user-images.githubusercontent.com/117935868/211186297-f2c4b782-566c-44ec-bf49-06c5681ad737.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program
