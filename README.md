# Cyclistic Bike-Share Analytics — Enterprise Power BI Platform

An enterprise **Microsoft Power BI** executive analytics solution analyzing 61,973 Cyclistic bike-share trips across the Chicago network. Built on an enterprise **Star Schema data model**, **35+ production DAX measures**, **custom executive theme**, and **What-If financial modeling**.

## 📊 Live Interactive Dashboard
Open the live interactive dashboard in your browser: **https://tamim-shadman.github.io/cyclistic-powerbi-analytics/**

## 🏛️ Repository Structure
- `index.html`, `style.css`, `app.js` — Interactive web application with Leaflet Chicago map and What-If simulator
- `cyclistic_theme.json` — Custom Power BI executive theme
- `DAX_Measures.dax` — 35+ enterprise DAX formulas (IBCS variance, Moving averages, LTV)
- `PowerQuery_ETL_Queries.m` — Power Query M data extraction & calendar dimension scripts
- `POWERBI_SOLUTION_BLUEPRINT.md` — Visual-by-visual build specifications for all 6 pages
- `data/` — 1 Fact table (`Fact_Rides.csv`) and 6 Dimensions (`Dim_Date`, `Dim_Time`, `Dim_Station`, `Dim_UserType`, `Dim_BikeType`, `Dim_RideCategory`)

## ⚡ Quick Start in Power BI Desktop
1. Open **Power BI Desktop** > Click **Get Data > Text/CSV** > Load all CSVs in `data/`.
2. Go to **View > Themes > Browse for themes** > Select `cyclistic_theme.json`.
3. Create a blank `_Measures` table > Paste measures from `DAX_Measures.dax`.
