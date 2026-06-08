# Blinkit Grocery Sales Analysis

A data analytics project exploring sales performance, outlet characteristics, and product trends for Blinkit — India's last-minute grocery delivery app — using Power BI and Excel.

 ## Project Overview
 
This project analyzes Blinkit's grocery sales data to uncover key business insights around:

Total and average sales performance

Item type popularity and fat content breakdown

Outlet size, location, and establishment trends

Customer ratings across product and outlet segments

The findings are presented through an interactive Power BI dashboard built on top of structured Excel data.

![image alt](https://github.com/rt5899-art/Blinkit_Analysis/blob/439c147b447426259b21415c9403cda8f9b174f7/ss-blinkit%20.png)


#### Dashboard Highlights

File: Blikit_power_bi presentation.pbix
The Power BI report includes the following visuals and KPIs:

#### Key Metrics

Total Sales — Overall revenue generated

Average Sales — Mean sales per item-outlet combination

Number of Items — Total distinct products

Average Rating — Customer satisfaction score

 ## Charts & Visuals

Fat Content vs. Sales — Donut chart comparing Low Fat vs. Regular item sales

Item Type Performance — Bar chart of sales by product category

Outlet Establishment Trend — Line chart showing sales growth over outlet age

Outlet Size Distribution — Pie/donut chart of sales split by store size

Outlet Location Analysis — Funnel chart comparing Tier 1, 2, and 3 city performance

Outlet Type Comparison — Matrix table with sales, items, ratings, and item visibility


### Tools and Technologies

Business Intelligence Platform: Microsoft Power BI

Data Transformation Engine: Power Query (M Language)

Analytical Calculation Language: DAX (Data Analysis Expressions)

Data Storage: Local flat-file architecture

### Getting Started
Requirements

Microsoft Power BI Desktop (Version 2.126 or higher recommended)

System memory: Minimum 8 GB RAM (16 GB recommended for large data models)

Operating System: Windows 10 or Windows 11

Data Source File: Cleaned transactional data in Excel format

### Challenges Faced

Visual Label Truncation: During the development of the product category bar chart, lengthy category names (e.g., Frozen Foods, Household items) were truncated. This was resolved by adjusting the left margin padding and setting responsive font scaling to preserve visual clarity without sacrificing the data labels.

Data Standardization Across Outlets: Inconsistencies in reporting metrics across different outlet types (Grocery Stores vs. Supermarkets) required rigorous data profiling. Power Query was used to standardize null values and enforce uniform numeric types for exact mathematical aggregation.

Complex Multi-KPI Filtering: Creating a seamless user experience across the slicers (Outlet Location, Outlet Size, and Outlet Type) caused performance lag initially. Optimizing the data model relationships and reducing unnecessary bi-directional filtering restored responsive cross-highlighting across all visualizations.


### Key Insights

Based on the aggregated data compiled in the dashboard interface, the following performance trends were identified:

High-Level Operational Metrics: The platform tracks a total sales volume of 1.20M with an overall average sales value of 140.99 across 8,523 total unique items. The customer experience maintains a strong baseline with an average rating of 3.92.

Fat Content Contribution: Low Fat (LF) items represent the dominant revenue driver, accounting for 776.32K (64.6%) of total sales compared to Regular fat content items, which brought in 0.43M.

Top Product Segments: Fruits and Vegetables alongside Snack Foods emerge as the highest-volume product categories, each generating 0.18M in total sales.

Historical Establishment Trends: Sales peaks are tied directly to outlet deployment years. Outlets established in 2018 achieved the highest performance peak at 205K in sales, while the initial baseline started at 78K during the 2011 launch window.

Geographical and Size Breakdown: Tier 3 locations generate the largest share of revenue at 472.13K, followed by Tier 2 at 393.15K, and Tier 1 at 336.40K. Medium-sized outlets contribute the largest operational share at 507K (approximately 42.0%), while Small outlets contribute 444.79K (37.01%).

Outlet Type Profitability Matrix: Supermarket Type1 represents the primary revenue engine, bringing in 7,87,549.89 in total sales across 5,577 items. In contrast, Supermarket Type3 brings in 1,30,714.67 sales across 935 items, while standard Grocery Stores generate 1,51,939.15 sales across 1,083 items but maintain the lowest item visibility profile.

### Recommendations for Improvements

Optimize Grocery Store Item Visibility: Grocery stores currently exhibit the highest aggregated item visibility index (113.57) relative to their lower sales volume (1,51,939.15). The placement strategy should be restructured to prioritize high-margin categories instead of over-exposing lower-performing inventory.

Replicate Supermarket Type1 Operational Model: Supermarket Type1 is the clear performance benchmark with 7,87,549.89 in sales. A detailed audit of their inventory mix and operational strategies should be conducted to apply those practices to Supermarket Type2 (1,31,477.78 sales) and Supermarket Type3 (1,30,714.67 sales) to lift their lagging revenue numbers.

Expand High-Value Product Stocking in Tier 3 Outlets: Since Tier 3 regions represent the highest revenue sector at 472.13K, inventory allocation for the top two revenue-generating categories (Fruits/Vegetables and Snack Foods, both at 0.18M) should be increased by 15-20% in these locations to capitalize on high consumer demand.

Address the 2019-2020 Performance Drop: Dashboard historical charts reveal a sharp decline in sales from the 2018 peak (205K) down to 2020 (129K). Operational data from that specific timeframe should be isolated and analyzed to establish safeguards against recurring supply chain disruptions or management inefficiencies.


##### Contact
Author: @rt5899-art# Blinkit_Analysis
