Behavioral and Alcohol Consumption Data-Driven Models for Academic Success Prediction

Project Overview
This project aims to predict students' academic success based on behavioral and alcohol consumption data. The goal is to explore the relationships between students' personal factors, behavioral patterns, and their academic performance. By building and comparing various regression models, such as Quantile Regression, Ridge Regression, Lasso Regression, Bayesian Ridge Regression, and Random Forest Regressor, the project assesses which model is most effective in predicting students' average grades.

The dataset includes variables such as:

Demographic information (age, gender, school type, etc.)
Family background (parents' education, jobs, etc.)
Behavioral and lifestyle factors (time spent on study, health, social activities, and alcohol consumption)
Academic performance data (grades in different periods)
Different regression models, including Quantile Regression, Ridge Regression, Lasso Regression, Bayesian Ridge, and Random Forest Regressor, are employed to predict the students' academic performance.

Project Structure
├── data
│   └── student-por.csv 
├── notebooks
│   └── code.ipynb  
└── README.md  # Project documentation


Key Features and Analysis

Data Preprocessing: The dataset is cleaned by removing any duplicates and handling missing values.
Categorical variables are encoded into numeric values using label encoding to make them suitable for machine learning models.
Exploratory Data Analysis (EDA): Visualizations are created to explore the distribution of student data, including school, gender, family relationships, study time, alcohol consumption, and academic grades. Analysis of correlations between features to identify the impact of various factors on student grades.
Modeling: Several regression techniques are implemented to predict students' average grades:
- Quantile Regression: Estimates conditional quantiles and allows for modeling of the distribution of academic scores.
- Ridge Regression: Applies regularization to prevent overfitting while predicting academic performance.
- Lasso Regression: Similar to Ridge, but applies L1 regularization to encourage sparsity.
- Bayesian Ridge Regression: Uses Bayesian methods to estimate the parameters with uncertainty.
- Random Forest Regressor: A tree-based ensemble learning method that models complex relationships in the data.

Hyperparameter tuning is performed for each model using Grid Search with cross-validation to find the best parameters for each model.
Evaluation

Model performance is evaluated using various metrics:
- Mean Absolute Error (MAE)
- Median Absolute Error (MedAE)
- R-squared (R²)

Results: After tuning and training the models, results are compared to determine the best-performing model for predicting academic success.

Acknowledgments
The dataset used in this project is originally from the UCI Machine Learning Repository.