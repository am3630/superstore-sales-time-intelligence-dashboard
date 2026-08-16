# Superstore Sales & Time Intelligence Dashboard

A Power BI dashboard analysing Superstore sales performance across shipping methods, customer segments, and product sub-categories, with a focus on year-over-year time intelligence.

## Dataset
[Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/yesshivam007/superstore-dataset) — multi-year retail sales transactions covering sales, profit, shipping cost, customer segment, and product category.

## Tools Used
- Power BI (custom Date table, DAX time intelligence, multi-visual dashboard design)
- DAX: TOTALYTD, SAMEPERIODLASTYEAR, QTD, MTD, DIVIDE (for YoY/MoM growth measures)

## Key Insights

- **Shipping behaviour:** Standard Class dominates shipping method by a wide margin (£1.63M vs £0.15M for Same Day), suggesting customers strongly favour cost over speed — worth investigating whether faster shipping is priced/promoted effectively.
- **Customer segment:** Consumer accounts for over half of total sales (54%), more than double Home Office and Corporate combined proportionally — indicating the business is heavily consumer-driven rather than B2B-led.
- **Product performance:** Phones lead all sub-categories in sales, notably ahead of Copiers and Chairs.
- **YoY growth:** Built a full year-over-year sales comparison (2011 vs 2012) using SAMEPERIODLASTYEAR, showing consistent growth across most months, with a notable dip in July both years — a possible seasonal pattern worth monitoring in future data.

## Dashboard Preview
![Superstore Dashboard](<img width="1322" height="704" alt="image" src="https://github.com/user-attachments/assets/b55d2da5-f063-43cd-adcf-1102163f8554"/>)


## What This Project Demonstrates
- Building a proper Date table and applying DAX time intelligence functions (YTD, QTD, MTD, YoY comparisons) from scratch
- Translating raw sales data into a clear, multi-angle business narrative (shipping, segment, product, and trend)
- Fast, focused dashboard iteration — built and presented in a single sitting, with clear insight-first thinking
