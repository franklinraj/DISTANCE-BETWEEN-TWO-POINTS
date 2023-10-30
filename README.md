# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Start the program
### Step 2: 
Get the input from the user using eval(input)
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4:
using the slicing concept rotate the list 
### Step 5: 
using concatination operation display in the entire rotated list
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by:Franklin raj G 
#RegisterNumber:23001518
import math
def distance(x1,y1,x2,y2):
    dx=x2-x1
    dy=y2-y1
    d=math.sqrt(dx**2+dy**2)
    return d
x1=4
y1=2
x2=10
y2=6
d=distance(x1,y1,x2,y2)
print(round(d,2))
```
### OUTPUT:
!["output](/distance.png)
### RESULT:
Thus the python program for distance between two points is excueted successfully
