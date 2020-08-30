# Simple/Multiple Linear Regression Implementation 

## Project overview
This project is about modelling the linear relationshp between Height and Weight of Men and Women.


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
The RMSE value has been found to be 12.1781. It means the standard deviation for our prediction is 12.1781. So, sometimes we expect the predictions to be off by more than 12.1781 and other times we expect less than 12.1781.


##  R2 Score

R2 Score is another metric to evaluate performance of a regression model. It is also called coefficient of determination. It gives us an idea of goodness of fit for the linear regression models. It indicates the percentage of variance that is explained by the model. 

Mathematically, 
R2 Score = Explained Variation/Total Variation

In general, the higher the R2 Score value, the better the model learned the data. Usually, its value ranges from 0 to 1. So, we want its value to be as close to 1. In this case R2 is computed as 0.8577 which pretty much close to 1.


## Training Error and Testing Error
The calculate training set score as 0.8542. Similarly, the calculate test set score as 0.8570. 
The scores are reasonably good. So, the model does learn the relationships appropriately from the training data and perform well on the testing dataset. 
