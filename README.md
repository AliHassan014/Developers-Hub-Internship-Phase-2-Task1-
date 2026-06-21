# Developers-Hub-Internship-Phase-2-Task1-Bank Term Deposit Prediction (Machine Learning Project)
📌 Overview

This project focuses on predicting whether a bank customer will subscribe to a term deposit based on data collected during a marketing campaign. The goal is to help banks identify potential customers more effectively and improve the success rate of their marketing efforts using machine learning.

🎯 Problem Statement

Banks often run large marketing campaigns, but not all customers end up subscribing to term deposits. This leads to wasted time and resources. The objective of this project is to build a predictive model that can classify whether a customer will subscribe or not, allowing better targeting and more efficient decision-making.

📂 Dataset

The dataset used is the Bank Marketing Dataset from the UCI Machine Learning Repository. It contains customer information such as age, job, marital status, education, account balance, and previous marketing outcomes.

⚙️ Workflow
1. Data Loading & Exploration
Loaded the dataset using Pandas
Checked shape, columns, missing values, and data types
Explored both numerical and categorical features
2. Data Preprocessing
Converted all categorical features into numerical form using Label Encoding
Ensured the dataset was ready for machine learning models
3. Model Training

Two classification models were trained:

Logistic Regression
Random Forest Classifier

The dataset was split into training and testing sets to evaluate performance fairly.

Model Evaluation

The models were evaluated using:

Confusion Matrix
F1-Score
ROC Curve

These metrics helped measure how well the models distinguish between customers who subscribe and those who do not.

 Model Explainability

To make the model more transparent, SHAP (SHapley Additive Explanations) was used. It helped explain at least 5 individual predictions by showing which features influenced each decision. This made the model easier to interpret and trust.

 Results
Both Logistic Regression and Random Forest performed well on the dataset
Random Forest generally provided better accuracy and stability
SHAP analysis showed that features like balance, duration, and previous campaign outcome had strong influence on predictions
 Conclusion

This project demonstrates how machine learning can be used to support bank marketing strategies by predicting customer behavior. It also shows the importance of model interpretability using SHAP, making predictions more understandable and transparent.
