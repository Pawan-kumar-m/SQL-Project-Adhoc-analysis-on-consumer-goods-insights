# SQL-Project-Adhoc-analysis-on-consumer-goods-insights
## Project Details

1. **Atliq Hardwares** is a leading computer hardware producer in India and other countries(imaginary company FYI).
2. The management wants to expand their data analytics team by hiring junior data analysts.
3. The task involves running SQL queries to answer 10 ad-hoc requests.

## Concepts Used

1. **Common Table Expressions (CTEs)**: Used to break down complex queries into manageable parts and improve readability.
2. **Window Functions**: Employed to rank products within each division based on total sold quantities.
3. **Aggregate Functions**: Utilized to calculate total sold quantities, average discount percentages, and gross sales amounts.
4. **Joins**: Performed to combine data from multiple tables, such as `fact_sales_monthly` and `dim_product`.
5. **Filtering and Sorting**: Applied to filter results based on specific criteria and sort them in descending order.

## What I Learned from the SQL Queries

1. **Importance of proper table aliasing**: Using meaningful aliases for tables makes the queries more readable and easier to understand.
2. **Grouping and aggregating data**: Grouping data by relevant columns and using aggregate functions like `SUM()`, `AVG()`, and `COUNT()` is crucial for calculating insights.
3. **Ranking and partitioning**: Window functions like `RANK()` and `PARTITION BY` allow for ranking products within each division based on total sold quantities.
4. **Filtering and sorting results**: Applying `WHERE` and `ORDER BY` clauses helps in filtering and sorting the final output as per the requirements.

By working through the SQL queries provided in the `SQL PROJECT: ADHOC ANALYSIS ON CONSUMER GOODS INSIGHTS OF ATLIQ HARDWARE` file, I gained valuable experience in solving real-world business problems using SQL. The queries cover various aspects of data analysis, from calculating product rankings to generating reports for specific customer segments and time periods. Practicing these queries has improved my understanding of SQL concepts and their practical applications in a business context.

This Project was given by [codbasics](https://codebasics.io/challenge/codebasics-resume-project-challenge)
