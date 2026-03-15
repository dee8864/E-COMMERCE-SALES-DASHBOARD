# E-COMMERCE-SALES-DASHBOARD
1. Project Title:
"Madhav E-Commerce Sales Dashboard"
An interactive Power BI report built to monitor, analyze, and derive actionable insights from e-commerce sales data — covering revenue, profit trends, customer behavior, product performance, and regional sales distribution.

2. Short Description: 
The Madhav E-Commerce Sales Dashboard is a visually rich and analytically powerful Power BI report designed to give a 360° view of an e-commerce business's performance. It enables business owners, analysts, and decision-makers to track critical KPIs such as total revenue, profit, quantity sold, and Average Order Value (AOV) — all broken down by product category, payment mode, geography, time period, and customer. The dashboard empowers smarter, data-driven decisions by surfacing patterns in purchasing behavior, profitability dips, and regional demand — all within a single, interactive dark-themed interface.

3. Tech Stack:
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop — Primary platform used for designing and publishing the interactive report
📂 Power Query — Used for importing, cleaning, and transforming raw Excel/CSV data before loading into the model
🧠 DAX (Data Analysis Expressions) — Applied for creating calculated measures such as Sum of Amount, Sum of Profit, Sum of Quantity,      and Average Order Value (AOV)
🔗 Data Modeling — Relationships established between order-level fields (Order ID, Category, Sub-Category, PaymentMode, State,            CustomerName) to enable seamless cross-filtering
📁 File Format — .xlsx as the data source; .pbix for development; .png for dashboard preview and documentation


4. Data Source:
Source: Internal E-Commerce Transaction Records (Excel file — Details sheet)
The dataset captures individual order-level transactions with the following key fields:
Order ID - Unique identifier for each transaction (e.g., B-25681)
Amount - Total sale value of the order
Profit - Net profit generated from the order
Quantity - Number of units sold per order
Category - High-level product group — Electronics, Furniture, Clothing
Sub-Category - Detailed product type — Printers, Phones, Bookcases, Saree, Chairs, Hankerchief, Kurti, Trousers, etc.
PaymentMode - Mode of payment — COD, EMI, Credit Card, Debit Card, UPI

The dataset also implicitly contains State and CustomerName fields (visible in the dashboard visuals), enabling geographic and customer-level breakdowns across Indian states like Maharashtra, Madhya Pradesh, Uttar Pradesh, and Delhi.

5. Features:
🔴 Business Problem
E-commerce businesses generate large volumes of transactional data daily, yet without a centralized view, critical questions remain unanswered:

*  Which product categories and sub-categories are driving profit — and which are draining it?
*  Which months show profit dips or losses, and why?
*  Which states and customers contribute the most to revenue?
*  How are customers paying, and does payment mode influence order size?

Without visual analytics, answering these questions requires manual effort across spreadsheets — slow, error-prone, and inefficient.

🎯 Goal of the Dashboard
To build a single-screen, interactive sales command center that:

* Provides instant visibility into overall business health via KPI cards
* Enables quarterly and state-wise filtering for focused analysis
* Breaks down performance by product, geography, customer, and payment mode
* Identifies seasonal profit trends to support inventory and marketing planning


📊 Walkthrough of Key Visuals
📌 KPI Cards (Top Row)
Four headline metrics give an instant business health snapshot:

*  Sum of Amount: 438K — Total revenue generated
*  Sum of Quantity: 5,615 — Total units sold
*  Sum of Profit: 37K — Net profit across all orders
*  Sum of AOV: 121K — Average Order Value, reflecting per-transaction revenue strength

📌 Quarter & State Filters (Top Filters)
Interactive slicers allow users to drill into any specific quarter (Qtr 1–4) or Indian state, dynamically updating all visuals on the page for focused, time-bound or region-specific analysis.
📌 Profit by Month (Bar Chart — Top Right)
A monthly bar chart reveals the profit trajectory across all 12 months. Positive months (January–March, November) are highlighted in blue, while red bars expose loss-making months (notably June–September and December), pointing to mid-year sales slumps that require strategic intervention.
📌 Sum of Profit by Sub-Category (Horizontal Bar Chart)
Ranks product sub-categories by profitability:

*  Printers lead with the highest profit (~9K)
*  Bookcases and Saree follow
*  Accessories and Tables show comparatively lower profit margins this helps in identifying star products vs. underperformers.

📌 Sum of Quantity by Category (Donut Chart)
Displays the volume share across three categories:

*  Clothing: 63% — Dominant category by quantity
*  Electronics: 21%
*  Furniture: 17%
Clothing clearly drives volume, though not necessarily profit — an important distinction for margin analysis.

📌 Sum of Amount by CustomerName (Bar Chart)
Ranks top customers by purchase value:

*  Harivansh appears as the top revenue-generating customer (shown in red, possibly flagged)
*  Followed by Madhav, Madan Mohan, and Shiva
    This visual supports customer retention and VIP prioritization strategies.

📌 Sum of Quantity by PaymentMode (Donut Chart)
Breaks down how customers prefer to pay:

💰 COD: 44% — Cash on Delivery dominates, indicating trust barriers with digital payments
📱 UPI: 21% — Growing digital preference
💳 Debit Card: 13%, Credit Card: 12%, EMI: 10%
Actionable for payment gateway optimization and targeted EMI/discount promotions.

📌 Sum of Amount by State (Horizontal Bar Chart)
Identifies the top revenue-generating Indian states:

*  Maharashtra leads significantly (~100K)
*  Madhya Pradesh follows
*  Uttar Pradesh and Delhi trail behind
*  Useful for logistics planning, regional marketing spend, and expansion targeting.


💼 Business Impact & Insights

📦 Inventory Management: Since Clothing drives 63% of quantity but Printers lead profit, businesses can rebalance stock strategies — reducing low-margin clothing overstock and prioritizing high-margin electronics.
📉 Seasonal Strategy: The mid-year profit dip (June–September) signals the need for targeted promotions, discount campaigns, or new product launches during off-peak months.
🗺️ Regional Focus: Maharashtra's dominance in revenue suggests it as a priority market for ad spend, while Delhi and UP represent growth opportunities.
💳 Payment Optimization: With 44% COD orders, introducing COD-to-digital incentives (cashback on UPI/card) can reduce return rates and improve cash flow.
🙋 Customer Loyalty: Identifying top customers like Harivansh and Madhav opens the door to personalized loyalty programs and repeat purchase campaigns.


6. Dashboard Preview
[Dashboard Preview](https://github.com/dee8864/E-COMMERCE-SALES-DASHBOARD/blob/main/E%20COMMERCE%20ANALYSIS.png)
