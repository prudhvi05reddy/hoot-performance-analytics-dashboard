# HOOT – Power BI Analytics Dashboard

This repository contains an end-to-end **Power BI analytics dashboard** built for the **HOOT application**, an English communication and performance tracking platform used in academic environments.

The project demonstrates practical skills in **API-based data integration**, **data modeling**, **DAX calculations**, and **interactive dashboard design** using Power BI.

---

## 🚀 Project Overview

The HOOT Power BI Dashboard is designed to help educators and administrators:

- Monitor student communication performance
- Analyze accuracy and attempt trends
- Compare performance across pools and technologies
- Gain insights into Listening, Speaking, Reading, and Writing (LRWS) skills

The dashboard focuses on **clarity, usability, and actionable insights**.

---

## 📊 Dashboard Pages

### 🏠 Home
- Introduction to the HOOT platform
- High-level overview
- Navigation to analytical pages

### 🧑‍💻 Technology View
- Technology-wise performance analysis  
  (AWS, Full Stack, Data Specialist, Flutter, VLSI, ServiceNow)
- Pool-wise attempt distribution
- Pool-wise accuracy comparison

### 🏊 Pool-wise Analysis
- Student-level drill-down
- Pool and technology mapping
- LRWS skill metrics
- Total attempts, duration, and accuracy
- Last 15 days accuracy tracking

### 📈 Dashboard (Analytics View)
- Key KPIs: Total Attempts, Accuracy, Duration
- Last 30 days accuracy trend
- Gender-wise participation analysis
- Skill-wise attempt distribution
- Daily attempt analysis
- Skill-wise accuracy gauges

### 📘 View Tips
- HOOT learning schedule
- Skill-wise topic guidance
- Recommendations for improving communication skills

---

## 🔗 Data Source

- Source Type: REST API (Development / Internal)
- API Status: Not live
- Data Format: JSON
- Integration Method: Power BI Web Connector
- Data Processing: Power Query (M Language)

Sample data structures are included for reference.  
Sensitive API endpoints and credentials are intentionally excluded.

---

## 🧠 Key Metrics & KPIs

- Total Attempts  
- Total Accuracy (%)  
- Total Duration  
- Pool-wise Attempts & Accuracy  
- Skill-wise Accuracy (Listening, Speaking, Reading, Writing)  
- Last 15 & 30 Days Accuracy Trends  
- Daily Attempt Count  
- Gender-wise Participation  

---

## 🧮 DAX & Data Modeling

- Custom DAX measures for KPIs and trends
- Dedicated Date Table for time-based analysis
- Optimized relationships for performance
- Modular and reusable calculations

---

## 🛠 Tools & Technologies

- Power BI Desktop
- REST API (Development Environment)
- Power Query (M Language)
- DAX
- Data Modeling & Visualization

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| HOOT LRWS Analytics Dashboard.pbix | Main Power BI dashboard file |
| README.md | Project documentation |
| dashboard_pages.md | Clear description of every page in Dashboard |
| api.md | API integration details |
| dax_measures.md | DAX logic documentation |

---

## 👨‍💻 Author

**Prudhvi**

This project is part of my **Power BI and Data Analytics portfolio**, showcasing real-world dashboard development using API-based data.
