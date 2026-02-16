💳 Credit Risk Prediction
 Project Overview

This project focuses on predicting whether a loan applicant is likely to default on a loan using supervised machine learning classification techniques. Credit risk prediction is essential for financial institutions to minimize losses and make informed lending decisions. By analyzing applicant data, this model helps distinguish between high-risk and low-risk customers.

Objective

To build a machine learning classification model that predicts loan default risk and evaluates its performance using accuracy and confusion matrix.

📂 Dataset

Loan Prediction Dataset (Kaggle)
The dataset includes the following features:
Applicant Information: Gender, Education, Marital Status
Financial Attributes: Applicant Income, Coapplicant Income, Loan Amount
Loan Details: Loan Term, Credit History

Target Variable:
Loan_Status = 1 → Loan Approved (Low Risk)
Loan_Status = 0 → Loan Rejected / High Risk

⚙️ Methodology
1. Data Cleaning & Missing Value Handling

Identified missing values in the dataset
Handled missing data using appropriate techniques (mean, median, mode)
Ensured data consistency for modeling

2. Exploratory Data Analysis (EDA)

Visualized key features such as:

Loan Amount

Education

Applicant Income 
Analyzed relationships between features and loan status
Used plots to understand data distribution and trends

3. Categorical Data Encoding

Converted categorical variables into numerical format using:
Label Encoding
One-Hot Encoding

4. Model Training

Split the dataset into training and testing sets
Trained classification models such as:
Logistic Regression
Decision Tree Classifier

5. Model Evaluation

Evaluated model performance using:

Accuracy Score
Confusion Matrix
Analyzed true positives, false positives, true negatives, and false negatives

🧠 Skills & Techniques Used

Data Cleaning and Handling Missing Values
Exploratory Data Analysis (EDA)
Binary Classification using Machine Learning
Feature Encoding
Model Evaluation using Accuracy and Confusion Matrix

Results

The trained model successfully predicts whether a loan applicant is likely to default. Evaluation metrics indicate reliable performance and provide insights into decision boundaries between high-risk and low-risk applicants.

🛠 Tools & Libraries

Python
Pandas
NumPy
Matplotlib / Seaborn
Scikit-learn

📁 Project Structure
Credit-Risk-Prediction/
├── loan_dataset.csv
├── credit_risk_prediction.ipynb
├── README.md

🚀 Future Improvements

Implement advanced models (Random Forest, XGBoost)
Perform hyperparameter tuning
Add more feature engineering

Deploy model as a web app
