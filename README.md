# 🏥 Hospital Emergency Room Analysis Dashboard

An end-to-end **Power BI** project that analyzes Hospital Emergency Room (ER) operations — patient volume, wait times, satisfaction scores, and department referrals — to help hospital stakeholders make data-driven decisions on staffing, resource allocation, and service quality.

---

## 📌 Project Overview

Emergency rooms generate huge volumes of patient-level data every day, but without proper visualization it's hard to spot bottlenecks, seasonal trends, or service gaps. This project transforms raw ER visit data into a **4-page interactive Power BI dashboard** that tracks key performance indicators (KPIs) and surfaces actionable insights for hospital management.

## 🎯 Business Requirements

The goal was to build a dashboard that enables stakeholders to track, analyze, and act on ER performance data. Core KPIs required:

- **Number of Patients** – total daily ER visits, with a daily trend (area sparkline) to spot peak days/seasonal patterns
- **Average Wait Time** – average time before a patient is attended to, tracked daily to flag operational bottlenecks
- **Patient Satisfaction Score** – daily average satisfaction to evaluate service quality and correlate dips with operational issues
- **Patients Referred** – daily count of patients referred to specific departments, to identify departments needing more resources

## 📊 Dashboard Pages

The report is built as **4 dashboards**:

| # | Dashboard | Purpose |
|---|-----------|---------|
| 1 | **Monthly View** | Month-by-month trends: admission status, age distribution (10-year bands), department referrals, % seen within 30 minutes, gender split, racial demographics, and volume by day/hour |
| 2 | **Consolidated View** | Same core metrics as the Monthly View, aggregated over a fully customizable date range for broader trend analysis |
| 3 | **Patient Details** | A granular, filterable grid with Patient ID, full name, gender, age, admission date, race, wait time, department referral, and admission status |
| 4 | **Key Takeaways** | A summary page consolidating findings from all dashboards — patterns, anomalies, and actionable recommendations for optimizing ER operations |

## 🛠️ Project Workflow

1. Requirement Gathering / Business Requirements
2. Data Walkthrough
3. Data Connection
4. Data Cleaning / Quality Check
5. Data Modeling
6. Data Processing
7. DAX Calculations
8. Dashboard Lay-outing
9. Charts Development & Formatting
10. Dashboard / Report Development
11. Insights Generation

## 🗂️ Dataset

**File:** `Hospital_ER_Data.csv`
**Size:** ~9,200 patient records | 12 columns

| Column | Description |
|---|---|
| Patient Id | Unique patient identifier |
| Patient Admission Date | Date & time of ER admission |
| Patient First Initial / Last Name | Patient name fields |
| Patient Gender | M / F / NC |
| Patient Age | Patient age (1–79) |
| Patient Race | Patient's reported race/ethnicity |
| Department Referral | Department the patient was referred to (e.g., General Practice, Orthopedics, Cardiology, Neurology, Gastroenterology, Renal, Physiotherapy) |
| Patient Admission Flag | Whether the patient was admitted (True/False) |
| Patient Satisfaction Score | Patient-reported satisfaction (0–10) |
| Patient Waittime | Wait time in minutes |
| Patients CM | Case management flag |

> Data covers ER visits from **April 2023 to October 2024**.

## 🧰 Tools & Technologies

- **Power BI Desktop** – data modeling, DAX measures, and dashboard visualization
- **DAX** – calculated measures and KPIs
- **Power Query** – data cleaning and transformation
- **PowerPoint** – project documentation (requirements & methodology walkthrough)

## 📁 Repository Contents

```
├── Hospital_Emergency_Data_Dashboard.pbix     # Power BI dashboard file
├── Hospital_ER_Data.csv                       # Source dataset
├── Hopital_Emergency_Room_PPT.pptx            # Project documentation & requirements deck
└── README.md
```

## 🚀 How to Use

1. Clone/download this repository.
2. Open `Hospital_Emergency_Data_Dashboard.pbix` in **Power BI Desktop** (free download from Microsoft).
3. If prompted, update the data source path to point to `Hospital_ER_Data.csv` on your local machine.
4. Explore the four report pages: Monthly View, Consolidated View, Patient Details, and Key Takeaways.

## 💡 Key Insights

- Wait times, admissions, and satisfaction scores are tracked daily to catch operational issues early.
- Department referral analysis highlights which departments (e.g., General Practice, Orthopedics) receive the highest patient volume and may need more resources.
- Age and demographic breakdowns support more equitable and targeted resource planning.
- The % of patients seen within 30 minutes serves as a core timeliness/service-level KPI.

## 📬 Contact

Feel free to reach out if you have questions or suggestions about this project!

---
*This project was built as a Power BI portfolio project to demonstrate end-to-end dashboard development — from business requirement gathering through data modeling, DAX, and insight generation.*
