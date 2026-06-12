[PBI.Emp_Attri_Readme.md](https://github.com/user-attachments/files/28883964/PBI.Emp_Attri_Readme.md)
# 📊 Employee Attrition Analysis — Power BI Report

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

https://github.com/user-attachments/assets/0e59d034-92c6-46ce-a6eb-ecadcaad5dbe

## 📌 What This Project Does

This Power BI report analyses **employee attrition patterns** across an organisation — identifying *who* is leaving, *why* they may be leaving, and *which segments* are most at risk. It is designed to help HR teams and business leaders make data-informed decisions around employee retention.

The report is built across **two interactive pages**:

### Page 1 — Main Dashboard
A high-level attrition overview with dynamic filtering and visual breakdowns across key dimensions:

| Visual | Insight |
|---|---|
| **Attrition Rate KPI Card** | Overall attrition rate at a glance |
| **Attrition Rate by Salary** | Identifies if lower salary bands have higher attrition |
| **Attrition Rate by Age** | Highlights age groups most prone to leaving |
| **Attrition by Marital Status** | Donut chart showing attrition split across marital categories |
| **Attrition by Project Count** | Bar chart revealing workload's impact on attrition |
| **Attrition by Distance from Home** | Line chart correlating commute distance with attrition |
| **Scrolling Ticker** | Real-time scrolling text visual for key highlights |

**Slicers / Filters available:**
- Department
- Job Role
- Relationship with Manager
- Gender
- Salary Range
- Age

---

### Page 2 — Employee Details
A drill-down page for individual employee lookup. Enter an **Employee ID** to retrieve:

- Salary, Department, Gender
- Total Experience & Experience in Current Role
- Job Role & Marital Status
- Attrition Status (Active / Left)

---

## 💡 Why This Project Is Useful

Employee attrition is one of the most costly and underanalysed HR challenges. This report enables:

- **HR teams** to identify high-risk segments before attrition happens
- **Department heads** to spot patterns tied to workload, role, or management
- **Business leaders** to quantify the impact of salary, distance, and tenure on retention
- **Data practitioners** to see a structured example of DAX measures, slicers, and KPI design in Power BI

---

## 🛠️ Technical Stack

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Report building, layout, and publishing |
| **DAX** | Custom measures — Attrition Rate, Attribute Rate by Salary, Attribute Rate by Age, Employee-level lookups |
| **Power Query (ETL)** | Data transformation and preparation |
| **Custom Visual** | ScrollingTextVisual for dynamic headline display |

**Key DAX Measures built:**
- `Attribute Rate` — Core attrition % across the full dataset
- `Attribute Rate Salary` — Attrition rate filtered to selected salary band
- `Attribute Rate Age` — Attrition rate filtered to selected age group
- `Curr Date` — Dynamic current date display
- Employee-level measures: `esal`, `Emp_Department`, `Emp_Gender`, `Emp_Job Role`, `Emp_Total Exp`, `Exp_current_role`, `Maritial_Status`, `Emp_Attrition`

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) — version 2024 or later recommended

### Steps to Open the Report

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/your-username/emp-attrition-powerbi.git
   ```

2. **Open the file** `Emp_Attrition_Rep_Project.pbix` in Power BI Desktop.

3. **Refresh the data** if prompted (you may need to update the data source path to your local environment).

4. **Interact with the report** using the slicers on Page 1, or navigate to Page 2 and enter an Employee ID to look up individual records.

> **Note:** If the custom scrolling text visual prompts a security warning, click *Enable* to load it from the trusted marketplace source.

---

## 📂 Repository Structure

```
📁 emp-attrition-powerbi/
│
├── Emp_Attrition_Rep_Project.pbix   # Main Power BI report file
└── README.md                        # Project documentation
```

---

## 🙋 Getting Help

If you run into issues or have questions:

- Open an [Issue](https://github.com/your-username/emp-attrition-powerbi/issues) on this repository
- Reach out via [LinkedIn](https://linkedin.com/in/your-profile)
- For Power BI-specific questions, the [Microsoft Power BI Community](https://community.powerbi.com/) is an excellent resource

---

## 👤 Maintainer

**[Chitra]**
Data Analyst | Power BI · SQL · Python

- 🔗 [LinkedIn](https://www.linkedin.com/in/mchitra-dataanalyst/)
- 💻 [GitHub](https://github.com/Chitra246)
- 📧 mchitra210100@gmail.com

This project was built as part of a 6-month Data Analytics Internship at **Infotech Pvt Ltd (Jan–Jun 2026)**, applying end-to-end analytics in a live IT environment.

---

## 📄 License

This project is open for reference and learning purposes. Please credit the author if you use or adapt any part of this work.

---

*Built with Power BI Desktop · DAX · Power Query*
