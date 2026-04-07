Workforce Analytics & Attrition Dashboard (Power BI)
🚀 Project Overview

The Workforce Analytics & Attrition Dashboard is a Power BI project designed to analyze employee data and uncover key insights related to attrition, retention, and workforce trends.

This dashboard helps organizations make data-driven HR decisions by identifying patterns in employee behavior, performance, and turnover.


🎯 Objectives
Analyze employee attrition trends
Identify key drivers of employee turnover
Track retention metrics
Provide interactive insights for HR decision-making
🛠️ Tools & Technologies Used
Power BI – Data visualization & dashboard creation
DAX (Data Analysis Expressions) – Calculations & KPIs
Excel / CSV – Data source
Data Modeling – Relationships between tables
📂 Dataset Description

The dataset includes employee-related information such as:

Employee ID
Age
Department
Job Role
Salary
Years at Company
Attrition Status (Yes/No)
Job Satisfaction
Performance Rating
📈 Key Features of Dashboard
1. Attrition Analysis
Total Employees vs Attrition Count
Attrition Rate (%)
Attrition by Department, Job Role, and Age Group
2. Employee Demographics
Age Distribution
Gender Distribution
Education Background
3. Salary & Compensation Insights
Salary Slabs vs Attrition
Income impact on employee retention
4. Job Satisfaction & Performance
Correlation between satisfaction level and attrition
Performance rating analysis
5. Interactive Filters
Department-wise filtering
Job Role filtering
Gender & Age slicers
📊 Key Insights
Higher attrition observed in specific departments and job roles
Employees with lower job satisfaction show higher churn
Salary and work experience significantly impact retention
Early-stage employees (0–2 years) have higher attrition rates
🧠 DAX Measures Used

Some important DAX calculations used:

Attrition Count = COUNTROWS(FILTER(Employee, Employee[Attrition] = "Yes"))

Attrition Rate = 
DIVIDE([Attrition Count], COUNT(Employee[EmployeeID]), 0)

Average Salary = AVERAGE(Employee[MonthlyIncome])
📌 Project Workflow
Data Collection
Data Cleaning & Preprocessing
Data Modeling (Relationships)
DAX Calculations
Dashboard Design
Insights Generation
📸 Dashboard Preview

(Add screenshots of your Power BI dashboard here)

💡 Business Impact
Helps HR teams reduce employee turnover
Improves workforce planning
Identifies high-risk employee segments
Supports strategic decision-making
🔗 How to Use
Download the .pbix file from this repository
Open in Power BI Desktop
Interact with filters and visuals
📌 Future Enhancements
Predictive attrition model (Machine Learning integration)
Real-time data integration
Advanced HR analytics (forecasting trends)
👨‍💻 Author

Prashant Kumar

Aspiring Data Analyst
Skills: SQL, Python, Power BI, Excel
