# 360 Education Business Analytics – Power BI Dashboard

## 📊 Project Overview

**360 Education Business Analytics** is a Power BI business intelligence project designed to provide an executive-level view of an education business.

The dashboard brings together information related to **students, admissions, courses, branches, fees, leads, calls, marketing, employees, and placements**. It converts operational data into interactive business insights that can support performance monitoring and decision-making.

The main report page is an **Executive Overview Dashboard** with KPI cards and visual analysis for revenue, students, admissions, outstanding amounts, branch performance, course-wise student distribution, placement status, and admission trends.

---

## 🎯 Objectives

- Monitor overall education-business performance.
- Track total revenue and outstanding/remaining amounts.
- Understand student and admission volumes.
- Compare performance across branches.
- Analyze student distribution across courses.
- Monitor placement outcomes.
- Analyze admission trends over time.
- Organize reusable DAX measures for different business areas.
- Build an interactive and professional Power BI dashboard for management-level analysis.

---

## 🖥️ Dashboard Highlights

The Executive Overview Dashboard includes:

### KPI Cards
- **Total Revenue**
- **Total Students**
- **Total Admissions**
- **Total Remaining Amount**

### Revenue Analysis
- Monthly Revenue Trend
- Total Revenue by Branch

### Student & Course Analysis
- Total Students by Course
- Course-wise student distribution
- Placement status analysis

### Admission Analysis
- Total Admission by Year/Month
- Admission trend over time

### Interactive Analysis
The report uses Power BI visuals and filters to make the dashboard interactive and allow users to explore the underlying business data.

---

## 🗂️ Data Model / Semantic Model

The Power BI project contains business tables and dimension tables representing major areas of the education business.

### Main Tables

| Table | Purpose |
|---|---|
| `admissions` | Admission-related business data |
| `branches_dim` | Branch information |
| `calls` | Call-related data |
| `courses_dim` | Course information |
| `employees_dim` | Employee information |
| `fees` | Fee and payment-related data |
| `leads` | Lead-related business data |
| `marketing` | Marketing-related data |
| `placements` | Placement-related data |
| `students_dim` | Student information |
| `DateTable` | Date-based analysis |

The model also contains dedicated measure tables/folders for different analytical areas, including:

- `lead measures`
- `call measures`
- `marketing measures`
- `placement measures`
- `Revenue measures`
- `student measures`

These measures support the dashboard's KPI and analytical visuals.

---

## 📈 Key Business Questions

The dashboard can be used to answer questions such as:

1. What is the total revenue generated?
2. How many students are present in the education business?
3. How many admissions have been completed?
4. What is the remaining fee amount?
5. Which branch contributes more revenue?
6. How are students distributed across different courses?
7. How many students are placed or not placed?
8. How does admission volume change over time?
9. What business areas require further attention?
10. How can management use the available data for better decision-making?

---

## 🧮 Measures & DAX Organization

The project uses separate measure groups to keep calculations organized.

### Revenue Measures
Used for revenue-related KPIs and visual analysis.

### Student Measures
Used for student counts and student-related analysis.

### Lead Measures
Used for lead/business-development analysis.

### Call Measures
Used for call-related analysis.

### Marketing Measures
Used for marketing performance analysis.

### Placement Measures
Used for placement-related analysis.

This structure helps keep the semantic model organized and makes the report easier to maintain.

---

## 🎨 Report Theme & Visual Design

The report uses a Power BI theme named **CY26SU05**.

The theme defines:

- Report color palette
- Typography
- Visual formatting
- Chart behavior
- Card formatting
- Slicer formatting
- Page background
- Borders and outlines
- Visual responsiveness

The theme includes a blue, orange, purple, pink, green, and related extended color palette. The report also uses **DIN** and **Segoe UI** font families for different text classes.

The report configuration enables features such as enhanced tooltips, responsive visuals, interactive filtering, and summarized data export.

---

## 🛠️ Power BI Project Structure

This project is stored using the **Power BI Project (`.pbip`)** format.

A typical project structure is organized around the report and semantic model:

```text
360-Education-Business-Analytics/
│
├── Report/
│   ├── definition/
│   │   ├── report.json
│   │   ├── version.json
│   │   └── StaticResources/
│   │       └── CY26SU05.json
│   │
│   └── ...
│
├── SemanticModel/
│   ├── definition/
│   │   ├── expressions/
│   │   ├── model/
│   │   └── ...
│   │
│   └── ...
│
├── Power BI Project.pbip
└── README.md
```

> The exact generated folder/file names can vary depending on the Power BI Desktop version and how the project is saved.

---

## ⚙️ Technologies Used

- **Microsoft Power BI Desktop**
- **Power BI Project (`.pbip`)**
- **DAX**
- **Power BI Semantic Model**
- **Power BI Report Definition**
- **Power BI Theme / Static Resources**

---

## 🔍 Power BI Development Concepts Demonstrated

This project demonstrates practical knowledge of:

- Data modeling
- Dimension and business tables
- Semantic model organization
- DAX measures
- KPI development
- Time-based analysis
- Revenue analysis
- Branch analysis
- Course analysis
- Student analytics
- Placement analytics
- Interactive slicers and filters
- Power BI report formatting
- Custom report themes
- Power BI Project structure

---

## 📊 Dashboard Preview

### Executive Overview

The dashboard contains an executive-level summary with KPI cards, revenue trends, branch-wise revenue analysis, and other business visuals.

### Course & Placement Analysis

The report includes course-wise student distribution, placement-status analysis, and admission trends over time.

---

## 🚀 How to Open the Project

1. Install **Power BI Desktop**.
2. Download or clone this repository.
3. Locate the `.pbip` Power BI Project file.
4. Open the `.pbip` file using Power BI Desktop.
5. Review the semantic model and report pages.
6. Use the available slicers, filters, and visuals to explore the dashboard.

---

## 📌 Project Purpose

This project is created as a **business analytics / portfolio project** to demonstrate how Power BI can transform education-business data into an interactive executive dashboard.

It focuses on combining multiple business areas into one analytical view rather than presenting raw data alone.

---

## 👩‍💻 Author

**Rucha**

This project is part of a data analytics portfolio demonstrating practical skills in Power BI, DAX, data modeling, and business intelligence.

---

## ⭐ Key Takeaway

**360 Education Business Analytics** provides a centralized analytical view of an education business, helping management understand revenue, students, admissions, branches, courses, fees, leads, marketing, calls, and placements through interactive Power BI reporting.

