# Customer Shopping Behavior Analysis

**Data Analytics Portfolio Project | Python · PostgreSQL · SQL · Power BI**

## Project Overview

This project analyzes **3,900 customer shopping records** to explore purchasing patterns, product preferences, customer segments, and subscription behavior. The analysis combines Python data preparation, SQL-based business analysis, and an interactive Power BI dashboard.

## Dataset

- **3,900 records** and **18 original columns**
- Includes customer demographics, purchase amounts, product categories, discounts, shipping methods, subscription status, and product reviews
- **37 missing review ratings**, handled during data cleaning

Dataset: [`customer_shopping_behavior.csv`](customer_shopping_behavior.csv)

## Tools & Technologies

**Python (pandas)** for cleaning and preparation · **PostgreSQL / SQL** for analysis · **Power BI** for visualization · **VS Code / Jupyter Notebook** for development

## Project Workflow

1. Explored and cleaned the dataset using Python, including missing-value handling and column standardization.
2. Created features such as `age_group` and `purchase_frequency_days`.
3. Loaded the prepared data into PostgreSQL and answered **10 business questions** using SQL.
4. Built an interactive Power BI dashboard with KPIs, charts, and filters.

## Power BI Dashboard

The dashboard includes **customer count, average purchase amount, average review rating**, subscription breakdown, revenue and sales by category, and revenue and sales by age group. Filters let viewers explore results by gender, category, shipping type, and subscription status.

**Dashboard file:** [`customer_behavior_dashboard.pbix`](customer_behavior_dashboard.pbix)

*Dashboard screenshot can be added here later.*

## Key Findings

| Metric | Finding |
| --- | ---: |
| Total purchase value | **$233,081** |
| Average purchase amount | **$59.76** |
| Average review rating | **3.75 / 5** |
| Highest-revenue category | **Clothing ($104,264)** |
| Subscribers | **1,053 (27%)** |
| Non-subscribers | **2,847 (73%)** |

Subscriber and non-subscriber average purchase amounts were very similar (**$59.49** vs. **$59.87**). These descriptive results do not show that subscriptions cause higher spending.

## Business Recommendations

- Focus marketing tests on high-revenue categories while monitoring profitability.
- Improve subscription benefits and evaluate their impact on customer engagement.
- Use product ratings and purchase patterns to inform merchandising decisions.
- Review discount effectiveness before expanding promotions.

## Project Files

- [Python notebook](Customer_Shopping_Behavior_Analysis.ipynb)
- [SQL business analysis](customer_analysis.sql)
- [Power BI dashboard](customer_behavior_dashboard.pbix)
- [Project report (PDF)](Customer_Shopping_Behavior_Report.pdf)

## Acknowledgment

This is a **tutorial-guided project**, based on Amlan Mohanty's [*Complete Data Analytics Portfolio Project in 6 Easy Steps | Python + SQL + Power BI*](https://www.youtube.com/watch?v=5PrZvPeUw60). Credit for the original tutorial and project approach goes to its creator.
