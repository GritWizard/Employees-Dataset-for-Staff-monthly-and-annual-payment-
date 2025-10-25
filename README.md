# Employees-Dataset-for-Staff-monthly-and-annual-payment-

## 📊 Project Overview
This project analyzes **staff salary distribution** with the goal of measuring both **monthly and annual payments**.  
The dataset titled **“EMPLOYEES DATASET”** contains detailed information on 10,000 employees across different job categories, education levels, company types, and locations.

The objectives of this analysis are to:
- Examine **monthly and annual salary trends**.
- Compare salaries by **gender**, **education level**, **occupation**, and **company type**.
- Perform **regression and correlation analysis** to identify factors influencing salary variations.
- Build **interactive Power BI dashboards** for clear visualization and reporting.

---

## 🧾 Dataset Description

| Column Name         | Description |
|----------------------|-------------|
| `id`                 | Unique identifier for each employee |
| `age`                | Employee’s age |
| `Sex`                | Gender of the employee (Male/Female) |
| `Job Type`           | Work arrangement (Remote, On-site, or Hybrid) |
| `Company Type`       | Type of organization (Startup, Large Enterprise, etc.) |
| `Marital Status`     | Marital status (Single, Married, etc.) |
| `Location`           | Location category (Rural, City, Metro) |
| `Certifications`     | Professional certifications held |
| `Education_level`    | Highest academic qualification |
| `Bonus`              | Bonus range received by employee |
| `Allowances`         | Type of additional benefits (e.g., Food, Housing, Travel) |
| `Occupation`         | Career level (Fresher, Intermediate, Professional) |
| `Working Hours`      | Average daily working hours |
| `Salary Per Month`   | Base monthly salary in Naira (₦) |

---

## 📈 Analytical Goals
1. Compute **Annual Salary** (`Salary Per Month × 12`).
2. Examine average salary variations by:
   - Gender  
   - Education Level  
   - Occupation  
   - Company Type  
3. Explore relationships between:
   - Education level and Salary  
   - Working hours and Salary  
   - Age and Salary  
4. Identify **key predictors** of higher salaries using **regression analysis**.
5. Develop **interactive Power BI dashboards** to visualize patterns and correlations.

---

## 🧮 Methodology

### 1. Data Preparation
- Cleaned and standardized dataset by removing duplicates and inconsistencies.  
- Created a new calculated field for **Annual Salary**.  
- Encoded categorical data where necessary for regression and correlation testing.  

### 2. Descriptive Analysis
- Computed summary statistics (mean, median, and salary ranges).  
- Segmented employees by gender, education, and occupation level.

### 3. Correlation Analysis
- Explored linear relationships between **Salary Per Month** and numerical variables such as:
  - **Age**
  - **Working Hours**
  - **Education Level (encoded)**  
- Visualized correlation coefficients using Power BI correlation matrix visuals.

### 4. Regression Analysis
- Built a **Multiple Linear Regression model** to predict Salary Per Month using:
  - `Age`, `Education Level`, `Working Hours`, and `Company Type`  
- Interpreted regression coefficients to identify the **most influential salary factors**.  
- Validated model fit using R² and p-values to assess statistical significance.  

### 5. Visualization (Power BI)
- Created **interactive dashboards** showing:
  - Salary distribution by gender, company type, and education.
  - Correlation heatmaps for numerical relationships.
  - Regression trend lines showing salary progression by age and education level.
  - Annual salary breakdown across departments and occupations.

---

## 🛠️ Tools 
- **Microsoft Excel:** Initial data cleaning and preparation  
- **Power BI:** Data modeling, correlation and regression analysis, interactive dashboard creation  
- **Statistical Methods:** Descriptive statistics, correlation matrix, multiple regression analysis  



---

## 🧭 Executive Summary

### Employee Characteristics and Salary Structure
This analysis explores the relationship between employee characteristics — **Education Level**, **Working Hours**, **Job Type**, **Marital Status**, **Location**, and **Gender** — and their impact on salary structure.

---

### 🎓 Question 1 — Education Level
Average monthly salaries are fairly similar across all education levels, ranging between **₦85,000 and ₦88,000**.  
This indicates that higher educational qualifications do not necessarily translate to significantly higher monthly earnings in this dataset.

---

### ⏰ Question 2 — Working Hours
The **correlation coefficient** between *Working Hours* and *Salary Per Month* is **0.013**, which is extremely close to zero.  
This means there is virtually **no relationship** between the number of hours worked and salary earned.  
In essence, **working longer hours does not increase or decrease salary** in any meaningful way.

---

### 💼 Question 3 — Experience Level and Job Type
Employees with more experience tend to earn **slightly higher salaries**, but the overall difference remains minimal.  
Job type (e.g., remote, on-site, or hybrid) shows little variation in pay across experience levels.

---

### 💍 Question 4 — Marital Status
Salary levels are **nearly identical** regardless of marital status.  
This suggests that employers in the dataset do not factor marital status into compensation decisions.

---

### 👩‍💼 Question 5 — Gender and Experience Level
**Male and female employees** earn almost **identical average salaries** across all experience levels.  
There is no statistically significant gender pay gap observed in the dataset.

---

### 📊 Overall Findings
The analysis suggests that **salary distribution is largely uniform** across demographic and professional factors.  
Salary in this dataset is **not strongly influenced** by:
- Education Level  
- Gender  
- Marital Status  
- Working Hours  

The **only mild factor** with a measurable impact is **experience**, though even this effect remains relatively small.

---

### 🧩 Conclusion
The results highlight a pay structure that appears **equitable and consistent**, showing minimal salary variation across personal or demographic characteristics.  
This finding may suggest standardized pay policies within organizations represented in the dataset, or limited salary differentiation practices in the sampled population.

---

## 👤 Author
**Jimoh Qoseem**  
ICT Instructor & Data Analyst  
Heritage Global Academy, Lagos, Nigeria  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jimoh-abolore-qoseem-a25a5a249)

📧 qoseem.jimoh@heritageglobalacademy.com
