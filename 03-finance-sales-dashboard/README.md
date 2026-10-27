# Finance Sales Performance Dashboard

## Overview

This project uses an assignment-provided Excel workbook, `Finance.xlsx`, to create a financial sales report in Microsoft Power BI.

The project focuses on comparing sales and profit across years, products, customer segments, discount bands, and countries.

## Tools

- Microsoft Power BI
- Microsoft Excel
- DAX calculated columns and measures


## Calculations

**Profit calculated column**

`Profit = Sales - COGS`

**Profit Margin measure**

`Profit Margin = SUM(Profit) / SUM(Sales)`

The Profit Margin measure should be formatted as a percentage with two decimal places.

## Dashboard Pages

The following pages and visualisations:

- **Sales:** Sales and profit comparisons by year, product, segment, and discount band, with a country slicer.
- **Sales by Country:** A treemap for sales and a funnel visual for profit by country, supported by a narrative.
- **Profit:** A visual using the calculated Profit column.
- **Profit Margin:** A visual using the Profit Margin measure.
- **Sales Progress:** A waterfall chart showing sales progress by year.
- **Profit Progress:** A waterfall chart showing profit progress by year.

The published Power BI report should be checked to confirm which of these requirements were implemented.

## Files

- `dashboard.pbix` — Power BI report.
- `screenshots/` — Dashboard screenshots.

## Data Disclaimer

It should not be represented as financial reporting for an actual business operated or advised by the author.

## Viewing

Open `dashboard.pbix` in Microsoft Power BI Desktop. If the report depends on the Excel workbook at a local file path, update the data source path before refreshing.
