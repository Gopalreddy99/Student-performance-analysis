# Student Habits & Academic Performance Analysis

> Analysing 80,000 student records to find what truly drives academic
> success and what puts students at dropout risk.

---

## Project Summary

| Detail | Info |
|--------|------|
| Dataset | 80,000 student records, 31 features |
| Tools | Excel (cleaning) + Power BI (dashboard) |
| Dashboard | 6 interactive pages with slicers |
| Skills | Data cleaning, feature engineering, DAX, visualisation |

---

## Dashboard Preview

![Dashboard Screenshot](images/dashboard_screenshot.png)

---

## Top 5 Key Findings

| # | Finding | Value |
|---|---------|-------|
| 1 | Previous GPA is the #1 predictor of exam score | r = 0.93 |
| 2 | Dropout students have nearly double the stress | 8.9 vs 4.9 |
| 3 | Study environment impacts score by 5.7 points | 91.3 vs 85.6 |
| 4 | Family income has almost no effect on scores | 89.1 vs 89.2 |
| 5 | Study hours make a 9 point difference | 93 vs 84 avg |

---

## Dashboard Pages

| Page | Title | Key Visual |
|------|-------|------------|
| 1 | Overview | KPI cards + grade distribution |
| 2 | Study Habits | Study hours vs score scatter |
| 3 | Dropout Risk | Stress level bar + matrix heatmap |
| 4 | Lifestyle | Sleep hours + exercise frequency |
| 5 | Socioeconomic | Income + parental education |
| 6 | Student Profiles | GPA vs score scatter (r=0.93) |

---

## Data Cleaning Steps (Done in Excel)

1. Checked missing values — 0 missing cells found
2. Removed duplicates — 0 duplicates found
3. Validated numeric ranges (sleep, attendance, age)
4. Checked text columns for inconsistencies using Filter
5. Added 4 new columns: exam_grade, age_group,
   performance_tier, total_screen_time

---

## Tools Used

- Microsoft Excel — data cleaning and feature engineering
- Power BI Desktop — dashboard and visualisation
- DAX — custom measures (Avg Score, Dropout Rate, Tutoring Boost)

---
