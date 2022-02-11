# Multiplying-two-matrix

## AIM:
To write a python program for multiplying two matrix.

## ALGORITHM:
### Step 1:
Import Numpy as np.
### Step 2:
Get input from the user.
### Step 3:
Create empty lists l1 and l2.
### Step 4:
Use for loop to append the values into the list created.
### Step 5:
Print the product of two arrays.

## PROGRAM: 
```
To write a python program for multiplying two matrix.
Developed by: Aashima Nazreen Sayeed S
Register no: 21500368
import numpy as np
x = int(input())
l1 =[]
l2 =[]
for i in range(x):
    l1.append(int(input()))
for i in range(x):
    l2.append(int(input()))
arr1 = np.array(l1)
arr2 = np.array(l2)
print("Product of two arrays is:",arr1*arr2)
```

## OUTPUT:
![multiply](https://user-images.githubusercontent.com/93427086/153587811-c828b27f-5f49-4c9a-996f-be0233876258.png)

## RESULT:
Thus the program is written to multiply two matrix.

