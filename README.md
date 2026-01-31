# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Load the dataset into a DataFrame and explore its contents to understand the data structure.

2.Separate the dataset into independent (X) and dependent (Y) variables, and split them into training and testing sets.

3.Create a linear regression model and fit it using the training data.

4.Predict the results for the testing set and plot the training and testing sets with fitted lines.

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
import numpy as np
from sklearn.linear_model import LinearRegression
import matplotlib.pyplot as plt

X = np.array([30, 40, 50, 65, 75,85,95]).reshape(-1, 1)
y = np.array([25, 30, 45, 50, 80,90,100])

model = LinearRegression()
model.fit(X, y)

y_pred = model.predict(X)

print("Slope (Coefficient):", model.coef_[0])
print("Intercept:", model.intercept_)

plt.scatter(X,y)
plt.plot(X, y_pred)
plt.xlabel("ATTENDENCE")
plt.ylabel("MARKS")
plt.legend()

Developed by: Varsha M
RegisterNumber:  25001006
*/
```

## Output:
<img width="886" height="653" alt="image" src="https://github.com/user-attachments/assets/c8c6dca7-44b5-417a-831e-43f423351e6a" />



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
