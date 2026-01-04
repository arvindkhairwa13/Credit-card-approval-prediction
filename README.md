# 💳 Credit Card Approval Prediction using Machine Learning

---

## 📌 Project Overview

This project focuses on building a **data-driven credit card approval prediction system** using customer demographic and financial information. The objective is to support **risk-based credit approval decisions** by analyzing applicant profiles and identifying key factors that influence approval outcomes.

The project follows an **end-to-end data science pipeline**, covering data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning model development. Since the dataset does not contain an explicit approval label, a logical approval indicator is engineered based on income level and employment stability to simulate real-world credit decision rules.

---

## 📂 Dataset Description

- Structured credit application dataset containing **demographic and financial attributes**
- Key variables include:
  - Income level
  - Employment duration
  - Age
  - Education level
  - Housing ownership
  - Family and marital status
- A **proxy approval indicator** was engineered using business logic based on income thresholds and employment tenure

---

## 🧠 Approach & Methodology

- Performed **data cleaning and preprocessing** to handle unrealistic values and missing data  
- Conducted **exploratory data analysis (EDA)** to identify patterns and approval drivers  
- Applied **feature engineering**, including age and employment duration conversion  
- Encoded categorical variables using **one-hot encoding**  
- Built and evaluated machine learning models with a focus on **interpretability and predictive performance**

---

## 🤖 Models Evaluated

- **Logistic Regression** (baseline and interpretable model)
- Decision Tree
- Random Forest *(optional extension)*

Models were evaluated using:
- Accuracy  
- Confusion Matrix  
- Classification Report  

with emphasis on minimizing incorrect approval decisions.

---

## 📊 Key Results

- Achieved **~80% accuracy** on test data using Logistic Regression  
- Improved identification of high-risk applicants through rule-based target engineering  
- Identified major approval drivers such as:
  - Income level  
  - Employment stability  
  - Education level  
  - Housing ownership  

---

## 💼 Business Impact

- Enables **risk-based credit card approval decisions**
- Supports early identification of potentially risky applicants  
- Demonstrates how machine learning can:
  - Reduce approval risk  
  - Improve portfolio quality  
  - Enhance data-driven decision-making in financial institutions  

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**

---

## ✅ Conclusion

This project demonstrates the practical application of **machine learning in credit risk assessment**. By combining business logic with data science techniques, the model provides meaningful insights into approval decisions and highlights the importance of interpretable models in financial analytics.

---

