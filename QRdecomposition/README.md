# Algorithm for QR Decomposition
## Aim:
To implement QR decomposition algorithm using the Gram-Schmidt method.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Intialize the matrix Q and u
2.	The vector u and e is given by

![image](https://github.com/Harishspice/Mathematics-for-Artificial-Intelligence/assets/117935868/e78d2b51-5c1b-4590-95c0-2b48934d1008)

![image](https://github.com/Harishspice/Mathematics-for-Artificial-Intelligence/assets/117935868/83e59c11-e985-4aed-a72d-e1dfbf853e7b)

![image](https://github.com/Harishspice/Mathematics-for-Artificial-Intelligence/assets/117935868/60890874-8910-45e2-b46b-c6999349cb08)

3.	Obtain the Q matrix   
![image](https://github.com/Harishspice/Mathematics-for-Artificial-Intelligence/assets/117935868/b074bf68-5208-4373-8693-d952c77de596)
4.	Construct the upper triangular matrix R
![image](https://github.com/Harishspice/Mathematics-for-Artificial-Intelligence/assets/117935868/d9f355db-5f52-43a8-9e46-9f79df7e06ab)



## Program:
### Gram-Schmidt Method
```
Developed by: Harish R
RegisterNumber: 22005828
import numpy as np
arr=np.array(eval(input()))
n,m=arr.shape
u=np.empty((n,m))
e=np.empty((n,m))
u[:,0]=arr[:,0]
e[:,0]=u[:,0]/np.linalg.norm(u[:,0])
for i in range (1,n):
u[:,i]=arr[:,i]
for j in range(i):
u[:,i]-=(arr[:,i]@e[:,j])*e[:,j]
e[:,i]=u[:,i]/np.linalg.norm(u[:,i])
R=np.zeros((n,m))
for i in range(n):
for j in range(i,m):
R[i,j]=arr[:,j]@e[:,i]
print(e)
print(R)






```

## Output
![Screenshot (68)](https://user-images.githubusercontent.com/117935868/215328467-e41558fd-41e5-482b-885a-548703e9d595.png)


## Result
Thus the QR decomposition algorithm using the Gram-Schmidt process is written and verified the result.
