# Read-from-CSV

## AIM:
To write a python program for reading the csv file content
## ALGORITHM:
### Step 1:
load the csv into a dataframe.
### Step 2:
print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in pandas option settings.
### Step 4:
Check your system's maximum coloumn with the pd.options.max_coloumn statement.
### Step 5:
Increase the maximum  number of rows to display the entire  DataFrame.

## PROGRAM:
### Developed by: kabilan T
### Register Number: 22009071
```
import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:
![output](csv.jpg)
## RESULT:
Thus the program is written to read the csv file
