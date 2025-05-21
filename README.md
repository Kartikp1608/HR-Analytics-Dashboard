# 📊 HR Analytics & Attrition Dashboard

## 🔍 Overview
This project analyzes employee attrition using IBM HR data to uncover trends related to job satisfaction, compensation, department, and work-life balance. The goal is to help HR teams identify factors leading to churn and build data-driven retention strategies.



## 🧾 Dataset
- **Source**: IBM HR Analytics Employee Attrition & Performance Dataset  
- **Records**: 1,470 employees  
- **Fields**: 35+ columns covering personal, job, performance, and compensation data  
- **File**: `cleaned_hr_data.csv`


## 🛠 Tools Used
- **Power BI**: for dashboard design and interactivity  
- **Python (Pandas, Seaborn)**: for data cleaning and EDA  
- **MySQL** *(optional)*: for storing and querying data  
- **Jupyter Notebook**: for preprocessing pipeline


## 📈 Key Visuals in the Dashboard
- **KPI Cards**: Total Employees, Attrition Rate, Avg Monthly Income, Avg Tenure  
- **Bar Charts**: Attrition by Department, Job Role, and OverTime  
- **Scatter Plot**: Years at Company vs Monthly Income by Attrition  
- **Heatmap**: Job Satisfaction vs Work-Life Balance vs Attrition  
- **Slicers**: Gender, JobLevel, BusinessTravel, EducationField, MaritalStatus

![Screenshot 2025-05-21 115336](https://github.com/user-attachments/assets/b0f89240-262e-4b1e-a6cf-7e993e399eb6)


---

## ✅ Key Insights
- **Overall attrition rate**: ~16%  
- Employees with **OverTime**, low **JobSatisfaction**, and **short tenure** are more likely to leave  
- **Sales** and **Research & Development** departments had the highest churn  
- High **WorkLifeBalance** and **Income** correlated with lower attrition

---

## 🚀 How to Run This Project
1. Run the Jupyter Notebook (`hr_attrition_analysis.ipynb`) to generate `cleaned_hr_data.csv`  
2. Load `cleaned_hr_data.csv` into Power BI  
3. Use the provided visuals or create your own from suggested fields  
4. Publish to Power BI Service if needed

---

## 📌 Future Improvements
- Time-series exit trend tracking with synthetic `ExitDate`  
- Predictive modeling (Logistic Regression, Decision Trees)  
- Automated reporting pipeline using Python + Power BI REST API

---

## 🤝 Let's Connect
If you're an employer, analyst, or student interested in data analytics or HR insights, feel free to reach out!

