# Maven Fuzzy Factory Report

An Excel dashboard on e-commerce sales, traffic and marketing performance for an online toy store.

## Project Overview

Maven Fuzzy Factory is an online toy store. This project analyses its website traffic, orders, revenue, marketing channels and product sales from 2012 to 2015. The goal is to find out what drives growth, when demand peaks, which channels and products earn the most, and where the business can improve.

## Data Source

Maven Analytics Toy Store E-Commerce Database:
https://mavenanalytics.io/data-playground/toy-store-e-commerce-database

## Tools Used

- Microsoft Excel
- Power Query (importing and cleaning the CSV files)
- Power Pivot (building the Data Model, linking the tables and creating measures)
- PivotTables and PivotCharts
- Slicers

## Data Preparation and Modelling

1. Imported the CSV files into Excel using Power Query.
2. Cleaned the data and set the correct data types.
3. Loaded the tables into the Data Model and linked them in Power Pivot using the shared keys.
4. Created measures such as total revenue, order count, session count, conversion rate, revenue per order and revenue per session.
5. Built PivotTables and PivotCharts from the Data Model and arranged them on the dashboard.
6. Added a slicer to filter every chart by year.

## Key Metrics

| Metric | Value |
|---|---|
| Total Revenue | $1,938,509.75 |
| Total Orders | 32,313 |
| Total Sessions | 472,871 |

## Data Visualization

![Maven Fuzzy Factory Dashboard](Screenshot%202026-10-10%20235950.png)

The dashboard contains:

- Website Session and Order Trend
- Marketing Channels by Revenue and Order
- Product Sales
- Total Revenue by Year
- Revenue per Order and Revenue per Session Trend
- Session-to-Order Conversion Rate
- Product Revenue

The slicer (2012 to 2015) filters every chart at once.

## Insights

1. 2014 was the breakout year. Revenue went from $393,248 (2013) to $1,075,612, about 2.7 times, and 2015 already has $340,376 from January to March alone.
2. November and December are the peak months. Sessions reach 53,168 and 55,529 (against 29,058 in April), and orders reach 3,464 and 3,867 (against 1,893).
3. Conversion and order value are steady. Conversion stays between 6.38% and 7.59% (6.83% overall), and revenue per order stays between $58.99 and $61.82.
4. gsearch drives the business. It brings $1,276,144.89 and 21,333 orders (about 66% of both), while socialbook adds only $22,259.33 and 343 orders (about 1%).
5. The Original Mr. Fuzzy is the top product. It sold 24,226 items and earned $1,211,057.74, about 60% of all items sold.

## Recommendations

1. Keep investing in what drove the 2014 growth, and track whether 2015 keeps the same pace.
2. Plan stock, staffing and promotions ahead of November and December, and run campaigns in the slow months (April to September) to lift traffic.
3. Focus on growing traffic rather than conversion, since conversion and order value are already stable.
4. Protect gsearch performance, and review socialbook and other small channels. Either improve them or cut the spend.
5. Promote the other three products and bundle them with The Original Mr. Fuzzy to reduce reliance on one product.

## Notes

- 2015 only covers January to March, so it cannot be compared fairly with full years.
- The NULL channel in the marketing chart represents sessions with no recorded campaign source.

