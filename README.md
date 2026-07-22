# Car Sales Dashboard - 2026

A two-page Power BI dashboard analyzing car sales performance by region, category, customer type, and sales channel.

## Key Metrics
- Maximum Sales: ₹5,019.27K
- Product Categories: 4
- Avg Quantity Sold: 0.03K
- Sales Amount (unit price & discount): 72.70K (Goal: 40.40K, +79.92%)

## Features
- Front page with brand showcase
- Filters: Product Category, Payment Method, Region
- Sales by region, customer type, sales channel, and product category

## How I Built It
1. Imported sales transaction data (product category, sales amount, unit price, discount, region, customer type, sales channel) into Power BI
2. Modeled and cleaned data in Power Query
3. Created DAX measures for Max Sales, Sum of Sales Amount, and a Goal measure to track performance vs target
4. Built a KPI card visual to show sales amount against goal with variance %
5. Designed a Front Page with brand logos and a button to navigate to the main Dashboard page
6. Added slicers for Product Category, Payment Method, and Region
7. Built a pie chart (unit price by region), line chart (sales by customer type), and bar charts (sales channel, product category)
8. Used a black/blue theme for contrast

## Tools Used
- Power BI Desktop
- Power Query
- DAX

## Files
- `Car_Sales_Dashboard.pdf` – Static dashboard preview
