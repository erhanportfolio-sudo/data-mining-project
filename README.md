🏦 Bank Customer Churn Prediction

This repository contains a comprehensive end-to-end data science project focused on predicting customer churn for a banking institution. The goal is to identify high-risk customers and understand the underlying factors that lead to churn using various Machine Learning techniques.

📊 Project Overview

Customer churn occurs when customers stop doing business with a company. For banks, retaining existing customers is often more cost-effective than acquiring new ones. This project analyzes customer behavior and builds predictive models to anticipate potential churn.
Key Features of the Project:

    Exploratory Data Analysis (EDA): Deep dive into demographics (Age, Geography, Gender) and financial behavior (Balance, Number of Products, Credit Score).
    
    Data Preprocessing: Handling outliers, feature encoding (OneHot & Label Encoding), and feature scaling.
    
    Addressing Class Imbalance: Applied SMOTE (Synthetic Minority Over-sampling Technique) to handle the skewed distribution of churned vs. non-churned customers.
    
    Model Benchmarking: Comparison of multiple algorithms including Gradient Boosting, Tree-based models, and Linear models.

🛠️ Tech Stack

    Language: Python
    Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn
    Algorithms: XGBoost, CatBoost, LightGBM, Random Forest, AdaBoost, SVC, Logistic Regression

📈 Model Performance

The models were evaluated based on Accuracy, Precision, and Recall. Below are the results from the top-performing classifiers:

Model,Accuracy,Precision,Recall

LGBM Classifier  86.65%  0.7316  0.5012

CatBoost Classifier  86.65%  0.7461  0.4860

AdaBoost Classifier  85.95%  0.7029  0.4936

XGBoost Classifier 85.75%  0.6742  0.5318

Key Insight: While CatBoost and LightGBM provide the highest overall accuracy, XGBoost offers a better balance for Recall, making it more effective at identifying actual churners.

🔍 Visual Insights

    Age: Customers between the ages of 40-60 show a significantly higher churn rate.
    
    Product Usage: Customers with 3 or 4 products have an extremely high probability of churning.
    
    Geography: Germany has a higher churn rate compared to France and Spain, suggesting region-specific retention issues.
    
👨‍💻 Author

    Erhan Er 
    erhan.er7@std.yeditepe.edu.tr
