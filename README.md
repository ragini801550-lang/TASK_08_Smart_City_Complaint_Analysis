# 🏙️ Smart City Complaint Analysis Dashboard
 Domain: Data Analytics + Civic Analytics + Smart City Intelligence


## 📌 Problem Statement

Modern cities receive thousands of citizen complaints every day related to garbage collection, water supply, road damage, street light failures, traffic congestion, drainage problems, and public safety issues. Manually monitoring and resolving these complaints becomes difficult as cities grow.

This project builds a Smart City Complaint Analytics Dashboard to help city officials make data-driven decisions to improve urban services.

---

## 📂 Dataset Description

- **Type:** Synthetic City Complaint Dataset
- **Total Records:** 50,000 rows
- **Time Period:** January 2023 - December 2024
- **Total Columns:** 22

| Column | Description |
|--------|-------------|
| Complaint_ID | Unique complaint identifier |
| Citizen_Name | Name of the citizen |
| Phone_Number | Contact number |
| Complaint_Date | Date complaint was filed |
| Resolved_Date | Date complaint was resolved |
| Zone | City zone (8 zones) |
| Area_Name | Area/Street name |
| Landmark | Nearby landmark |
| Category | Type of complaint (7 categories) |
| Department | Responsible department |
| Priority | Low / Medium / High |
| Priority_Score | 1 / 2 / 3 |
| Status | Resolved / Pending / In Progress |
| Resolution_Delay_Days | Days taken to resolve |
| Citizen_Satisfaction_Score | Score out of 5.0 |
| Officer_Assigned | Officer handling the complaint |
| Complaint_Description | Description of the issue |
| Feedback_Comments | Citizen feedback |
| Month | Month of complaint |
| Year | Year of complaint |
| Quarter | Q1 / Q2 / Q3 / Q4 |
| Week | Week number |

---

## 📊 KPI Definitions

| KPI | Definition |
|-----|------------|
| Total Complaints | Total number of complaints filed |
| Resolved Complaints | Complaints with status = Resolved |
| Resolution Rate | (Resolved / Total) * 100 |
| Avg Resolution Time | Average days taken to resolve complaints |
| High Priority Complaints | Complaints with Priority = High |
| Citizen Satisfaction Score | Average satisfaction score out of 5.0 |
| Complaint Hotspot Zones | Zones with highest complaint count |
| Department Performance Score | Resolution rate per department |

---

## 🔍 Key Findings

1. **Most frequent complaint category** is Garbage Collection and Water Supply
2. **Central Zone and North Zone** have the highest number of complaints
3. **Sanitation Department** handles the most complaints overall
4. **High Priority complaints** are resolved faster than Low Priority ones
5. **Citizen satisfaction** is higher when complaints are resolved within 3 days
6. **Complaint volume** peaks during Q2 and Q3 months

---

## 💡 Recommendations

1. **Increase Sanitation staff** in high complaint zones
2. **Prioritize Water Supply issues** as they affect daily life
3. **Set resolution SLA** - High Priority within 3 days, Medium within 7 days
4. **Deploy more officers** in Central Zone and North Zone
5. **Regular monitoring** of department performance scores
6. **Citizen feedback system** should be improved for better satisfaction scores

---

## 🚀 Future Scope

1. Real-time complaint tracking using live data feeds
2. Machine Learning model to predict complaint hotspots
3. NLP analysis on complaint descriptions
4. Mobile app integration for citizen complaint filing
5. Geo-mapping with actual GPS coordinates
6. Automated alert system for high priority complaints

---

## 🛠️ Tools Used

- **Python** - Data Analysis
- **Google Colab** - Development Platform
- **Pandas & NumPy** - Data Processing
- **Matplotlib & Seaborn** - Static Visualizations
- **Plotly** - Interactive Dashboard

---

## 📁 Project Structure

```
TASK_08_Smart_City_Complaint_Analysis/
│── data/
│   └── smart_city_complaints_50k.csv
│── notebook/
│   └── Smart_City_Analysis.ipynb
│── dashboard/
│   └── dashboard_screenshots/
│── images/
│   └── phase1_eda.png
│   └── phase2_kpi.png
│   └── chart1_zone.png
│   └── chart2_category.png
│   └── chart3_trends.png
│   └── chart4_priority.png
│   └── chart5_heatmap.png
│   └── chart6_satisfaction.png
│── reports/
│   └── kpi_report.pdf
│── README.md
│── requirements.txt
```

---

## ⚙️ Requirements

```
pandas
numpy
matplotlib
seaborn
plotly
```

---



**Internship Project - Task 16**
Smart City Complaint Analysis
AI & ML Internship Program
