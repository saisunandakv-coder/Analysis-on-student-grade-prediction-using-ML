# Analysis-on-student-grade-prediction-using-ML

Project Overview

This project applies machine learning regression models to predict students’ final grades in the Portuguese language, using demographic, family, and academic factors. The dataset was taken from Portuguese secondary school students, containing 649 instances and 33 features.

The study compares multiple regression techniques to identify the most accurate model for grade prediction.

Contents of the Presentation

Introduction – Background of dataset and problem statement.

Objective – Goal of predicting student performance.

Data Validation – Data cleaning, handling categorical features, ensuring no missing values.

Exploratory Data Analysis (EDA) – Boxplots, scatterplots, and histograms to understand trends, outliers, and distributions.

Feature Engineering – Conversion of categorical data, VIF analysis, and dimensionality reduction.

Model Evaluation – Comparison of multiple ML algorithms.

Conclusion – Best-performing model identified.

Future Insights – Recommendations for improving dataset and model performance.

Appendix – Supporting material (libraries, preprocessing steps, ML models used).

🛠️ Methods & Models Applied

Regression Models:

Linear Regression

Lasso & Ridge Regression

Support Vector Regression (SVR)

Decision Tree Regression

K-Nearest Neighbors (KNN)

Random Forest

Bagging, Boosting (AdaBoost, Gradient Boosting, XGBoost)

Artificial Neural Network (ANN)

Evaluation Metric: Mean Absolute Error (MAE)

Train/Test Split: 80:20

 Key Findings

The best-performing model was Support Vector Regression (SVR) with:

MAE: 0.667

Train/Test Split: 80:20

Final grades clustered between 11–14.

Study time, absences, and social outings significantly impacted grades.
