# Read-from-CSV

## AIM:
To develop a python program to read a file rom csv.
## ALGORITHM:
### Step 1:
Import the pandas function as pd.
### Step 2:
Print the head 
### Step 3:
Print the tail
### Step 4:
Print the number of rows using the length function(len).
### Step 5:
Print the number of coloumns using the same length function(len).

## PROGRAM:
```py
#Python program to read a file from csv.
#Program developed by:R.Joyce Beulah
#Reference number:22009334

import pandas as pd
f=pd.read_csv('cars.csv')
print(f.head(10))
print(f.tail())
print("Row:",len(f.axes[0]))
print("Col:",len(f.axes[1]))
```
## OUTPUT:
![ex6](https://user-images.githubusercontent.com/91368803/215014972-96a2086b-c270-42de-941e-a6a3e0d52a52.png)


## RESULT:
Thus the program for opening a csv file is successfully executed.
