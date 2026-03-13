# supply_chain_analysis/Supply Chain Analysis Using Python

This project focuses on analyzing a supply chain dataset to derive actionable business insights using Python. It covers multiple areas including
-revenue analysis by location,
-transportation mode optimization,
-demand forecasting, and-inventory management.

Dataset Overview:
The dataset includes detailed records of 
product types,
sales,
stock levels,
logistics,
manufacturing costs,
inspection outcomes, and
transportation information.
It has 24 columns and captures key dimensions of supply chain operations.

Key Features:
Product type, SKU, Price
Number of products sold, Revenue generated
Availability, Stock levels, Lead times, Order quantities
Manufacturing lead time, Manufacturing costs, Defect rates, Inspection results
Transportation modes, Routes, Costs
Customer demographics, Location

Key Analysis Areas:
1. Revenue by Location
Identified Mumbai and Kolkata as top contributors to total revenue.

Suggested bundling strategies and targeted marketing for other locations.

2. Transportation Mode Strategy
Analyzed cost-effectiveness, average shipping times, and revenue impact of each mode.

Found rail generated the highest revenue, while sea was the most cost-efficient.

3. Demand Forecasting
Used RandomForestRegressor to predict the Number of products sold.

Features selected: price, stock levels, lead times, production volumes, and manufacturing costs.

4. Inventory Optimization
Calculated stock turnover rate to identify fast-moving product categories.

Skincare showed the highest turnover, requiring more frequent restocking.

Tools & Libraries Used:
pandas, numpy – Data manipulation
matplotlib, seaborn – Visualization
sklearn – Machine learning (modeling, training, and evaluation)

Insights Generated:
Road transport is the most cost-effective.
Rail generates the most revenue.
Skincare has the highest sales and stock turnover rate.
Forecasting sales helps in inventory planning and minimizing stockouts.

Business Insights:
sales trends
top products
monthly revenue chart
forecasting

Future Enhancements:
Integrate time-series analysis if timestamp data becomes available.
Add supplier performance metrics.
Explore clustering for customer segmentation.

Folder Structure

├── data/
│   └── supply_chain_data.csv
├── notebooks/
│   └── supply_chain_analysis.ipynb
├── images/
│   └── charts_and_graphs.png
├── README.md
└── requirements.txt

How to Run
Clone the repository

Install dependencies using pip install -r requirements.txt

Open the Jupyter notebook and run the cells
