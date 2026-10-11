# B2B Invoice Sales Analysis Dashboard

## Project Overview
This project focuses on cleaning, preparing, and analyzing Business-to-Business (B2B) invoice data to understand sales performance, revenue, costs, profit margins, customer activity, and product performance.

The project uses Microsoft Excel for data preparation and Tableau for interactive data visualization.

## Project Objectives
- Clean and prepare raw B2B invoice data.
- Analyze revenue, costs, and profit margins.
- Understand sales performance across product categories and customer segments.
- Identify top-performing products.
- Analyze order trends and delivery times.
- Build a Tableau dashboard to present key business insights.

## Tools and Technologies
- **Microsoft Excel** — Data cleaning and preparation
- **Tableau** — Data visualization and dashboard development
- **CSV** — Raw dataset format
- **XLSX** — Cleaned dataset format

## Dataset Overview
The original dataset contains **6,059 rows and 15 columns**. The cleaned dataset contains **6,001 rows and 14 columns**.

The cleaned dataset includes the following fields:

| Column | Description |
|---|---|
| Order Date | Date the order was placed |
| Customer ID | Unique customer identifier |
| Customer | Customer or business name |
| Product ID | Product identifier |
| Product | Product name |
| Category | Product category |
| Segment | Customer or sales segment |
| Quantity | Quantity ordered |
| Unit Cost | Cost per unit |
| Unit Price | Selling price per unit |
| Revenue | Revenue generated |
| Cost | Total product cost |
| Margin | Difference between revenue and cost |
| Ship Date | Date the order was shipped |

## Data Cleaning and Preparation
The raw invoice data was prepared for analysis in Excel.

The project includes:
- Reviewing the original dataset and its structure.
- Inspecting missing values and inconsistent records.
- Preparing date fields for analysis.
- Reviewing invoice, customer, and product information.
- Removing records that were not retained in the cleaned dataset.
- Preparing the final dataset with consistent column names.
- Checking the cleaned data for missing values.

The final cleaned dataset contains 6,001 records and 14 columns, with no missing values in the inspected fields.

## Tableau Dashboard

The Tableau workbook contains visualizations covering the following business metrics:

### Key Performance Indicators (KPIs)
- Total Revenue
- Total Orders
- Total Customers
- Total Quantity
- Average Order Value

### Charts and Analysis
- **Average Days to Deliver by Category:** Compares average delivery time across product categories.
- **Daily Orders Trend:** Tracks order activity over time.
- **Daily Revenue Trend:** Shows daily revenue trends.
- **Profit:** Provides a view of profitability.
- **Revenue by Segment:** Compares revenue across customer segments.
- **Revenue vs. Margin by Category:** Compares revenue and margin across categories.
- **Top 10 Products by Revenue:** Identifies products generating the most revenue.

## Files Included
- `b2b_invoices.csv` — Original raw dataset.
- `b2b_invoices_Cleaned(3).xlsx` — Cleaned dataset.
- `Sales Performance Dashboard.twb` — Tableau workbook containing the visualizations and dashboard.

## Key Learnings
- Preparing business transaction data for analysis.
- Working with dates, revenue, costs, and profit margins.
- Comparing sales performance across categories and segments.
- Analyzing product and customer performance.
- Building KPI views and charts in Tableau.
- Turning invoice data into business-focused visualizations.

## Conclusion
This project demonstrates a B2B sales analysis workflow, from raw invoice data preparation to interactive dashboard development in Tableau. It showcases practical skills in data cleaning, spreadsheet analysis, business metrics, and data visualization.

## Author
Esakkimuthu
