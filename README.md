# SWIGGY-DATA-ANALYSIS---EXCEL
Swiggy Order Data Analysis Excel Project


https://github.com/amaan20002023-sketch/SWIGGY-DATA-ANALYSIS---EXCEL/edit/main/README.md
 
Overview
This GitHub repository hosts an Excel-based project for analyzing personal Swiggy order data. The goal is to uncover insights into ordering habits, spending patterns, food preferences, restaurant choices, and delivery performance. The core file, SWIGGY REVISE.xlsx, contains raw data, processed analyses, pivot tables, KPIs, and a dashboard for visual summaries.
Data is fetched using a JavaScript script from Swiggy's API and analyzed in Excel with formulas, pivots, and charts. This project demonstrates data cleaning, visualization, and insight generation using spreadsheet tools—ideal for personal analytics or learning data analysis.
Key analyses include:

Monthly expenditure trends (MoM comparisons).
Restaurant and area-level order distributions.
Food item frequencies (Veg vs. Non-Veg).
Delivery metrics (on-time rates, cancellations).
Coupon and rain mode usage.

Table of Contents

Features
Data Structure
Installation and Setup
Usage Guide
Key Insights
Screenshots
Technologies Used
Contributing
License
Contact

Features

Data Extraction Script: JavaScript code to download order history as JSON from Swiggy.
Excel Workbook Structure:
Raw data sheets (e.g., orders, food items).
Analysis sheets (e.g., restaurant rankings, area breakdowns, monthly spending).
KPI summaries and interactive dashboard with charts.

Visualizations: Pivot charts for order trends, pie charts for area percentages, bar graphs for top items.
Custom Metrics: Percentage calculations for coupons, rain deliveries, and on-time performance.
Extensibility: Easily update with new data; add custom pivots or formulas.
Homework Extensions: Open-ended analyses like restaurant-level metrics.

Data Structure
The Excel file (SWIGGY REVISE.xlsx) has multiple sheets:

Working with Top-Bottom Data: Examples of ranking and JSON handling.
1. Objective Requirement: Project goals and analysis focus areas.
Swiggy_Orders_Data: Raw order details (107 orders, columns like order_id, restaurant_name, net_total).
Restaurant Area Correction: Mapping for area codes.
Food Item Level Data: Item-level breakdown (Veg/Non-Veg, quantities).
Restaurant Level Analysis: Orders per restaurant with rankings.
Area Level Analysis: Orders by area, percentages, top food items.
Monthly Expenditure: MoM revenue and order comparisons.
Food Items Analysis: Item counts and frequencies.
KPIs: Key metrics like average order value, total revenue (₹43,964).
Dashboard: Summary visuals and tables.
Some more analysis: Additional metrics (e.g., coupon %: 71%).
javascript_swiggy_data_download: API fetch script.

Data spans 2023-2024, with 107 orders from Bangalore areas like HSR (41%).
Installation and Setup

Clone the Repository:textgit clone https://github.com/yourusername/swiggy-excel-analysis.git
cd swiggy-excel-analysis
Requirements:
Microsoft Excel (2016+ recommended for pivots and charts).
Web Browser (e.g., Chrome) for running the JavaScript script.
Optional: Python with pandas/openpyxl for advanced automation.

Fetch Your Data:
Log into Swiggy.
Open browser console (F12).
Paste and run the script from javascript_swiggy_data_download sheet.
Download swiggy_orders.json and import into Excel (use Power Query: Data > Get Data > From File > From JSON).


Usage Guide

Open Excel File:
Launch SWIGGY REVISE.xlsx.
Refresh pivots (Data > Refresh All) after adding new data.

Perform Analysis:
Dashboard Sheet: View KPIs, charts, and summaries.
Update Data: Paste new orders into Swiggy_Orders_Data and refresh.
Custom Queries: Use pivots in Area Level Analysis for filters (e.g., top items per area).



Total Orders: 107, Revenue: ₹43,964, Avg. Order: ₹411.
Top Restaurant: Subway (11 orders).
Top Area: HSR (44 orders, 41%).
Food Preferences: Veg (102 items) > Non-Veg (68); Top Item: Single Lamb Cheese Burger (6 times).
Monthly Peaks: May (23 orders, ₹10,369); Drops in July.
Delivery: 97% delivered (44% on-time), 3 cancellations.
Coupons: Applied in 71% of orders; Rain Mode: 3%.
