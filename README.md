# 📊 HR Analytics & Employee Attrition Dashboard

### Interactive Power BI Dashboard for Workforce Analytics, Employee Attrition & HR Decision Support

<p align="center">

<img src="https://img.shields.io/badge/Power%20BI-Business%20Intelligence-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
<img src="https://img.shields.io/badge/SQL-Data%20Analysis-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL">
<img src="https://img.shields.io/badge/Power%20Query-ETL-5E5E5E?style=for-the-badge" alt="Power Query">
<img src="https://img.shields.io/badge/DAX-Analytics-1F4E79?style=for-the-badge" alt="DAX">
<img src="https://img.shields.io/badge/Excel%20%2F%20CSV-Data%20Source-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="CSV">

</p>

---

## 📌 Overview

This project develops an **HR Analytics Dashboard in Microsoft Power BI** to analyze employee characteristics and identify patterns associated with **employee attrition**.

The analysis focuses on workforce attributes including:

* Age
* Gender
* Education
* Salary
* Job role
* Years at the company
* Employee attrition

The project combines data preparation and analysis with interactive Power BI visualization to transform employee-level data into an HR decision-support dashboard.

The repository contains the Power BI report and the underlying HR analytics dataset.

---

# 🎯 Project Objective

The primary objective is to provide an interactive analytical view of employee attrition and workforce characteristics.

The dashboard is designed to help HR stakeholders investigate questions such as:

* Which employee groups experience higher attrition?
* How does attrition vary across age groups?
* Are there differences in attrition by gender?
* How does salary relate to employee attrition?
* Which job roles show different attrition patterns?
* How does employee tenure relate to attrition?
* What demographic and employment characteristics are associated with workforce turnover?

---

# 🧩 Business Problem

Employee attrition can create significant organizational challenges through:

* Recruitment costs
* Replacement and onboarding effort
* Loss of organizational knowledge
* Workforce instability
* Productivity disruption

Understanding the characteristics associated with employee turnover can help HR teams identify patterns and support more informed workforce planning.

This dashboard transforms employee data into interactive visual analysis that can be used to explore attrition patterns from multiple perspectives.

---

# 🔄 Analytics Workflow

```text
                    Employee Data
                          │
                          ▼
                  Data Preparation
                          │
                          ▼
                 SQL Data Analysis
                          │
                          ▼
              Cleaned / Transformed Data
                          │
                          ▼
                    Power BI
                          │
              ┌───────────┴───────────┐
              │                       │
              ▼                       ▼
        Data Modeling            Visualization
              │                       │
              └───────────┬───────────┘
                          ▼
                 Interactive HR
                  Analytics
                          │
                          ▼
                 Attrition Insights
```

The original project description states that SQL was used for employee-data processing, cleaning, transformation, and analysis before integrating the resulting data with Power BI.

---

# 📊 Analytical Dimensions

The project analyzes employee attrition across several workforce dimensions.

## 👤 Demographics

The dashboard considers:

* Age
* Gender
* Education

These dimensions allow employee attrition patterns to be explored across different demographic groups.

---

## 💼 Job & Employment

The analysis includes:

* Job role
* Years at the company

These variables help investigate whether employee position and tenure are associated with workforce turnover.

---

## 💰 Compensation

Salary is included as an analytical factor to investigate potential relationships between compensation levels and employee attrition.

---

# 📈 Attrition Analysis

The central analytical focus is **employee attrition**.

The dashboard enables HR-related analysis of attrition patterns across:

```text
                     Attrition
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
      Age             Gender           Education
        │                │                │
        └────────────────┼────────────────┘
                         │
              ┌──────────┴──────────┐
              │                     │
              ▼                     ▼
          Job Role               Salary
              │                     │
              └──────────┬──────────┘
                         ▼
                  Years at Company
```

This multidimensional approach allows workforce turnover to be investigated rather than treated as a single aggregate metric.

---

# 🧹 Data Preparation

The project description specifies a data preparation workflow involving:

1. Employee data extraction.
2. Data cleaning.
3. Data transformation.
4. SQL-based analysis.
5. Integration with Power BI.
6. Interactive visualization.

The objective of these steps is to prepare employee data for analytical reporting and dashboard development.

> **Repository note:** The current GitHub repository contains `HR_Analytics.csv` and the Power BI report but does not include the SQL scripts or database used in the described SQL workflow.

---

# 🧠 Business Intelligence Approach

The project follows a standard BI workflow:

```text
Raw Data
   │
   ▼
Data Cleaning
   │
   ▼
Data Transformation
   │
   ▼
Analytical Modeling
   │
   ▼
Power BI Visualization
   │
   ▼
Interactive Exploration
   │
   ▼
HR Decision Support
```

The dashboard converts structured employee information into an interactive reporting environment for workforce and attrition analysis.

---

# 🖥️ Power BI Dashboard

The main deliverable is:

```text
HR Analytics Dashboard.pbix
```

The repository includes the Power BI report together with the source CSV dataset.

The `.pbix` file contains the Power BI dashboard/report used for the analysis.

### Dashboard Focus

The report is centered around:

* Employee attrition
* Workforce demographics
* Salary
* Job roles
* Education
* Employee tenure

---

# 🔎 Key Analytical Questions

The dashboard is designed to support questions such as:

### Demographics

* How does attrition vary by age?
* Are there differences in attrition by gender?
* How does education relate to employee turnover?

### Employment

* Which job roles show higher attrition?
* How does tenure relate to attrition?

### Compensation

* Is employee attrition associated with salary levels?
* Do different workforce segments demonstrate different turnover patterns?

---

# 💡 Business Value

The dashboard provides a centralized analytical view that can help HR stakeholders:

* Identify workforce segments with higher attrition.
* Explore demographic patterns.
* Analyze job-role-specific turnover.
* Examine compensation-related patterns.
* Investigate the relationship between tenure and attrition.
* Support data-driven workforce planning.

The objective is not to replace HR decision-making, but to provide a structured analytical layer for exploring workforce patterns.

---

# 🛠️ Technology Stack

| Technology             | Purpose                                                 |
| ---------------------- | ------------------------------------------------------- |
| **Microsoft Power BI** | Interactive dashboard and business intelligence         |
| **SQL**                | Data extraction, cleaning, transformation, and analysis |
| **Power Query**        | Data preparation within the Power BI workflow           |
| **DAX**                | Analytical calculations and measures                    |
| **CSV**                | Source employee dataset                                 |
| **Data Visualization** | Workforce and attrition reporting                       |

### Primary Skills Demonstrated

* Data analysis
* Business intelligence
* Data cleaning
* Data transformation
* SQL analysis
* Power BI dashboard development
* HR analytics
* Data visualization
* KPI-oriented reporting
* Business problem analysis

> **Technical accuracy note:** SQL is part of the project's documented workflow, but SQL scripts are not currently stored in the GitHub repository. Similarly, the current repository page does not expose the internal PBIX model/measure definitions, so specific DAX measures should only be documented if you add them to the repository.

---

# 📂 Repository Structure

```text
HR-Analytics-Dashboard-Power-BI-Project/
│
├── HR Analytics Dashboard.pbix
├── HR_Analytics.csv
└── README.md
```

The current repository contains these three primary project artifacts.

### `HR Analytics Dashboard.pbix`

Power BI report containing the HR analytics dashboard.

### `HR_Analytics.csv`

Underlying employee dataset used for the analysis.

### `README.md`

Project documentation and analytical overview.

---

# 🚀 Getting Started

## Prerequisites

To explore or modify the dashboard, install:

* Microsoft Power BI Desktop
* Access to the included CSV dataset

If reproducing the documented SQL workflow, a compatible SQL environment is also required.

---

## 1. Clone the Repository

```bash
git clone https://github.com/Vinrach/HR-Analytics-Dashboard-Power-BI-Project.git

cd HR-Analytics-Dashboard-Power-BI-Project
```

---

## 2. Open the Power BI Report

Open:

```text
HR Analytics Dashboard.pbix
```

using **Microsoft Power BI Desktop**.

---

## 3. Connect the Dataset

The included:

```text
HR_Analytics.csv
```

provides the underlying employee data.

If the report requires a refreshed local path, update the dataset source in Power BI accordingly.

---

# 🔁 Reproducing the Analysis

A complete reproduction workflow would follow:

```text
HR_Analytics.csv
       │
       ▼
SQL Environment
       │
       ├── Data Cleaning
       ├── Data Transformation
       └── Data Analysis
       │
       ▼
Prepared Dataset
       │
       ▼
Power BI
       │
       ├── Data Model
       ├── Measures
       ├── Visualizations
       └── Dashboard
       │
       ▼
HR Attrition Analysis
```

The existing project description identifies SQL-based processing and Power BI integration as the intended workflow.

---

# 📊 Recommended Dashboard Sections

The analytical structure of the project can be organized around:

```text
HR Analytics
│
├── Workforce Overview
│
├── Attrition Analysis
│
├── Demographic Analysis
│   ├── Age
│   ├── Gender
│   └── Education
│
├── Job Analysis
│   └── Job Role
│
├── Compensation Analysis
│   └── Salary
│
└── Tenure Analysis
    └── Years at Company
```

This structure provides a clear progression from workforce overview to detailed attrition analysis.

---

# 📌 Important Metrics

For an HR analytics implementation, useful measures include:

* Total Employees
* Total Attrition
* Attrition Rate
* Active Employees
* Average Salary
* Average Tenure
* Employees by Job Role
* Attrition by Job Role
* Attrition by Age
* Attrition by Gender
* Attrition by Education
* Attrition by Salary Range

> These are recommended analytical metrics for the dashboard structure. They should only be described as implemented metrics if they are actually present in the `.pbix` file.

---

# 🔮 Future Improvements

## Data Engineering

* Add the original SQL scripts to the repository.
* Add database schema documentation.
* Separate raw and transformed datasets.
* Add reproducible ETL steps.
* Introduce data-quality validation.

## Power BI

* Document the semantic data model.
* Add a dedicated KPI overview page.
* Add drill-through analysis.
* Add tooltip pages.
* Add dynamic filtering.
* Add bookmarks for executive views.
* Document DAX measures.
* Add a data dictionary.

## HR Analytics

* Attrition prediction using machine learning.
* Employee retention risk scoring.
* Cohort-based tenure analysis.
* Salary-band analysis.
* Department-level workforce analysis.
* Hiring and retention trend analysis.
* Employee segmentation.

## Reporting & Deployment

* Publish the report to Power BI Service.
* Configure scheduled data refresh.
* Implement row-level security where appropriate.
* Add automated data-refresh monitoring.
* Create an executive summary page.

---

# ⚠️ Data Privacy

HR analytics can involve sensitive employee information.

Any production implementation should ensure:

* Appropriate access controls.
* Data anonymization where necessary.
* Secure storage.
* Restricted report sharing.
* Role-based access.
* Compliance with applicable privacy regulations.

The repository should contain only appropriately anonymized or publicly distributable data.

---

# 🎓 Project Context

This project demonstrates the application of **Business Intelligence and Data Analytics** techniques to a human-resources use case.

The workflow combines:

```text
SQL
  +
Data Preparation
  +
Power BI
  +
Data Visualization
  +
HR Analytics
```

The primary business objective is to analyze employee characteristics and their relationship with attrition, enabling more informed workforce analysis and decision support.

---

# 🧠 Skills Demonstrated

### Data Analytics

* Data cleaning
* Data transformation
* Exploratory analysis
* Workforce analytics
* Attrition analysis

### Business Intelligence

* Power BI
* Interactive dashboards
* KPI reporting
* Data visualization
* Business-oriented analytics

### Data Management

* SQL
* CSV data processing
* Data preparation
* Analytical data modeling

### Business Domain

* Human Resources Analytics
* Employee Attrition
* Workforce Planning
* Employee Demographics
* Compensation Analysis

---

# 📚 Project Resources

### GitHub Repository

**[HR Analytics Dashboard — GitHub](https://github.com/Vinrach/HR-Analytics-Dashboard-Power-BI-Project)**

### Power BI Report

The `.pbix` report is available directly in this repository:

**`HR Analytics Dashboard.pbix`**

---

# 👨‍💻 Author

**Vinrach**

Master's Degree / Data Analytics Project

GitHub: **[@Vinrach](https://github.com/Vinrach)**

---

<div align="center">

### Data Analytics • Business Intelligence • Power BI • SQL • HR Analytics

**Turning Workforce Data into Actionable HR Insights**

</div>

![image](https://github.com/user-attachments/assets/dee34da2-3547-4e88-9cce-622ecc2d7f92)

