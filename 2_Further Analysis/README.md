# 📊 Data Job Market Analysis Using Excel

## Overview

This project provides a comprehensive analysis of the data job market using a real-world dataset of data-related roles from 2023. The objective was to explore the correlation between skills and salary, regional variations in compensation, and the most in-demand technical skills in the industry.

The analysis was conducted entirely in Microsoft Excel using advanced features such as Power Query, Power Pivot, DAX, PivotTables, and PivotCharts. The goal is to guide data professionals on which skills to focus on and how those skills relate to job opportunities and compensation.

---

## 📌 Key Questions Explored

- Do more skills lead to higher salaries?
- What are the most in-demand skills in the data industry?
- How do salaries vary across the top 10 skills?

---

## 🛠️ Tools & Techniques Used

The following Excel features were used to conduct the analysis:

- **Power Query** (ETL operations)
- **PivotTables** and **PivotCharts**
- **Power Pivot** and **Data Modeling**
- **DAX** (Data Analysis Expressions)

---

## 🔍 1. Do More Skills Correlate with Better Pay?

### Approach

- Extracted and cleaned the job data using Power Query.
- Created separate queries for job listings and job-related skills.

![Dashboard Preview](/assets/Data%20jobs%20all%20power%20query.png)

![Dashboard Preview](/assets/Data%20job%20skills%20power%20query.png)
- Built a data model connecting job roles and their associated skills.

![Dashboard Preview](/assets/Data%20model%20diagram.png)
- Analyzed the correlation between the number of listed skills and average salary.


![Dashboard Preview](/assets/Salary-skills%20window.png)
### Insights

- A positive correlation exists: roles requiring more technical skills (such as **Senior Data Engineer**, **Data Scientist**) tend to offer significantly higher compensation.
- Generalist roles (like **Business Analyst**) with fewer skill requirements are typically associated with lower salary ranges.

### Interpretation

This finding suggests that cultivating a broader technical skill set can enhance earning potential in the data domain.



---

## 🔧 2. Most In-Demand Skills in Data Roles

### Approach

- Merged job and skills data using Power Pivot's data modeling.
- Built relational models between `job_id` in both datasets.
- Analyzed the frequency and distribution of specific skills across job postings.


![Dashboard Preview](/assets/skill%20job%20analysis.gif)
### Insights

- **SQL** , **Excel** and **Python** were the most frequently requested skills, confirming their foundational importance in data work.
- Cloud platforms such as **AWS** and **Azure** are increasingly prevalent, reflecting industry trends towards cloud-native solutions.

### Interpretation

Professionals should prioritize core data skills (**SQL**, **Excel** and **Python**) while also gaining exposure to cloud services for enhanced employability.

---

## 💼 3. Salary Comparison for Top 10 Skills

### Approach

- Created combo PivotCharts to visualize salary trends and skill frequency.
![Dashboard Preview](/assets/combo%20pivot%20chart.png)
- Plotted median salary against skill likelihood for the top 10 technologies.
![Dashboard Preview](/assets/skill%20likelihood%20x%20median%20salary.png)

### Insights

- **Python**, **SQL**, and **Oracle** are associated with higher median compensation.
- Office tools like **PowerPoint** and **Word**, while occasionally listed, do not contribute significantly to salary increases.

### Interpretation

Investing in high-value technical skills is key to securing competitive salaries in the data industry.

---

## 📌 Conclusion

This project offers actionable insights into the skills and roles that define today's data job market. The findings highlight the tangible value of technical proficiency and the growing demand for cloud and programming expertise.

By leveraging Excel’s advanced analytical tools, this analysis demonstrates how non-code platforms can still yield rich, impactful data insights—making it accessible for both aspiring data professionals and business stakeholders.

---

## 📫 Contact


**Pritish Kumar Singh**  
If you'd like to connect, collaborate, or discuss improvements:
- 📧 Email: [pritishsinghprf@gmail.com](mailto:pritishsinghprf@gmail.com)
- 🔗 GitHub: [https://github.com/PritishAnalyst](https://github.com/PritishAnalyst)  
- 🧑‍💼 LinkedIn: https://linkedin.com/in/pritish1298
