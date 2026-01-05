# API Integration – HOOT Power BI Dashboard

This Power BI dashboard is built using data obtained from a **REST API** provided by the **HOOT application** for development and internal analysis purposes.  
The API serves as the primary data source for tracking student communication performance and learning activity.

---

## API Overview

- API Type: REST
- Method: GET
- Environment: Development / Internal
- API Status: Not live
- Response Format: JSON

The API provides structured data related to student activity across different technologies, pools, and communication skills.

---

## Data Provided by the API

The API response includes information such as:

- Student identifiers
- Technology (AWS, Full Stack, Data Specialist, Flutter, VLSI, ServiceNow)
- Pool number and mapping
- Communication skills:
  - Listening
  - Speaking
  - Reading
  - Writing
- Attempt count
- Accuracy percentage
- Duration of activity
- Activity date

This data enables detailed analysis at both **aggregate** and **student-level** views.

---

## Power BI Integration

The API is integrated into Power BI using the **Web connector**.  
The JSON response is parsed and transformed using **Power Query (M Language)** to prepare the data for analytics.

Key integration steps include:
- Connecting to the API endpoint
- Expanding nested JSON structures
- Data type standardization
- Column renaming for clarity
- Removing null or invalid records

---

## Data Modeling & Usage

After transformation, the API data is used to:
- Build a clean data model
- Create relationships with a Date table
- Enable time-based analysis such as:
  - Last 15 days accuracy
  - Last 30 days accuracy
  - Daily attempt trends

The modeled data supports multiple dashboard pages including:
- Technology-wise analysis
- Pool-wise analysis
- Skill-wise (LRWS) performance
- KPI-driven summary views

---

## Dashboard Dependency on API Data

All major visuals and KPIs in the dashboard are derived from the API data, including:
- Total Attempts
- Total Accuracy
- Total Duration
- Pool-wise Accuracy
- Skill-wise Accuracy
- Trend and distribution visuals

The API acts as the single source of truth for the dashboard.

---

## Security & Access Notes

- The API is not publicly accessible
- Endpoints, tokens, and authentication details are intentionally excluded
- Sample data structures are provided only for reference

This approach ensures transparency while maintaining data security.

---

## Purpose of API Documentation

This document is included to:
- Explain the data source clearly
- Demonstrate API integration knowledge
- Provide context for dashboard metrics and visuals
- Support mentor review and interview discussions
