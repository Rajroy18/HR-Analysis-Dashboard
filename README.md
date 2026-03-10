# HR Analytics Dashboard (Power BI)

## Overview

The **HR Analytics Dashboard** is a Power BI report designed to analyze workforce trends, employee attrition, and HR performance metrics. It enables HR teams and business leaders to monitor employee data, identify attrition patterns, and make data-driven workforce decisions.

This dashboard consolidates employee data into interactive visualizations, allowing stakeholders to explore workforce demographics, performance indicators, and attrition insights.

---

# Dashboard Features

## 1. Workforce Overview

Provides a high-level snapshot of the organization’s workforce.

**Typical metrics displayed:**

* Total Employees
* Active Employees
* Attrition Count
* Attrition Rate
* Average Age
* Average Salary
* Average Years at Company

Purpose:

* Quickly assess the health of the workforce
* Track employee turnover

---

## 2. Attrition Analysis

Analyzes employees who left the company.

Key insights include:

* Attrition by Department
* Attrition by Job Role
* Attrition by Gender
* Attrition by Age Group
* Attrition by Education
* Attrition by Salary Band

Purpose:

* Identify patterns causing employee turnover
* Highlight high-risk departments or roles

---

## 3. Demographic Insights

Provides employee demographic distribution.

Common dimensions analyzed:

* Age distribution
* Gender distribution
* Education field
* Marital status
* Job role distribution

Purpose:

* Understand workforce diversity
* Support workforce planning strategies

---

## 4. Department Performance

Displays employee distribution across departments.

Typical visuals include:

* Employees by Department
* Attrition by Department
* Job Role breakdown
* Department attrition rate

Purpose:

* Identify departments with high turnover
* Optimize HR policies

---

## 5. Employee Tenure Analysis

Shows employee experience levels and tenure trends.

Metrics may include:

* Years at Company
* Years in Current Role
* Years Since Last Promotion
* Years with Current Manager

Purpose:

* Understand employee retention patterns
* Identify stagnation in promotions

---

# Visualizations Used

The report contains approximately **15 visuals** on the main dashboard page.

Common Power BI visuals likely used include:

| Visualization    | Purpose                                               |
| ---------------- | ----------------------------------------------------- |
| KPI Cards        | Display key metrics like employee count and attrition |
| Bar Charts       | Compare departments, job roles, and education         |
| Pie/Donut Charts | Show employee distribution                            |
| Stacked Charts   | Attrition by category                                 |
| Slicers          | Filter dashboard by attributes                        |
| Tables           | Display detailed employee metrics                     |

---

# Filters and Slicers

Interactive filters allow users to explore data dynamically.

Possible slicers include:

* Department
* Job Role
* Gender
* Education
* Age Group
* Attrition Status

Purpose:

* Enable customized analysis
* Drill into specific workforce segments

---

# Data Model

The report uses an **embedded Power BI data model**.

Typical HR dataset fields include:

| Column          | Description                |
| --------------- | -------------------------- |
| EmployeeID      | Unique employee identifier |
| Age             | Employee age               |
| Gender          | Male / Female              |
| Department      | Employee department        |
| Job Role        | Specific job title         |
| Education       | Education level            |
| Salary          | Employee compensation      |
| Attrition       | Whether employee left      |
| YearsAtCompany  | Employee tenure            |
| JobSatisfaction | Satisfaction score         |

---

# Key Business Questions Answered

The dashboard helps answer questions such as:

* Which departments have the highest attrition?
* What age groups leave the company most frequently?
* Are employees leaving due to low salary or job satisfaction?
* How does tenure affect attrition?
* Which job roles experience the most turnover?

---

# File Structure

```
HR Analytics.pbix
│
├── DataModel
├── Report
│   └── Layout
├── Metadata
├── Settings
└── Theme Resources
```

---

# Tools Used

* **Microsoft Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Power Query for data transformation**

---

# How to Use the Dashboard

1. Open the `.pbix` file in **Power BI Desktop**
2. Navigate to the **HR Analytics Dashboard page**
3. Use **filters and slicers** to explore employee data
4. Hover over visuals for **detailed tooltips**
5. Drill down into charts for deeper insights

---

# Example Insights From the Dashboard

The report can reveal insights such as:

* Younger employees leaving more frequently
* Higher attrition in certain departments
* Salary ranges correlated with employee retention
* Employees with fewer promotions leaving sooner

---

# Future Improvements

Possible enhancements:

* Predictive attrition modeling
* HR forecasting
* Integration with real HR systems
* Department performance scorecards
* AI insights using Power BI

---

# Use Cases

This dashboard can be used by:

* HR Managers
* Business Leaders
* Workforce Analysts
* Talent Acquisition Teams

---

# License

This project is for **educational and analytical purposes**.
