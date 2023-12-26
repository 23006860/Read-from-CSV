# Read-from-CSV

AIM:
### To Write a python program for reading content from a CSV file

ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv

### Step 3:
use head and tail method to get the required contents from the file

### Step 4:
Use len() method to get the number of rows and columns.

### Step 5:
print the output
## PROGRAM:
```
Developed by: RAHUL.V
Register Number:23006860
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0))
print("NUmber of columns:",len(df.axes[1]))
```

## OUTPUT:
![Screenshot 2023-12-26 144655](https://github.com/23006860/Read-from-CSV/assets/139841752/7b807894-46c2-4004-ba06-311866378d1e)


## RESULT:
Thus a python program is written to read the contents of a CSV file
