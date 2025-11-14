# Sales Order Analysis Using Power BI & Excel

## Project Overview

This repository presents a formal analytical solution for the comprehensive analysis of sales order data using Microsoft Power BI in conjunction with Excel datasets. The project facilitates advanced data-driven decision-making and performance insights for business stakeholders by leveraging interactive dashboards and robust key performance indicators (KPIs).


## Dataset Description

### [Orders.csv](https://github.com/Neha-Ydv/sales-order-analysis-powerbi-excel/blob/main/Orders.csv)

This file contains primary sales order data with attributes such as:
- **Order ID**: Unique identifier for each order
- **Customer Name**
- **Order Date**
- **Region**
- **Total Amount**

### [Details.csv](https://github.com/Neha-Ydv/sales-order-analysis-powerbi-excel/blob/main/Details.csv)

This supplementary file provides line-item details linked to each order:
- **Order ID**: Foreign key to Orders.csv
- **Product Name**
- **Quantity**
- **Unit Price**
- **Discount Applied**

## Power BI Dashboard Explanation

The interactive dashboard is developed using [Sales_Dashboard.pbix](https://github.com/Neha-Ydv/sales-order-analysis-powerbi-excel/blob/main/Sales_Dashboard.pbix). It integrates both datasets to deliver a unified business intelligence platform where users can drill down through sales trends, customer profiles, and product performance with dynamic filters and slicers.

## KPIs Utilized

- **Total Sales Revenue**
- **Average Order Value**
- **Number of Orders per Month**
- **Top-Performing Regions**
- **Most Popular Products**
- **Total Discount Impact**
- **Sales Growth Rate**

<img width="1303" height="731" alt="Screenshot 2025-11-14 144339" src="https://github.com/user-attachments/assets/67e4318e-9d7d-45e9-9e66-1deb07953a61" />


## Analytical Workflow

1. **Data Importation**: Ingest `Orders.csv` and `Details.csv` into Power BI.
2. **Data Preparation**: Clean, validate, and establish relational connections using Power Query and data model setup.
3. **Metric & KPI Construction**: Define DAX formulas for business KPIs and calculated fields.
4. **Dashboard Design**: Develop interactive reports with suitable chart types, filters, and navigation controls.
5. **Insight Extraction**: Contextual review of results to identify actionable business opportunities.

## Key Insights

- Identification of high-performing regions and product categories
- Seasonality patterns affecting order volumes
- Quantitative evaluation of discount strategies on overall sales
- Opportunities detected for cross-selling and upselling based on purchasing trends

## Skills Demonstrated

- Power BI dashboard development and DAX programming
- Excel-based data management and preprocessing
- Data cleaning and transformation (Power Query)
- Business intelligence reporting
- Data visualization and interpretation
- Professional report documentation

## Conclusion 

This repository serves as a formal showcase of sales analytics best practices through clear presentation, structured data processing, and advanced visualization techniques. It is suitable as a template or starting point for organizational analytics initiatives. Contributions, suggestions, and improvements are welcomed via Issues and Pull Requests.

---

**Repository Owner:** Neha-Ydv  
**License:** MIT  
