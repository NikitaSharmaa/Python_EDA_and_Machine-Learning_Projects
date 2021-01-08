## Prediction using Supervised ML

![enter image description here](https://www.thestatesman.com/wp-content/uploads/2018/01/kid.jpg)

The aim of this project is to __predict the percentage of marks__ that a student is expected to score __based upon the number of hours they studied__. 

This is a simple project for practicing Linear Regression. In this project we will see how the Python Scikit-Learn library for machine learning can be used to implement regression functions. This is a simple linear regression task as it involves just two variables.

The dataset of this project contains 
1.  25 observations: student data (rows)
2.  2 columns	
- Hours: Number of study hours
- Score: Marks scored

## Introduction to Linear Regression

**Linear regression**  is a  _basic_  and  _commonly_  used type of  **predictive analysis**. The overall idea of regression is to examine two things:

-   Does a set of  **predictor variables**  do a good job in predicting an  **outcome**  (dependent) variable?
-   Which variables in particular are  **significant predictors**  of the outcome variable, and in what way they do  **impact**  the outcome variable?

These regression estimates are used to explain the  **relationship between one dependent variable and one or more independent variables**. The simplest form of the regression equation with one dependent and one independent variable is defined by the formula :  
𝑦=𝛽0+𝛽1𝑥y=β0+β1x

![enter image description here](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQjUY15ETxLjSulW7BLpzWCstNNzBfcAtQfTg&usqp=CAU)

What does each term represent?

-   𝑦y  is the response
-   𝑥x  is the feature
-   𝛽0β0  is the intercept
-   𝛽1β1  is the coefficient for x

#### Assumptions of Linear Regression[](http://localhost:8889/notebooks/Documents/DataScience/INSAID/Term%203%264/ML/LinearReg/LinearRegression_TVsales.ipynb#4.1.1-Assumptions-of-Linear-Regression)

1.  There should be a linear and additive relationship between dependent (response) variable and independent (predictor) variable(s). A linear relationship suggests that a change in response Y due to one unit change in X¹ is constant, regardless of the value of X¹. An additive relationship suggests that the effect of X¹ on Y is independent of other variables.
2.  There should be no correlation between the residual (error) terms. Absence of this phenomenon is known as Autocorrelation.
3.  The independent variables should not be correlated. Absence of this phenomenon is known as multicollinearity.
4.  The error terms must have constant variance. This phenomenon is known as homoskedasticity. The presence of non-constant variance is referred to heteroskedasticity.
5.  The error terms must be normally distributed.


