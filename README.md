# Blinkit Sales Dashboard | Power BI

## Project Overview

This project presents a comprehensive sales analysis dashboard for Blinkit using Power BI. The dashboard helps analyze sales performance, outlet performance, product categories, and customer ratings through interactive visualizations and KPIs.

## Objectives

- Analyze overall sales performance.
- Identify top-performing product categories.
- Compare sales across outlet types and outlet sizes.
- Evaluate outlet performance by location tier.
- Understand customer satisfaction through ratings.

## Dataset Description

The dataset contains information about:

- Item Type
- Outlet Establishment Year
- Outlet Identifier
- Outlet Location Type
- Outlet Size
- Outlet Type
- Item Visibility
- Item Weight
- Sales
- Rating

## Data Cleaning

The following preprocessing steps were performed:

- Handled missing values in Item Weight using average value imputation.
- Corrected data types for Sales, Rating, and Item Weight.
- Checked for inconsistencies and null values.
- Retained Item Visibility values of 0 as valid observations.

## DAX Measures Used

```DAX
Total Sales = SUM('Blinkit'[Sales])

Average Sales = AVERAGE('Blinkit'[Sales])

Average Rating = AVERAGE('Blinkit'[Rating])

No of Outlets = DISTINCTCOUNT('Blinkit'[Outlet Identifier])


```

## Dashboard Features

### KPI Cards

- Total Sales
- Average Sales
- Average Rating
- Number of Outlets
- Total Items

### Visualizations

- Sales by Item Type
- Sales by Outlet Size
- Sales by Outlet Type
- Sales by Outlet Location Type
- Average Rating by Item Type

### Interactive Filters

- Outlet Type
- Outlet Size
- Outlet Location Type

## Key Insights

- Fruits & Vegetables generated the highest sales.
- Medium-sized outlets contributed the largest share of revenue.
- Supermarket Type 1 was the best-performing outlet type.
- Tier 3 locations generated the highest sales.
- Average customer rating remained close to 4 out of 5.

## Dashboard Preview

![Dashboard](Dashboard.jpeg)

## Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel

## Author

**M.V.S.A.L Suvarna**



