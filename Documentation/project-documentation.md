
# 📊 AdventureWorks Business Performance Dashboard



## Project Documentation

---

## 1. 📌 Project Overview

The **AdventureWorks Business Performance Dashboard** is an interactive
Business Intelligence project developed using Microsoft Power BI.

The project analyzes sales, profit, tax, order quantity, products,
customers, and geographical performance using the AdventureWorks dataset.

The primary objective is to transform raw transactional data into a
clear and interactive dashboard that helps business users monitor
performance and identify important trends.

---

## 2. 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall sales performance.
- Monitor total profit and profitability.
- Track order quantity and sales order lines.
- Analyze monthly sales trends.
- Identify high-performing products and categories.
- Analyze customer and geographical performance.
- Create interactive KPI cards and visualizations.
- Build reusable DAX measures.
- Apply dimensional data modeling concepts.
- Present business insights through an interactive Power BI dashboard.

---

## 3. 🛠️ Tools & Technologies

| Technology | Purpose |
|------------|---------|
| Power BI Desktop | Dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | Measures and calculations |
| SQL | Data querying and analysis |
| AdventureWorks Dataset | Source data |
| GitHub | Project version control and documentation |

---

# 4. 🗃️ Dataset Description

The project is based on the **AdventureWorks** sample business dataset.

The dataset contains information related to:

- Sales transactions
- Products
- Product categories
- Customers
- Territories
- Dates
- Orders
- Taxes
- Profit
- Sales quantities

The main fact table used in the Power BI model is:

`Fact_Sales3`

Important columns include:

- `CustomerKey`
- `OrderDate`
- `OrderQuantity`
- `ProductKey`
- `Profit`
- `SalesAmount`
- `SalesOrderLineNumber`
- `SalesOrderNumber`
- `SalesTerritoryKey`
- `TaxAmt`
- `UnitPrice`
- `ShipDate`

---

## 🏗️ Data Model

The dashboard uses a dimensional/star-schema approach to organize
sales, customer, product, territory, and date information.

![Data Model](Screenshots/Data-model.png)
