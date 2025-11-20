# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import panda as pd

### Step2
import linear model from sk learn

### Step3
read the csv file

### Step4
find the multivariate regression

### Step5
display the output

## Program:
```
import pandas as pd
from sklearn import linear_model
df = pd.read_csv("C:\\Users\\admin\\Downloads\\car (1).csv")
X = df[["Volume", "Weight"]]
Y = df["CO2"]
regr = linear_model.LinearRegression()
regr.fit(X,Y)
print("Coefficence", regr.coef_)
print("Intercept", regr.intercept_)
print("Predicting the CO2", regr.predict([[3300, 1300]]))
```
## Output:

<img width="1402" height="427" alt="Screenshot 2025-11-20 102959" src="https://github.com/user-attachments/assets/bc11dd88-3798-4d52-a486-bd8d6eba1da2" />

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
