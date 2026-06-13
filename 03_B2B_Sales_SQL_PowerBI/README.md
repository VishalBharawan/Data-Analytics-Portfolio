# 📊 B2B Enterprise Sales Pipeline Architecture

## 🏢 The Business Problem
A European B2B enterprise was tracking its sales pipeline across disconnected flat files (Deals, Companies, Contacts, and Sales Teams). This fragmentation made it impossible for the VP of Sales to see real-time win rates, track regional quota attainment across EMEA and the UK, or forecast end-of-month revenue. 

## 🛠️ The Technical Solution
I architected a fully automated, end-to-end analytics pipeline:
* **Database Setup:** Migrated 4 raw CSV files into a structured PostgreSQL database.
* **Data Transformation:** Wrote optimized SQL scripts utilizing Common Table Expressions (CTEs) and `LEFT JOIN` logic to map deal stages to their correct European account managers and corporate clients.
* **Visualization:** Connected Power BI directly to the SQL database to build a dynamic Sales Funnel and Rep Performance Leaderboard.

## 📈 The Business Impact
* **Time Saved:** Eliminated 10+ hours of manual Excel merging per week.
* **Strategic Clarity:** Leadership can now instantly identify pipeline bottlenecks and track exactly which regional managers (e.g., EMEA - Central vs. Nordics) are hitting their monthly targets.
* **Scalability:** The SQL database can now ingest thousands of new CRM rows without breaking the frontend Power BI dashboard.
