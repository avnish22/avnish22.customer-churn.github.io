# Customer Churn Prediction – Telecom Dataset 📊

## 📌 Business Problem
Telecom companies face a critical challenge: **customer churn** (customers leaving for competitors).  
High churn means **revenue loss**, higher **acquisition costs**, and declining **customer lifetime value**.  

The key question is:  
**“Are customers leaving the company, and how can we reduce churn?”**

---

## 🎯 Project Goal
- Analyze customer behavior to **identify churn drivers**.  
- Use **statistics + machine learning (Logistic Regression)** to predict which customers are likely to churn.  
- Provide **business insights** for retention strategies.  

---

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Google Colab / Kaggle** for development  
- **Machine Learning**: Logistic Regression  

---

## 📂 Dataset
- Dataset: [Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Features include:** demographics, services subscribed, contract type, billing, tenure, charges, etc.  
- **Target variable:** `Churn` (Yes/No → converted to `Churn_Flag` 1/0).  

---

## 📊 Project Workflow
1. **Data Cleaning**
   - Handle missing values in `TotalCharges`.  
   - Drop irrelevant columns (`customerID`).  

2. **Exploratory Data Analysis (EDA)**
   - Statistical summary of numeric features.  
   - Churn rate comparisons (tenure, monthly charges, services).  
   - Correlation heatmap for numeric variables.  
   - Visualization of churn distribution.  

3. **Insights from Statistics**
   - Customers with **short tenure (<12 months)** churn more.  
   - Customers with **high monthly charges** churn more.  
   - **Online Security, Tech Support, Long-term contracts** reduce churn risk.  

4. **Modeling**
   - Logistic Regression with preprocessing pipeline (scaling + encoding).  
   - Evaluated using Accuracy, Precision, Recall, F1-score, Confusion Matrix.  

5. **Feature Importance**
   - Key churn drivers identified via logistic regression coefficients.  

---

## 📈 Results
- **Accuracy:** ~0.79 (79%)  
- **Recall for churn:** ~0.54 → model catches 54% of churners.  
- **Business Interpretation:**  
  - Strong focus on reducing false negatives (missed churners).  
  - Recommend targeted retention offers for **new customers** and **high-bill customers**.  

---

## 👨‍💻 My Role
- Designed an **end-to-end analytics + ML pipeline**.  
- Combined **statistics + visualization** for insights.  
- Built and evaluated a **predictive churn model**.  
- Delivered **business recommendations** for retention strategies.  

---

## 🚀 Next Steps
- Try advanced models (Random Forest, XGBoost) to improve recall.  
- Apply **SMOTE** or **class weights** to handle class imbalance.  
- Build a **dashboard** (Power BI / Tableau / Streamlit) for stakeholders.  

---


