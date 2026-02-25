# 📊 Northwind Database: Advanced SQL Data Analysis & Business Insights

## 📌 Project Summary
This project is a comprehensive data analytics and business strategy (Business Intelligence) study conducted on the well-known **Northwind** database. The primary goal is not just to write SQL queries, but to process raw data and generate **actionable business insights** that support the decision-making processes of company management (C-Level).

Nine different case studies touching on all departments of the company were analyzed, ranging from customer loyalty (CRM) and supply chain risks to workforce optimization and sales forecasting.

## 🛠️ Technologies and Analytical Skills Used
* **Database:** Microsoft SQL Server (SSMS) / T-SQL
* **Advanced SQL Structures:** Common Table Expressions (CTEs), Subqueries, Data Aggregation (`SUM`, `COUNT DISTINCT`), Date/Time Functions (`DATEADD`, `DATENAME`), Conditional Logic (`CASE WHEN` - Pivot Tables).
* **Business Focus Areas:** * B2B Customer Analytics & Cross-Selling
  * Sales Performance Measurement & YTD Trend Analysis
  * Supply Chain & Disruption Risk Management
  * Operational Workforce Optimization

---

## 🔍 Key Business Problems Solved & Strategic Insights

### 1. Customer Analytics (CRM) and Loyalty Program

* **VIP Customer Identification:** Data revealed that a large portion of the company's revenue comes from a small number of "Whale" clients (e.g., Ernst Handel), aligning with the Pareto Principle (80/20 rule). A "Key Account Management (KAM)" strategy was recommended for these VIP customers.
![VIP Customer Analysis](İmages/8.png)

* **Product Diversity & Cross-Selling:** It was identified that customers who prefer the widest variety of products favor the "Beverages" category. A/B testing campaigns for complementary products like "Confections" were designed for this target audience.
![Cross-Selling Analysis](İmages/2.png)

### 2. Sales Performance and Employee Productivity

* **Volume vs. Efficiency:** It was proven that the employee with the highest total revenue and the employee with the highest "Average Order Value" were different. An internal skills transfer (cross-training) strategy was developed to boost overall efficiency.
![Employee Efficiency](İmages/1.png)

* **Monthly Sales Trends (Pivot):** A cross-tabular analysis highlighted specific high-performing months and individual consistency. A quarterly bonus structure was proposed to ensure fairness across the sales team.
![Pivot Table Trends](İmages/7.png)

* **Forecasting Anomaly:** Growth rates were calculated by comparing 1997 and 1998. In this analysis using CTEs, a "Data Anomaly" was detected due to 1998 data ending in May, and a new forecasting model based on YTD (Year-to-Date) was proposed.
![Sales Forecasting](İmages/5.png)

### 3. Supply Chain and Operational Optimization

* **Top Revenue Products & Supplier Risk:** Analysis of the top 5 revenue-generating products revealed a heavy reliance on a single supplier for premium goods. Hedging contracts and finding "Plan B" alternative suppliers were strongly advised.
![Product Profitability](İmages/4.png)

* **Critical Stock Alarm:** Using dynamic time functions, "Star Products" that were actively sold in the last 3 months but fell below the "Reorder Level" (or even hit zero) were identified. Urgent expedited shipping and dynamic stock parameters were recommended.
![Stock Management](İmages/6.png)

* **Workforce Planning:** When analyzing daily order volume, it was observed that orders were homogeneously distributed across weekdays. Instead of dynamic shifts, a "Fixed Staff Strategy" and a cross-training model to combat the Monday rush were designed.
![Order Volume Distribution](İmages/9.png)

### 4. Geographic Market and Pricing Strategy

* **Premium Market Identification:** The US market was proven to be the most profitable region, with both high volume and an average basket size "34% above the global average." It was emphasized that investments should be made in quality and logistics speed rather than price cutting in this premium market.
![Geographic Sales Power](İmages/3.png)

---

## 📂 File Structure
* `northwind_case_study.sql`: Contains the end-to-end SQL codes for all questions in the project and detailed "Business Insight" comment blocks written for management.
* `images/`: Directory containing screenshots of the SQL query results supporting the business insights.

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Open the `northwind_case_study.sql` file in SSMS (SQL Server Management Studio) or your preferred IDE.
3. Ensure that the **Northwind** database is installed and running in the background.
4. Execute the queries to review the results and the associated business insights.

---
*If you'd like to talk more about extracting stories from data and generating business strategy, feel free to contact me!*
