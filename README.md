## Project Overview

Developed an end-to-end **Forecasting Analytics and Demand Planning Performance Analysis** project for a simulated FMCG company, **ABC FMCG Ltd.**, using **SQL, Excel, and Power BI**.

The project focuses on analyzing historical demand, sales, forecasts, inventory, promotions, holidays, customers, channels, products, and regional performance to evaluate **forecast quality, demand patterns, inventory risks, and planning performance**.

The business objective is to identify issues such as **stockouts, excess inventory, poor forecast accuracy, forecast bias, inconsistent demand, and regional demand variation**, and convert the analysis into actionable demand-planning recommendations.

## Data Architecture

The project follows a **Medallion Architecture**:

* **Bronze Layer** – Raw CSV data ingestion
* **Silver Layer** – Cleaned and validated data
* **Gold Layer** – Analytics-ready data model and business analysis

The database contains a central **Fact Forecast Demand** table connected with dimension tables for:

* Products
* Customers
* Channels
* Regions
* Warehouses
* Promotions
* Holidays

The dataset contains key operational measures including:

* Actual Demand Quantity
* Forecast Quantity
* Sales Quantity
* Sales Value
* Opening Inventory
* Closing Inventory
* Safety Stock
* Reorder Point
* Lead Time
* Lost Sales
* Returns
* Stockout Flag
* Discount Percentage

## Current SQL Analysis

The current stage of the project includes **Exploratory Data Analysis (EDA)** using SQL.

The analysis covers:

### Sales & Demand Analysis

* Total Sales
* Total Demand
* Total Forecast Quantity
* Sales performance by product
* Sales performance by category

### Regional Analysis

* Sales by country
* Sales by region
* Sales by zone
* Forecast quantity by region
* Actual demand by region

### Channel Analysis

* Sales by channel
* Lost sales by channel
* Forecast vs actual demand by channel

### Customer Analysis

* Customer sales performance
* Sales quantity by customer
* Lost sales by customer
* Customer type analysis

### Promotion Analysis

* Sales by promotion
* Promotion type performance

### Holiday Analysis

* Sales performance by holiday
* Holiday type analysis

### Time-Based Analysis

* Monthly sales analysis
* Weekly sales analysis
* Holiday and monthly sales relationships

These analyses align with the project brief's EDA requirements covering **sales, demand, forecasts, products, regions, channels, customers, promotions, holidays, and monthly/weekly trends**.

## Planned Forecasting Analysis

The core phase of the project will evaluate forecasting performance using:

* Forecast Error
* Forecast Accuracy
* Forecast Bias
* MAPE
* WAPE
* MAE
* MAD
* RMSE
* Tracking Signal

Forecast performance will be analyzed across:

* Products
* Categories
* Brands
* Regions
* Warehouses
* Customers
* Channels
* Months
* Quarters

These metrics and dimensions are specifically required in the project brief as the core **Forecast Analysis** phase.

## Further Business Analysis

The project will also investigate:

### Variance Analysis

* Forecast vs Actual Demand
* Sales vs Forecast
* Forecast vs Inventory
* Forecast Variance Quantity
* Forecast Variance Percentage
* Over-forecasted products
* Under-forecasted products

### Inventory Analysis

* Opening Inventory
* Closing Inventory
* Safety Stock
* Reorder Point
* Stockouts
* Lost Sales
* Excess Inventory

### Promotion & Holiday Impact

* Promotion Lift
* Sales Lift
* Demand Lift
* Holiday demand impact
* Forecast performance during holidays

### Root Cause Analysis

The project will investigate potential causes of forecast errors, including:

* Promotions
* Holidays
* Stockouts
* Demand spikes
* Discounts
* Lead time
* Warehouse issues

The objective is not only to identify that forecast performance is poor, but to determine **why the forecast is inaccurate and what operational actions can improve demand planning**.

## Tools & Technologies

**SQL Server**

* Data ingestion
* Data cleaning
* Data validation
* Joins
* Aggregations
* CTEs
* Window Functions
* Date Functions
* Forecast KPI calculations
* Analytical queries

**Excel**

* Data validation
* PivotTables
* PivotCharts
* Forecast calculations
* Error metrics
* Ad-hoc analysis

**Power BI**

* Data modeling
* DAX
* Interactive dashboards
* KPI visualization
* Trend analysis
* Drill-down analysis
* Executive storytelling

The project brief specifically recommends SQL, Excel, and Power BI for these analytical stages.

## Final Power BI Dashboard

The planned Power BI report will contain:

1. Executive Dashboard
2. Demand Trends
3. Forecast Performance
4. Product Analysis
5. Regional Analysis
6. Customer & Channel Analysis
7. Inventory Analysis
8. Promotion & Holiday Analysis
9. Root Cause Analysis
10. Recommendations

This structure follows the recommended business reporting structure in the project brief.

## Expected Business Outcome

The final analysis will help management:

* Improve forecast accuracy
* Reduce forecast bias
* Identify high-risk products
* Reduce stockouts
* Reduce excess inventory
* Improve safety-stock decisions
* Understand regional demand variation
* Evaluate promotional demand impact
* Identify recurring forecasting problems
* Improve overall demand-planning performance

The final deliverable will translate analytical findings into **practical recommendations for improving FMCG demand planning and inventory decisions**.

