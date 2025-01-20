##Medical Insurance Cost Prediction

Overview
This project leverages machine learning to predict medical insurance costs based on various features such as age, sex, BMI, smoking habits, region, and more. The goal is to develop a model that can accurately estimate medical insurance costs, which could be beneficial for healthcare providers, insurance companies, and individuals seeking cost predictions.

Problem Statement
Medical insurance cost prediction is essential for healthcare providers to offer tailored plans. By predicting medical costs based on personal attributes and historical data, we can make better, data-driven decisions to optimize insurance pricing and improve customer satisfaction.

Tools and Technologies
Programming Language: Python
Libraries Used:
pandas - Data manipulation
numpy - Numerical operations
matplotlib & seaborn - Data visualization
scikit-learn - Machine learning models and evaluation
Model Used:
Linear Regression (as the primary model for cost prediction)
Other models (like Decision Trees, Random Forest) for comparison
Dataset
The dataset used in this project is the Medical Insurance Cost Dataset, which contains the following columns:

age: Age of the primary beneficiary
sex: Gender (male/female)
bmi: Body Mass Index (BMI)
children: Number of children/dependents covered by the insurance
smoker: Whether the person smokes (yes/no)
region: Residential area (northeast, northwest, southeast, southwest)
charges: Medical insurance costs (target variable)
You can download the dataset from here.

Steps Followed
Data Exploration:

Explored the dataset to understand its structure and identify missing values or outliers.
Visualized data to observe relationships between variables and the target variable.
Data Preprocessing:

Handled missing values using mean imputation or other appropriate techniques.
Encoded categorical variables like sex, smoker, and region using One-Hot Encoding.
Feature Engineering:

Selected the most relevant features for prediction.
Applied scaling for features like BMI and age to ensure they are in the same range.
Modeling:

Split the dataset into training and test sets.
Trained multiple models, including linear regression, decision trees, and random forest.
Evaluated models using R², Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
Model Evaluation:

Linear Regression: Achieved 85% accuracy in predicting insurance costs.
Decision Tree and Random Forest: Compared the models and selected the best performing one.
Results
The Linear Regression model was the most accurate, achieving an 85% R² score.
Some of the key features that influenced the insurance cost the most were age, BMI, and smoker.
