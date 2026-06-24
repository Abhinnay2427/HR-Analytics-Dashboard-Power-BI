# HR-Analytics-Dashboard-Power-BI

**📝** **Project Overview**

The HR Analytics Dashboard is an end-to-end Power BI project designed to analyze employee data and provide meaningful insights into workforce performance, attendance, recruitment, training, and attrition.

This project transforms raw HR data into interactive dashboards that help organizations make data-driven decisions regarding employee management and workforce planning.

---

🎯 **Business Problem**

HR teams often struggle to monitor workforce performance, employee engagement, recruitment effectiveness, and employee turnover due to scattered data sources.

This dashboard centralizes HR data into a single analytical platform, enabling stakeholders to track KPIs, identify trends, and improve decision-making.

---


**🔄** **End-to-End Workflow**

CSV Dataset
     ↓
Power Query
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Calculations
     ↓
Dashboard Development
     ↓
Business Insights

---

**📂** **Data Source**

**Source Type:** CSV File

**Dataset Name:** https://1drv.ms/x/c/00b1e276a52f7d08/IQDKNcEKJWCiTIQu5Gbt6R8sAbhZMTc4AW846VCHc2bQ1sw?e=ykFnyn


**Dataset Includes:**

* Employee Information
* Department Details
* Attendance Records
* Recruitment Sources
* Training Programs
* Attrition Information
* Salary Information
* Performance Scores

---

**🧹** **Data Cleaning & Data Preparation**

The dataset was cleaned and transformed using Power Query.

**Cleaning Steps**

✔ Removed duplicate records

✔ Corrected inconsistent values

✔ Handled missing data

✔ Standardized department names

✔ Converted columns into appropriate data types

✔ Verified attendance and performance metrics

---

**📈** **Power BI Dashboard**

**Dashboard 1:** 

* **HR Analytics Dashboard**

1. KPI Cards

2. Active Employees

3. Total Employees

4. Average Performance

5. Attrition Rate

6. Average Salary

* **Visualizations**

**Employee Distribution**

1. Donut Chart

2. Total Employees by Department

* **Attendance Analysis**

1. Line Chart

2. Average Attendance by Month

* **Attrition Analysis**

1, Bar Chart

2. Attrition Count by Exit Reason

* **Recruitment Analysis**

1. Donut Chart

2. Joined Employees by Source

* **Interactive Slicers**
1. Department
2. Location
3. Gender
4. Job Level
5. Employment Status


***Dashboard 2:**

* **Training Dashboard**

* **Visualizations**

Training Hours by Training Program

* **Programs Included**:

✔ Excel Advanced

✔ Power BI

✔ Leadership Skills

✔ POSH Awareness

✔ Agile & Scrum

✔ Communication Skills

✔ Data Analytics

---

**💡** **Key Insights**

**Workforce Insights**

1. Employee distribution is balanced across departments.

2. Data Analytics and IT departments have strong representation.

**Attendance Insights**

1. Attendance remains consistently above 87%.

2. Workforce engagement remains stable.

**Top recruitment channels:**

1. Indeed
2. Campus Hiring
3. Shine Naukri
4. Attrition Insights

**Major reasons for employee exits:**

1. Work Culture
2. Family Reasons
3. No Growth Opportunities
4. Personal Reasons
5. Training Insights

**Top training programs:**

* Excel Advanced
* Six Sigma
* Power BI
* SAP HR
* Leadership Skills

---

  

**🛠 ****Tools & Technologies**

  
| Category      | Tool             |
| ------------- | ---------------- |
| Visualization | Power BI         |
| Data Cleaning | Power Query      |
| Data Modeling | DAX              |
| Data Source   | CSV / Excel      |
| Documentation | GitHub           |
| Reporting     | Power BI Desktop |


---


**📁** **Repository Structure**


HR-Analytics-Dashboard/

│

├── Data/

│   └── HR_Analytics.csv

│

├── PowerBI/

│   └── HR_Analytics_Dashboard.pbix

│

├── Screenshots/

│   ├── HR_Analytics_Dashboard.png

│   └── Training_Dashboard.png

│

├── README.md

│

└── LICENSE

---



**📋** **Data Structure**



| Column Category      | Description                     |
| -------------------- | ------------------------------- |
| Employee Information | Employee ID, Gender, Department |
| Job Information      | Job Level, Employment Status    |
| Salary Information   | Employee Salary                 |
| Performance Metrics  | Performance Score               |
| Attendance Metrics   | Attendance Percentage           |
| Recruitment Data     | Hiring Source                   |
| Attrition Data       | Exit Reason                     |
| Training Data        | Training Program & Hours        |




---



**🔄** **Raw Data**

The original dataset was imported from a CSV file and contained workforce information, attendance records, recruitment data, training records, and attrition details.


---


**✅** **Structured & Cleaned Data**

**After Power Query transformation:**

* Removed duplicate records
* Standardized values
* Corrected data types
* Created business-ready datasets
* Optimized for dashboard reporting

---

**📊** **DAX Measures Used**


**Total Employees =**
COUNT(Employee_ID)

**Active Employees =**
CALCULATE(
    COUNT(Employee_ID),
    Employment_Status = "Active"
)

**Average Salary =**
AVERAGE(Salary)

**Average Performance =**
AVERAGE(Performance_Score)

**Attrition Rate % =**
DIVIDE(
    Attrition_Count,
    Total_Employees
) * 100

---


**🖼** **Dashboard Preview**


**HR Analytics Dashboard**

Provides a complete overview of employee metrics, attendance, recruitment performance, and attrition analysis.

<img width="1157" height="655" alt="Screenshot 2026-06-18 125235" src="https://github.com/user-attachments/assets/3ab49b41-4aca-4fe7-98bd-af7078dd9323" />

---


**Training Dashboard**

Provides insights into employee learning and development through training participation analysis.

<img width="1160" height="648" alt="Screenshot 2026-06-18 125254" src="https://github.com/user-attachments/assets/1e06ae52-7feb-43b0-a588-fc98753b7f01" />

---


**⭐** **Project Highlights**


* End-to-End Power BI Project
* HR Analytics Reporting
* KPI Monitoring
* Interactive Dashboard Design
* DAX Calculations
* Data Cleaning using Power Query
* Employee Attrition Analysis
* Recruitment Source Analytics
* Training Effectiveness Analysis
* Executive-Level Reporting

---

**🚀** **Future Enhancements**

* SQL Database Integration
* Real-Time Data Refresh
* Predictive Attrition Analytics
* Machine Learning Models
* Workforce Forecasting
* Mobile Dashboard Version

---

**⚠** **Disclaimer**

This project is developed for educational and portfolio purposes only. The dataset used is sample HR data and does not represent any real organization or employee information.


---

**📜** **License**

This project is licensed under the MIT License.

---


**👨‍💻** **Author**

**Jujare Sai Abhinay**

🎓 B.Com (Computer Applications) 

📧 Email: jsaibhinay53@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/j-sai-abhinay-594822362/

----






