#  E‑Commerce Sales Analytics Dashboard (Power BI)

Project Overview  
This project is a fully interactive Power BI Sales Analytics Dashboard built to analyze an E‑commerce business using a star‑schema data model.  
It provides actionable insights on sales trends, customer behavior, regional performance, product performance, and profitability.

The dashboard is divided into two pages:

Overview Page
- Total Sales  
- Total Profit  
- Average Order Value  
- Month‑over‑Month (MoM) Growth  
- Sales Trend (Month‑Year)  
- Sales by Product Category  

Deep Insights Page
- Sales by State  
- Sales by City  
- Customer Segment contribution  
- Sales by Payment Mode  
- Top Customers  
- Top Products
  
 Data Model
Your Power BI model includes:

Dimension Tables
- Dim_Product→ Product ID, Category, Subcategory, Default Margin  
- Dim_Customer → Customer ID, Customer Key, Segment  
- Dim_Date→ Date, Month Name, Month Number, Year  
- Dim_Geography→ City, State  

Fact Table
- Fact_Sales 
  - Order ID  
  - Order Date  
  - Customer Name  
  - Customer Segment  
  - Product Category  
  - Quantity  
  - Payment Mode  
  - Discount  
  - Order ID  
  - Sales Amount  
  - Profit  

 Relationships
- Dim_Product → Fact_Sales (Product ID)  
- Dim_Customer → Fact_Sales (Customer ID)  
- Dim_Date → Fact_Sales (Date)  
- Dim_Geography → Fact_Sales (City)  
- All relationships are one‑to‑many, forming a standard star schema.

 Tools & Technologies
- Power BI  
- Power Query  
- DAX  
- Excel/CSV  
- Star Schema Modeling  

Project Structure
Dashboard Insights

 Overview Page
- Total Sales:79.47M  
- Average Order Value: 6.62K  
- Total Profit: 15.06M  
- MoM Growth: 0.09  
- Category-wise sales: Electronics, Home Appliances, Accessories, Books, Clothing  
- Monthly sales trend shows consistent growth with strong end‑of‑year spike.

 Deep Insights Page
- Top States:Maharashtra, Uttar Pradesh, Delhi, Haryana, Tamil Nadu  
- Top Cities:Bengaluru, Mumbai, Delhi, Hyderabad  
- Customer Segment Split:
  - Consumer (largest)  
  - Corporate  
  - Small Business  

- Payment Mode:
  - UPI (45%)
  - Card (30%)
  - COD (25%)

- Top Customers: Based on Order count  
- Top Products: Accessories lead followed by Electronics and Home Appliances

Key Business Insights
- Maharashtra contributes the highest revenue among all states.  
- The Consumer segment drives more than 60% of total sales.  
- UPI is the most preferred payment mode.  
- Accessories outperform other product categories in order volume.  
- Year-end sales spike indicates strong seasonal demand (festive months).
- 
How to Use
1. Download `E-commerce Sales Analytics.pbix`  
2. Open in Power BI Desktop  
3. Review visuals or apply filters  
4. Replace dataset if needed  
5. Refresh the dashboard  

## Author  
Samaira Arora
