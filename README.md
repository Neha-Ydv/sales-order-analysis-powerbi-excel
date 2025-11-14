# Indica eCommerce — Sales Order Analysis Using Power BI & Excel

## Project Overview

This repository provides a formal and comprehensive analytical framework for evaluating sales order data for **Indica eCommerce**, leveraging Microsoft Power BI alongside Excel datasets. The objective is to facilitate advanced, data-driven decision-making for business stakeholders through interactive dashboards and robust key performance indicators (KPIs), tailored specifically for the eCommerce domain.

## Dataset Description

### [Orders.csv](https://github.com/Neha-Ydv/sales-order-analysis-powerbi-excel/blob/main/Orders.csv)

The primary sales order dataset contains:
- **Order ID**: Unique identifier for each order
- **Customer Name**
- **Order Date**
- **Region**
- **Total Amount**

### [Details.csv](https://github.com/Neha-Ydv/sales-order-analysis-powerbi-excel/blob/main/Details.csv)

The supplementary line-item dataset includes:
- **Order ID**: Foreign key referencing Orders.csv
- **Product Name**
- **Quantity**
- **Unit Price**
- **Discount Applied**

## Power BI Dashboard Overview

The interactive dashboard, created in [Sales_Dashboard.pbix](https://github.com/Neha-Ydv/sales-order-analysis-powerbi-excel/blob/main/Sales_Dashboard.pbix), integrates both datasets to deliver a unified business intelligence solution focused on Indica eCommerce operations. Users are provided with dynamic filters and slicers, enabling in-depth exploration of sales trends, customer segmentation, and product performance metrics.

## Key Performance Indicators (KPIs)

- **Total Sales Revenue**
- **Average Order Value**
- **Orders per Month**
- **Top-Performing Regions**
- **Most Popular Products**
- **Total Discount Impact**
- **Sales Growth Rate**

<img width="1303" height="731" alt="Screenshot 2025-11-14 144339" src="https://github.com/user-attachments/assets/67e4318e-9d7d-45e9-9e66-1deb07953a61" />

## Analytical Workflow

1. **Data Importation**  
   Import `Orders.csv` and `Details.csv` into Power BI.

2. **Data Preparation**  
   Cleanse and validate data; establish relationships between datasets utilizing Power Query and data modeling features.

3. **Metric & KPI Construction**  
   Develop and implement DAX formulas dedicated to eCommerce-specific KPIs and calculated measures for Indica eCommerce.

4. **Dashboard Design**  
   Construct interactive reports with visually suitable chart types, relevant filters, and easy-to-navigate controls tailored for retail analytics.

5. **Insight Extraction**  
   Perform contextual analysis to extract actionable business insights and identify opportunities for operational enhancement.

## Insights

- Identification of high-performing regions and product categories within Indica eCommerce
- Analysis of seasonality effects and the impact of promotional campaigns on order volumes
- Quantitative assessment of discount strategies and their influence on sales and profit margins
- Recognition of cross-selling and upselling opportunities based on customer purchasing trends

## Conclusion

This repository exemplifies sales analytics best practices for Indica eCommerce, featuring clear presentation, structured data management, and advanced visualization methodologies. It is intended as a template or foundation for organizational analytics in the eCommerce sector. Contributions, suggestions, and enhancements are welcome through Issues and Pull Requests.

---

**Repository Owner**: [Neha-Ydv](https://github.com/Neha-Ydv)
