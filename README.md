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
#program to implement multivariate linear regression 
#developed by : PREM KUMAR G
#register no:23003614

import pandas as ps
from sklearn import linear_model
data=ps.read_csv("cars.csv")
x=data[['Weight','Volume']]
y=data[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(x,y)
print('Coefficients:',regr.coef_)
print('Intercept:',regr.intercept_)
predict=regr.predict([[3300,1300]]) 
print('Predicted CO2 for for the corresponding weight and volume',predict)
```

## OUTPUT:

![image](https://github.com/PremkumarG3/Read-from-CSV/assets/138955646/db3a0ef7-56cc-4cf8-8a00-c7f2b25a493b)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
