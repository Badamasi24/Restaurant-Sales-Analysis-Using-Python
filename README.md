# Restaurant Sales Analysis Using Python

## Project Overview

This project explores restaurant sales data using Python to identify customer payment preferences, product performance, revenue distribution across cities and managers, and monthly revenue trends.

The objective is to transform raw restaurant data into meaningful business insights that can support data-driven decision-making, sales optimization, and operational planning.

## Objectives

- Clean and prepare the dataset for analysis.
- Identify the most frequently used payment methods.
- Determine the best-selling products by quantity and revenue.
- Analyze revenue performance across cities and managers.
- Examine monthly revenue trends.
- Develop actionable business recommendations from the findings.

## Tools and Technologies

- **Python** — Data analysis and processing.
- **Pandas** — Data cleaning, grouping, aggregation, and manipulation.
- **Matplotlib / Seaborn** — Data visualization, where applicable.
- **Jupyter Notebook** — Interactive analysis and documentation.

## Data Cleaning and Preparation

Before conducting the analysis, I performed the following data preparation tasks:

1. Checked the dataset for duplicate records and removed duplicates.
2. Converted the price and quantity columns to appropriate data types.
3. Converted the date column to a datetime format to support time-based analysis.
4. Prepared the dataset for grouping, aggregation, and visualization.

## Analysis and Key Findings

### 1. Customer Payment Preferences

I used Pandas' `value_counts()` function to identify the most frequently used payment methods.

| Payment Method | Count |
|---|---:|
| Credit Card | 120 |
| Cash | 76 |
| Gift Card | 58 |

**Insight:** Credit cards were the most frequently used payment method, followed by cash and gift cards.

**Recommendation:** Maintain reliable card-payment facilities while continuing to support other payment options.

### 2. Product Performance by Quantity and Revenue

I used `groupby()` and aggregation functions to calculate total quantity sold and revenue for each product category.

**Quantity sold**

| Product | Quantity |
|---|---:|
| Beverages | 34,988 |
| Fries | 32,023 |
| Burgers | 29,018 |
| Chicken Sandwiches | 11,133 |
| Sides & Other | 9,800 |

**Revenue generated**

| Product | Revenue |
|---|---:|
| Burgers | 376,943.82 |
| Fries | 125,626.57 |
| Chicken Sandwiches | 114,612.45 |
| Beverages | 103,214.60 |
| Sides & Other | 48,902.00 |

**Insights:**
- Beverages recorded the highest quantity sold.
- Burgers generated the highest revenue.
- Sides & Other recorded the lowest quantity sold and revenue among the listed categories.

**Recommendations:** Maintain adequate beverage inventory, protect burger sales, and investigate opportunities to increase sales of Sides & Other through product bundling and targeted promotions.

### 3. Revenue by City

I aggregated revenue by city to compare geographical sales performance.

| City | Revenue |
|---|---:|
| Lisbon | 241,635.49 |
| London | 211,160.04 |
| Madrid | 136,154.24 |
| Berlin | 100,572.34 |
| Paris | 79,777.33 |

**Insight:** Lisbon recorded the highest revenue, while Paris recorded the lowest among the five cities analyzed.

**Recommendation:** Investigate the factors contributing to Lisbon's performance and identify opportunities to improve sales in lower-performing locations.

### 4. Revenue by Manager

I grouped the data by manager and calculated total revenue to compare manager-associated sales performance.

| Manager | Revenue |
|---|---:|
| JoaoSilva | 241,635.49 |
| TomJackson | 211,160.04 |
| PabloPerez | 136,154.24 |
| WalterMuller | 100,572.34 |
| RemyMonet | 79,777.33 |

**Insight:** JoaoSilva recorded the highest manager-associated revenue, while RemyMonet recorded the lowest.

**Recommendation:** Investigate the practices associated with higher revenue and compare managers using relevant context, including city assignments, transaction volumes, and operating costs.

*Note: The identical revenue totals for the city and manager rankings should be validated against the manager-city assignments before drawing conclusions about individual performance.*

### 5. Monthly Revenue Analysis

I grouped transactions by month and calculated total revenue to examine changes in sales over time.

| Month | Revenue |
|---|---:|
| November | 332,015.12 |
| December | 437,284.32 |

**Insight:** Revenue increased by 105,269.20 between November and December, representing approximately **31.7% month-on-month growth**.

**Recommendation:** Investigate whether seasonal demand, promotions, transaction volume, or product mix contributed to the increase. Additional monthly data is needed to establish the overall trend throughout the year.

## Business Recommendations

Based on the analysis, I recommend that restaurant management:

1. **Optimize payment services:** Ensure reliable credit card processing while retaining alternative payment methods.
2. **Improve product strategy:** Maintain beverage availability, protect burger revenue, and explore ways to increase sales of lower-performing products.
3. **Monitor geographical performance:** Investigate differences in city revenue and identify opportunities for improvement.
4. **Evaluate manager performance fairly:** Consider location assignments, sales volume, and operating costs before comparing individual results.
5. **Use monthly trends for planning:** Incorporate verified sales patterns into inventory management, staffing, and promotional planning.

Revenue alone does not measure profitability. Cost data would be required to identify the most profitable products, cities, and managers.

## Skills Demonstrated

- Data cleaning and preprocessing
- Duplicate detection and removal
- Data type conversion
- Exploratory Data Analysis (EDA)
- Pandas `value_counts()`
- Pandas `groupby()` and aggregation
- Revenue and quantity analysis
- Time-series analysis
- Data visualization
- Business insight generation

## Conclusion

This project demonstrates how Python can be used to clean restaurant data, analyze sales performance, identify customer payment preferences, and uncover opportunities for business improvement.

The findings highlight the importance of combining data preparation, quantitative analysis, and business interpretation to support informed decisions.

## Repository Contents

- `restaurant_sales_analysis.ipynb` — Jupyter Notebook containing the analysis.
- `restaurant_data.csv` — Dataset, if permitted to share.
- `images/` — Analysis charts and visualizations, if included.

*Update the repository contents to match the files actually uploaded.*

## Connect

I am continuously developing my skills in Python, data analytics, business intelligence, and data-driven problem-solving.

Feel free to explore this project, share feedback, and connect with me.

**#Python #DataAnalysis #Pandas #EDA #DataAnalytics**
