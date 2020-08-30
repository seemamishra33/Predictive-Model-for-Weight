# Simple/Multiple Linear Regression Implementation 

## Project overview
This project is about modelling the linear relationshp between Height and Weight of Men and Women.

### Linear Regression
Linear regression is an approach to model the relationship between a single dependent variable (target variable) and one (simple regression) or more (multiple regression) independent variables. The linear regression model assumes a linear relationship between the input and output variables. If this relationship is present, we can estimate the coefficients required by the model to make predictions on new data. This technique is applicable for Supervised learning Regression problems where we try to predict a continuous variable.

Linear Regression can be further classified into two types – Simple and Multiple Linear Regression. In this project, We will employ Simple LR and multiple LR technique.

Simple Linear Regression (SLR)
Simple Linear Regression (or SLR) is the simplest model in machine learning. It models the linear relationship between the independent and dependent variables.

In this project, there is one independent or input variable which represents the Height data and is denoted by X. Similarly, there is one dependent or output variable which represents the Weight data and is denoted by y. We want to build a linear relationship between these variables. This linear relationship can be modelled by mathematical equation of the form:-

             Y = β0   + β1*X    -------------   (1)
In this equation, X and Y are called independent and dependent variables respectively,

β1 is the coefficient for independent variable and

β0 is the constant term.

β0 and β1 are called parameters of the model.

We can see that

slope of the line is given by β1, and

intercept of the line by β0.

M### Multiple Linear Regression (MLR)
Multiple linear regression uses a linear function to predict the value of a target variable y, containing the function n independent variable x=[x₁,x₂,x₃,…,xₙ].

                 Y = β0   + β1*X1+ β2*X2+ ...βn*Xn   -------------   (2)
Ordinary Least Square Method
Now, our task is to find a line which best fits this data. This line will help us to predict the value of any Target variable for any given Feature variable. This line is called Regression line.

We can define an error function for any line. Then, the regression line is the one which minimizes the error function. Such an error function is also called a Cost function.

Cost Function
The obective of method is to get the regression to be as close to actual data points as possible. It can be achieved by minimizing the vertical distance between the actual data point and fitted line. The vertical distance between each data point and the line is called the residual.

So, in oher words, we try to minimize the residuals by finding the line of best fit.

We can try to minimize the sum of square of the residuals to avoid to cancel the positive residual and negative residuals.

Mathematically, we denote actual data points by yi and predicted data points by ŷi. So, the residual for a data point i would be given as

            di = yi -  ŷi
Sum of the squares of the residuals is given as:

            D = Ʃ di**2       for all data points
This is the Cost function. It denotes the total error present in the model which is the sum of the total errors of each individual data point.

We can estimate the parameters of the model β0 and β1 by minimize the error in the model by minimizing cost function.

This method of finding the parameters of the model and thus regression line is called Ordinary Least Square Method.

### Performance Mettrics to Evaluate Model
Two performance metrics

RMSE (Root Mean Square Value)
R2 Score

### Software information
Python libraries
Anaconda Python distribution. It comes with most of the standard Python libraries The basic Python libraries used:-

• Numpy – It provides a fast numerical array structure and operating functions.

• pandas – It provides tools for data storage, manipulation and analysis tasks.

• Scikit-Learn – The required machine learning library in Python.

• Matplotlib – It is the basic plotting library in Python. It provides tools for making plots.

• Seaborn - for plotting


## About the dataset

The data set has been imported from the Kaggle website with the following url:-

https://www.kaggle.com/mustafaali96/weight-height?select=weight-height.csv

The dataset contains the height and weight of 500 males and 500 females.


## Regression metrics for model performance


For regression problems, I have used two metrics to compute the model performance. They are RMSE (Root Mean Square Error) and R-Squared Value.

### RMSE
