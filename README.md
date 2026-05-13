# House-Price-Prediction---Machine-Learning-Project
**Project Overview**
This project aims to predict residential real estate prices based on various structural and locational attributes. By utilizing a dataset of 545 houses, I implemented a Linear Regression model to understand the correlation between house features (like area, bedrooms, and bathrooms) and their market value.

The project covers the entire data science pipeline, from exploratory data analysis (EDA) and data cleaning to model training and performance evaluation.

Dataset Description
The dataset used in this project contains 545 entries with 13 initial features:

Target Variable: price

Numerical Features: area, bedrooms, bathrooms, stories, parking

Categorical Features: mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus

Key Technical Steps
1. Exploratory Data Analysis (EDA)
Analyzed the dataset structure using .info() and .describe() to understand data types and statistical distributions.

Generated a Correlation Matrix to identify the strongest predictors of price (e.g., area and bathrooms showed strong positive correlations).

2. Data Preprocessing
Feature Selection: To simplify the model and focus on structural attributes, I dropped several categorical columns including mainroad, guestroom, basement, hotwaterheating, and airconditioning.

Handling Categorical Data: The project involves preparing variables like furnishingstatus and prefarea for the regression model.

3. Model Implementation
Algorithm: Linear Regression (via sklearn.linear_model).

Process:

Split data into training and testing sets.

Trained the model on structural features to find the best-fit hyperplane.

Executed predictions on the test set to evaluate accuracy.

Technologies Used
Python

Pandas: Data manipulation and cleaning.

Matplotlib & Seaborn: Data visualization and correlation heatmaps.

Scikit-Learn: Machine learning model implementation (Linear Regression).
