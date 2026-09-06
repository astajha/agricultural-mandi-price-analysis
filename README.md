# agricultural-mandi-price-analysis

An interactive Power BI dashboard for analyzing and comparing agricultural commodity prices across Indian mandis.

## 📌 Project Overview

This project analyzes agricultural commodity prices across different states, districts, and mandis in India to identify regional price disparities, price volatility, and differences between markets.

The analysis uses a single-day snapshot of agricultural market data from the Government of India's AGMARKNET platform, dated **28 March 2026**.

The project focuses on:
- Comparing commodity prices across mandis
- Identifying high and low price volatility
- Finding commodities with significant price variations
- Comparing prices across states, districts, and mandis
- Providing insights that can support better mandi selection and decision-making

## 📊 Dataset

**Source:** Government of India – AGMARKNET  
**Platform:** data.gov.in  
**Dataset Date:** 28 March 2026

The dataset contains:
- State
- District
- Mandi
- Commodity
- Variety
- Minimum Price
- Maximum Price
- Modal Price

> Note: This project uses a single-day snapshot, so it focuses on cross-sectional comparison rather than time-series trends or forecasting.

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Cleaning & Transformation
- Data Analysis
- Data Visualization

## 🔄 Project Workflow

1. Collected agricultural market data from AGMARKNET
2. Imported the dataset into Power BI
3. Cleaned and transformed the raw data using Power Query
4. Standardized fields and handled data inconsistencies
5. Created a derived **Price Range** metric:
   
   `Price Range = Maximum Price - Minimum Price`

6. Analyzed price variations across states, districts, and mandis
7. Identified high and low volatility cases
8. Compared average modal prices across commodities
9. Built an interactive Power BI dashboard using KPIs, slicers, charts, maps, and tables

## 📈 Key Analysis

### 1. Mandi-wise Price Comparison
Compares modal prices across different mandis to identify markets offering relatively better prices for specific commodities.

### 2. Price Volatility Analysis
Uses the difference between maximum and minimum prices to identify high and low volatility cases.

### 3. Commodity Price Comparison
Compares average modal prices across commodities to identify relatively high- and low-priced commodities.

### 4. KPI Analysis
The dashboard provides key indicators including:
- Average Modal Price
- Price Range
- High Volatility Count
- First/Top Commodity indicators

## 🔍 Key Insights

- Agricultural commodity prices show significant variation across states, districts, and mandis.
- Price differences can exist even between nearby mandis.
- Some markets show high price volatility, while others demonstrate relatively stable pricing.
- Commodity prices vary considerably based on market and regional conditions.
- Comparing modal prices can help identify potentially better markets for selling specific commodities.

## 📊 Dashboard

The Power BI dashboard provides interactive filtering and visualization through:

- State slicer
- District slicer
- Mandi slicer
- Commodity slicer
- KPI cards
- Commodity price comparison charts
- Mandi-wise price comparison
- Geographic visualization
- Volatility distribution
- Conditional formatting

## 🎯 Project Objective

The primary objective is to use data analytics and business intelligence techniques to make agricultural market information easier to analyze and interpret.

The dashboard can help users compare mandi prices and understand regional price differences, while providing insights that may support farmers and policymakers in decision-making.

## 🚀 Future Scope

Future improvements could include:

- Time-series analysis using historical mandi prices
- Agricultural commodity price forecasting using Machine Learning
- Integration of weather and crop production data
- Real-time AGMARKNET data integration
- Transportation cost and mandi-distance analysis
- Mobile or web application for easier farmer access
- Advanced geographical and clustering analysis

## 👩‍💻 Author

**Aastha Kumari**  
B.Tech Computer Science & Engineering  
Lovely Professional University

## 📚 References

- Government of India – AGMARKNET / data.gov.in
- Microsoft Power BI Documentation
