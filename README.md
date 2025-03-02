# HR Analytics Dashboard  

This repository contains an **HR Analytics Dashboard** designed to visualize employee attrition trends based on various factors such as education, age, salary, and job roles. The dashboard provides insights into attrition rates and helps in understanding key factors influencing employee turnover.

---

## 📊 Dashboard Overview  

The dashboard includes:  
- **Total Employees & Attrition Count** – Displays the overall workforce and attrition rate.  
- **Attrition Breakdown** – Analyzes attrition by age, education, salary range, and job roles.  
- **Job Satisfaction Levels** – Shows attrition based on employee satisfaction scores.  
- **Gender-Based Filtering** – Allows filtering attrition trends by male and female employees.  
- **Interactive Visuals** – Helps in understanding key trends affecting employee retention.  

---

## 📸 Dashboard Preview  

![HR Analytics Dashboard](images/dashboard.png)  

---

## 🔍 Data Cleaning & Processing  

Before building the dashboard, the dataset underwent **data cleaning** and **preprocessing** to ensure accuracy and consistency. The steps included:

### 1️⃣ **Handling Missing Values**  
- Identified missing values in key columns (e.g., salary, job role, satisfaction score).  
- Used **mean/median imputation** for numerical fields like salary and job satisfaction.  
- Used **mode imputation** for categorical values such as job roles.  

### 2️⃣ **Removing Duplicates**  
- Checked for duplicate employee records using `Employee ID`.  
- Removed duplicate entries to ensure accuracy.  

### 3️⃣ **Data Type Corrections**  
- Converted categorical variables like `Job Role` and `Education Level` into appropriate formats.  
- Standardized `Salary` data to ensure consistency in units (e.g., thousands).  

### 4️⃣ **Outlier Detection & Removal**  
- Used **IQR (Interquartile Range) Method** to detect anomalies in age and salary data.  
- Removed extreme outliers that could skew the analysis.  

### 5️⃣ **Feature Engineering**  
- Created **age groups** (e.g., 18-25, 26-35, etc.) for better visual representation.  
- Categorized salaries into brackets (`<5K`, `5K-10K`, etc.).  
- Transformed job satisfaction ratings into meaningful insights.  

### 6️⃣ **Data Normalization**  
- Standardized numerical columns to prevent bias in visual representation.  
- Used **Min-Max Scaling** for salary and experience levels.  

---

## 📁 Repository Structure  

