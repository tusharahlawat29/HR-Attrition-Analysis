# HR Attrition Analysis 

##  Project Overview

This project analyzes employee attrition data to uncover key patterns and insights behind why employees leave an organization. The goal is to help HR departments identify high-risk employees and take strategic actions to improve employee retention.

---

##  Objective

- Predict whether an employee will leave the company (Attrition: Yes/No)
- Identify top contributing factors to attrition (e.g., OverTime, Marital Status, Department, etc.)
- Provide actionable business recommendations based on data insights

---

##  Tools & Technologies

- **Python** (Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn)
- **Jupyter Notebook**
- **Dataset:** IBM HR Analytics Employee Attrition Dataset

---

##  Dataset

- Total Records: 1470 employees
- Features include: Age, Gender, Department, OverTime, JobSatisfaction, MonthlyIncome, etc.
- Target variable: `Attrition` (Yes/No)

---

##  Exploratory Data Analysis (EDA)

- **OverTime vs Attrition**: Employees working overtime are more likely to leave
- **Age Distribution**: Younger employees show a higher attrition rate
- **Correlation Heatmap**: Reveals relationships among numerical features (e.g., MonthlyIncome, JobSatisfaction, Age)

---

##  Model Building

- **Model Used**: Logistic Regression
- **Accuracy Achieved**: ~86%
- **Confusion Matrix**: [250 5]
                        [35  4]

---

- **Classification Report**:
- High precision and recall for non-attrition cases
- Challenges in predicting rare attrition cases

---

##  Key Insights

- **OverTime** is the most influential feature
- **Single employees** and **Sales department** showed higher attrition rates
- Age, MonthlyIncome, and JobRole also impact attrition risk

---

##  Business Recommendations

1. **Monitor and manage OverTime** work hours to reduce burnout.
2. **Create targeted retention plans** for employees in the Sales department.
3. **Offer support programs** for single employees who may lack work-life balance.
4. **Focus on employee satisfaction**, particularly among younger age groups.

---


