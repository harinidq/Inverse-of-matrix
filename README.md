# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a matrix.

## ALGORITHM:
### Step 1:
Use import as np.
### Step 2:
Enter the input.
### Step 3:
Use for loop and range.
### Step 4:
Use np.linalg.inv() to find inver of a matrix.
### Step 5:
Print()


## PROGRAM:
```
##Developed by:m.d.harini
##RegisterNumber: 22001980

import numpy as np
a,b=int(input()),int(input())
l1,l2=[],[]
for i in range(a):
    for j in range (b):
        num=l1.append(int(input()))
    l2.append(l1)
    l1=[]
print(l2)
a1=np.array(l2)
x=np.linalg.inv(a1)
print(x)

```

## OUTPUT:
![Screenshot from 2022-10-17 11-19-33](https://user-images.githubusercontent.com/113497680/196099079-53398b6b-31f1-47b3-9691-f57919a4d6ee.png)



## RESULT:
Thus the program is written to find the matrix.
