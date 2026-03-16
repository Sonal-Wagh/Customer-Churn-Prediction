# Customer Churn Prediction

## Project Highlights
- Built a machine learning model to predict telecom customer churn.
- Performed Exploratory Data Analysis (EDA) to understand customer behavior.
- Identified key factors influencing churn such as tenure, contract type, and internet services.
- Implemented KNN and Random Forest models for churn prediction.
- Evaluated models using accuracy score and confusion matrix.

---

# Problem Statement

Customer churn is one of the major challenges faced by telecom companies. Acquiring new customers is significantly more expensive than retaining existing ones. Therefore, predicting which customers are likely to churn allows companies to take preventive measures such as improving customer service, offering personalized discounts, or providing loyalty programs.

The goal of this project is to analyze telecom customer data and build machine learning models that can accurately predict customer churn.

---

# Dataset

The dataset used in this project is the **Telco Customer Churn dataset**.

### Dataset Features

The dataset contains information about:

- Customer demographics (Gender, Senior Citizen, Partner, Dependents)
- Account information (Tenure, Contract Type, Payment Method)
- Services subscribed (Internet Service, Phone Service, Streaming Services)
- Billing information (Monthly Charges, Total Charges)
- Target variable: **Churn**

Each row represents a customer and whether they have churned or remained with the company.

---

# Project Workflow

## 1 Data Exploration
- Loaded the dataset
- Checked data types and structure
- Identified missing values
- Generated summary statistics

## 2 Data Preprocessing
- Handled missing values
- Converted categorical variables into numerical features
- Performed feature engineering
- Split dataset into training and testing sets

## 3 Exploratory Data Analysis
Visualizations used in this project include:

- Churn distribution
- Gender vs Churn
- Internet service vs Churn
- Payment method distribution
- Tenure vs Churn
- Correlation heatmaps

These visualizations help understand the patterns and relationships in the dataset.

---

## 4 Machine Learning Models

The following models were implemented:

### K-Nearest Neighbors (KNN)
A distance-based classification algorithm that predicts the class of a data point based on its nearest neighbors.

### Random Forest Classifier
An ensemble learning method that builds multiple decision trees and combines their predictions to improve accuracy and reduce overfitting.

---

# Model Evaluation

The models were evaluated using:

- Accuracy Score
- Confusion Matrix

The confusion matrix helps analyze how well the model correctly predicts churn and non-churn customers.

---

# Key Insights

Important findings from the analysis include:

- Customers with **month-to-month contracts** show higher churn rates.
- Customers with **short tenure** are more likely to churn.
- Customers with **higher monthly charges** tend to churn more frequently.
- Certain internet service types influence churn probability.

These insights can help companies improve customer retention strategies.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Project Structure
