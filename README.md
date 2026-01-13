# QA Metrics Analysis Dashboard

## Overview
This project analyzes Quality Assurance (QA) on-the-floor (OTF) coverage and its impact on operational outcomes using SQL Server and Power BI.

The dashboard highlights how increased QA staffing and coverage in 2024 correlated with:
- Reduced average daily deviations
- Increased QA hours on the floor
- Improved operational oversight

## 🛠️ Tools & Technologies

### **SQL Server (T-SQL)**
- Built relational tables for QA operations, headcount, audits, deviations, and coverage metrics  
- Created aggregated views for daily, monthly, and year-over-year analysis  
- Performed before/after staffing comparisons using date-based joins and window logic  

### **Data Analysis (SQL)**
- Calculated key metrics including:
  - QA coverage ratio  
  - Average daily deviations  
  - QA hours on the floor  
- Used `JOIN`, `GROUP BY`, `CASE`, and CTEs to validate and align multiple data sources  

### **Power BI**
- Designed an executive-level dashboard with KPI cards, trend analysis, and distribution visuals  
- Built measures to track QA coverage %, deviations, audits, and observations  
- Used annotations and narrative text to translate analysis into business insights  

### **Excel (Source Data)**
- Served as the source for QA on-the-floor activity and staffing headcount  
- Cleaned and standardized date fields and column naming prior to database ingestion  

### **Analytics Techniques**
- Before/After analysis of QA staffing changes  
- Trend analysis to identify sustained operational shifts  
- Distribution analysis of daily QA hours on the floor  

## Key Metrics
- QA Coverage %
- Deviation Count
- Audit Count
- Total QA Observations
- Daily QA Hours on the Floor

## 📊 Dashboard Preview

![QA Metrics Dashboard](QA_Coverage_Analysis.png)

## Key Insights
- Higher QA coverage in 2024 coincided with an approximate 50% reduction in average daily deviations.
- QA staffing increases in early 2024 resulted in sustained higher QA presence on the floor.
- Increased QA hours aligned with improved compliance and monitoring consistency.
