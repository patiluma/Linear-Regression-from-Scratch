# Linear Regression from Scratch

This project implements Linear Regression from scratch using Python and NumPy, without using machine learning libraries such as scikit-learn. The model is trained using Gradient Descent to learn the optimal weights and bias.

The purpose of this project is to understand the mathematics and optimization behind linear regression models.

## **Overview**

Linear Regression is a supervised machine learning algorithm used to model the relationship between a dependent variable (target) and one or more independent variables (features).

It assumes a linear relationship between input features and the output:
y=wx+b

Where:
- w = weight (slope)
- b = bias (intercept)
- x = feature input
- y = predicted output

The model learns the parameters w and b by minimizing the prediction error.

## **Gradient Descent**

To find the optimal parameters, this implementation uses Gradient Descent, an optimization algorithm that iteratively updates model parameters to minimize the loss function.
The loss function used is Mean Squared Error (MSE)

MSE = 1/n ​∑(ypred​−ytrue​)2

Update Rules: 

w = w−α(∂L/∂w)​

b = b−α(∂L/∂b)
	​
Where:
- α = learning rate
- L = loss function

Gradient Descent updates weights repeatedly until the model converges.

## **Advantages of Linear Regression**
- Simple and easy to interpret
- Fast to train
- Works well when relationships are linear
- Requires relatively little data preparation
- Useful baseline model for many machine learning problems

## **Disadvantages**
- Assumes a linear relationship between variables  
- Sensitive to outliers  
- Cannot capture complex nonlinear patterns  
- Performance depends on feature scaling and data quality

