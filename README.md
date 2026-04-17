# 👥 HR Attrition Analytics Dashboard

> A predictive analytics solution to identify key drivers of employee attrition and enable proactive retention strategies.

---

## 📌 Project Overview

Employee attrition is one of the most costly challenges organizations face. This project builds an end-to-end analytics pipeline that identifies **why employees leave** and **who is most at risk** — empowering HR teams to act before it's too late.

The solution combines machine learning classification models with an interactive Power BI dashboard, giving HR leadership clear, actionable insights backed by data.

---

## 🎯 Objectives

- Identify the top factors contributing to employee attrition
- Build a predictive model to flag at-risk employees
- Deliver an interactive dashboard for HR decision-makers
- Provide recommendations to improve employee retention

---

## 🗂️ Dataset

- **Source:** IBM HR Analytics Employee Attrition Dataset
- **Records:** 1,470 employee records
- **Features:** 35 attributes including Age, Department, Job Role, Monthly Income, Overtime, Job Satisfaction, Years at Company, and more
- **Target:** `Attrition` (Yes / No)

---

## 🔍 Key Findings

- Employees working **overtime** are significantly more likely to leave
- **Low job satisfaction** and **low environment satisfaction** are strong attrition indicators
- **Early-career employees** (0–3 years tenure) show the highest attrition rate
- **Sales** and **Human Resources** departments have the highest attrition percentages
- Monthly income below a certain threshold correlates strongly with attrition

---

## 🤖 ML Models Used

| Model | Accuracy |
|---|---|
| Logistic Regression | ~82% |
| Random Forest Classifier | ~86% |
| Decision Tree | ~79% |

> Random Forest was selected as the final model based on accuracy and feature importance interpretability.

---

## 📊 Dashboard Features

- Overall attrition rate KPI cards
- Attrition breakdown by Department, Job Role, Age Group, and Gender
- Satisfaction score analysis across attrition segments
- At-risk employee filter and drill-through view
- Monthly income vs attrition correlation chart

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Data cleaning, EDA, model building |
| Pandas & NumPy | Data manipulation |
| Scikit-learn | ML model training & evaluation |
| Matplotlib & Seaborn | Exploratory visualizations |
| Power BI | Interactive dashboard |
| SQL | Data querying |

---

## 📁 Project Structure

```
hr-attrition-dashboard/
│
├── data/
│   └── HR_Employee_Attrition.csv
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Preprocessing.ipynb
│   └── 03_Model_Building.ipynb
│
├── dashboard/
│   └── HR_Attrition_Dashboard.pbix
│
├── outputs/
│   └── model_results.csv
│
└── README.md
```
