# DAX Measures Documentation – HOOT Power BI Dashboard

This document describes the key DAX measures and calculated tables implemented
in the HOOT Power BI Dashboard. These measures support KPI cards, trend analysis,
pool-wise comparisons, and performance segmentation.

The focus is on clarity of logic rather than exposing every formula in detail.

---

## 📊 Core Performance Measures

### Average Accuracy
Used to calculate the overall accuracy of student attempts across the platform.
This measure serves as the base for multiple trend and time-based calculations.

**Purpose:**
- Overall performance evaluation
- Input for rolling-period accuracy calculations

---

### Total Attempts
Calculates the total number of attempts recorded in the dataset.

**Purpose:**
- KPI cards
- Activity and engagement analysis
- Pool-wise and daily comparisons

---

## ⏱ Time Intelligence Measures

### Last 30 Days Accuracy
Calculates the average accuracy over the most recent 30-day period using a
calendar-based date filter.

**Purpose:**
- Recent performance tracking
- Trend analysis in dashboard visuals
- Identifying short-term improvement or decline

---

## 📅 Date & Calendar Tables

### Calendar Table
A calculated calendar table created using the minimum and maximum dates
available in the dataset.

**Attributes Included:**
- Year
- Month
- Month-Year

**Purpose:**
- Enables month-wise and year-wise analysis
- Supports time intelligence functions

---

### Date Table (Extended)
An enhanced date table created to support detailed time-based analysis.

**Attributes Included:**
- Weekday name and number
- Week start date
- Week index
- Day number

**Purpose:**
- Daily attempt analysis
- Weekday trends
- Weekly performance comparison

---

## 🎯 Performance Classification

### Accuracy Band
Groups performance into predefined accuracy ranges.

**Accuracy Ranges:**
- 0–60%
- 61–75%
- 76–90%
- 91–100%

**Purpose:**
- Visual segmentation of performance
- Distribution analysis
- Identifying high and low performing groups

---

## 🏊 Pool-wise Measures

### Pool-wise Accuracy
Calculates average accuracy separately for each pool.

**Purpose:**
- Compare learning performance across pools
- Identify strong and weak pools

---

### Pool-wise Attempts
Calculates total attempts made by students in each pool.

**Purpose:**
- Measure engagement levels
- Compare participation across pools

---

## 📈 How These Measures Are Used in the Dashboard

The above measures are used to power:
- KPI cards (Attempts, Accuracy)
- Pool-wise comparison charts
- Time-based trend visuals (Last 30 Days)
- Accuracy distribution charts
- Daily and weekly activity analysis

---

## 🧠 Design Considerations

- Measures are modular and reusable
- Time intelligence is handled using a dedicated date table
- Calculations are optimized for dashboard performance
- Logic is designed to support drill-down and filtering

---

## 📌 Purpose of This Documentation

This file is included to:
- Clearly explain how key metrics are calculated
- Demonstrate understanding of DAX concepts
- Support mentor reviews and interview discussions
- Improve maintainability of the Power BI solution
