Walmart Sales Data Analysis & Business Intelligence Dashboard

Project Overview

This project focuses on analyzing historical sales data from 45 Walmart stores over the period 2010–2012.

The main objective is to explore sales performance, identify business patterns, evaluate the relationship between external factors and sales, and present actionable insights through interactive management dashboards.

The project uses PostgreSQL for data storage and Metabase for data exploration, analysis, and visualization.

Tools & Technologies

- PostgreSQL
- Metabase
- SQL
- Excel / CSV

Dataset Structure

The project uses three main datasets:

- Sales: Historical weekly sales records.
- Stores: Store information, including store type and size.
- Features: External factors such as temperature, fuel price, unemployment rate, holidays, and promotional markdowns.

Project Workflow

1. Organized the source datasets and imported them into PostgreSQL.
2. Connected Metabase to the PostgreSQL database.
3. Explored and analyzed the data using Metabase Query Builder.
4. Used SQL for more advanced analytical queries.
5. Designed management dashboards to visualize sales performance and key business indicators.
6. Interpreted the results to identify patterns and support business decision-making.

Key Analytical Areas

1. Sales Performance Analysis

- Analyzed overall sales performance.
- Explored monthly sales trends.
- Compared sales performance across stores.
- Evaluated average sales across different store types (A, B, and C).

2. External Factors Analysis

- Examined sales patterns during holiday and non-holiday weeks.
- Investigated the relationship between unemployment rates and sales.
- Analyzed sales patterns across different temperature ranges.

3. Promotional Analysis

- Compared average sales during weeks with and without promotional markdowns.
- Investigated promotional effects across individual departments.
- Identified departments with notable differences in average sales.

4. Advanced SQL Analysis

- Combined datasets using multi-condition JOIN operations.
- Applied SQL aggregation and analytical queries.
- Used Window Functions for department ranking and cumulative sales contribution.
- Performed Pareto analysis to examine sales distribution across departments.
- Calculated and compared sales relative to store size.

Key Findings

- Total sales across the analyzed dataset were approximately $6.7 billion.
- Average sales during holiday weeks were approximately 6–7% higher than non-holiday weeks.
- Sales showed a non-linear pattern across temperature ranges, with higher averages observed under moderate temperature conditions.
- Promotional analysis revealed substantial differences across departments; one department showed an approximately 60% higher average sales figure in the promotional group.
- Pareto analysis indicated a relatively balanced distribution of sales across departments rather than strong concentration in a small number of departments.
- One store demonstrated particularly strong sales relative to its size, despite not ranking first in total sales.

Dashboard Previews

The following screenshots show selected visualizations and dashboards developed in Metabase.

Dashboard 1

"Dashboard Screenshot 1" (Screenshot%202026-11-05%20221227.png)

Dashboard 2

"Dashboard Screenshot 2" (Screenshot%202026-11-05%20221237.png)

Dashboard 3

"Dashboard Screenshot 3" (Screenshot%202026-11-05%20221250.png)

Dashboard 4

"Dashboard Screenshot 4" (Screenshot%202026-11-05%20221259.png)

Dashboard 5

"Dashboard Screenshot 5" (Screenshot%202026-11-05%20221312.png)

Project Scope

This project focuses on descriptive and diagnostic analysis of historical sales data. It does not include a predictive machine learning model.

Conclusion

This project provided practical experience in database integration, business intelligence, dashboard development, SQL-based analysis, and translating raw business data into meaningful insights.
