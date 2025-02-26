# BoomBikes
Bike sharing assignment involving MLR

Problem Statement:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.

The company wants to know: Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands

Model Evaluation: At the end - calculate the R-squared score on the test set.

from sklearn.metrics import r2_score r2_score(y_test, y_pred)

where y_test is the test data set for the target variable, and y_pred is the variable containing the predicted values of the target variable on the test set.

'''

Load and Explore the Data ○ Read the dataset and the data dictionary. ○ Check for missing values, outliers, and data types. ○ Convert categorical numerical values (like 'season', 'weathersit') into categorical string values. ○ Analyze the 'yr' column to decide whether to keep it.
Feature Engineering ○ Drop irrelevant columns. ○ Convert categorical variables using one-hot encoding or label encoding. ○ Perform feature scaling if necessary.
Model Building ○ Split data into training and testing sets. ○ Train a linear regression model. ○ Perform feature selection to keep significant variables.
Model Evaluation ○ Analyze residuals for assumptions of linear regression. ○ Calculate R-squared and adjust the model accordingly.
'''
