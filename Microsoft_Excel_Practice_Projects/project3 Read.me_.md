# 📊 Data Science Job Market Analysis (Excel Project)

## 📘 Overview
This Excel-based project explores the **2023 Data Science job market**, analyzing salary trends, skills demand, and regional differences.  
By leveraging **Power Query, Power Pivot, DAX, PivotTables, and PivotCharts**, it provides answers to four major analytical questions:

1. Do more skills get you better pay?  
2. What’s the salary for data jobs in different regions?  
3. What are the top skills of data professionals?  
4. What’s the pay for the top 10 skills?

---

## ⚙️ Tools & Features Used
- **Power Query** – Extract, transform, and load (ETL) raw data.  


- **Power Pivot & Data Model** – Build relational models and connect tables via `job_id`.  
- **DAX (Data Analysis Expressions)** – Create calculated measures such as `MEDIAN()` and `CALCULATE()`.  
- **PivotTables & PivotCharts** – Summarize and visualize data dynamically.  
- **Combo Charts** – Display salary vs. skill likelihood on dual axes.  


![]()
---

## 🧭 Project Workflow

1. **Extract & Transform** – Imported `data_salary_all.xlsx` using Power Query, cleaned and formatted columns, trimmed spaces, and removed irrelevant fields. 

![Powerquery_interface.png](/Microsoft_Excel_Practice_Projects/Resources/Powerquery_interface.png)


2. **Data Modeling** – Related `data_jobs_all` and `data_job_skills` tables via `job_id` in Power Pivot.

![Data_Modelling](/Microsoft_Excel_Practice_Projects/Resources/relationship.png)
3. **Measure Creation (DAX)** – Computed median salaries and scoped measures (e.g., by region).  
4. **Visualization** – Created PivotTables and combo charts to visualize skill impact and regional pay differences.  
5. **Interpretation** – Derived insights to identify market patterns and actionable recommendations.  

---

## 💡 Key Insights

- More (and more specialized) skills = higher median salaries.  
- **Senior Data Engineer** and **Data Scientist** roles offer the highest pay.  
- **Python** and **SQL** dominate the top skill rankings; **AWS** and **Azure** show growing demand.  
- **US-based roles** lead global pay averages, especially in advanced technical jobs.  
- Basic skills (e.g., Word, PowerPoint) show minimal correlation with pay.  

---

## 🧠 Recommendations

| Audience | Recommendation |
|-----------|----------------|
| **Job Seekers** | Focus on high-value technical skills: Python, SQL, cloud platforms (AWS, Azure). |
| **Employers** | Benchmark salaries by region and demand to attract top talent. |
| **Educators** | Build curricula emphasizing Python, SQL, and modern cloud data tools. |

---

## 🎓 Skills Gained

- End-to-end Excel BI workflow: **Power Query → Power Pivot → DAX → PivotCharts**  
- Building relational data models in Excel  
- Creating dynamic measures and insights using DAX  
- Designing professional, interactive dashboards  
- Turning job market data into actionable career insights  

---

## 📊 Key Visuals & Metrics
- Combo chart showing median salary vs. skill likelihood  
- Pivot chart comparing regional salary distribution  
- Data model relationships (job_id linkage)  
- Median salary calculations by title and region 


---

## 🏁 Conclusion
This Excel project demonstrates how to perform full-scale business intelligence within Excel — from **data cleaning to interactive dashboards**.  
It reveals that **diverse technical skills (Python, SQL, Cloud)** significantly boost earning potential, especially in advanced data roles like Data Scientist and Data Engineer.  

---


