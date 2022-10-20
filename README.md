# Multiplying-two-matrix

## AIM:


To write a python program for multiplying two matrix.


## Equipments Required:


1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner


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
```python
To write a python program for multiplying two matrix.
Developed by: DHARSHAN V
Register no: 22003103

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
![output](/output.png)

## RESULT:
Thus the program is written to multiply two matrix.

