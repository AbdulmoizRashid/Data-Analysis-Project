# Toman Bike Share Dashboard  

## Project Overview  
This project is a Power BI Dashboard built to analyze bike share data imported from SQL Server Management Studio (SSMS). The dashboard highlights revenue trends, gross profit, rider behavior, and seasonal patterns to provide insights into business performance and rider activity.  

## Key Features  
- Data Source: Connected Power BI to SQL Server (SSMS) using a custom query with CTE and joins.  
- Metrics Displayed:  
  - Revenue ($10M)  
  - Gross Profit ($7M)  
  - Profit Margin (45%)  
  - Total Riders (2M)  
- Insights Provided:  
  - Peak Earning Times: Highest sales between 10 AM – 3 PM, with Wednesday & Friday as top-performing days.  
  - Seasonal Revenue Trends: Summer generated the highest revenue ($3.2M).  
  - Rider Segmentation: Majority (81.81%) are registered riders, while 18.19% are casual riders.  
  - Monthly Performance: Revenue and gross profit tracked by month with riders count.  

## Data Transformation  
- Added conditional column to label year (2021 if yr=0, 2022 if yr=1).  

## Visualization in Power BI  
- Line & clustered chart (monthly trends).  
- Bar chart (revenue by season).  
- Donut chart (rider type distribution).  
- KPI cards (Revenue, Gross Profit, Riders, Profit Margin).  

## Purpose  
The dashboard helps business stakeholders identify:  
- The most profitable times and days to increase fleet availability.  
- Seasonal revenue opportunities.  
- Rider behavior insights for marketing strategies.  

## Tools & Skills Used  
- SQL Server (SSMS) – Querying & Data Preparation  
- Power BI – Dashboard & Visualization  
- DAX & M Query – Data transformation and calculations  
