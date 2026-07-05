# 📊 HR Employee Attrition Analysis

## 📌 Overview

Employee attrition is a major challenge for organizations as it increases recruitment costs, training expenses, and productivity loss. This project analyzes the **IBM HR Employee Attrition** dataset using **SQL** and **Python** to identify the key factors influencing employee turnover.

The analysis focuses on employee demographics, departments, job roles, salary, overtime, business travel, job satisfaction, and years at the company to generate meaningful business insights.


## 🎯 Project Objectives

- Calculate the overall employee attrition rate.
- Analyze attrition across departments and job roles.
- Study the impact of age, salary, overtime, and business travel.
- Identify patterns related to employee retention.
- Visualize insights using Python.

## 🛠️ Tools & Technologies

- **SQL (MySQL)**
- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

## 📂 Dataset

**Dataset:** IBM HR Employee Attrition Dataset

The dataset contains information about **1,470 employees** with features such as:
- Employee Age
- Department
- Job Role
- Monthly Income
- Attrition
- Business Travel
- OverTime
- Job Satisfaction
- Years at Company
- Work-Life Balance
- Education
- Performance Rating
- and other HR-related attributes.

# SQL Analysis

The SQL analysis is divided into business-focused sections:

### 1. Dataset Overview
- Total employees
- Overall attrition
- Average salary
- Employee distribution

### 2. Department Analysis
- Employees by department
- Attrition rate by department
- Average salary by department

### 3. Job Role Analysis
- Employees by job role
- Average salary
- Attrition by job role

### 4. Overtime Analysis
- Employees working overtime
- Attrition by overtime
- Average salary by overtime

### 5. Age Analysis
- Average employee age
- Employee distribution by age group
- Attrition across age groups

### 6. Business Travel Analysis
- Employees by business travel
- Attrition by business travel
- Average years at company

### 7. Advanced Queries
- Employees earning above the company average salary
- Average profile comparison

## 📊 Python Visualizations

The project includes the following visualizations:

- Overall Employee Attrition (Pie Chart)
- Employee Attrition by Age Group
- Attrition Rate by Department
- Attrition by Monthly Income (Box Plot)
- Attrition by OverTime (Count Plot)
- Attrition Rate by Years at Company
- Attrition byJob Satisfaction
- Attrition by Job Role

## 🔍 Key Insights

- Overall employee attrition is **16.1%**.
- Employees aged **25–34** have the highest attrition.
- The **Sales** department records the highest attrition rate.
- Employees with lower monthly income are more likely to leave.
- Employees working overtime have significantly higher attrition.
- Most employees leave during their first few years at the company.
- Lower job satisfaction is associated with higher employee turnover.
- Attrition varies across different job roles.

## 📁 Project Structure

```
HR-Employee-Attrition-Analysis/
│
├── Data/
│   └── HR_Employee_Attrition.csv
│
├── SQL/
│   ├── 01_create_database.sql
│   ├── 02_create_table.sql
│   └── hr_attrition_analysis.sql
│
├── Notebook/
│   └── attrition_analysis.ipynb
│
├── Images/
│   ├── attrition_by_job_role.png
│   ├── attrition_rate_by_department.png
│   ├── attrition_rate_by_years_at_company.png
│   ├── employee_attrition_by_age_group.png
│   ├── monthly_income_vs_attrition.png
│   ├── overall_employee_attrition.png
│   ├── overtime_vs_attrition.png
│   └── job_satisfaction_vs_attrition.png
└── README.md
```

## 🚀 How to Run the Project

### SQL

1. Import the dataset into MySQL.
2. Execute the queries from `hr_attrition_analysis.sql`.

### Python

Install the required libraries:

```bash
pip install pandas matplotlib seaborn
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open `attrition_analysis.ipynb` and run all cells.

---

## 📌 Project Highlights

✔ Cleaned and analyzed HR employee data using Python.
✔ Wrote **20+ SQL business queries** for employee analysis.
✔ Created **8 professional visualizations** using Matplotlib.
✔ Identified key factors influencing employee attrition.
✔ Generated actionable business insights for improving employee retention.


## 💼 Business Recommendations

Based on the analysis, the following recommendations can help reduce employee attrition:
- Focus on improving employee retention in the Sales department.
- Reduce excessive overtime to improve work-life balance.
- Provide competitive salaries and career growth opportunities.
- Improve job satisfaction through employee engagement programs.
- Support new employees during their first few years in the company.
- Conduct regular employee feedback surveys to identify concerns early.


  ## 📌 Key Learnings

Through this project, I learned how to:
- Analyze HR data using SQL and Python.
- Write business-focused SQL queries.
- Clean and transform datasets using Pandas.
- Create professional visualizations using Matplotlib and Seaborn.
- Generate business insights from data analysis.
- Present findings in a clear and structured manner.

## 💡 Conclusion

The analysis shows that employee attrition is influenced by multiple factors, including **age, department, job role, salary, overtime, job satisfaction, and years at the company**. Employees in the **Sales department**, younger employees, those with **lower salaries**, and employees working **overtime** are more likely to leave the organization. These insights can help HR teams develop targeted strategies to improve employee retention and workforce stability.

## 👩‍💻 Author

**Darshana Mangesh Mancharkar**
