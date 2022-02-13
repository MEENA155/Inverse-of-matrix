# Inverse-of-matrix

## AIM:
To write a python program to multiply two arrays using numpy.
## ALGORITHM:
### Step 1:
Import numpy as np
### Step 2:
declare a variable array1 as a empty list
### Step 3:
declare a variable array2 as a empty list
### Step 4:
get input value as n
### Step 5:
iterate a variable i in range n by for loop and append the values to the list array 1 end the loop
### Step 6:
iterate a variable j in range n by for loop and append the values to the list array 2 end the loop
### Step 7:
Declare a variable product to array and compute array1*array2
### Step 8:
Print the value of the product

## PROGRAM:
import numpy as np
l1,l2 = [],[]
r,c=int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value1=np.array(l2)
inverse = np.linalg.inv(value1)
print(inverse)
## OUTPUT:
![Screenshot (111)](https://user-images.githubusercontent.com/94677128/153770781-e8396b02-4676-4bc8-a3cf-3ed3fe19d272.png)

## RESULT:
The program run successfully
