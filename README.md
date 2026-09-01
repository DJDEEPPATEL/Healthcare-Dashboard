# Patient Waiting List Analysis - Power BI Dashboard
An interactive Power BI dashboard for analysing patient waiting list trends across specialties, case types, and age profiles. The report tracks total wait list volumes over time, breaks them down by specialty group, and allows drill-through from summary KPIs down to record-level detail.

![Summary Page](https://github.com/DJDEEPPATEL/Healthcare-Dashboard/blob/main/Home_Page.png)

📊 Overview
This report answers questions such as:
How is the total patient wait list trending month over month, and how does it compare to the same period last year?
How is the wait list split across Day Case, Inpatient, and Outpatient case types?
Which specialties and specialty groups have the largest wait lists?
How does wait time vary by age profile (0–15, 16–64, 65+) and time band (0–3 months up to 18+ months)?
What does the wait list look like at a granular, per-specialty, per-date level?

🗂️ Report Pages
1. Summary
High-level KPIs and trend visuals for a quick overview of the current wait list position.
Total wait list vs. prior-year comparison cards
Wait list bifurcation by case type (donut chart)
Wait list analysis by time band vs. age profile (stacked column)
Top 5 specialties by wait list volume
Monthly trend of Day Case / Inpatient vs. Outpatient volumes

2. Detail
A filterable, expandable matrix showing wait list counts by Archive Date → Specialty → Age Profile, broken out by Day Case, Inpatient, Outpatient, and Total. Includes slicers for date range, case type, specialty, age profile, and time band.

![Detail Page](https://github.com/DJDEEPPATEL/Healthcare-Dashboard/blob/main/Detail_Page.png)

3. DrillDown
Drill-through page showing total wait list broken down by Specialty Group (e.g. Bones, General, ENT, Eyes, Skin, Heart), reached by drilling from the Summary or Detail pages.

![DrillDown Page](https://github.com/DJDEEPPATEL/Healthcare-Dashboard/blob/main/DrillDown_Page.png))

🛠️ Built With
Power BI Desktop
DAX for calculated measures
Custom visuals (advanced card visual)
Key fields: `Archive_Date`, `Case_Type`, `Speciality_Name`, `Age_Profile`, `Time_Bands`, `Total`, `Specialty Group`
Key DAX measures:
`Latest Month Wait List`
`PY Latest Month Wait List` (prior-year comparison)
`Avg/Mid Wait List`
`Calc Method`
`Dynamic Title`

📁 Repository Structure
```
├── BI_file.pbix          # Power BI report file
├── screenshots/          # Dashboard preview images
│   ├── home_page.png
│   ├── detail_page.png
│   └── drilldown_page.png
└── README.md
```

👤 Author
Deep Patel
https://www.linkedin.com/in/deep-patel-msc-cs-0aa383200/
