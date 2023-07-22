# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys



### Step 2: 
 Open file using commandline arguments.


### Step 3: 
Using for loop find the word count from the contents of a file.


### Step 4:  
Use len to count number of words.


### Step 5: 
Print the statement.


### Step 6: 
End the program.


## PROGRAM:
```
Developed by:harini.m.d
Registration no:22001980
import sys
count=0
with open(sys.argv[0],'r') as f:
    for line in f:
        word = line.split()
        count+= len(word)
print("World Count in File = ",count)  
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/117935868/214646001-e9af18c5-aa3c-43fb-9d4b-7555036b2233.png)

![image](https://user-images.githubusercontent.com/117935868/214646048-c2671a67-5a91-4de6-ab1f-2fa4f024e720.png)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
