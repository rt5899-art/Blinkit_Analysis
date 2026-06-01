# Blinkit Grocery Sales Analysis
A data analytics project exploring sales performance, outlet characteristics, and product trends for Blinkit — India's last-minute grocery delivery app — using Power BI and Excel.

 ## Project Overview
This project analyzes Blinkit's grocery sales data to uncover key business insights around:

Total and average sales performance
Item type popularity and fat content breakdown
Outlet size, location, and establishment trends
Customer ratings across product and outlet segments

The findings are presented through an interactive Power BI dashboard built on top of structured Excel data.

#### Repository Structure
Blinkit_Analysis/
│
├── BlinkIT Grocery Data.xlsx          # Raw dataset with grocery sales records
└── Blikit_power_bi presentation.pbix  # Interactive Power BI dashboard

### Dataset Overview
File: BlinkIT Grocery Data.xlsx
The dataset includes the following key fields:
ColumnDescriptionItem IdentifierUnique product IDItem TypeCategory of the grocery item (e.g., Fruits, Snacks, Dairy)Item Fat ContentWhether the item is Low Fat or RegularItem WeightWeight of the productItem VisibilityDisplay/shelf visibility scoreItem MRPMaximum retail priceOutlet IdentifierUnique outlet IDOutlet SizeSize of the store (Small, Medium, High)Outlet Location TypeTier 1, Tier 2, or Tier 3 cityOutlet TypeStore format (Supermarket, Grocery Store)Outlet Establishment YearYear the outlet was openedItem Outlet SalesTarget variable — total sales for that item at that outletRatingCustomer satisfaction rating

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


### Tools Used
ToolPurposeMicrosoft Power BIDashboard creation and data visualizationMicrosoft Excel (.xlsx)Data storage and preprocessing

### Getting Started
Prerequisites

Microsoft Power BI Desktop (free download)
Microsoft Excel or any compatible spreadsheet viewer

#### Steps

Clone the repository

bash   git clone https://github.com/rt5899-art/Blinkit_Analysis.git
   cd Blinkit_Analysis

Open the dataset (optional — for raw data exploration)

   Open: BlinkIT Grocery Data.xlsx

Open the Power BI dashboard

   Open: Blikit_power_bi presentation.pbix

If prompted to refresh data, point the source to BlinkIT Grocery Data.xlsx in the same folder.


## Key Insights

Low Fat items account for a significant portion of total sales, indicating health-conscious consumer behaviour.
Tier 3 cities contribute surprisingly strong sales volumes, suggesting untapped market potential.
Supermarket Type 1 outlets dominate both in item count and total revenue.
Outlets established around 2018 show the highest average sales performance.
Fruits & Vegetables and Snack Foods are the top-selling categories by volume.


##### Contact
Author: @rt5899-art# Blinkit_Analysis
