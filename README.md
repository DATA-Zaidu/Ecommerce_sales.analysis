🛒 E-Commerce Sales Analysis
End-to-End Exploratory Data Analysis (20,000+ Orders)
📌 Project Overview

This project performs a complete exploratory data analysis (EDA) on an e-commerce dataset containing 20,000+ customer orders using Python and Pandas.
The objective is to uncover revenue drivers, customer purchasing patterns, payment preferences, and product performance to support data-driven business decisions.

This project simulates the day-to-day analysis work of a Data Analyst / MIS / Reporting role, focusing on insight generation rather than just visualization.

🎯 Business Questions

Which states contribute the highest revenue?

How does revenue trend over time, and are there seasonal patterns?

On which days do customers place the most orders?

What payment methods do customers prefer?

Which products generate the highest sales volume?

🗂️ Project Structure

ecommerce-portfolio/
│

├── Python/

│   └── Ecommerce_Analysis.ipynb     # Complete analysis notebook
│

├── Visuals/

│   ├── state_revenue.png

│   ├── monthly_revenue.png

│   ├── orders_weekday.png

│   ├── payment_share.png

│   └── top_products.png
|
├── requirements.txt

└── README.md

🛠️ Tools & Technologies

Python

Pandas — data cleaning & aggregation

Matplotlib — data visualization

Jupyter Notebook / Google Colab

📊 Dataset Summary

Orders: 20,000+

Data Level: Order-level transactional data

Key Fields:

Order Date

State

Product Category

Revenue

Payment Method

Customer ID

📈 Key Metrics (KPIs)

Metric	Description
Total Revenue	Sum of all completed order values
Total Orders	Count of all orders
Unique Customers	Distinct customer count

These KPIs provide a high-level snapshot of business performance.

🔍 Analysis Performed

✔ Data Cleaning

Converted date columns to datetime format

Removed null values

Removed duplicate orders

Standardized column names

✔ Exploratory Analysis

State-wise revenue aggregation

Monthly revenue trend analysis

Order distribution by weekday

Payment method share

Top-selling product analysis

✔ Visualization

All visualizations are saved automatically inside the Visuals/ folder using:

plt.savefig("plots/figure_name.png", dpi=300, bbox_inches="tight")

🧠 Key Insights & Findings

⭐ 1. Revenue Concentration by State

Delhi, Maharashtra, Gujarat, and Karnataka contribute the highest revenue.

Indicates strong demand concentration in major commercial regions.

⭐ 2. Monthly Revenue Trends

Revenue increases sharply between March to May.

Suggests seasonal purchasing behavior, possibly driven by sales campaigns or festive demand.

⭐ 3. Weekday Ordering Behavior

Thursday and Friday show the highest order volume.

Sunday records the lowest activity, indicating weaker weekend demand.

⭐ 4. Payment Preferences

Cash on Delivery (COD) remains the dominant payment method.

Online payments are increasing but still trail COD usage.

⭐ 5. Best-Selling Products

Top-performing products include:

Smartphones

Jeans

Smartwatches

Shoes

Jackets

These products drive a significant portion of total sales volume.

💡 Business Implications

High-revenue states should be prioritized for inventory and marketing investments.

Seasonal peaks (March–May) can be leveraged with targeted promotions.

COD dominance highlights the need for trust-building incentives for digital payments.

Top-selling products are strong candidates for bundling and upsell strategies.
