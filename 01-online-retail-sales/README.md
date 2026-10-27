# Online Retail Sales Analytics

## Overview

This project demonstrates how a relational SQL database can be connected to Microsoft Power BI to explore sales performance and customer purchasing patterns.

The project was developed as a capstone assignment. Sample customer, product, order, and regional records were manually entered into SQL before being used for dashboard analysis.

## Business Questions

- Which products generate the highest revenue?
- How do sales vary across regions and cities?
- How can monthly sales and profit be compared?
- Which customers purchase most frequently?
- Which payment methods are most commonly used?
- How does profitability vary by product or region?

## Tools

- SQL Server or MySQL, depending on the database used
- Microsoft Power BI
- SQL queries and relational database design

## Database Design

The assignment covers the following tables:

- `Customers`
- `Products`
- `Orders`
- `OrderDetails`
- `Regions`

The intended design uses primary keys to identify records and foreign keys to link related entities.

## Analysis

The planned analysis includes monthly sales, profit and quantity sold, top products by revenue, regional and city sales, customer purchase frequency, payment mode usage, and product-category contribution.

Power BI visualisations are intended to communicate trends and comparisons using charts, maps, and slicers.

## Data Disclaimer

The records were manually entered as sample data for an academic exercise. They are not actual transactions from a verified retail business. Any sales, profit, or customer insights are illustrative.

## Files

- `dashboard.pbix` — Power BI report.
- `sql/` — SQL scripts, if available.
- `screenshots/` — Dashboard screenshots, if available.

## Viewing

Open `dashboard.pbix` in Microsoft Power BI Desktop. To reproduce the SQL analysis, the database schema and sample data must be available and the connection settings must be configured.

## Limitations

The small, manually populated sample dataset is intended for demonstrating SQL and Power BI workflows. It cannot support reliable conclusions about real retail markets or customer behaviour.

