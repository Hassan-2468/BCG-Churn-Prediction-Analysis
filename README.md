# BCG Gamma Virtual Experience - Customer Churn Prediction 

##  Project Overview
This project is part of the **BCG Data Science & Analytics Virtual Experience**. The goal was to help **PowerCo**, a major energy utility, understand and predict customer churn among their SME (Small and Medium Enterprise) customers.

The core challenge was to test the hypothesis that **price sensitivity** is the main driver of churn and to build a predictive model that identifies at-risk customers.

##  Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
* **Model:** Random Forest Classifier.

##  Key Insights & Findings
* **Price Sensitivity:** While price is a factor, it is not the primary driver of churn.
* **Major Churn Drivers:** High **net margin** and **annual consumption** (12 months) showed a stronger correlation with churn behavior.
* **Data Imbalance:** The dataset was highly imbalanced (~10% churners), requiring specialized handling and evaluation metrics.

## Model Performance
To prioritize business impact (identifying potential churners), I optimized the model's threshold:
* **Initial Recall:** 5% (Ineffective for business intervention).
* **Optimized Recall (Threshold 0.25):** **21%**.
* **Result:** Captured 4x more churners compared to the baseline model, allowing for targeted retention strategies.
 
## 📈 Executive Summary
The final recommendation to PowerCo was to focus retention efforts on **high-margin/high-consumption customers** rather than just focusing on price-sensitive ones. A 5% discount strategy was proposed for customers identified by the model as high-risk.

--
### 🎓 Acknowledgment
*Completed as part of the BCG Virtual Experience Program on Forage.*
