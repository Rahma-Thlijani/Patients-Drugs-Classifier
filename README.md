![Image](drugs1.jpg)
# Patients Drugs Classification
## Data Description

The datasets has 205 rows and 27 columns containing the cars' characteristics such as 'symboling', 'normalized-losses', 'maker', 'fuel-type', 'aspiration',
'num-of-doors', 'body-style', etc.

We have Drugs dataset. This dataset have each patient a data point (227 patients in total), and for each, we have 4 columns, each column represents a different aspect or measure of the specific country.

## Project Overview
In this project, will apply supervised learning techniques, we will build a Patients Drugs Classifier.
The goal of the project is to understand the dataset, to get some insights from it, and finally to choose the best model that can predict the type of drug for a taget patient.
To accomplish this, we will:
* Understand, manipulate, process and explore the data.
* Try three different models:
 1. k nearest neighbors (KNN)
 2. Decision Tree
 3. Random Forest
* Get the optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.
* Choose the best performer model. 
* Detect the features importance for each model.

## Project Steps
All the project steps are organized and listed below:
### 1. Data Import
### 2. Data Understanding and Manipulation
* Show data header
* Show columns names
* Data information
* Check to number of rows and columns
### 3. Data Processing
* Dealing with missing data
* Drop the duplicate rows
### 4. Data Exploration
* Data Description
* Target Variable (Drugs) and Insights
* Features and Insights
* Analyzing and Dealing with Outliers
### 5. Model Development
* Data Preparation
* Model1: KNN
* Model2: Decision Tree
* Model3: Random Forest
### 6. Model Optimization
* Model1: KNN
* Model2: Decision Tree
* Model3: Random Forest
### 7. Model Evaluation
* Model1: KNN
* Model2: Decision Tree
* Model3: Random Forest
### 8. Feature Importance
* Model1: Decision Tree 

![Image](importance1.png)

* Model3: Random Forest 

![Image](importance3.png)
## Conclusion
Three different learning classifierss (KNN, Decision Tree and Random Forest) were tested and  evaluated using...... we have achieved the best prediction performance using Random Forest, followed by Gradient Boosting, then Linear Regression.

Using all features in the dataset, dt is the best classifiers, the results are presented using the following metrics:

Mean Absolute Error (MAE): 2142.13
Root mean squared error (RMSE): 3097.19
R-squared Score (R2_Score): 0.8839

