# Customer-Churn-PredictionCustomer Churn Prediction
Project Highlights

Built a machine learning model to predict telecom customer churn.

Performed Exploratory Data Analysis (EDA) to understand customer behavior.

Identified key factors influencing churn such as tenure, contract type, and internet services.

Implemented KNN and Random Forest models for churn prediction.

Evaluated models using accuracy, confusion matrix, and classification analysis.

This project helps companies identify customers likely to churn and take proactive retention actions.

Problem Statement

Customer churn is one of the major challenges for telecom companies. Acquiring new customers is significantly more expensive than retaining existing ones. Therefore, predicting which customers are likely to churn allows companies to take preventive measures such as personalized offers, improved customer service, or loyalty programs.

The goal of this project is to analyze telecom customer data and build machine learning models that can accurately predict customer churn.

Dataset

The project uses the Telco Customer Churn dataset, which contains information about customers of a telecom company.

Dataset Features

The dataset includes information such as:

Customer demographics (gender, senior citizen, partner, dependents)

Account information (tenure, contract type, payment method)

Services subscribed (internet service, phone service, streaming services)

Billing information (monthly charges, total charges)

Target variable: Churn

Each row represents a customer and whether they left the service or remained.

Project Workflow
1 Data Exploration

Checked dataset structure

Identified missing values

Analyzed data types

Generated descriptive statistics

2 Data Preprocessing

Handled missing values

Converted categorical variables into numerical features

Feature engineering

Train-test split

3 Exploratory Data Analysis

Several visualizations were used to understand customer churn patterns:

Churn distribution

Gender vs Churn

Internet service vs Churn

Payment method distribution

Tenure vs Churn

Correlation heatmaps

These visualizations helped identify important patterns influencing churn behavior.

4 Machine Learning Models

The following models were implemented:

K-Nearest Neighbors (KNN)

Distance-based classification algorithm

Used to classify customers based on similarity

Random Forest Classifier

Ensemble learning method

Combines multiple decision trees to improve prediction accuracy

Model Evaluation

The models were evaluated using:

Accuracy Score

Confusion Matrix

Classification metrics

Example Confusion Matrix Interpretation:

Correctly predicted non-churn customers

Correctly predicted churn customers

False positives and false negatives

This helps understand how well the model distinguishes between churn and non-churn customers.

Key Insights

Some important findings from the analysis include:

Customers with month-to-month contracts have higher churn rates

Customers with short tenure are more likely to churn

Certain internet service types influence churn probability

Customers with higher monthly charges tend to churn more frequently

These insights can help companies improve retention strategies and customer satisfaction.

Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

Project Structure
Customer-Churn-Prediction
│
├── Customer_churn.ipynb
├── dataset.csv
└── README.md
