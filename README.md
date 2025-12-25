# SQL Sales & Revenue Analysis Project

## Overview
This project demonstrates the use of SQL to analyze sales data and answer
real-world business questions. The analysis is performed using a relational
database containing customers, products, and orders, executed inside a
Jupyter Notebook using SQLite.

The project covers SQL fundamentals as well as intermediate concepts such as
multi-table joins, aggregations, conditional logic, and time-based analysis.
The goal is to transform raw transactional data into meaningful business
insights.

## Dataset Description
The database consists of three tables:

- **customers**
  - customer_id
  - name
  - city

- **products**
  - product_id
  - product_name
  - price

- **orders**
  - order_id
  - customer_id
  - product_id
  - quantity
  - order_date

Note: `These tables are linked using primary and foreign keys to enable relational analysis.`

## Tools & Technologies
- SQL (SQLite)
- Python
- Pandas
- Jupyter Notebook

## Key SQL Concepts Demonstrated
- Data retrieval using `SELECT` and `WHERE`
- Aggregate functions: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`
- Multi-table `JOIN` operations
- Revenue calculation using derived metrics
- Conditional logic using `CASE WHEN`
- Date-based analysis using SQL date functions
- Clean and readable SQL with table aliases

## Business Questions Answered
- Total quantity sold by product and by city
- Revenue contribution by city
- Average, minimum, and maximum order values
- Identification of high-value and low-value orders
- Customer spend segmentation
- Monthly revenue trends and time-based performance analysis

## Key Insights
- Revenue was driven more by high-priced products than by order volume alone.
- High-value orders contributed a disproportionate share of total revenue.
- Customer spending patterns varied significantly across the dataset.
- Monthly revenue analysis highlighted the importance of tracking performance
  over time rather than relying only on cumulative totals.

## Reproducibility Note
The notebook includes a data reset step that clears existing records before
data insertion. This prevents duplicate records when the notebook is re-run
and ensures consistent results.

## Conclusion
This project showcases how SQL can be applied to perform end-to-end data
analysis on relational datasets. The same analytical approach can be extended
to larger datasets or integrated with BI and visualization tools such as
Power BI or Tableau.

## Future Improvements
- Add visualizations for revenue trends
- Extend analysis with larger or external datasets
- Integrate with BI tools for dashboarding
