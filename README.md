#  HR Analytics Dashboard | Power BI

##  Project Overview

This project showcases an interactive **HR Analytics Dashboard** developed in **Power BI** to help organizations analyze their workforce and support data-driven HR decisions.

The dashboard provides insights into employee headcount, retention, turnover, organizational structure, and workforce demographics through an intuitive and professional interface.

The project follows Power BI best practices by using a **Star Schema** data model, optimized DAX measures, interactive navigation, synchronized slicers, and dynamic tooltips.

---

##  Project Objectives

- Design a scalable **Star Schema** data model.
- Create HR KPIs using **DAX**.
- Analyze workforce distribution across departments and job levels.
- Monitor employee retention and turnover.
- Explore demographic trends such as age, gender, race, education, and marital status.
- Build a modern, interactive dashboard with a professional user experience.

---

##  Technologies Used

- **Power BI**
- **Power Query**
- **DAX**
- **Star Schema Data Modeling**
- **CSV Files**

---

##  Data Model

The model consists of one central **Fact Table (People Fact)** connected to several dimension tables:

- Department
- Job Level
- Demographics
- Education
- Location
- Marital Status
- Manager Hierarchy
- Termination

This structure improves model performance and simplifies DAX calculations.

---

##  Dashboard Pages

###  Home
- Landing page with navigation buttons
- Project overview
- Interactive page navigation

###  Headcount
- Total Headcount KPI
- Employees by Department and Job Level
- Remote vs On-site distribution
- Employee map by city
- Demographic analysis (Gender, Race, Age, Education, Marital Status)

###  Retention
- Overall Retention KPI
- Retention by Department and Job Level
- Starting vs Ending Headcount
- Interactive field parameters

###  Turnover
- Overall Turnover KPI
- Turnover trend over time
- Employee termination details
- Analysis by Department, Job Level, Location, Termination Type, and Reason

---

##  Dashboard Features

- Interactive slicer panel with bookmarks
- Dynamic tooltips
- Synchronized filters across pages
- Professional UI and navigation
- Responsive layout
- Clean color palette and modern design

---

##  Project Structure

```
HR-Analytics-Dashboard/
│
├── HR_Analytics.pbix
├── Dataset/
│   ├── People Data.csv
│   └── Employment History.csv
├── Images/
│   ├── Home.png
│   ├── Headcount.png
│   ├── Retention.png
│   └── Turnover.png
└── README.md
```


##  Skills Demonstrated

- Data Modeling
- Power Query (ETL)
- DAX Measures
- KPI Development
- Dashboard Design
- Data Visualization
- HR Analytics
- Business Intelligence

---

##  Author

**Chaimaa**

Junior Data Analyst

**Tools:** Power BI • SQL • Python • Excel • Tableau
