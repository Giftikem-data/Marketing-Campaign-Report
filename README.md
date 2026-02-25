**PROJECT TITLE**
Digital Marketing Campaign Performance Analysis – Power BI Report

**Problem statement**
This project evaluates the effectiveness of the company’s digital marketing campaigns by building a report to monitor and analyze key performance indicators such as ROI, conversion rate, and channel efficiency.

**Tools Used**
PowerBi Desktop
DAX – Calculated measures (ROI, CTR, Conversion Rate)

**Dataset Overview**
File Format: Microsoft Excel (.xlsx)
Number of Records: 1,000 rows
Number of Fields: 11 columns
Metrics analyzed: Impressions, Clicks, Conversions, Spend, Revenue, CTR, ROI
Date Range Covered: November 2024 – February 2025
Initial Data Quality Issues Identified: None

**Data transformation**
- Changed Campaign ID data type to Text, Ad spend data type to Currency and selected 
Indian Rupee(English), Revenue data type to Currency and selected Indian Rupee 
(English).  
- Commas were used as values separators in numbers and currency.

**Dax performed** 
Created calculated fields for CTR, Conversion Rate, ROI and ROI Outcome 
- CTR  =  DIVIDE([Clicks], [Impressions]), format to % 
- Conversion Rate= DIVIDE([Conversions], [Clicks]), format to % 
- ROI = DIVIDE([Revenue ] - [Ad Spend ], [Ad Spend ]), format to % 
- ROI Outcome = IF(DIVIDE([Revenue ]- [Ad Spend ], [Ad Spend ]) < 0, "Loss", "Profit")

**Interactivity** 
- Slicers were added for Campaign Date, Product Name, Product Category, and Marketing Channel. 
- Slicers were synchronized to control visuals across pages.

Key Insights


Recommendations

**Outcome**
The project delivered a comprehensive performance evaluation of the company’s digital marketing campaigns, identifying high-ROI categories, underperforming campaigns, seasonal trends, and budget inefficiencies. The analysis provides actionable insights to optimize marketing spend, improve conversion efficiency, and support data-driven strategic decision-making.

