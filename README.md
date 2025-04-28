📞 Telecommunications Churn Prediction Project

Welcome to my Telecommunications Churn Prediction project!
In this project, I developed a machine learning model to predict whether a customer would churn (leave) or stay with a telecom company, using their subscription and service behavior.

📚 Project Overview

Churn prediction is crucial for telecom companies aiming to retain customers and reduce losses.
This project focuses on building a predictive model that can classify customers into "Churn" or "No Churn" based on various service and billing-related features.

🛠️ Tools and Technologies

Python
Pandas, NumPy (Data analysis and manipulation)
Matplotlib, Seaborn (Data visualization)
Scikit-learn (Modeling and evaluation)
Jupyter Notebook

📊 Dataset Features

The dataset contains customer records with information like:
CustomerID: Unique customer identifier
Gender
SeniorCitizen: Indicates if the customer is a senior citizen
Partner/Dependents: Family status
Tenure: How long the customer has been with the company
Services: Phone service, Internet service, Online security, Tech support, Streaming services
Payment Details: Contract type, Payment method, Monthly and total charges
Churn: Target variable (Yes/No)

⚙️ Workflow Summary

Data Cleaning
Dropped unnecessary columns like customerID.
Replaced "No internet service" with "No" for clarity across multiple service columns.
Encoded 'Yes'/'No' and binary features into 1/0.
Used Label Encoding for columns with multiple categories (e.g., InternetService, PaymentMethod).
Feature Engineering
Converted total charges into numeric data.
Handled missing values effectively.
Exploratory Data Analysis (EDA)
Plotted churn distribution.
Identified correlations between features and churn.
Visualized important relationships using countplots and heatmaps.

Model Building

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Gradient Boosting Classifier

Model Evaluation
Accuracy score
Classification report (Precision, Recall, F1-score)
Confusion matrix for visualization
Compared model performances

📈 Results

Achieved high accuracy while maintaining a good balance between precision and recall.
Key drivers of churn included Contract type, Tenure, and MonthlyCharges.

🔍 Key Insights

Customers with Month-to-Month contracts are far more likely to churn compared to those on annual contracts.
Higher monthly charges are linked with higher churn rates.
Lack of tech support and online security services increased the likelihood of churn.
Customers who use electronic check as payment method churn more than those using automatic payment setups.
