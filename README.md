# Customer-Churns-Predictive-Model

This study seeks to forecast whether customers will continue subscribing to the telephonic products offered by a company named Telco, or opt to unsubscribe from Telco's products.

The Analysis to build an adequate customers retention program.

## Random Forest Model for Customer Churn Prediction
This repository contains code for building a Random Forest model to predict customer churn. Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company Called Telco. Predicting churn can help businesses identify at-risk customers and take proactive measures to retain them.

### Before Hyperparameters Tuning
The initial version of the Random Forest model was built using default hyperparameters. The code reads the dataset from a CSV file, preprocesses the data, and trains a Random Forest classifier. The model is evaluated based on accuracy and classification report.

#### Requirements:
Python 3.x
pandas
scikit-learn

### After Hyperparameters Tuning
After identifying the need for improving model performance, hyperparameters tuning was performed using Grid Search. The code now includes a grid search for n_estimators, max_depth, and min_samples_split hyperparameters. The best hyperparameters are determined, and the model is retrained with the optimized settings. Performance evaluation is conducted with the tuned model.

#### Requirements
Python 3.x
pandas
scikit-learn

## Linear Regression Model for Customer Churn Prediction

This repository contains code for building a Linear Regression model to predict customer churn. Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company called Telco. Predicting churn can help businesses identify at-risk customers and take proactive measures to retain them.

### Before Hyperparameters Tuning
The initial version of the Linear Regression model was built using default settings. The code reads the dataset from a CSV file, preprocesses the data, and trains a Linear Regression model. The model is evaluated based on accuracy and classification report.

#### Requirements
Python 3.x
pandas
scikit-learn
