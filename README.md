# Sales Analysis Dashboard - Power BI Project

## Overview
This project is a sales analysis dashboard built using a fictitious dataset of food and beverage sales from 2017 to 2019. The goal was to provide insights into total sales, average ticket value, and sales volume across different product categories and time periods.

https://app.powerbi.com/view?r=eyJrIjoiNzExNTRmNDAtNDM5YS00ZjJhLTg0ZmMtNjU3ZWU5MTFkYmMzIiwidCI6IjA1YzA0OGU0LTFhN2YtNDBlOC1iM2M4LWVhY2MyYTc1ZTlkMyJ9

## Steps Taken
### 1. Data Cleaning and Integration:
  - The original sales data was split into three separate tables for the years 2017, 2018, and 2019.
  - Using Power Query, these tables were combined into a single fact table, fVendas, to simplify analysis and reporting.

### 2. Data Model Creation:
  - Created relationships between the fact table and the dimension tables:
  - dVendedor (Salesperson),
  - dCliente (Customer),
  - dProduto (Product),
  - dProdutoGrupo (Product Group).
Established one-to-many relationships to ensure data consistency.

### 3. Creation Calendar Table:
A Calendar Table was generated using DAX to support time-based analysis. This allowed for year-over-year and monthly comparisons.

### 4. DAX Measures:
  - Several DAX measures were created to facilitate key insights:
  - Total Revenue (Faturamento Total)
  - Average Ticket (Ticket Médio)
  - Total Quantity Sold (Quantidade Total)
  - Year-over-Year Comparisons
  - Revenue by Product Category and Team

### 5. Visualizations:
- Key visual elements include:
  - A bar chart comparing current and previous year sales.
  - A donut chart showing revenue by product category (food vs. beverages).
  - A matrix summarizing total sales, average ticket value, and sales quantity by sales team.
  - A bar chart showing the top product groups by total revenue.
  - 
### 6. Tools and Technologies Used:
  - Power Query for cleaning and transforming the data.
  - Power BI for data modeling, visualization, and DAX measures.
  - DAX (Data Analysis Expressions) for creating calculated columns and measures.
 
### Key Learnings:
Data Integration: Combining multiple tables into a single fact table to improve efficiency and insights.
Time Intelligence: Leveraging DAX to generate dynamic date-based calculations.
Effective Visualizations: Creating visual representations that communicate key business insights effectively.
