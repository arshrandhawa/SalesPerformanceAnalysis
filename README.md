<table align="center">
  <tr>
	<td align="center">
      <a href="https://github.com/arshrandhawa/portfolio/blob/main/README.md">
        <img src="https://img.shields.io/badge/-Homepage-gray?style=for-the-badge&logo=github&scale=2" alt="Homepage">
      </a>
    </td>
	<td align="center">
      <a href="https://github.com/arshrandhawa/BusinessIntelligencePortfolio/blob/main/README.md">
        <img src="https://img.shields.io/badge/-Business_Intelligence-blue?style=for-the-badge&logo=tableau&scale=4" alt="Business Intelligence">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/arshrandhawa/DataAnalystPortfolio/blob/main/README.md">
        <img src="https://img.shields.io/badge/-Data_Analyst-green?style=for-the-badge&logo=sqlite&scale=4" alt="Data Analyst">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/arshrandhawa/DataEngineerPortfolio/blob/main/README.md">
        <img src="https://img.shields.io/badge/-Data_Engineering-orange?style=for-the-badge&logo=docker&scale=4" alt="Data Engineering">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/arshrandhawa/DataSciencePortfolio/blob/main/README.md">
        <img src="https://img.shields.io/badge/-Data_Science-purple?style=for-the-badge&logo=scikit-learn&scale=4" alt="Data Science">
      </a>
    </td>
  </tr>
</table>

# Advanced SQL Queries

## [Sales Performance Analysis](https://github.com/arshrandhawa/SalesPerformanceAnalysis/blob/main/SalesPerformanceViewByArsh.sql) – Project Overview 
This project focuses on analyzing sales performance using **SQL** with complex queries to rank salespeople, track total sales, calculate running totals, and generate territory-based performance insights. It is designed to handle large datasets efficiently, leveraging **Common Table Expressions (CTEs), ranking functions, and advance SQL techniques** for optimization.

## Key Features & Insights

### 1. Sales Performance Metrics
- Extracted **total sales** using the `TotalDue` column.
- Calculated **distinct order counts** to assess order volume per salesperson.

### 2. Ranking Salespeople
- Ranked salespeople **within each territory** based on total sales.
- Ranked salespeople **across all territories** for company-wide performance insights.

### 3. Running Totals & Historical Sales Trends
- Implemented **quarterly running totals** to track cumulative sales performance over time.
- Used **window functions** for efficient aggregation of sales data.

### 4. Overall Ranking System
- Defined **overall ranking** by combining **sales rank and order count rank** to measure comprehensive performance.
- Ensured that salespeople **without sales data** for a given quarter were still included if they were active in that territory.

### TODO: Performance Optimization
- **Indexing** to reduce query execution time and improve efficiency.
- **Clustered and Non-Clustered Indexes** on key tables like `SalesOrderHeader` and `SalesPerson` to optimize query performance.

## Technologies Used
- **SQL Server (T-SQL)**
- **Common Table Expressions (CTEs)**
- **Ranking Functions ( `DENSE_RANK()`)**
- **Window Functions (`SUM() OVER`, `COUNT() OVER`)**

## How to Use
1. Use Adventure Works 2019 on SQL Server
2. Clone the repository and set up an **SQL Server instance**.
3. Load the provided **SQL scripts** into your database environment.
4. Execute queries to analyze sales performance across different dimensions.

---
This project highlights **data-driven decision-making**, **query optimization**, and **advanced SQL techniques** 🚀
