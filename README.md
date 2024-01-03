# Read-from-CSV

## AIM:
To write the program to read from csv.
## ALGORITHM:
### Step 1:
Import the pandas library as "pd".
### Step 2:
Read the CSV file "cars.csv" using read_csv() method and assign it to the variable "df".
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns and 'shape' attribute to find the dimensions of the dataframe.
### Step 5:
Print the output and end the program.
## PROGRAM:
```
#program to read contents from a csv file
#developed by : PREM KUMAR G
#register no:23003614

import pandas as pd
df=pd.read_csv('cars.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
print(df.shape)
```

## OUTPUT:

![WhatsApp Image 2024-01-03 at 19 41 30_6f85858c](https://github.com/PremkumarG3/Read-from-CSV/assets/138955646/47a52e8d-8ebc-48d4-9982-f7441d91d5e3)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
