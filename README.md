# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas module as pd.
### Step 2:
Using pd.read_csv() method read the CSV file.
### Step 3:
Using df.head() print the first 10 rows of the CSV file.
### Step 4:
Using df.tail() print the last 5 of the CSV file.
### Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.
## PROGRAM:
'''
Developed by: DEEPAK RAJ S
Register no:212222240023
import pandas as pd
f = pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print("row:",len(f.axes[0]))
print("col:",len(f.axes[1]))
print(f.head())
```
## OUTPUT:
![image](https://github.com/DEEPAK2200233/Read-from-CSV/assets/118707676/f8f68221-a84c-4628-927b-56846d00e317)

## RESULT:
Thus the program executed successfully.
