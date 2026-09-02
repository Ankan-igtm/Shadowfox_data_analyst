# ShadowFox Data Analyst Internship – Advanced Level

## IBM HR Analytics Dashboard

This project is the **Advanced Level** submission for the ShadowFox Data Analyst Internship.

The objective of this project is to build an **executive-style HR Analytics Dashboard in Power BI** using the IBM HR Analytics dataset. The dashboard focuses on employee demographics, job satisfaction, attrition, overtime, department performance, and employee tenure to provide business-focused HR insights.

---

## 📌 Project Objective

The main objective is to analyze employee data and create an interactive dashboard that helps HR teams and management:

- Monitor employee workforce metrics
- Understand employee attrition patterns
- Analyze job satisfaction
- Compare departments and job roles
- Identify the relationship between overtime and attrition
- Analyze employee age groups
- Understand employee tenure within the organization

---

## 📊 Dataset

**Dataset:** IBM HR Analytics Employee Attrition & Performance

The dataset contains **1,470 employee records and 35 columns** covering employee demographics, job information, compensation, satisfaction, working conditions, and attrition.

### Key Data Fields

- Age
- Gender
- Department
- Job Role
- Job Level
- Monthly Income
- Years at Company
- Total Working Years
- Job Satisfaction
- Environment Satisfaction
- Job Involvement
- OverTime
- Attrition
- Business Travel
- Education
- Marital Status
- Work-Life Balance

---

## 🧹 Data Cleaning & Transformation

The raw dataset was analyzed and prepared using **Python and Pandas** in Google Colab.

The data preparation process included:

- Dataset structure inspection
- Data type verification
- Missing-value analysis
- Duplicate-value analysis
- Categorical-value inspection
- Numerical-value validation
- Identification of constant columns
- Creation of employee age groups
- Creation of salary groups
- Creation of company tenure groups
- Creation of Attrition Flag
- Creation of OverTime Flag
- Calculation of Company Tenure Percentage
- Exporting the cleaned dataset for Power BI

The cleaned dataset was then imported into Power BI for dashboard development.

---

## 📈 Power BI Dashboard

The dashboard was designed as a **single-page executive HR analytics dashboard**.

### KPI Cards

The dashboard contains the following key performance indicators:

1. Total Employees
2. Attrition Count
3. Average Job Satisfaction
4. Average Age
5. Average Monthly Income
6. Average Years at Company

### Visualizations

The dashboard includes:

- Attrition by Department
- Job Role by Attrition
- Overtime by Attrition
- Age Group by Attrition
- Average Years at Company by Attrition
- Employee Number by Department
- Average Job Satisfaction by Department

### Interactive Filters

Users can interact with the dashboard using:

- Department
- Age Group
- Job Role
- Job Level
- OverTime

These filters allow HR teams to analyze different employee groups and investigate attrition and satisfaction patterns.

---

## 💡 Key Business Insights

The dashboard provides insights into:

- Employee attrition across different departments
- Attrition patterns across job roles
- The relationship between overtime and employee attrition
- Attrition across different age groups
- Differences in employee tenure
- Department-level job satisfaction
- Workforce distribution across departments

These insights can help organizations identify areas requiring further HR investigation and employee-retention strategies.

---

## 🎯 Business Recommendations

Based on the dashboard analysis, organizations can:

- Monitor departments with higher employee attrition
- Investigate job roles experiencing higher turnover
- Review overtime-related workload and employee retention
- Improve employee engagement and job satisfaction
- Develop targeted retention strategies for vulnerable employee groups
- Monitor employee tenure and workforce stability
- Use HR analytics regularly to support data-driven workforce decisions

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Google Colab**
- **Microsoft Power BI**
- **Microsoft Excel / CSV**
- **Git & GitHub**

---

## 📁 Project Structure

```text
Advance/
│
├── Data Cleaning/
│   └── IBM_data.ipynb
│
├── Dataset/
│   ├── Raw Data.csv
│   └── IBM_HR_Analytics_Cleaned.csv
│
├── IBM HR ANALYTIS DASHBOARD.pbix
│
├── IBM HR ANALYTIS DASHBOARD.pdf
│
└── Report.pdf
