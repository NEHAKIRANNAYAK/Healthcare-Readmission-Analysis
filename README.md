# Healthcare-Readmission-Analysis
This project explores real-world hospital data to uncover patterns in patient readmission using statistical analysis and predictive modeling techniques. It was developed as part of an academic exercise to strengthen data handling, hypothesis testing, and model interpretation skills using the **Diabetes 130-US Hospitals** dataset.

---

## 📌 Objective

To identify key factors influencing **hospital readmission** and analyze how demographics, medication usage, and length of stay affect outcomes. The project applies:
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Binary logistic regression
- One-way ANOVA with post-hoc testing

---

## 🛠️ Tools & Technologies

- **IBM SPSS** (for statistical modeling and hypothesis testing)
- **Python** (for report generation using ReportLab)
- **ReportLab / FPDF** (PDF exports)
- **Data Source**: [UCI Machine Learning Repository – Diabetes 130-US Hospitals Dataset](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008)

---

## 📊 Key Features

- Cleaned and processed hospital records with over **100,000 patient encounters**
- Identified missing values, removed duplicates, and handled outliers
- Performed EDA: descriptive statistics, bar charts, boxplots, and correlation analysis
- Built **logistic regression models** to predict readmission based on:
  - Race
  - Time in hospital
  - Diabetes medication
- Used **Exp(B)** (odds ratios) to interpret model coefficients
- Conducted **ANOVA** to test if average hospital stay varied across age groups
- Applied **Tukey’s HSD** post-hoc test to identify specific differences

---

## 🔍 Findings

- White patients had a **50.4% higher** chance of readmission than non-White patients.
- Each additional hospital day increased the odds of readmission by **3.1%**.
- Patients on diabetes medications had a **37.5% higher** readmission risk.
- ANOVA confirmed **statistically significant differences** in hospital stay durations by age — older patients stayed longer on average.

---

## 📁 Files Included
- Original Dataset
- Cleaned Dataset
- Project Report

---

## 🚀 How to Reproduce

1. Download the dataset from [UCI Repository](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008)
2. Load it into SPSS
3. Apply data cleaning steps as detailed in the report
4. Perform logistic regression and ANOVA using SPSS 
5. Interpret the outputs using Exp(B) and significance values

---
