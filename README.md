# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Load the CSV into a DataFrame.

## Step 2:
Print the number of contents to be displayed using df.head().

## Step 3:
The number of rows returned is defined in Pandas option settings.

## Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

## Step 5:
Increase the maximum number of rows to display the entire DataFrame

## Step 6:
End the program.

## PROGRAM:
```
To write a python program for reading content from a CSV file.
Developed by: HAREVASU S
Register Number: 212223230069

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2024-05-11 144023](https://github.com/Harevasu/Copy-File/assets/147985044/385e6221-c684-4b41-8bfb-70d9c66dd375)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
