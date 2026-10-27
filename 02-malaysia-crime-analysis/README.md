# Malaysia Crime Data Analysis

## Overview

This project uses Malaysian crime statistics obtained from the official data.gov.my data catalogue to build a Power BI data visualisation report.

The purpose is to explore the available crime statistics and communicate patterns using interactive visuals.

## Data Sources

The project files include the following datasets:

- `crime_district.csv` — crime statistics by district and crime category.
- `population_district.csv` — population estimates by administrative district.
- `population_malaysia.csv` — national population statistics.

Official catalogue: https://data.gov.my/data-catalogue

Dataset pages:

- Crime by district: https://data.gov.my/data-catalogue/crime_district
- Population by district: https://data.gov.my/data-catalogue/population_district
- National population: https://data.gov.my/data-catalogue/population_malaysia

The crime dataset's definitions and coverage should be checked before interpreting its counts. Crime counts, reported incidents, and cases resulting in conviction are not interchangeable measures.

## Tools

- Microsoft Power BI
- Public statistical datasets
- Data cleaning and visualisation

## Analytical Scope

The dashboard should be interpreted according to the fields and visuals actually implemented in the Power BI report. Potential areas of analysis include crime categories, geographical comparisons, and trends over time.

Population-adjusted crime rates should only be calculated if the crime and population data have compatible geographical boundaries and time periods.

## Files

- `dashboard.pbix` — Power BI report.
- `data/README.md` — Source descriptions and data limitations.
- `screenshots/` — Dashboard screenshots, if available.

## Data Attribution

The data was obtained from Malaysia's official data catalogue. Credit the original publisher and retain the dataset definitions and applicable licence information when reusing the data.

## Limitations

Official statistics reflect the definitions, coverage, and collection practices specified by the data publisher. District boundaries and reporting units may differ between crime and population datasets.

The dashboard is a descriptive analysis and should not be used by itself to infer the causes of crime or to rank locations without considering population, coverage, and other relevant context.
