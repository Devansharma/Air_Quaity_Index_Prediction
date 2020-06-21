# Air_Quaity_Index_Prediction

This project is for predicting the air quality index. It consists the complete life-cycle of data science project from data collection to the model deployment.

## Steps:
### 1. Data Collection: 
Data collection is done using requests library in python to download to html files and then using Beautiful Soup to scrape the data(Table) from the html files.

###  2. Data Cleaning:
Data cleaning was done using pandas library by removing the null values and joing the independent variables with the dependent variables ie AQI.

### 3. Data Modelling:
For modelling the data various models were used for the prediction like:
#### a. Linear Regression
#### b. Ridge and Lasso Regression
#### c. Decision Tree Regression
#### d. Random Forest Regression
#### e. XGboost
