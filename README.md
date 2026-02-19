# Emergency Room Patient Flow Dashboard

## Project Overview

This Power BI dashboard provides a comprehensive analysis of Emergency Room (ER) patient flow, focusing on patient demographics, admission patterns, wait times, and operational performance metrics.

The dashboard enables hospital administrators and ER managers to monitor patient volume, identify bottlenecks, optimize staffing, and improve patient experience.

---

## Business Objectives

The dashboard answers the following key questions:

- How many patients visited the ER during the selected period?
- What is the average wait time and satisfaction score?
- What percentage of patients were admitted?
- Which patient demographics dominate ER visits?
- Which departments refer the most admissions?
- How does patient arrival vary by day of the week?
- What are the patterns in admissions vs non-admissions?

---

## Key Performance Indicators (KPIs)

| KPI | Description |
|-----|------------|
| Total Patients | Total ER visits in the selected time period |
| Average Wait Time | Mean waiting time before consultation |
| Average Satisfaction Score | Patient satisfaction rating |
| Total Admissions | Number of patients admitted |
| Admission % | Percentage of ER patients admitted |

---

## Dashboard Pages

### 1. ER Overview Dashboard
Includes:
- Patient demographics (Age, Gender, Race)
- Admissions vs Non-admissions
- Department referrals
- Day-of-week arrival trends
- Operational KPIs

### 2. ER Dashboard – Daywise
Time-based analysis with trend insights across selected date ranges.

### 3. Patient List
Detailed patient-level table including:
- Patient ID
- Name
- Age
- Gender
- Race
- Wait time
- Admission status
- Admission date

---

## Insights

- 9,200+ patients analyzed in the dataset.
- Average wait time is approximately 35 minutes.
- Admissions represent nearly 50% of total visits.
- Highest patient volume occurs on Sundays and Mondays.
- “None” referral category accounts for the largest share of admissions.
- Age distribution is balanced, with slightly higher counts in 20–40 and 40–60 ranges.
- Gender distribution is nearly even.
- White patients represent the largest demographic group.

---

## Tools & Technologies Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling (relationships, hierarchies)
- CSV data source

---

## Repository Structure

```
er-patient-flow-dashboard
│
├── screenshots/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│   └── patient_list.png
├── Emergency_Room_Dashboard.pbix
└── README.md
```

---

## How to Use

1. Download the `.pbix` file.
2. Open in Power BI Desktop.
3. Refresh data if needed.
4. Use the date and category filters to explore the dashboard interactively.
