# 📊 Churn Prediction Analysis

This project focuses on analyzing customer churn for a telecom company using machine learning. It includes customer profiling, churn risk prediction, and dashboards for insights.

## 🔍 Overview

- **Goal**: Predict which customers are likely to churn.
- **Tech Stack**: Python (Jupyter Notebook), Pandas, Scikit-learn, Power BI.
- **Model Used**: Random Forest
- **Accuracy Achieved**: 86%

## 📁 Files Included

| File Name                        | Description                                                                          |
|----------------------------------|--------------------------------------------------------------------------------------|
| `Churn Prediction.ipynb`        | Jupyter Notebook with EDA, preprocessing, model training, evaluation, and results.  |
| `Churn Analysis-Prediction.png` | Power BI dashboard showing predicted churner profiles and customers at risk.        |
| `Churn Analysis-Summary.png`    | Power BI dashboard showing churn distribution, trends, and risk segments.           |
| `Churn Analysis.pbix`						| Power BI dashboard showing churn distribution and predicted Churner Profile.
| `README.md`                     | Project documentation (this file).                                                  |

## 📈 Key Insights

- **Churn Rate**: 27%
- **High-Risk Profiles**:
  - Gender: Mostly Female
  - Age: 20–50
  - Tenure: < 12 Months
  - Payment Method: Credit Card, Bank Withdrawal
  - Contract Type: Month-to-Month
- **Top Churn States**: Uttar Pradesh, Maharashtra, Tamil Nadu
- **Service Factors**: Lack of device protection and online security correlates with higher churn

## 🧠 Model Highlights

- **Features Used**: Gender, Age, Tenure, Monthly Charges, Contract Type, Internet Service, etc.
- **Evaluation Metrics**:
  - Accuracy: `86%`
 
## 📊 Visual Dashboards

Interactive dashboards were created using **Power BI** to translate complex churn prediction results into business-friendly insights. These dashboards enable easy interpretation of customer behavior and risk segmentation.

### 🔍 Prediction Dashboard

Displays predicted churners along with demographic breakdowns such as gender, age group, marital status, state, payment method, and contract type.  
It helps identify high-risk customer segments for targeted retention efforts.

![Prediction Dashboard](Churn%20Analysis-Prediction.png)

### 📈 Churn Summary Dashboard

Provides detailed churn rate analysis across various dimensions including:

- **Demographics**: Age, gender, marital status  
- **Account Info**: Contract type, payment method, tenure  
- **Geography**: Churn rate by top states  
- **Services Used**: Impact of services like internet, phone, and backups on churn  
- **Churn Reasons**: Categorized by competition, dissatisfaction, pricing, and more

![Churn Summary Dashboard](Churn%20Analysis-Summary.png)

> These dashboards were built using advanced Power BI visualizations and slicers for dynamic filtering.
