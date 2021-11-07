# House_Price_prediction
Aim

To predict the sale prices of the houses and improve the log error i.e. the error due to the difference between the actual and the predicted home values.
 

Tech stack

Language - Python
Libraries - Scikit-learn, pandas, numpy, matplotlib, seaborn, scipy, xgboost, joblib
 

 

Approach

Importing the required libraries and reading the dataset.
Merging of the two datasets
Understanding the dataset
Exploratory Data Analysis (EDA) –
Data Visualization
Feature Engineering
Duplicate value removal
Missing value imputation
Rescaling of incorrectly scaled data
Standardization
Encoding of categorical variables
Generation of new feature wherever required.
Dropping of redundant feature columns
Checking for multi-collinearity and removal of highly correlated features
Check for the outliners and removal of outliers.
 

Model Building
Performing train test split
Feature Scaling
Dropping features if necessary
Linear Regression Model
Elastic Net
Ridge Regression
Lasso Regressor
XGBoost Regressor
Adaboost Regressor
Gradient Boosting Regressor
Decision Tree Regressor
Random Forest Regressor
Model Validation
Mean Absolute Error
Hypermeter Tuning (GridSearchCV)
For Random Forest Regressor
Checking for Feature Importance
Creating the final model and making predictions
