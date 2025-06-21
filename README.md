#  Data Jobs Salary Intelligence Dashboard

![Dashboard Preview](/Content/Salary%20dashboard%20gif.gif)

## Overview

This project presents a dynamic Excel-based dashboard designed to explore and compare salaries across various data-related job roles. The dashboard enables job seekers, analysts, and HR professionals to make informed decisions based on **job title**, **location**, and **work type**. The dataset and logic were structured to deliver real-time interactivity and clarity.

## 🎯 Objectives

- **Provide insights into salary distributions across roles and geographies**
- **Offer an interactive tool to compare median salaries by job type, country, and work schedule**
- **Utilize advanced Excel formulas and charts to build a professional-grade dashboard**

---

## 🧾 Dataset

The dataset includes real-world data job postings from 2023 and contains:

- Job Titles (short & descriptive)
- Locations (city + country)
- Salary details
- Schedule types (e.g., Full-time, Internship)
- Work-from-home indicators

---
## 📥 How to Use 

1. Download and open the file: [Download the Excel Dashboard](./Data%20Jobs%20Salary%20Dashboard.xlsx)

2. Use the dropdowns on the dashboard to select:
   - Job Title
   - Country
   - Work Schedule
3. Dashboard updates automatically to reflect salary trends

---

## 📁 Project Structure

| Sheet Name           | Purpose                                                              |
| -------------------- | -------------------------------------------------------------------- |
| `Data`               | Raw dataset with job listings, titles, salaries, countries, and more |
| `DASHBOARD`          | Final interactive dashboard for user-facing visualizations           |
| `Data_Validation`    | Backend logic for dropdown inputs and validation                     |
| `job_med_salary`     | Chart data source for job title-based salary visualization           |
| `country_med_salary` | Country-wise median salary calculations for map visualization        |
| `type`               | Median salaries grouped by job schedule type                         |

---

## 📈 Key Features & Excel Skills Demonstrated

### 🔢 Advanced Formulas

- **Array formulas** using `MEDIAN`, `IF`, `SEARCH` for multi-condition filtering
- **Lookup logic** via `XLOOKUP` to retrieve salary stats dynamically
- **Dynamic filtering** using `FILTER`, `SORT`, and `UNIQUE` for table generation

### 📊 Interactive Visualizations

####  Job Titles - Median Salary Bar Chart

![Dashboard Preview](/Content/title%20vs%20median%20gif.gif)

-  **Excel Features:** Horizontal bar chart built using dynamic named ranges powered by `XLOOKUP` and `FILTER`.
-  **Design Choice:** Sorted by descending salary for quick comparative analysis.
-  **Data Source:** Data pulled from `job_med_salary` sheet with dropdown interactivity.
-   **Insights Gained:** This chart allows users to uncover role-based salary patterns and spot outliers — highlighting how job function and specialization can influence compensation, not just seniority.



####  Country-wise Median Salary Map Chart

![Dashboard Preview](/Content/map%20gif.gif)

![Dashboard Preview](/Content/map%202%20gif.gif)

-  **Excel Features:** Map chart plotted from `country_med_salary` sheet, with country names dynamically linked to their median salary for a particular job title.
-  **Design Choice:** Heatmap style with color gradients to indicate salary tiers visually.
-  **Data Representation:** Automatically updates based on selected job title and job type from the dashboard.
-  **Insights Gained:** Offers a regional salary perspective, helping users assess how location impacts pay — while also showing that high-paying regions are not always aligned with role-specific demand.



####  Work Schedule Type - Median Salary Bar Chart

![Dashboard Preview](/Content/type%20bar%20gif.gif)

-  **Excel Features:** Bar chart created from `type` sheet, using formulas like `MEDIAN`, `IF`, and dynamic filtering.
-  **Design Choice:** Emphasizes contrast between Full-time, Part-time, and Internship salaries.
-  **Responsive Dashboard:** Chart updates dynamically when a different schedule type is selected.
-  **Insights Gained:** Encourages comparison between full-time, internship, contractor, temp work and part-time roles, shedding light on how work arrangement and availability affect pay expectations — without assuming a fixed hierarchy.




### ✅ Data Validation

- Restricts user input using dropdowns for:
  - Job Title
  - Country
  - Schedule Type
- Enhances consistency and prevents invalid entries

---

## 📌 Insights Unlocked

- Senior roles and engineering positions tend to offer higher median salaries
- Regional variations are clearly visible
- Internship and part-time roles offer significantly lower compensation but vary by region

---

## 🛠️ Tools Used

- **Microsoft Excel**
- Built-in functions: `XLOOKUP`, `FILTER`, `SORT`, `UNIQUE`, `MEDIAN`, `IF`, `SEARCH`
- Excel charting features: Bar Chart, Map Chart
- Slicers and Validation Lists for interactivity

---


## 📌 Future Improvements

- Integrate Power Query for live data fetching
- Add slicers and pivot charts for advanced filtering
- Convert to web-based dashboard using Power BI / Tableau

---

## 📧 Contact

Made with precision by **Pritish Kumar Singh**  
If you'd like to connect, collaborate, or discuss improvements:

- 📬 Email: [pritishsinghprf@gmail.com](mailto:pritishsinghprf@gmail.com)
- 🧑‍💼 LinkedIn: https://linkedin.com/in/pritish1298

----

