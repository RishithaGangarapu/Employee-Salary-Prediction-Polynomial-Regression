
# Employee Salary Prediction using Polynomial Regression

## Project Overview

This is a Machine Learning practice project that predicts employee salary using Polynomial Regression.

Polynomial Regression is used to model non-linear relationships by transforming the independent variable into polynomial features.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithm

Polynomial Regression

## Project Workflow

1. Import required libraries
2. Load the employee salary dataset
3. Select independent and dependent variables
4. Train Linear Regression model
5. Transform the independent variable using PolynomialFeatures
6. Train Polynomial Regression model
7. Visualize the regression curve
8. Predict salary for a given position level

## Polynomial Regression

In this project, a degree-5 polynomial model is used.

```python
from sklearn.preprocessing import PolynomialFeatures
from sklearn.linear_model import LinearRegression

poly_reg = PolynomialFeatures(degree=5)

x_poly = poly_reg.fit_transform(x)

lin_reg_2 = LinearRegression()
lin_reg_2.fit(x_poly, y)
```
