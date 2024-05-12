# Read-from-CSV

## AIM:
To write a program to read a content from a CSV file.

## ALGORITHM:
### Step 1:
Import the Pandas library with the alias 'pd'.
### Step 2:
Use the 'pd.read_csv()' function to read the "nba.csv" file located at "C:/Users/admin/Downloads/nba.csv" into a DataFrame object named 'df'.
### Step 3:
Print the first 10 rows of the DataFrame using the 'head()' method.
### Step 4:
 Print the last 5 rows of the DataFrame using the 'tail()' method.
### Step 5:
Print the number of rows and columns in the DataFrame using the 'len()' function along with the 'axes' attribute.

## PROGRAM:
```python
/*
To write a program for reading content from a CSV file:
Developed by: Visalan H
Register number: 212223240183
*/

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
### HEAD()
![image](https://github.com/Visalan-H/Read-from-CSV/assets/152077751/3e87226b-69aa-4bd2-9c4a-3426c5713a98)
### TAIL()
![image](https://github.com/Visalan-H/Read-from-CSV/assets/152077751/3aede001-41c2-41df-8e8c-2da1eb8c8786)
### Number of rows and columns
![image](https://github.com/Visalan-H/Read-from-CSV/assets/152077751/d3137bcf-3f6f-4a50-80c3-e90f8742e12e)

## RESULT:
Thus a program for reading content from a CSV file is executed successfully.
