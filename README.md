<p align="center">
  <img src="assets/Mtn-Churn-Project-Asset.png" alt="MTN Churn Prediction Banner" width="100%">
</p>

# 📱 MTN Customer Retention Engine

**End-to-End Churn Prediction & ROI Optimization System**

---

## 🚀 Overview

Customer churn is one of the biggest revenue leaks in telecom.

This project builds a data-driven retention engine that predicts which MTN Nigeria customers are at risk of leaving—and enables proactive intervention before churn happens.

🔍 Using transactional data, I transformed raw records into actionable customer intelligence and a business-ready decision system.

---

## 💼 Business Problem

- 📉 Customer acquisition is expensive  
- 📈 Retention is significantly cheaper  
- ❌ Traditional reporting is reactive  

👉 **The goal:**  
Identify churn risk early and intervene at low cost

---

## ⚙️ Solution Architecture

### 🛠️ 1. Data Engineering (SQL Layer)

- Aggregated **974 transactions → 496 customer profiles**
- Built behavioral features:
  - Total_Spend  
  - Purchase_Frequency  
  - Avg_Satisfaction  
- Standardized geographic data  
- Designed a customer-level analytical dataset  

---

### 🤖 2. Machine Learning Pipeline

- Model: **Random Forest Classifier**
- Handled imbalance using `class_weight='balanced'`
- Controlled overfitting via depth tuning  

#### 🎯 Optimization Strategy

- Focused on **Recall (93%)**  
- Applied **30% probability threshold**  
- Captures **27 out of 29 churners**

---

### 💰 3. Business ROI Modeling

Translated predictions into financial impact:

| Metric | Value |
|--------|-------|
| Recall | 93% |
| Intervention Cost | ₦500 |
| Customer Value (ARPU) | ₦5,000 |
| Estimated ROI | 181% |

📌 *Assumption: Not all targeted customers are successfully retained, reflecting real-world campaign effectiveness*

---

## 📊 Key Insights

- **Primary Driver:** Total Spend  
  → High-value customers are more sensitive to dissatisfaction  

- **Behavioral Signal:**  
  Satisfaction + usage patterns strongly influence churn  

- **Geographic Risk:**  
  Osun State shows elevated churn risk  
  → Potential infrastructure/service issue  

- **Strategic Lever:**  
  A 30% threshold balances cost vs retention impact effectively  
