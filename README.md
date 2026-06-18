# Emergency Room Patient Flow Dashboard — Power BI

**Tools:** Power BI Desktop · DAX · Power Query · Star Schema  
**Domain:** Healthcare Operations Analytics  
**Duration:** October 2025

---

## Business Problem

Hospital ER leadership needed real-time visibility into patient flow, admission patterns, and wait times to make data-driven staffing and resource allocation decisions. Key questions:

- How many patients are visiting the ER and when?
- What is the average wait time and admission rate?
- Which departments refer the most admitted patients?
- What demographic groups dominate ER visits?

---

## What I Built

A 3-page interactive Power BI dashboard analyzing **9,216 ER visits** with full drill-down capability by date, demographics, and department.

### Page 1 — ER Overview Dashboard
- KPI Cards: Total Patients, Avg Wait Time, Admission Rate, Avg Satisfaction Score
- Patient distribution by race, gender, and age group
- Admissions vs non-admissions comparison
- Day-of-week patient volume heatmap
- Department referral analysis
- Year and month filters for dynamic reporting

### Page 2 — Date Analysis View
- Date range slicer for trend analysis across specific admission periods
- Time-series view of patient volume and admissions

### Page 3 — Patient-Level Detail
- Searchable and filterable patient list
- Fields: Patient ID, Name, Age, Gender, Race, Wait Time, Admission Status, Admission Date
- Supports drill-down and individual record review

---

## Key Metrics

| KPI | Value |
|---|---|
| Total Patients | 9,216 |
| Avg Wait Time | 35.26 minutes |
| Avg Satisfaction Score | 4.99 / 10 |
| Total Admissions | 4,612 |
| Admission Rate | 50.04% |

---

## Key Insights

- **Sundays and Mondays** show the highest patient volumes — key for staffing optimization
- **~50% of ER visits** result in hospital admission, indicating high severity intake
- The **"None" referral category** is the largest group, suggesting most patients arrive directly without a referral
- Age distribution is relatively **balanced across 20–60**, with slightly higher volume in middle age ranges
- Gender distribution is **nearly even** across the dataset

---

## Data Model

- Star Schema: fact table linked to date and demographic dimension tables
- Power Query: data cleaning, deduplication, and relationship setup
- DAX measures: Total Patients, Avg Wait Time, Total Admissions, Admission Rate %

---

## Dashboard Preview

### ER Overview
![ER Overview](screenshots/dashboard_page1.png)

### Date-Based Analysis
![Date Analysis](screenshots/dashboard_page2.png)

### Patient Detail Page
![Patient List](screenshots/patient_list.png)

---

## How to Use

1. Download the `ER dashboard.pbix` file
2. Open in Power BI Desktop
3. Use the Year, Month, and Date slicers to filter
4. Navigate between pages: Overview → Date Analysis → Patient Detail
