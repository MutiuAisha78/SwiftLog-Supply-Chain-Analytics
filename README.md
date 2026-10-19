Technical Architecture & Data Pipeline
1. Extract, Transform, Load (ETL)
Utilized Power Query to clean, shape, and merge multi-table relational datasets covering Orders, Customers, Inventory, Shipments, Suppliers, and Products.
Normalized text strings, handled null values, formatted currency attributes, and validated date fields for accurate time-intelligence analysis.
2. Data Modeling (Star Schema)
Structured an optimized Star Schema with central Fact tables (Orders, Shipments) linked to Dimension tables (Customers, Products, Warehouses, Suppliers).
Created a dedicated Date Dimension Table for continuous time-series calculations.
3. Analytics Engine (DAX)
Engineered dynamic Data Analysis Expressions (DAX) measures, including:
Revenue Metrics: Total Revenue, Average Order Value (AOV), Revenue per Customer.
Logistics KPIs: Fulfillment Lateness Rate (%), Dispatch Deficit Rate (%).
Inventory KPIs: Inventory Turnover Ratio, Safety Stock Deficit Alerts.
 Dashboard Suite Architecture
The interactive Power BI solution consists of 5 dedicated views:
Executive Dashboard: High-level financial KPIs, revenue breakdown by region and category, and fulfillment efficiency summaries.
Customer Analytics Dashboard: Account-level transaction history, geographic concentration, and customer lifetime value (CLV) ranking.
Inventory & Warehouse Dashboard: Warehouse capacity utilization, SKU turnover speeds, and stockout vulnerability alerts.
Logistics & Fulfillment Dashboard: Dispatch lead-time tracking, 3PL carrier SLA compliance, and return reason breakdown.
Supplier & Product Performance Dashboard: Vendor volume contribution, defect rates, and inventory reorder planning.
 
 Strategic Recommendations
Enforce Logistics SLAs: Implement strict dispatch windows and contractual penalty clauses for third-party logistics providers to reduce the 40% delivery delay rate.
Automate Warehouse Barcode Verification: Introduce mandatory pre-shipment barcode scanning at fulfillment centers to eliminate the 33% wrong-item dispatch return rate.
Deploy Automated Inventory Reordering: Utilize dynamic DAX safety-stock threshold triggers within Power BI to automatically alert procurement prior to stock depletion on high-turnover SKUs.
