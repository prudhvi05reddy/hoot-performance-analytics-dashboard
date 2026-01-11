# Dashboard Pages – HOOT Power BI Dashboard

This document provides a detailed, page-by-page explanation of the HOOT Power BI
Dashboard. It highlights the purpose of each page, the key visuals used, and
the DAX measures that power the analytics.

The dashboard is designed to transform API-based data into meaningful insights
using data modeling and DAX calculations.

---

## 🏠 Home Page

### Purpose
- Introduces the HOOT application and the analytics dashboard
- Provides a high-level understanding of what insights are available
- Acts as the primary navigation page

### Key Elements
- Platform overview and description
- Navigation buttons to all analytical pages
- Consistent branding and layout

### DAX Usage
- No complex DAX measures are used on this page
- This page primarily serves as a navigation and overview layer

---

## 🧑‍💻 Technology View

### Purpose
- Analyze student performance across different technologies such as
  AWS, Full Stack, Data Specialist, Flutter, VLSI, and ServiceNow

### Key Visuals
- Technology-wise total attempts
- Pool-wise accuracy comparison by technology
- Bar and comparison charts

### DAX Measures Used
- **Total Attempts**
- **Average Accuracy**
- **Pool-wise Accuracy**
- **Technology-wise Attempts**
- **Technology-wise Accuracy**

### Insights
- Identifies technologies with high engagement and strong accuracy
- Helps compare learning outcomes across different tracks

---

## 🏊 Pool-wise Analysis

### Purpose
- Provide detailed performance insights at the pool and student level
- Enable drill-down analysis for mentors and administrators

### Key Visuals
- Student-level tabular view
- Pool and technology mapping
- LRWS (Listening, Speaking, Reading, Writing) accuracy metrics
- Total attempts, duration, and accuracy indicators
- Last 15 days accuracy trend

### DAX Measures Used
- **Pool-wise Accuracy**
- **Pool-wise Attempts**
- **Skill-wise Accuracy (Listening, Speaking, Reading, Writing)**
- **Last 15 Days Accuracy**
- **Total Attempts**
- **Total Duration**

### Insights
- Highlights individual and pool-level performance
- Helps identify students or pools requiring additional support
- Shows recent performance trends using time intelligence

---

## 📈 Dashboard (Analytics View)

### Purpose
- Present a consolidated view of overall platform performance
- Highlight trends, engagement patterns, and skill-level insights

### Key Visuals
- KPI cards for Total Attempts, Accuracy, and Duration
- Last 30 days accuracy trend line
- Gender-wise participation analysis
- Skill-wise attempt distribution
- Daily attempt analysis by weekday
- Skill-wise accuracy gauge visuals

### DAX Measures Used
- **Total Attempts**
- **Average Accuracy**
- **Total Duration**
- **Last 30 Days Accuracy**
- **Daily Attempt Count**
- **Skill-wise Accuracy**
- **Accuracy Band**

### Insights
- Provides a complete snapshot of learning performance
- Highlights short-term trends using rolling-period DAX calculations
- Helps decision-makers understand engagement and accuracy patterns

---

## 📘 View Tips

### Purpose
- Provide structured learning guidance to students
- Bridge the gap between analytics and actionable improvement steps

### Key Elements
- Topic-wise learning schedule
- Skill-based recommendations
- Daily practice guidance

### DAX Usage
- This page does not rely on complex DAX calculations
- It complements analytical insights with instructional content

---

## 📌 Summary

Each page in the HOOT Power BI Dashboard is powered by carefully designed
DAX measures and a structured data model.

- DAX measures drive KPIs, trends, and comparisons
- Time intelligence enables recent performance analysis
- Pool-wise and technology-wise measures support targeted insights
- Skill-level measures help track communication improvement

This structured approach ensures that the dashboard is both
**analytically strong** and **easy to interpret** for mentors and stakeholders.
