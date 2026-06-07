# synent-task8--Machine-Learning-Model-Kanksha


Student Performance Prediction using Machine Learning
Project Overview

This project focuses on predicting student exam scores using Machine Learning techniques. The dataset contains academic and behavioral factors such as study hours, attendance, sleep quality, study methods, and other student-related attributes.

The goal is to build predictive models that estimate student performance and identify the factors that have the greatest impact on exam scores.

Objective
Perform data preprocessing and feature engineering.
Analyze student performance data.
Build and train Machine Learning models.
Evaluate model performance using regression metrics.
Identify important factors influencing student scores.
Dataset Features
Input Features
Age
Gender
Course
Study Hours
Class Attendance
Internet Access
Sleep Hours
Sleep Quality
Study Method
Facility Rating
Exam Difficulty
Target Variable
Exam Score
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Project Workflow
1. Data Exploration
Loaded and inspected the dataset.
Checked dataset structure using:
head()
info()
describe()
isnull()
duplicated()
2. Data Preprocessing
Handled categorical variables using Label Encoding.
Removed unnecessary columns.
Prepared data for Machine Learning models.
3. Feature Selection
Selected relevant input features.
Defined target variable (exam_score).
4. Train-Test Split
Split data into:
80% Training Data
20% Testing Data
5. Model Training

Implemented the following regression models:

Linear Regression

Used as a baseline model to establish prediction performance.

Random Forest Regressor

Used to capture complex relationships and improve prediction accuracy.

6. Model Evaluation

Evaluated both models using:

RMSE (Root Mean Squared Error)

Measures prediction error. Lower values indicate better performance.

R² Score

Measures how well the model explains variations in exam scores. Higher values indicate better performance.

7. Visualization

Created:

Actual vs Predicted Score Plot
Feature Importance Plot

These visualizations help understand model performance and important influencing factors.

Results
Successfully predicted student exam scores using Machine Learning.
Random Forest Regressor achieved better performance compared to Linear Regression.
Study-related features and attendance showed significant influence on student performance.
Key Learnings
Data preprocessing and encoding techniques.
Regression model development.
Model evaluation using RMSE and R² Score.
Feature importance analysis.
End-to-end Machine Learning workflow.



Video Link: https://drive.google.com/file/d/1cf0c8xph3-YcCJ18AePziYW0AufeNG6Z/view?usp=sharing

Conclusion
This project demonstrates a complete Machine Learning pipeline for student performance prediction. By comparing Linear Regression and Random Forest models, meaningful insights were generated regarding the factors that affect academic performance and the effectiveness of different regression techniques.
