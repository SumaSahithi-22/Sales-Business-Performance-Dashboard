# Sales & Business Performance Dashboard

## 📊 Project Overview
The **Sales & Business Performance Dashboard** provides insights into sales trends, regional performance, and customer order behavior.  
This project demonstrates how business data can be analyzed using **SQL Server** and visualized using **Power BI** to support data-driven decision making.

The dashboard helps stakeholders monitor key metrics such as revenue growth, order volume, and regional sales performance.

---

## 🛠 Tools & Technologies
- Microsoft Power BI – Data visualization and dashboard creation
- Microsoft SQL Server – Data querying and analysis
- Microsoft Excel – Data preprocessing and validation

---

## 📁 Dataset
The dataset contains sales transaction details including:

- SalesOrderNumber
- CustomerKey
- SalesTerritoryKey
- OrderDate
- ShipDate
- OrderQuantity
- SalesAmount
- TaxAmount

---

## 📈 Dashboard Features
The dashboard includes several visualizations for business analysis:

- **KPI Cards**
  - Total Sales
  - Total Orders
  - Total Quantity Sold
  - Average Order Value

- **Sales Trend Analysis**
  - Line chart showing monthly or yearly sales performance

- **Regional Sales Analysis**
  - Clustered column chart comparing sales across territories

- **Order Quantity Distribution**
  - Bar chart showing order quantity patterns

- **Sales vs Tax Comparison**
  - Donut chart showing tax contribution

- **Shipping Performance**
  - Analysis of order and shipping dates

- **Interactive Filters**
  - Date slicer
  - Territory slicer
  - Shipment mode filter

---

## 🧮 Sample SQL Queries

### Total Sales
```sql
SELECT SUM(SalesAmount) AS Total_Sales
FROM Orders;
