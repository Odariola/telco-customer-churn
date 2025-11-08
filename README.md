# telco-customer-churn
Predicting customer churn using ML models 


📌 Overview
This project analyzes the **Telco Customer Churn dataset** to predict whether a customer will leave the company.  
It demonstrates skills in **data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning model tuning**.  
Beyond technical modeling, the project also translates insights into **business recommendations** for customer retention.

---

## ⚙️ Tech Stack
- Python (Jupyter Notebook)
- Pandas, NumPy
- scikit-learn
- XGBoost
- Matplotlib / Seaborn

---

## 🚀 Workflow
1. **Data Cleaning**
   - Handled missing values and encoded categorical variables.  

2. **Exploratory Data Analysis (EDA)**
   - Boxplots and correlation heatmaps revealed churn patterns.  
   - Customers on month-to-month contracts with low tenure and high monthly charges were disproportionately likely to churn.  

3. **Model Training & Tuning**  
   - Baseline: Random Forest → **79.21% accuracy**  
   - Tuned XGBoost (via GridSearchCV) → **81.33% accuracy**  
   - Net improvement: ~2.12 percentage points.  

4. **Feature Importance**  
   - Top churn drivers:  
     - **Tenure** (short-term contracts more likely to churn)  
     - **MonthlyCharges** (higher charges → higher churn risk)  
     - **TechSupport** (lack of support increases churn)  
     - **InternetService type**  

---

## 📊 Results
- Tuned XGBoost outperformed baseline Random Forest.  
- Feature importance aligned with EDA findings.  
- Visualizations (feature importance chart, churn distribution plots) supported conclusions.  

---

## 💼 Business Recommendations
- **Target month-to-month customers with retention offers.**  
  - Provide timed discounts or loyalty credits to encourage longer contracts.  
- **Offer incentives for long-term contracts.**  
  - Moving customers to 12–24 month plans reduces churn probability.  
- **Expand tech support availability.**  
  - Customers with support are less likely to churn.  
- **Monitor high-charge customers.**  
  - Discounts or personalized offers can reduce churn among high-risk groups.  

---

## 🧠 What I Learned
- How to balance technical modeling with business impact.  
- Importance of feature engineering and hyperparameter tuning.  
- Translating machine learning results into actionable strategies for stakeholders.  

---

👨‍💻 Explore more projects on my [GitHub](https://github.com/odariola).
