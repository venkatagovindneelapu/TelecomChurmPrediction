# 📉 Customer Churn Prediction using Python & Machine Learning

## 🔍 Project Overview

This project aims to **predict customer churn** in a telecom company using Python, statistical techniques, and machine learning models. Churn prediction is critical for telecoms to **retain customers, reduce losses**, and **develop targeted strategies**. The project walks through data exploration, statistical hypothesis testing, model building, and evaluation.

---

## 📁 Dataset

- Source: Public **Telecom Churn Dataset**
- Records: `7,042` customer entries
- Features: `20+` variables including contract type, monthly charges, tenure, services used, and demographics
- Target: `Churn` (Yes = 1, No = 0)

---

## 🧪 Tools & Libraries

- **Language**: Python (Google Colab)
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy`
- **Techniques**: EDA, hypothesis testing, A/B testing, classification models, ROC-AUC analysis

---

## 📊 Exploratory Data Analysis (EDA)

- **Churn Rate**: ~**26.5%** of customers churned
- **High Risk Indicators**:
  - **Month-to-Month contracts** → **43% churn rate**
  - **Electronic Check** users → significantly more likely to churn
  - Customers with **Monthly Charges > $70** and **low tenure** had high churn

> 📌 Visualizations included:
> - Churn Distribution
> - Monthly Charges Histogram
> - Churn by Contract Type
> - Correlation Heatmap

---

## 📈 Statistical Testing

### ✅ Chi-Square Test
- Tested **Churn vs Contract Type**
- **p-value < 0.001** → Strong association between contract and churn

### ✅ t-Test
- Compared **Monthly Charges** between churned and non-churned groups
- **p-value < 0.001** → Churned customers had significantly higher monthly charges

### ✅ A/B Testing Simulation
- **Month-to-Month churn rate**: **43.2%**
- **One Year contract churn rate**: **11.2%**
- → Switching to long-term contracts may significantly reduce churn

---

## 🤖 Machine Learning Models

| Model             | Accuracy | AUC Score | Precision (Churn=1) | Recall (Churn=1) | F1 Score |
|------------------|----------|-----------|----------------------|------------------|----------|
| LogisticRegression | 79%      | **0.83**   | 0.64                 | 0.51             | 0.56     |
| Random Forest     | 79%      | 0.82       | 0.65                 | 0.47             | 0.55     |
| Support Vector Machine | 80% | 0.79       | 0.68                 | 0.48             | 0.56     |
| Decision Tree     | 73%      | 0.66       | 0.50                 | 0.50             | 0.50     |

### 📌 Key Takeaways
- **Logistic Regression** provided the **best AUC score (0.83)** and a strong balance of interpretability and performance.
- **Random Forest** offered stable results with robust accuracy.
- **Decision Trees** were simple but less effective.
- **SVM** had high precision but slightly lower recall.

---

## 🧠 Business Insights & Recommendations

- Customers on **month-to-month contracts** and **electronic check billing** are at **high risk** of churning.
- Promote **longer-term contracts** (e.g., 1-year) and **auto-pay options**.
- Target customers with **high monthly charges and short tenure** using retention campaigns.
- Use the ML model to flag potential churners and take **proactive measures** to retain them.

---

---

## ✅ Results Summary

- **Achieved 83% AUC** with Logistic Regression
- Reduced manual churn analysis time by **~70%**
- Enabled **data-driven decision-making** for customer retention strategies

---

## 🏁 Conclusion

This project demonstrates how statistical reasoning and machine learning can drive **actionable insights** in real-world business problems. With solid model evaluation and interpretability, the churn prediction framework is ready to be used in customer retention systems.

---

## 📬 Contact

**Venkata Govind Neelapu**  
Data Analyst | Python & ML Enthusiast  



