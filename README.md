# HR Analytics Dashboard

## 📊 Project Overview

The HR Analytics Dashboard is a data analytics project focused on exploring employee data and understanding workforce patterns, employee attrition, job roles, employee demographics, income, overtime, and other HR-related factors.

The project uses Python for data exploration, data cleaning, preprocessing, and exploratory data analysis (EDA), followed by Microsoft Power BI and DAX for creating an interactive HR Analytics Dashboard.

This project was completed as part of a Data Analytics Internship.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze employee attrition and workforce patterns
- Understand employee demographics
- Analyze department-wise employee distribution
- Analyze job roles and employee distribution
- Explore employee education and experience
- Analyze overtime and its relationship with employee attrition
- Analyze monthly income and other employee-related factors
- Explore job satisfaction and work-life balance
- Create an interactive HR Analytics Dashboard using Power BI
- Present HR-related information through clear and meaningful visualizations

---

## 🛠️ Tools & Technologies

### Programming & Data Analysis
- Python
- Pandas
- NumPy
- Matplotlib
- Visual studio code

### Data Visualization & Business Intelligence
- Microsoft Power BI
- DAX

### Version Control
- Git
- GitHub

---

## 📂 Dataset

The project uses the **HR Employee Attrition & Performance** dataset.

The dataset contains employee-related information such as:

- Age
- Attrition
- Business Travel
- Department
- Education
- Education Field
- Gender
- Job Role
- Job Level
- Job Satisfaction
- Monthly Income
- Overtime
- Performance Rating
- Relationship Satisfaction
- Total Working Years
- Training Times
- Work-Life Balance
- Years at Company
- Years in Current Role
- Years Since Last Promotion
- Years With Current Manager

The dataset is used for educational and analytical purposes.

---

## 🔄 Project Workflow

The project was completed through the following stages:

### 1. Data Collection

The HR employee attrition dataset was obtained from a publicly available dataset source and imported into Python for analysis.

### 2. Data Exploration

The dataset was explored using Python to understand:

- Dataset dimensions
- Column names
- Data types
- Statistical information
- Missing values
- Duplicate records
- Unique values
- Numerical and categorical variables

### 3. Data Cleaning & Preprocessing

The dataset was checked for:

- Missing values
- Duplicate records
- Irrelevant columns
- Data consistency

Columns that did not provide useful information for the analysis were removed during preprocessing.

The cleaned dataset was then exported as:

`Clean_HR_Analytics.csv`

### 4. Exploratory Data Analysis

Exploratory analysis was performed to understand employee and workforce patterns.

The analysis included:

- Employee attrition
- Department distribution
- Gender distribution
- Job role distribution
- Education
- Overtime
- Monthly income
- Age distribution
- Years at company
- Job satisfaction
- Employee experience

### 5. Power BI Dashboard

The cleaned dataset was imported into Microsoft Power BI.

DAX measures and Power BI visualizations were used to create an interactive HR Analytics Dashboard.

The dashboard provides a visual representation of employee-related metrics and allows HR-related patterns to be explored more easily.

---

## 📈 HR Analytics Dashboard

The Power BI dashboard focuses on important HR-related areas such as:

- Employee workforce overview
- Employee attrition
- Department analysis
- Job role analysis
- Employee demographics
- Income-related analysis
- Overtime analysis
- Employee-related trends

Screenshots of the dashboard are available in the `screenshots` folder.

The Power BI `.pbix` file is available in the `powerbi` folder.

---

## 📌 Business Questions

This project helps explore questions such as:

- How many employees are present in the dataset?
- What is the employee attrition rate?
- How is employee attrition distributed across departments?
- Which job roles have more employees?
- How is the workforce distributed by gender?
- How does overtime relate to employee attrition?
- What is the age distribution of employees?
- What is the average monthly income?
- How are employees distributed based on education?
- What patterns can be observed from job satisfaction and work-life balance?
- How does employee experience vary across the organization?

---

## 📁 Project Structure

```text
HR_Analytics_Dashboard/
│
├── Dataset/
│   ├── HR_Employee_Attrition_&_performance.csv
│   └── Clean_HR_Analytics.csv
│
├── notebook/
│   └── HR_analysis.ipynb
│
├── powerbi/
│   └── hr analytics dashboard.pbix
│
├── screenshots/
│   ├── Screenshot 2026-08-02 225636.png
│   ├── Screenshot 2026-08-10 212008.png
│   └── Screenshot 2026-08-10 212020.png
│
├── README.md
└── requirements.txt
