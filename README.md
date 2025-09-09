# Real Estate Agency Analysis
**Course:** _DA5020 - Collecting, Storing, and Analyzing Data

## Overview
This project simulates a real-world business analytics engagement for Arvind Choudry, a real estate owner in West Palm Beach, Florida. The objective was to analyze sales performance across his offices and agents, and to generate a polished, executive-ready HTML report with tables, charts, and statistical analysis.

The project integrates data from two sources:
* **Relational database** from MySQL database provided for coursework
* **XML file** containing agency information

**Note:** The shared MySQL database is no longer active, but the full methodology, SQL queries, and R Markdown workflow are documented and reproducible with any MySQL database.

## Files
* `real-estate-agency-analysis.Rmd` - R Markdown file that connects to MySQL database (credentials removed for security) and performs analysis to generate an HTML report.
* `real-estate-agency-report.html` - final rendered report
* `agencies.xml` - XML file containing agency data that was parsed directly from its URL for the report

## Workflow
1. Connect to MySQL database.
2. Parse `agencies.xml` from its URL and load into R.
3. Query sales data using SQL for aggregation and filtering.
4. Perform calculations an visualization.
5. Generate an HTML report.

## Results
The [final report](https://zoechow24.github.io/real-estate-agency-analysis/real-estate-agency-analysis.Rmd) highlights:
* Office-level and agent-level sales performance
* Aggregated statistics and rankings
* Visualization of revenue trends
* Regression modeling insights

## Notes
* The **original Aiven-hosted MySQL database** used in coursework is no longer active.
* All sensitive credentials have been removed.
* To reproduce, replace the database connection settings with your own MySQL instance.
