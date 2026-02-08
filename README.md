This project is a complete Power BI dashboard built to analyze marketing campaign performance across channels, regions, customer segments, and time periods. It includes data cleaning, modeling, DAX calculations, and interactive visual insights to support data-driven marketing decisions.

Project Overview

The goal of this project is to understand:

Which marketing channels generate the highest ROI

Campaign performance across regions and customer segments

Conversion trends over time

Budget utilization and revenue contribution

Factors influencing campaign success

What’s Included

Cleaned & validated Marketing Campaign dataset

Star Schema data model (Campaign, Customer, Channel, Date)

DAX measures for Conversions, Revenue, ROI, CTR

6-page interactive Power BI dashboard

AI visuals (Key Influencers & Decomposition Tree)

Final business insights & recommendations

Data Cleaning

Performed in Power Query:

Removed duplicate campaign records

Handled missing budget and conversion values

Standardized date formats

Cleaned channel and region fields

Created a proper Date table

Validated customer segment data

Data Model (Star Schema)

Fact Table:

Campaign Performance

Dimension Tables:

Channel

Customer Segment

Region

Date

This model improves report performance and simplifies DAX calculations.

Dashboard Pages

1. Marketing Campaign Analysis
KPIs, total spend, revenue, ROI, and campaign reach overview.

2. Campaign Performance
Channel performance, conversions, CTR, and cost analysis.

3. Customer & Regional Insights
Segment engagement and region-wise campaign impact.

4. Campaign Drivers Analysis (Decomposition Tree)
Breakdown of revenue and conversions by multiple influencing factors.

5. Influencer Insights Dashboard (Key Influencers)
Identifies key drivers impacting campaign success and ROI.

6. Marketing Insights Q&A
Interactive natural-language query page for business users.

Key DAX Measures
Total Spend = SUM(Campaign[Spend])

Total Revenue = SUM(Campaign[Revenue])

Conversions = SUM(Campaign[Conversions])

ROI = DIVIDE([Total Revenue] - [Total Spend], [Total Spend], 0)

CTR % = DIVIDE(SUM(Campaign[Clicks]), SUM(Campaign[Impressions]), 0)

Key Insights

Digital channels generate higher ROI than traditional media

Certain regions show strong conversion performance

Some campaigns have high spend but low returns

Customer segments respond differently to campaign types

Seasonal trends impact campaign effectiveness

Recommendations

Increase investment in high-ROI channels

Optimize or discontinue low-performing campaigns

Improve targeting for low-conversion segments

Adjust budget allocation based on regional performance

Use influencer insights to refine future strategies

Tools Used

Power BI Desktop

Power Query

DAX

Data Modeling

AI Visuals (Key Influencers & Decomposition Tree)
