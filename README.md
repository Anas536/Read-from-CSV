# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output

## PROGRAM:
```
# Developed by: Mohamed Anas O.I
# Register Number: 23008005
import pandas as pd
df = pd.read_csv('pandascsv.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![Screenshot 2023-12-24 205920](https://github.com/Anas536/Read-from-CSV/assets/139841834/fb714898-2ae5-4101-9c1d-543edc05f9ca)

## RESULT:
