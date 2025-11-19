Emergency Room Patient Flow Dashboard

A Power BI Analytics Project

This Power BI dashboard provides a comprehensive analysis of Emergency Room (ER) patient flow, focusing on key patient demographics, admission patterns, wait times, and operational performance metrics.

The dashboard helps hospital administrators, ER managers, and analysts monitor patient volume, identify bottlenecks, optimize staffing and improve patient experience.

The project demonstrates skills in:
Power BI visual design
Data modeling & relationships
DAX-based KPI creation
Analytical storytelling
Interactive reporting (date & category filters)

Objectives

The dashboard aims to answer the following key questions:

How many patients visited the ER during the selected period?
What is the average wait time and satisfaction score?
What percentage of patients were admitted?
Which patient demographics (age, gender, race) dominate ER visits?
Which departments refer the most admissions?
How does patient arrival vary by day of the week?
What are the patterns in admissions vs. non-admissions?

Key Performance Indicators (KPIs)
KPI	Description
Total Patients	Total ER visits in the selected time period
Average Wait Time	Mean waiting time before consultation
Average Satisfaction Score	Patient-provided satisfaction rating
Total Admissions	Number of patients admitted to the hospital
Admission %	% of ER patients who were admitted

Dashboard Visuals
1. Patient Demographics
Race distribution (e.g., White, African American, Asian, etc.)
Gender distribution (Male, Female, Not Categorized)
Age distribution (0–10, 10–20, … 70–80)

2. Operational Metrics
Patients by day of the week
Admissions by department referral
Admissions vs Non-Admissions (Donut chart)

3. Filters
Year filter
Month filter
Date range slicer
Patient name filter (on the patient list page)

Additional Pages
1. ER Dashboard – Daywise
Provides a performance perspective across time periods with trend-based visuals.
2. Patient List
A detailed table listing:
Patient ID
Full name
Age
Gender
Race
Wait time
Admission status
Admission date
This enables drill-down and patient-level analytics.

Insights 

Insights you can include based on your dashboard:
ER receives 9,200+ patients in the dataset, averaging 35 minutes wait time.
Admissions represent ~50% of total visits.
The highest patient volume occurs on Sundays and Mondays.
“None” category in referral accounts for the largest portion of admitted patients.
The most represented race is White, followed by African American and Two or More Races.
Age distribution is fairly balanced, with slightly higher counts in the 20–40 and 40–60 ranges.
Gender distribution is nearly even between M and F.

Tools & Technologies Used

Power BI Desktop (.pbix file)
Power Query
DAX formulas
Data modeling (relationships, hierarchies)
CSV data sources

Repository Structure
/ER-Patient-Flow-Dashboard
│
├── Emergency_Room_Dashboard.pbix
├── /screenshots
│     ├── dashboard_page1.png
│     ├── dashboard_page2.png
│     └── patient_list.png
└── README.md

How to Use This Dashboard
Download the .pbix file.
Open it in Power BI Desktop.
Refresh the data source if required.
Use the Date, Month, and Category filters to interact with the visualizations.

Connect
If you’d like help building or improving BI dashboards, feel free to reach out!
