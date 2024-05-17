# Read-from-CSV

## AIM:
To write a python program for reading the csv file content

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:

### Developed By : PRAKASH C
### Registration No: 212223240122
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:

![329804514-0c745bc3-f12c-4ebb-8c66-ebd922d3857b](https://github.com/Prakash-Chandran/Read-from-CSV/assets/147120899/a01853b1-6302-43cb-bbda-299a521e52cb)


## RESULT:
Thus the program is written to read the csv file.
