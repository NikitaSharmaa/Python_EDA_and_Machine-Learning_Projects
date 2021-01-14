## Car Sale Prediction (Linear Regression)

![enter image description here](https://raw.githubusercontent.com/NikitaSharmaa/Python_EDA_and_Machine-Learning_Projects/main/Car_Sale_Prediction_LinReg/car_sale.png)

The aim of this project is to **predict sale of cars** using various car parameters like price, engine_size, fuel_efficiency, vehicle_type  etc. We will see how the **Python Scikit-Learn library for machine learning can be used to implement regression functions.**

There are 156 observations and 16 different variables (viz.  'Sales_in_thousands', '_year_resale_value', 'Vehicle_type',  'Price_in_thousands', 'Engine_size', 'Horsepower', 'Wheelbase', 'Width', 'Length', 'Curb_weight', 'Fuel_capacity', 'Fuel_efficiency',  'Power_perf_factor'). 

**We have to create a Linear Regression model using the provided predictor variables for the prediction of sales of cars.**

To refer the jupyter notebook please click [here](https://github.com/NikitaSharmaa/Python_EDA_and_Machine-Learning_Projects/blob/main/Car_Sale_Prediction_LinReg/Car_Sales_Prediction.ipynb)


 
 ## Introduction to Linear Regression

**Linear regression** is a _basic_ and _commonly_ used type of **predictive analysis**. The overall idea of regression is to examine two things:

-   Does a set of **predictor variables** do a good job in predicting an **outcome** (dependent) variable?
-   Which variables in particular are **significant predictors** of the outcome variable, and in what way they do **impact** the outcome variable?

These regression estimates are used to explain the **relationship between one dependent variable and one or more independent variables**. The simplest form of the regression equation with one dependent and one independent variable is defined by the formula :  
𝑦=𝛽0+𝛽1𝑥y=β0+β1x

[![enter image description here](https://camo.githubusercontent.com/a0208475fc61b912e7a56a23404dc059e812ebe824c86f0b056391ba5c122982/68747470733a2f2f656e637279707465642d74626e302e677374617469632e636f6d2f696d616765733f713d74626e3a414e64394763516a555931354554784c6a53756c5737424c707a574373744e4e7a42666341745166546726757371703d434155)](https://camo.githubusercontent.com/a0208475fc61b912e7a56a23404dc059e812ebe824c86f0b056391ba5c122982/68747470733a2f2f656e637279707465642d74626e302e677374617469632e636f6d2f696d616765733f713d74626e3a414e64394763516a555931354554784c6a53756c5737424c707a574373744e4e7a42666341745166546726757371703d434155)

What does each term represent?

-   𝑦y is the response
-   𝑥x is the feature
-   𝛽0β0 is the intercept
-   𝛽1β1 is the coefficient for x

#### Assumptions of Linear Regression[](http://localhost:8889/notebooks/Documents/DataScience/INSAID/Term%203%264/ML/LinearReg/LinearRegression_TVsales.ipynb#4.1.1-Assumptions-of-Linear-Regression)

1.  There should be a linear and additive relationship between dependent (response) variable and independent (predictor) variable(s). A linear relationship suggests that a change in response Y due to one unit change in X¹ is constant, regardless of the value of X¹. An additive relationship suggests that the effect of X¹ on Y is independent of other variables.
2.  There should be no correlation between the residual (error) terms. Absence of this phenomenon is known as Autocorrelation.
3.  The independent variables should not be correlated. Absence of this phenomenon is known as multicollinearity.
4.  The error terms must have constant variance. This phenomenon is known as homoskedasticity. The presence of non-constant variance is referred to heteroskedasticity.
5.  The error terms must be normally distributed.
