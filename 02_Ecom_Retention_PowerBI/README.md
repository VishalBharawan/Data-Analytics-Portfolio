# 🛒 E-Commerce Customer Retention & Cohort Analytics

https://www.youtube.com/watch?v=LreFrbON8MU

## 🎯 The Business Problem
A growing e-commerce brand was successfully driving initial sales but struggling with long-term profitability. They had thousands of rows of transactional data but no visibility into customer loyalty. The Chief Marketing Officer (CMO) needed to know: *Are our customers coming back to buy again, or are they one-time purchasers?*

## 🛠️ The Technical Solution
I developed a multi-page interactive Power BI dashboard focused purely on customer behavior:
* **Data Modeling:** Built a robust Star Schema connecting `orders` and `customers` tables, governed by a custom DAX Date Dimension table.
* **Advanced DAX Logic:** Wrote dynamic measures to separate 'New' vs. 'Returning' customers and calculate Average Order Value (AOV).
* **Cohort Analysis:** Engineered a Cohort Retention Matrix (Heatmap) that tracks customer repurchase rates month-over-month based on their original acquisition date.

## 📈 The Business Impact
* **Targeted Marketing:** The marketing team can now visually identify exactly which monthly cohorts are dropping off (churning) and launch targeted email discount campaigns to re-engage them.
* **Shift to CLV:** Transitioned the business's focus from tracking simple daily revenue to optimizing Customer Lifetime Value (CLV).
* **Instant Insights:** Replaced weekly manual Excel exports with a single, auto-refreshing dashboard link.
