# Supermarket Sales Analysis Dashboard

## Project Overview

This project analyses the supplied BlinkIT Grocery Data and presents key
findings in an Excel dashboard. It uses Excel Tables, PivotTables,
PivotCharts and a scatter chart to explore sales across product
categories, outlet types, outlet locations and item fat content.

## Objectives

-   Review overall sales performance and summary measures.
-   Compare total sales across product categories.
-   Compare sales across outlet types and outlet location tiers.
-   Examine sales contribution by item fat content.
-   Compare average sales across product categories.
-   Explore the relationship between item visibility and sales.
-   Present the analysis in a clear Excel dashboard.

## Workbook Sheets

  Sheet                    Purpose
  ------------------------ -------------------------------------
  `BlinkIT Grocery Data`   Source records
  `Pivot_Analysis`         Total sales by product category
  `KPI_Summary`            Key performance indicator summary
  `Charts`                 Individual visualisations
  `Dashboard`              Consolidated dashboard presentation

Update these names if your final workbook differs.

## Charts

1.  Total Sales by Product Category --- horizontal bar chart.
2.  Total Sales by Outlet Type --- clustered column chart.
3.  Total Sales by Outlet Location --- clustered column chart.
4.  Sales by Fat Content --- doughnut chart.
5.  Average Sales by Product Category --- horizontal bar chart.
6.  Product Visibility vs Sales --- scatter chart (X: Item Visibility;
    Y: Sales).

## Tools

Microsoft Excel, Excel Tables, PivotTables, PivotCharts and chart
formatting.

## How to Use

1.  Open the Excel workbook.
2.  Review the source records in `BlinkIT Grocery Data`.
3.  Inspect the supporting PivotTables and charts.
4.  Open `Dashboard` for the consolidated view.
5.  If source data changes, refresh the PivotTables and check the
    charts.

## Data Preparation and Limitations

-   Standardise fat-content labels before refreshing the related
    PivotTable. For example, group `LF` with `Low Fat`, and `reg` with
    `Regular`, if these labels occur in the source data.
-   The scatter chart shows association, not proof that visibility
    causes higher sales.
-   The supplied dataset does not provide a transaction date suitable
    for monthly sales trend analysis in this project.
-   Results depend on the supplied dataset and the workbook's current
    PivotTable configuration.

## Repository Contents

-   `README.md` --- project overview.
-   `PROJECT_DOCUMENTATION.pdf` --- detailed documentation.
-   `LICENSE` --- MIT License.
-   `.gitignore` --- ignores temporary and Excel lock files.
-   Final Excel `.xlsx` workbook --- add this file to the repository
    before publishing.

## Author

JOSIYA ANTONY
