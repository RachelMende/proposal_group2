# 3360 Project Proposal – Group 2
Names: Roshan Ravichandran, Michael Hooper, Rachel Mende, Bilal Nadeem, Sai Gudapati
## Dataset:
For this project, we will be using a Kaggle data set of the sales of used cars across the United States on Craigslist, which was last updated in 2020. Using this dataset, we will look at car features such as manufacturer, condition, year, mileage, cylinders, transmission, and title status from the listed cars and create a regression model that will predict the price of these input features. Our data set is fairly extensive which allows us flexibility on which we can create subsets on various factors. Through our project we aim to understand the used car market and the factors that influence price. We aim to find and develop a model that can predict the price of a car.
https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data
## Data Visualization:
Before we create our regression models, we plan to explore the data through statistical analysis, which should give us a good feel of what our ranges and correlations are. For summary statistics we plan to use the standard deviation, covariance, interquartile range, variance, and correlation of the various features in the data set. Using these factors as well as visualization, we will be able to identify features that will not help us to predict price. Our findings will help us ensure the quality of the data and help design an effective predictive modeling system. By looking at the standard deviation within the data set we can see the spread of the data and by comparing the standard deviation between features, we will be able to find the most accurate features to use for our predictive modeling. Using the interquartile range, we will be able to eliminate outliers. The variance will help show us which features have a significant effect, the spread of data points, and how consistent the data is. The covariance will help us identify relationships between features and the strength of those relationships. Finding the correlation will help us assess features, assess relationships between variables, and help us understand what would be a good predictor.

**The calculations of these statistics can be well visualized through the use of a few tools, including:**
 
Boxplots

Scatterplots

Histograms

Line Plots

Heat Plots

Boxplots are able to visualize distribution of data, view skewness and spread. Heat plots will visualize the strength of the correlations and covariance of each observed feature.  Scatterplots will allow us to see the correlations between variables, identify outliers, and view patterns. Histograms will allow us to view symmetry, frequency, and identify anomalies. Finally, line plots allow us to get a feel for the correlation coefficient between one of our inputs and our output.

## Planned Models:

**We plan to use the following models to determine how each performs in data evaluation:**

Lasso Linear Regression

Ridge Linear Regression

Regression Tree

Polynomial Regression

Multiple Linear Regression

## Evaluation Metrics: 
**In order to determine how successful each model was in its job of predicting used car prices based on our inputs, we’ll use the following metrics:**

R-squared

Mean Absolute Error

Root Mean Squared Error

Correlation Coefficient 

Relative Absolute Error

R-squared will be able to tell us the fit of a model and will help communicate the accuracy of a model. Mean absolute square is able to tell us the magnitude of errors present and the absolute difference is easy to interpret. Root mean squared error is useful in optimization, gives large errors larger significance, and how good the fit is. The correlation coefficient will tell us the correlation between the model’s output price and the actual price as another method of computing accuracy. Relative absolute error provides us with a value depicting how well our model performed. 

## Workload:
 The workload for this project will be split among us in the following way:
 
**Each group member will focus on the creation and application of a regression model, it’ll look as follows:**

Roshan - Ridge Linear Regression

Bilal - Lasso Linear Regression

Sai - Regression Tree

Rachel - Polynomial Regression

Michael - Multiple Linear Regression

Once we have the performance of our models, we will analyze our findings as a group and draw our conclusions. 



