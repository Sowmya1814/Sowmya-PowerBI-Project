Marketing Campaign Effectiveness Analysis – Power BI
----------------------------------------------------

This project is a complete Power BI dashboard built to analyze marketing campaign performance across channels, regions, customer segments, and time periods. It includes data cleaning, modeling, DAX calculations, and interactive visual insights to support data-driven marketing decisions.

Project Overview
----------------------------------------------------

The goal of this project is to understand:

- Which marketing channels generate the highest ROI

- Campaign performance across regions and customer segments

- Conversion trends over time

- Budget utilization and revenue contribution

- Factors influencing campaign success

What’s Included
----------------------------------------------------

- Cleaned & validated Marketing Campaign dataset

- Star Schema data model (Campaign, Customer, Channel, Date)

- DAX measures for Conversions, Revenue, ROI, CTR

- 6-page interactive Power BI dashboard

- AI visuals (Key Influencers & Decomposition Tree)

- Final business insights & recommendations

Data Cleaning
----------------------------------------------------

Performed in Power Query:

- Removed duplicate records

- Handled missing and inconsistent values

- Standardized campaign & channel names

- Validated spend and revenue fields

- Created a proper Date table for time analysis

Data Model (Star Schema)
----------------------------------------------------

Fact Table:

- Campaign / Marketing Data

Dimension Tables:

- Customer

- Channel

- Date

This structure improves performance and simplifies DAX calculations.

Dashboard Pages
----------------------------------------------------

- Marketing Campaign Analysis: KPIs, revenue trends, channel performance, spend vs revenue analysis

- Campaign Performance: ROI, conversion rates, campaign comparison table, regional insights

- Strategy & Investment Insights: Budget allocation, underperforming campaigns, investment recommendations

- Decomposition Tree: Breakdown of revenue/ROI by channel, region, and campaign type

- Key Influencers: Factors impacting campaign success and conversion performance

- Q&A Dashboard: Natural language queries for interactive business insights

Key DAX Measures
----------------------------------------------------

- Total Revenue = SUM(Campaign[Revenue])

- Total Spend = SUM(Campaign[Spend])

- ROI = DIVIDE([Total Revenue] - [Total Spend], [Total Spend], 0)

- Conversion Rate = 
DIVIDE(SUM(Campaign[Conversions]), SUM(Campaign[Clicks]), 0)

Key Insights
----------------------------------------------------

- Search Ads generate the highest ROI and revenue

- TV Ads show strong conversion performance

- Some campaigns have high spend but low returns

- Regional performance varies significantly

- Conversion efficiency differs by channel

Recommendations
----------------------------------------------------

- Increase investment in high-ROI channels like Search Ads

- Optimize or reduce spend on underperforming campaigns

- Improve audience targeting strategies

- Enhance conversion funnels for better performance

- Allocate budgets based on data insights

Tools Used
----------------------------------------------------

- Power BI Desktop

- Power Query

- DAX

- Data Modeling
