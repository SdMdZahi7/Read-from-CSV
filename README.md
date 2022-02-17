# Read-from-CSV

## AIM:
To write a python program to read contents from a csv file.
## ALGORITHM:
### Step 1:Import pandas as pd.
### Step 2:Read the CSV file using read_csv method.
### Step 3:Use head and tail method to get the required contents from the file.
### Step 4:Use len() method to get the number of rows and columns.
### Step 5:Print the output.

## PROGRAM:

import pandas as pd
df=pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print('No. of Columns:',len(df.axes[1]))
print('No. of Rows:',len(df.axes[0]))

## OUTPUT:

![image](https://user-images.githubusercontent.com/94187572/154527463-6b00150d-e72f-4c3e-abb4-8448c73add2d.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
