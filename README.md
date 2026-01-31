# Blink-it-Dashboard

## 📊 BlinkIt Sales Analytics – SQL & Power BI Project
A compact end‑to‑end data analytics project showcasing my skills in data cleaning, SQL analysis, and interactive dashboarding with Power BI, using a BlinkIt sales dataset (retail grocery delivery).

## 📁 Project Overview

- Goal: Understand sales performance across outlets, locations, item types, and fat content to support business decisions.
​

- Tech stack: SQL Server, Power BI, Excel/CSV.
​

- Key steps: Load raw data → Clean & transform → Analyze with SQL → Build interactive Power BI dashboard.

## 🧾 Dataset
- Source: Public BlinkIt‑style retail dataset (items, outlets, sales, ratings, visibility).
  - <a href="https://github.com/Kani-mozhi3/Blink-it-Dashboard/blob/main/BlinkIT%20Grocery%20Data.xlsx"> Dataset</a>​​

- Size: ~8.5K item records across multiple outlet types (Supermarket & Grocery).

- Example fields: Item ID, Item Type, Fat Content, Outlet Type, Outlet Size, Outlet Location Type, Year Established, Item Visibility, Item MRP, Sales, Rating.

## 🧹 Data Cleaning
Main cleaning tasks performed in SQL Server / Power Query:

- Handled missing values for item weight, outlet size, and ratings using reasonable defaults or averages.
​
- Standardized categorical values (e.g., “low fat” vs “Low Fat”) and removed duplicates.
​
- Fixed data type issues for dates, numeric columns, and currency fields.
​
- Created derived columns such as total sales per item, outlet age, and sales categories for better analysis.

## 🧮 SQL Analysis
All analysis was first done in SQL Server, then key result sets were pushed to Power BI.

### Example analysis questions:

- What is the total and average sales across all outlets?

- Which outlet type and size generate the highest revenue?

- How do sales differ by fat content, item type, and location tier?

- How have outlet sales trended by year of establishment?

### Example SQL techniques used:

- Aggregate functions (SUM, AVG, COUNT, MIN, MAX).​

- GROUP BY, ORDER BY, HAVING for segment‑level insights.​

- CASE statements to bucket outlets or items into performance tiers.
​
- Joins between item and outlet tables to create analysis‑ready views.
​

## 📈 Power BI Dashboard
The final dashboard turns the SQL outputs into a recruiter‑friendly, interactive report.

Key features:

- KPI cards showing total sales, average sales, number of items, and average rating.

- Slicer panel for Location Type, Outlet Size, and Item Type to explore specific segments.

### Bar/column charts:

- Sales by Outlet Type and Outlet Location Tier.

- Sales by Item Type and Fat Content.

### Donut charts:

- Sales share by Fat Content (Low Fat vs Regular).

- Sales share by Outlet Size (Small, Medium, High).

### Line/area chart:

- Sales trend by Outlet Establishment Year, highlighting growth and dips over time.

- Each visual is formatted with consistent colors, labels, and tooltips to make insights clear to non‑technical stakeholders.


