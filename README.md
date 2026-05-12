# Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student

## AIM:
To write a program to implement the the Logistic Regression Model to Predict the Placement Status of Student.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Collect and preprocess the dataset (handle missing values, encode categorical data, and normalize features).

2.Split the dataset into training and testing sets to evaluate model performance.

3.Train the Logistic Regression model using the training data to learn the relationship between features and placement status.

4.Predict and evaluate the model using test data with metrics like accuracy, confusion matrix, or precision/recall. 

## Program:
Program to implement the the Logistic Regression Model to Predict the Placement Status of Student.

Developed by:A NANDHA

RegisterNumber:212225040271
```py
/*
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
data = pd.read_csv("Untitled.csv")
data = data.drop("salary", axis=1)
data = pd.get_dummies(data, drop_first=True)
X = data.drop("status_Placed", axis=1)
y = data["status_Placed"]
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
model = LogisticRegression(max_iter=1000)
model.fit(X_train, y_train)
print("Accuracy:", model.score(X_test, y_test))
X1 = X.iloc[:, 0].values.reshape(-1, 1)
model_plot = LogisticRegression(max_iter=1000)
model_plot.fit(X1, y)
plt.scatter(X1, y, color='blue')
x_values = np.linspace(X1.min(), X1.max(), 100)
y_values = model_plot.predict_proba(x_values.reshape(-1,1))[:,1]

plt.plot(x_values, y_values)

plt.xlabel("Feature")
plt.ylabel("Probability")
plt.title("Logistic Regression Curve")
plt.show()  
*/
```

## Output:
<img width="778" height="533" alt="image" src="https://github.com/user-attachments/assets/b40da7d9-c57c-46fe-87f5-c2d807b8cc59" />



## Result:
Thus the program to implement the the Logistic Regression Model to Predict the Placement Status of Student is written and verified using python programming.
