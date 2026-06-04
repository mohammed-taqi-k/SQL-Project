# SQL-Project
SQL Data Analysis project covering basic to advanced SQL concepts including joins, subqueries, window functions, data cleaning, and business insights generation using real-world datasets.

# Global Layoffs Data Cleaning & Exploratory Data Analysis (SQL Project)

## Overview

This project demonstrates a complete SQL data analysis workflow, including data cleaning, transformation, and exploratory data analysis (EDA) on a global layoffs dataset containing over 2,300 records from companies worldwide.

The objective was to transform raw layoff data into a clean, analysis-ready dataset and uncover meaningful business insights using SQL.

---

## Dataset Information

* Records: 2,361
* Features: 9
* Time Period: 2020–2023
* Total Reported Layoffs: 386,379

### Dataset Columns

* Company
* Location
* Industry
* Total Laid Off
* Percentage Laid Off
* Date
* Stage
* Country
* Funds Raised (Millions)

---

## Skills & Technologies Used

* SQL (MySQL)
* Data Cleaning
* Data Transformation
* Exploratory Data Analysis (EDA)
* Common Table Expressions (CTEs)
* Window Functions
* Aggregate Functions
* Data Standardization
* Ranking Functions
* Business Intelligence

---

## Data Cleaning Process

The following data quality issues were addressed:

* Removed duplicate records using ROW_NUMBER()
* Standardized company and industry names
* Trimmed unnecessary spaces
* Converted text dates into DATE format using STR_TO_DATE()
* Handled missing and null values
* Created staging tables to preserve raw data integrity

---

## Exploratory Data Analysis

Key analyses performed include:

* Total layoffs by company
* Total layoffs by industry
* Total layoffs by country
* Year-over-year layoff trends
* Monthly layoff analysis
* Rolling cumulative layoffs
* Top companies by layoffs each year
* Impact analysis based on funding stage

---

## Key Insights

### Top Companies by Layoffs

| Company    | Total Layoffs |
| ---------- | ------------- |
| Amazon     | 18,150        |
| Google     | 12,000        |
| Meta       | 11,000        |
| Salesforce | 10,090        |
| Philips    | 10,000        |

### Top Industries Affected

| Industry       | Total Layoffs |
| -------------- | ------------- |
| Consumer       | 46,682        |
| Retail         | 43,613        |
| Other          | 36,289        |
| Transportation | 31,998        |
| Finance        | 28,344        |

### Top Countries Affected

| Country       | Total Layoffs |
| ------------- | ------------- |
| United States | 256,474       |
| India         | 35,993        |
| Netherlands   | 17,220        |
| Sweden        | 11,264        |
| Brazil        | 10,691        |

### Layoff Events by Year

| Year | Events |
| ---- | ------ |
| 2020 | 635    |
| 2021 | 45     |
| 2022 | 1,213  |
| 2023 | 467    |

---

## Project Structure

```text
├── layoffs.csv
├── layoffs_Taqi.sql
└── README.md
```

---

## How to Run

1. Create a MySQL database.
2. Import `layoffs.csv`.
3. Execute `layoffs_Taqi.sql`.
4. Run the EDA queries to generate insights.

---

## Conclusion

This project demonstrates practical SQL skills used in real-world data analyst roles, including data cleaning, transformation, and business-focused analysis. The insights reveal global workforce trends and the impact of economic conditions on companies across industries.

### Author

**Mohammed Taqi**
Aspiring Data Analyst | SQL | Tableau | Power BI | Python
