 📊 IBM HR Analytics – Employee Attrition & Performance Analysis

 🔎 Project Overview

Employee attrition is one of the biggest challenges organizations face. High turnover increases recruitment costs, reduces productivity, and impacts long-term stability.

This project analyzes the IBM HR Employee Attrition dataset to:

- Measure overall attrition rate
- Identify key factors influencing employee turnover
- Analyze demographic and performance-based patterns
- Provide data-driven business recommendations

---

 📂 Dataset Information

- Total Records: 1470 employees
- Total Features: 35 columns
- Target Variable: Attrition (Yes / No)
- Dataset Condition: No missing values, No duplicate records

---

 📌 Key Performance Indicators (KPIs)

 📉 Attrition Rate
- Overall Attrition Rate: 16.12%
- Meaning: Approximately 16 out of every 100 employees left the company.

 ⏳ Average Tenure
- Average Years at Company: 7.01 years
- Indicates moderate workforce stability.

---

 🛠 Tools & Technologies Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn (Data Visualization)
- SQL (Data Analysis)
- Excel
- Jupyter Notebook

---

 🧹 Data Cleaning & Preparation

- Checked dataset shape (1470 × 35)
- Verified zero duplicates
- Verified zero missing values
- Confirmed appropriate data types
- Performed statistical summary using `.describe()`

The dataset was clean and ready for analysis.

---

 📊 Exploratory Data Analysis (EDA)

 👥 Demographic Insights

- Majority employees fall in the 30–35 age group.
- Research & Development department has the highest employee count.
- Male employees outnumber female employees.

---

 📈 Attrition Insights

Key findings from the analysis:

- Employees working overtime show higher attrition.
- Lower job satisfaction correlates with higher turnover.
- Sales Representatives have higher attrition compared to other roles.
- Employees with lower monthly income are more likely to leave.
- Poor work-life balance increases resignation probability.

---

 📊 Visualizations Created

- Attrition Distribution Bar Chart
- Age Distribution (KDE Plot)
- Gender-wise Attrition Rate
- Department-wise Distribution
- Attrition by Demographic Factors
- Tenure Analysis

---

 📌 Business Recommendations

- Reduce excessive overtime policies.
- Improve employee engagement and satisfaction programs.
- Review compensation strategy for lower-income roles.
- Focus retention efforts on high-risk departments.
- Strengthen work-life balance initiatives.

---

 📁 Project Structure

IBM-HR-Analytics/
│
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── notebooks/
│   └── IBM_HR_Attrition_Project.ipynb
│
└── README.md

---

 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:
