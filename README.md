# Canadian Canola Price Analysis Dashboard (2025)

## Project Overview
This project analyzes Canadian Canola price data for the year 2025 using official data from Statistics Canada.  
The objective is to demonstrate how raw agricultural data can be transformed into meaningful insights that support real-world decision-making through data cleaning, analysis, and visualization.

The workflow follows a standard data analytics pipeline:
- Data sourcing  
- Data cleaning (Microsoft Excel)  
- Data modeling and visualization (Power BI)  
- Insight generation  
- Decision-making support  

---

## Table of Contents
1. [Objectives](#objectives)  
2. [Data Source](#data-source)  
3. [Data Cleaning and Preparation (Excel)](#data-cleaning-and-preparation-excel)  
4. [Data Processing (Power BI)](#data-processing-power-bi)  
5. [Dashboard Overview](#dashboard-overview)  
6. [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)  
7. [Visualizations](#visualizations)  
8. [Interactive Elements](#interactive-elements)  
9. [Insights and Patterns Identified](#insights-and-patterns-identified)  
10. [Actionable Decisions and Recommendations](#actionable-decisions-and-recommendations)  
11. [Tools Used](#tools-used)  
12. [Conclusion](#conclusion)  

---

## Objectives
- Identify a reliable source of raw agricultural price data  
- Clean and process Canola price data  
- Create key performance indicators (KPIs)  
- Visualize trends, patterns, and regional differences  
- Enable actionable, data-driven decision-making  

---

## Data Source
- **Provider:** Statistics Canada (Government of Canada)  
- **Dataset:** Farm product prices, monthly  
- **Crop Analyzed:** Canola  
- **Time Period:** January 2025 – November 2025  

**Data Link:**  
https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3210007701  

Statistics Canada is a trusted and authoritative source that ensures data accuracy, consistency, and reliability.

---

## Data Cleaning and Preparation (Excel)

### Steps Taken

#### 1. Removed Irrelevant Metadata Columns
The following technical metadata columns were removed:
- DGUID, UOM_ID, SCALAR_FACTOR, SCALAR_ID  
- VECTOR, COORDINATE, STATUS, SYMBOL  
- TERMINATED, DECIMALS  

**Reason:**  
These fields are internal identifiers used by Statistics Canada and do not contribute to analytical insights or decision-making. Removing them allows focus on business-relevant variables.

#### 2. Renamed Columns for Clarity
| Original Column | Renamed Column |
|-----------------|---------------|
| REF_DATE        | Date          |
| GEO             | Province      |
| Farm products   | Product       |
| VALUE           | Price         |

#### 3. Ensured Correct Data Types
- Date column formatted as `Date`  
- Price column formatted as `Numeric` (2 decimal places)  

#### 4. Data Quality Checks
- Checked for missing values  
- Removed duplicate records  
- Standardized inconsistent naming using Power Query  

The cleaned dataset was saved as an Excel file and imported into Power BI.

---

## Data Processing (Power BI)
Data processing was performed using:
- DAX measures  
- Aggregations  
- Filters and slicers  

The analysis focuses exclusively on Canola to ensure deeper and more targeted insights.

---

## Dashboard Overview
The Power BI dashboard presents Canola price trends, regional comparisons, and key indicators in an interactive and user-friendly format.

<img width="481" height="289" alt="image" src="https://github.com/user-attachments/assets/53a82680-45b7-4d6d-bfcb-fb37c23a3f78" />


---

## Key Performance Indicators (KPIs)

### KPI 1: Average Monthly Price
- **Value:** $631.84  
- Represents the overall market price level and stability.

### KPI 2: Price Trend (%)
- **Value:** +0.96%  
- Indicates a slight upward trend, reflecting stable pricing over time.

### KPI 3: Maximum and Minimum Prices
- **Maximum Price:** $684.00  
- **Minimum Price:** $575.51  
- Highlights price range and potential market risk.

---

## Visualizations

### Line Chart – Price Trend Over Time
- Displays monthly Canola price trends  
- Identifies seasonal patterns  
- Shows the highest price recorded in August 2025 ($676.61)  

### Bar Chart – Average Price by Province
- Saskatchewan: $641.73  
- Alberta: $637.17  
- Ontario: $616.61  

This visualization highlights regional price differences across provinces.

### KPI Cards
- Average Monthly Price  
- Price Change (%)  
- Highest Recorded Price  
- Lowest Recorded Price  

---

## Interactive Elements
The dashboard includes slicers for:
- Province  
- Date  

These features allow users to dynamically explore the data and customize their analysis.

---

## Insights and Patterns Identified
- Canola prices remained relatively stable throughout 2025  
- A seasonal price peak occurred in August  
- Western provinces (Saskatchewan and Alberta) recorded higher average prices than Ontario  
- Price volatility was moderate, indicating manageable financial risk  

---

## Actionable Decisions and Recommendations

### Recommendation 1: Sales Timing Strategy
**Decision:**  
Farmers should strategically time Canola sales around peak pricing periods.

**Solution:**  
Historical trends show that prices peak during high-demand months such as August. Storing harvested Canola and delaying sales until these periods can help maximize revenue and improve profit margins.

---

### Recommendation 2: Regional Production Focus
**Decision:**  
Producers and investors should prioritize regions with stronger price performance.

**Solution:**  
Data shows Saskatchewan and Alberta consistently record higher average prices. Increasing production capacity and investment in these regions can lead to higher returns and improved competitiveness.

---

### Recommendation 3: Price Risk Management Strategy
**Decision:**  
Producers should adopt price risk management strategies to mitigate price fluctuations.

**Solution:**  
Given price variability between $575.51 and $684.00, farmers can reduce risk by:
- Using forward contracts or price hedging strategies  
- Diversifying sales across multiple months rather than selling all at once  

This approach supports income stability while still benefiting from high-price periods.

---

## Tools Used
- **Microsoft Excel:** Data cleaning and preparation  
- **Power BI:** Data modeling, visualization, and dashboard creation  
- **DAX:** KPI calculations and analytical measures  

---

## Conclusion
This project demonstrates how agricultural price data can be transformed into actionable insights through structured data analysis and visualization.  
By focusing on Canadian Canola prices, the dashboard supports informed decision-making for farmers, investors, and policymakers.

---

## Author
**Augusta Kasarachi Onyekwere**  
Student ID: C0967164  
Course: Management Information System  

