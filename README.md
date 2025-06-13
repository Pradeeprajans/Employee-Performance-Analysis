# 📊 Employee Performance Analysis – INX Future Inc.

![IABAC Certified](https://img.shields.io/badge/Certified-IABAC-blue)
![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Built with Scikit-learn](https://img.shields.io/badge/Built%20with-scikit--learn-yellow)

---

## 🧾 Project Overview

This project, created for the **IABAC Data Science Certification**, focuses on analyzing and predicting employee performance for **INX Future Inc.**  
It showcases a complete end-to-end data science pipeline — from data cleaning and visualization to feature engineering, model building, and actionable recommendations.

---

## 🎯 Objectives

- Analyze employee performance across roles and departments
- Identify the **top 3 factors** that influence performance
- Build a **classification model** to predict performance category (Low, Medium, High)
- Provide strategic HR recommendations based on data insights

---

## 📁 Folder Structure

```
Employee_Performance_Analysis/
├── Data/
│ ├── INX_Employee_Performance.xlsx
│ ├── Employee_Data_Engineered.csv
│ └── Employee_Data_Before_Encoding.csv
│
├── models/
│ ├── best_rf_model.pkl
│ ├── log_reg_model.pkl
│ └── scaler.pkl
│
├── PowerBI_visuals/
│ └── Dashboards.pbix
│
├── Project_summary/
│ └── Project_summary.ipynb
│
├── reports/
│ └── Correlation_matrix.png
│ └── Department-wise_Performance.png
│ └── Evaluation_report_RandomForest_Tuned.png
│ └── Top_10_important_Features_affecting_Performance.png
│
├── 01_EDA.ipynb
├── 02_Feature_Engineering.ipynb
├── 03_Model_Building.ipynb
├── 04_Model_Evaluation.ipynb
└── Insights_&_Recommendations.ipynb
└── Employee_Performance_Analysis_Presentation.pptx
└── README.md
```
---

## 📊 Exploratory Data Analysis (EDA)

- Conducted thorough demographic and department-wise analysis
- Found strong correlations between **environment satisfaction**, **training**, and **performance**
- Cleaned missing values and managed class imbalance in the target variable

---

## 🛠 Feature Engineering

Key features created:
- `ExperienceGap`: Difference between total experience and company experience  
- `AvgExperiencePerCompany`: Tenure ratio  
- `AgeGroup`, `TenureCategory`, and `PerformanceCategory` as grouped features  
- Label encoding for categorical features  
- Scaled numerical columns using MinMaxScaler  

---

## 🤖 Model Building & Results

Trained models:
- ✅ **Random Forest Classifier** → **97.9% Accuracy** (Best)
- Logistic Regression → 75% Accuracy

Used **GridSearchCV** for hyperparameter tuning  
All trained models saved as `.pkl` files for easy deployment

---

## 🔍 Top 3 Predictors Identified

1. `EmpEnvironmentSatisfaction`
2. `EmpLastSalaryHikePercent`
3. `YearsSinceLastPromotion`

---

## 💡 Business Recommendations

- Boost **work-life balance initiatives** across departments
- Use predictive insights to **support hiring, internal mobility, and training**
- Implement regular **employee feedback systems** to monitor satisfaction

---

## 🔭 Future Scope

- Integrate predictions with **live HR dashboards**
- Add **real-time feedback collection** to improve model inputs
- Continuously retrain the model with new employee performance data

---

## 👨‍💻 Author

**Pradeep Rajan**  
📧 pradeeeprajans@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/pradeeprajans)  
🔗 [GitHub](https://github.com/pradeeprajans)  
🔗 [Portfolio](https://pradeeprajans.github.io/Portfolio)

---

## 🙏 Acknowledgements

- Guided by **IABAC (International Association of Business Analytics Certifications)**
- Dataset provided by **INX Future Inc.** (synthetic)
