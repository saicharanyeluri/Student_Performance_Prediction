Predicting Student Performance Using Logistic Regression

Overview:
Our project aims to predict student performance, specifically identifying whether a student will drop out or graduate, using logistic regression. By leveraging data from the 'student_performance.csv' dataset, we aim to develop a predictive model that helps educational institutions identify at-risk students early and implement interventions to improve retention rates.

Objectives:
Data Preparation: Clean and preprocess the dataset to ensure it is suitable for modeling. This includes handling missing values, encoding categorical variables, and scaling numerical features.
Model Development: Build a logistic regression model to classify students into two categories: dropout and graduate.
Evaluation: Assess the model's performance using metrics such as accuracy, precision, recall, F1-score, and the confusion matrix.
Interpretation: Analyze the model's predictions to identify key factors contributing to student dropout and graduation.

Methodology:
Data Collection: Use the 'student_performance.csv' dataset, which contains various features related to student demographics, academic performance, and other relevant factors.
Feature Engineering: Select and engineer features that significantly impact student performance. This may involve creating new features or transforming existing ones.
Model Training: Split the data into training and testing sets. Train the logistic regression model on the training set and fine-tune hyperparameters to optimize performance.
Model Evaluation: Evaluate the model on the testing set. Generate a confusion matrix and calculate evaluation metrics to understand the model's strengths and weaknesses.
Model Interpretation: Use techniques such as coefficient analysis and SHAP values to interpret the model's predictions and identify the most influential features.
