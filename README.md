
📊 Wholesale Customer Type Prediction Using Supervised Machine Learning
---
📌 Project Overview

This project applies Supervised Machine Learning techniques to classify wholesale customers based on their purchasing behaviour.

The dataset contains annual spending information across multiple product categories such as Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicassen.

🎯 Goal:

Build a machine learning model that predicts whether a customer belongs to:

🛒 Retail

🍽 HORECA (Hotels, Restaurants, Cafes)

By identifying purchasing patterns, businesses can improve customer segmentation, marketing strategies, and operational decision-making. 

---

🏢 Business Context

Wholesale distributors supply products to different businesses such as retail stores and hospitality services.

Different customer types show distinct purchasing behaviour:

🛒 Retail customers

Higher spending on Grocery, Milk, and Detergents

🍽 HORECA customers

Higher spending on Fresh and Frozen products

Understanding these patterns helps businesses improve:

✔ Customer segmentation

✔ Inventory management

✔ Marketing strategies

✔ Operational efficiency 

---
❗ Problem Statement

The wholesale distributor wants to automatically predict customer type (Retail or HORECA) using historical purchasing data.

Currently, the organization has large volumes of transaction data but lacks an automated classification system.

This project builds a supervised machine learning model that predicts customer type based on annual spending across different product categories. 

---
🎯 Project Objectives

✔ Analyze customer purchasing behaviour

✔ Perform data preprocessing and cleaning

✔ Conduct Exploratory Data Analysis (EDA)

✔ Train multiple machine learning models

✔ Evaluate model performance using classification metrics

✔ Identify important features influencing predictions

✔ Provide business insights and recommendations 

---
📂 Dataset Description

Dataset: Wholesale Customers Dataset

Each row represents a customer and each column represents spending on product categories.

📑 Feature Description

Channel: Customer type (1 = HORECA, 2 = Retail)

Region: Geographic region

Fresh: Annual spending on fresh products

Milk:	Annual spending on milk products

Grocery: Annual spending on grocery products

Frozen: Annual spending on frozen products

Detergents_Paper: Spending on detergents and paper

Delicassen: Spending on delicatessen products

🎯 Target Variable: Channel

🔗 Dataset Link

https://drive.google.com/file/d/1UiVEK9ZvGT1BYzlyal_P8GDwDZITFcpl/view?usp=drivesdk 

---
🧹 Data Preprocessing

Before training models, the dataset was cleaned and prepared.

Steps performed:

✔ Missing value check

✔ Duplicate record removal

✔ Encoding categorical variables

✔ Feature scaling using StandardScaler

Feature scaling ensures consistent input for machine learning algorithms and improves model performance. 

---
📊 Exploratory Data Analysis (EDA)

EDA was performed to understand patterns in customer spending behaviour.

Key analysis included:

📈 Distribution of spending across product categories

📊 Comparison between Retail and HORECA customers

🔗 Feature correlations

📉 Data visualization using charts and plots 

---
🤖 Machine Learning Models Used

The following supervised learning algorithms were implemented:

🔹 Logistic Regression

🌳 Decision Tree

🌲 Random Forest

⚡ XGBoost

📉 Support Vector Machine (SVM)

These models were selected because they perform well for classification problems with structured numerical datasets. 

---
⚙ Model Training and Validation

📊 Train-Test Split

70% Training Data

30% Testing Data

📏 Evaluation Metrics

✔ Accuracy

✔ Precision

✔ Recall

✔ F1 Score

✔ Confusion Matrix


✔ Classification Report 

---
📈 Model Performance

Model	Accuracy

Logistic Regression	- 0.91

Decision Tree -	0.83

Decision Tree (Tuned) -	0.87

Random Forest -	0.90

XGBoost -	0.91

SVM	- 0.90

🏆 Best Models: Logistic Regression & XGBoost (91% Accuracy)

---
🔍 Key Insights

📌 Retail customers spend more on Grocery, Milk, and Detergents_Paper

📌 HORECA customers spend more on Fresh and Frozen products

📌 Detergents_Paper is one of the most influential features for classification

📌 Purchasing behaviour clearly differentiates customer segments

---
💡 Business Recommendations

👥 Customer Segmentation

Use machine learning predictions to categorize customers into Retail and HORECA groups.

🎯 Targeted Marketing

Develop different marketing strategies for each customer segment.

Example:

Promote grocery products to retail customers

Promote fresh and frozen products to hospitality businesses

📦 Inventory Optimization

Maintain optimal stock levels based on purchasing patterns.

💰 Pricing Strategies

Apply different pricing strategies for different customer segments. 

---
🛠 Tools and Technologies

💻 Programming Language

Python

📚 Libraries

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

☁ Development Environment

Google Colab 

---
📁 Project Structure

Wholesale-Customer-Type-Prediction
├── dataset
│   └── wholesale_customers_data.csv
│
├── notebook
│   └── supervised_learning_project.ipynb
│
└── README.md

---
▶ How to Run the Project

1️⃣ Clone the repository

git clone https://github.com/yourusername/repository-name.git

2️⃣ Install required libraries

pip install pandas numpy matplotlib seaborn scikit-learn xgboost

3️⃣ Open the notebook using Google Colab 

---
📌 Conclusion

This project demonstrates how supervised machine learning can classify wholesale customers as Retail or HORECA based on purchasing behaviour. Multiple models were evaluated, and Logistic Regression and XGBoost achieved the highest accuracy of 91%. The results show that machine learning can effectively support customer segmentation and data-driven business decisions.

---
