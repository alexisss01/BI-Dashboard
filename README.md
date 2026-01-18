## BI & Dashboarding

This report translates analytical findings into executive-ready dashboards.

### Tableau Public
🔗 [View Interactive Dashboard](https://public.tableau.com/app/profile/alexis.lee1551/viz/SalesCustomerProductPerformanceOverview/SalesCustomerProductPerformanceOverview)

# Tableau Story – Sales, Customer & Product Performance Overview

## Objective
To synthesise sales, customer, and product data into a concise business narrative that highlights revenue drivers, concentration risk, and optimisation opportunities.

## Data Foundation
- Source: Gold-layer star schema produced via SQL ETL
- Fact table: `fact_sales`
- Dimensions: `dim_customers`, `dim_products`

## Key Analytical Themes
1. **Sales Performance**
   - Overall revenue scale, order value, and temporal trends
   - Category-level contribution highlighting Bikes as the core revenue driver

2. **Market & Customer Concentration**
   - Revenue heavily concentrated in the United States and Australia
   - Older customer segments (45–54, 55+) contribute a disproportionate share of total sales
   - Age is a stronger driver of value than gender or marital status

3. **Product Portfolio Efficiency**
   - Strong Pareto effect: a small subset of products generates the majority of revenue
   - Long-tail SKUs exhibit diminishing returns, increasing operational complexity

## Business Implications
- Revenue concentration improves efficiency but introduces structural risk
- Customer strategy should prioritise high-value cohorts
- Product and inventory strategies should focus on core SKUs while actively reviewing long-tail items

## Deliverable
- Tableau Story (PDF): `Sales_Customer_Product_Performance_Overview.pdf`
