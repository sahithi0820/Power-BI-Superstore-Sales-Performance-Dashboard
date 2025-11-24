>## 📊 Power BI Superstore Sales Performance Dashboard**

An end-to-end Power BI project that transforms raw Superstore sales data into an interactive strategic dashboard for performance management and business intelligence.

>**📋 Project Overview**

This Power BI dashboard provides comprehensive analysis of Superstore sales performance, enabling stakeholders to track sales and profit trends, analyze performance by product category and region, and identify specific sub-categories impacting profitability.

>**🎯 Objectives**

•Track sales and profit trends over time

•Analyze performance by product category and region

•Identify profitable and loss-making sub-categories

•Provide actionable insights for business improvement

•Create an interactive, multi-page reporting solution

**📁 Files Included**

•Superstore_Sales_Dashboard.pbix - Main Power BI file

•Sample-Superstore.csv - Dataset

•README.md - Project documentation

•Output Dashboard Results Screenshots

**Implementation**

>Data Sources

•Primary Dataset: Superstore dataset sourced from Kaggle

•File Type: Excel/CSV format containing sales transactions

>Data Cleaning & Transformation

•I performed the following data preparation steps:

•Power Query Transformations Applied:

1. Source - Loaded raw Superstore dataset
   
2. Promoted Headers - Converted first row to column headers
   
3. Changed Types - Automated data type detection and conversion

4. Duplicated Column - Created copies of key columns for calculations
 
5. Extracted Year - Derived year from date columns for time analysis
 
6. Renamed Columns - Standardized column names for consistency
 
7. Multiple Error Removal Steps - Cleaned data inconsistencies
 
8. Added Custom - Created calculated columns including Profit Margin

> Custom Column - Profit Margin

I added a custom column in Power Query to calculate Profit Margin using the formula:

**Profit Margin = [Profit] / [Sales]**

This calculated column enables direct analysis of profitability percentages across different dimensions of the data.

**DAX Measures Created**

I implemented the following key DAX measures:

1. Total Sales - Total Sales = SUM(Sales[Sales])
   
2. Total Profit - Total Profit = SUM(Sales[Profit])
   
3. Profit Margin - Profit Margin = DIVIDE([Total Profit], [Total Sales])
   
4. Profit Margin % - Formatted percentage display of profit margin
   
5. Total Quantity Sold - Total Quantity = SUM(Sales[Quantity])

**Advanced Calculations:**

•Year-over-Year growth metrics

•Regional performance comparisons

•Category-wise profitability analysis

•Sub-category performance rankings

**📈 Dashboard Features**

> Interactive Components:

1. KPI Cards - Key performance indicators at a glance
   
2. Time-series Charts - Sales and profit trends over time
   
3. Geographical Map - Regional performance visualization
   
4. Profit vs. Sales Scatter Plot - Product portfolio analysis
   
5. Category/Sub-category Breakdown - Detailed performance drill-down
    
6. Multi-page Report - Comprehensive analysis across different dimensions

**🔍 Key Insights Discovered**

1. High-performing Areas
   
2. Improvement Opportunities
   
**🚀 How to Use This Repository**

1. Clone or download this repository
   
2. Open the .pbix file in Power BI Desktop
   
3. Refresh data if needed (ensure data source paths are correct)
   
4. Interact with the dashboard filters and visuals

**🛠️ Prerequisites**

1. Power BI Desktop (free download from Microsoft)
   
2. Basic understanding of business analytics concepts
   
3. Dataset access (included in repository)
