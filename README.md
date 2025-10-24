# Project: Startups Expansion Analysis

<p align="center">
  <img width="600" height="642" alt="Screenshot 2025-10-24 093317" src="https://github.com/user-attachments/assets/452e5c77-bcdb-44ec-b2bc-95718f8849f6" >
</p>

---


## Overview

This project analyzes the performance of startups across U.S. states and regions, focusing on revenue growth, marketing spend, and profit efficiency between new and old expansions.

The analysis combines Python (Pandas & NumPy) for data cleaning and computation, and Power BI for visualization and dashboard reporting.

##  Tools & Technologies
 Python — Data preparation & calculations

 Power BI — Interactive dashboards and visualization

 Pandas, NumPy — Data analysis

 CSV Dataset: startups-expansion-modified.csv
##  Steps Performed
1. **Data Preparation**
   - Loaded startup dataset using Pandas  
   - Cleaned missing and duplicate records  
   - Created new calculated columns:
     - `Profit = Revenue - Marketing Spend`
     - `ROMS = (Profit / Marketing Spend) * 100`
     - `ROMS% = ROMS / 100`

2. **Exploratory Data Analysis (EDA)**
   - Grouped and summarized data by City, State, and Region  
   - Identified top 10 cities by revenue and profit  
   - Calculated marketing efficiency metrics  

3. **Dashboard Design (Power BI)**
   - **Maps**: Profit and Revenue by State  
   - **Pie Chart**: Revenue by Sales Region  
   - **Bar Charts**:
     - Profit vs Marketing Spend by Store ID  
     - Profit by State and Expansion Type  
   - **KPIs**:
     - Total Revenue → **6M**  
     - Total Profit → **5M**  
     - Total Marketing Spend → **428K**  
   - Filters for **Region** and **New Expansion (New/Old)**

---
##  Key Insights
- Region 1 and Region 2 contribute almost equally to total revenue.  
- **Old expansions** achieve higher profit despite lower marketing spend.  
- California, Florida, and Texas lead in profitability.  
- Average ROMS for “Old” expansions is significantly higher than “New”.

---
