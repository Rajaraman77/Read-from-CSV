# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file
## ALGORITHM:
### Step 1:
import pandas as pd
### Step 2:
Read the csv file
### Step 3:
Print the first 10 rows
### Step 4:
Print the next five rows
### Step 5:
print the toal no.of rows and columns with argument 0 for row and argument 1 for column.
## PROGRAM:
```
## #Program to read contents from a CSV file.
#Developed by: RAJARAMAN V
#Reg No: 23014299
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no. of columns",len(df.axes[1]))OUTPUT:
```
## OUTPUT:
![image](https://github.com/Rajaraman77/Read-from-CSV/assets/150319383/337abceb-fb50-4d7e-8c06-59762f19aaca)

## RESULT:
The program is executed successfully
