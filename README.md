BMW Sales Dashboard — Power BI Project
Overview

This project presents an interactive Power BI dashboard that analyzes BMW sales performance across regions, models, fuel types, and years.
The dashboard helps visualize key metrics, uncover sales insights, and support data-driven decisions for business stakeholders.

Objectives

Visualize total BMW sales (USD) by region and model.

Analyze sales volume trends across years and fuel types.

Compare performance by color and transmission type.

Highlight top-selling models and regions using KPIs.
Dataset Information

The project uses two structured tables:

1. DIM_BMW_Sales_Data
Column	Description
Model	BMW vehicle model
Region	Market region (Africa, Asia, Europe, etc.)
Color	Vehicle color
Fuel_Type	Hybrid, Petrol, Diesel, Electric
Transmission	Gear type
Model_Key	Unique model identifier
Sales_Classification	Model grouping for analysis
2. FACT_BMW_Sales_Data
Column	Description
Price_USD	Sales price of the vehicle
Sales_Volume	Number of units sold
Engine_Size_L	Engine capacity in liters
Mileage_KM	Vehicle mileage
Year	Sales year
Dashboard Pages
Page 1 — BMW Sales Summary

KPI Card: Displays total BMW sales value in USD.

Bar Chart: Price distribution by model.

Column Chart: Yearly sales volume trends.

Donut Chart: Sales share by fuel type.

Table: Price breakdown by model and region.

Includes professional header with author, title, and report date.

Page 2 — Model Performance Analysis

Horizontal Bar Chart: Average sales volume per model.

Stacked Bar Chart: Model sales volume by fuel type.

Clustered Column Chart: Sales volume by model and color.

Design Highlights

Modern blue gradient background with a clean layout.

Consistent theme colors and visual alignment.

Emphasis on clarity, storytelling, and interactivity.

Uses slicers for dynamic filtering by Model, Region, and Year.

Optimized for executive reporting and easy interpretation.

Tools & Techniques

Power BI Desktop — visualization and report building

DAX (Data Analysis Expressions) — custom measures and KPIs

Excel / CSV Data — source data

Data Modeling — relationship between Dimension and Fact tables

Dashboard Preview
![alt text](https://github.com/briankorir006-a11y/BMW_SALES_PERFORMANCE_DASHBOARD/blob/main/ASSET/IMAGE%201.png?raw=true)
![alt text](https://github.com/briankorir006-a11y/BMW_SALES_PERFORMANCE_DASHBOARD/blob/main/ASSET/IMAGE%202.png?raw=true)







	
How to Use

Download the .pbix file from this repository.

Open in Power BI Desktop (latest version).

Explore visuals, apply filters, and interact with the dashboard to uncover insights.

👤 Author

Created by: Brian Kipkorir Kiptoo
Date: October 18, 2025
Tools: Power BI, Excel, DAX

