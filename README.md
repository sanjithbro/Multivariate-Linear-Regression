![293717810-e875da86-378f-40dd-b8c7-f3f4c0ea7342](https://github.com/sanjithbro/Multivariate-Linear-Regression/assets/167451460/baca90db-ea3b-482f-a888-14fba267e392)# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import pandas as pd.
### Step2
Read the csv file.
### Step3
Get the value of X and y variables.
### Step4
Create the linear regression model and fit
### Step5
Predict the CO2 emission of a car where the weight is 1000kg, and the volume is 1390cm3.
### step6
Print the predicted output.
## Program:
```PYTHON
#Multivariate Linear Regression
#Developed by : SANJITH.R
#Register Number : 212223230191
import pandas as pd
from sklearn import linear_model

df=pd.read_csv('/content/cars (1) (1).csv')
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient",regr.coef_)
print("Intercept",regr.intercept_)
print("Amount",regr.predict([[3300,1300]]))
```
## Output:
![293717810-e875da86-378f-40dd-b8c7-f3f4c0ea7342](https://github.com/sanjithbro/Multivariate-Linear-Regression/assets/167451460/6cef35a3-bd32-445b-a09c-65e247746f54)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
