# MACHINE-LEARNING-PROJECT
# Car Price Prediction: Regression Analysis
# Project Overview
This project aims to develop a predictive model for car prices based on various independent variables. A Chinese automobile company aspires to enter the US market and requires insights into the factors affecting car prices. The insights will guide their business strategy and car design.

The project involves preprocessing the dataset, applying various regression algorithms, comparing their performances, identifying significant features, and optimizing model parameters to achieve the best results.

# Dataset
Source: Provided by the consulting firm.
Link: Car Price Dataset
Description: Contains various features of cars sold in the American market, including their prices.
# Project Workflow
1. Data Preprocessing
Handled missing values by dropping rows with null values.
Applied one-hot encoding to categorical variables.
Normalized numerical features using StandardScaler.
Split the dataset into training (80%) and testing (20%) sets.
2. Regression Models
The following regression models were implemented and compared:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)
3. Model Evaluation
Models were evaluated using:
R-squared (R²)
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
The best-performing model was identified based on the highest R² score.
4. Feature Importance
For tree-based models, feature importance was analyzed to identify variables significantly impacting car prices.
5. Hyperparameter Tuning
Hyperparameter tuning was performed on the best-performing model using GridSearchCV.
The tuned model's performance was compared with the original to observe improvements.
# Results
Best Model: [Random Forest Regressor]
Performance Metrics (before tuning):
R² Score: [ 0.9391398898153419]
MSE: [4804541.809155916]
MAE: [1524.2910039660053]
Performance Metrics (After Tuning):
R² Score: [Best model R² score after tuning]
MSE: [Best model MSE after tuning]
MAE: [Best model MAE after tuning]
# Dependencies
Install the following Python packages:
    pip install pandas numpy matplotlib seaborn scikit-learn
# Files in the Repository
car_price_prediction.ipynb: Jupyter Notebook containing the full code and analysis.
README.md: Documentation for the project.
Dataset: Link to download the dataset.
# Key Insights
Identified the most significant factors affecting car prices.
Compared multiple regression models to find the best-performing algorithm.
Optimized model parameters to achieve improved performance.
# Acknowledgments
This project was undertaken as part of a data analysis assessment. The dataset was provided by the consulting firm representing the Chinese automobile company.
