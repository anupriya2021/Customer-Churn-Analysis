# Customer-Churn-Analysis
📌**TELECOM CUSTOMER CHURN ANALYSIS:**  

This project investigates customer churn in a telecom company using detailed exploratory analysis, feature engineering, and predictive modeling. It identifies churn patterns and builds strategies for customer retention through clustering and machine learning.


🎯**PURPOSE:**   
To understand key drivers behind churn, predict at-risk customers using classification models, and provide targeted recommendations that reduce churn and enhance customer loyalty.

🛠️**TECH STACK**
- Python: for data manipulation, visualization, and modeling
- Libraries: pandas, NumPy, matplotlib, seaborn, scikit-learn, XGBoost, SciPy
- Algorithms: Random Forest, Logistic Regression, XGBoost, K-Means Clustering
- Jupyter Notebook: for interactive coding and dashboard layout

📊**Data Source**
The dataset used for this project comes from the Telco Customer Churn dataset available on Kaggle. It contains information about a telecom company's customers, including demographics, account details, and usage metrics.

Source: Kaggle – Telco Customer Churn

Structure: Mix of categorical (services, demographics) and numeric (charges, tenure) data

Rows: ~7,043 records

Columns: 21 features + 1 target (Churn)

Preprocessing: Filled missing TotalCharges, converted types, encoded labels, and engineered features like TenureGroup, TotalServices, and binary flags for service usage


⭐**Features / Highlights**

🔍 Business Problem

High customer churn (~26.5%) leads to revenue loss. Identifying churn drivers is crucial for targeted retention efforts.

🎯 Goal of Dashboard

To provide a visual and analytical understanding of churn behavior, support decision-making through segmentation and prediction, and guide personalized retention strategies.

👁️‍🗨️ Walkthrough of Key Visuals

- Count & percentage of churn customers
- Gender, senior citizen status, contract type, and tenure-based churn distributions
- Stacked bar charts for service usage vs churn
- Chi-square tests for statistical significance
- Correlation heatmap
- Model comparison using AUC scores
- K-Means clustering to segment users by tenure and spending- XGBoost
  
📌 Business Impact & Insights

- High-risk churners: Senior citizens, month-to-month contracts, electronic payment users
- Sticky users: Those with add-on services (OnlineSecurity, StreamingTV)
- Model performance: Logistic Regression achieves AUC ~0.84 — most accurate for predicting churn
- Segmentation impact: Clustering enables tailored offers for loyalty, upsell, or onboarding

 **🧩Business Problem**
 
Telecom companies face significant loss due to customer churn. Understanding which customers are most likely to churn—and why—can help prioritize retention efforts, reduce revenue leakage, and improve service value perception.

  






