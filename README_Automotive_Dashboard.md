# Global Automotive Dashboard — Sales Analysis 2000–2025

An interactive Power BI dashboard analyzing global automotive sales, pricing, and product trends from 2000 to 2025 across 44 brands and multiple regions — built to uncover market share shifts, pricing trends, and regional performance in the automotive industry.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/status-completed-brightgreen)

---

## 📊 Overview

The dashboard covers **42.32M units sold**, **$1,539.51bn in total revenue**, across **44 brands**, spanning car types (SUV, Sedan, Pickup, Hatchback, Coupe, Convertible, MPV), fuel types (Petrol, Hybrid, Diesel, Electric), and both new and used vehicles.

**Headline Metrics:**
| Metric | Value |
|---|---|
| Sales Volume | 42.32M (+7.8%) |
| Total Revenue | $1,539.51bn (+7.2%) |
| Previous Avg Price | $1.14bn (+7.4%) |
| Total Brands | 44 |
| Used % / New % | 91.42% / 8.58% |
| Top Region | Saudi Arabia (5.6M units) |
| Top Brand | Ford (7.0M units) |
| Fastest-Growing Car Type | Sedan (+4.1M units) |

---

## 🗂️ Report Structure

The report spans 5 pages:

### 1. Cover
Branded landing page with navigation to all report sections.

### 2. Executive Sales Overview
- KPI cards: Total Brand, Sales Volume, Total Revenue, Previous Avg Price
- Sales volume by fuel type and by country of origin
- Top brands by sales volume (Ford leads with 7.0M units)
- Sales volume and brand distribution by country of origin (map)
- Car type breakdown by New vs. Used

### 3. Pricing & Product Analysis
- Pricing trends and product-level breakdowns
- Filters by Brand, Car Type, Model, Class, Color, Year

### 4. Sales Performance & Product Analysis
- Top 10 total revenue by region and by brand
- Regional brand performance map (Middle East & North Africa focus)
- Car type performance (New vs. Used)

### 5. Sales Explorer
- Decomposition-tree style deep dive across Region → Brand → Car Type → Class → Fuel Type → Transmission
- Fully interactive drill-down for ad-hoc exploration (e.g., Saudi Arabia → Toyota → New → SUV → Petrol → CVT)

A companion page also breaks down **Sales Volume by Powerhouse** (Low/Medium/High Power, Electric), average price trend from 2000–2025, new vs. used car type trends by year, and niche/luxury brand performance (Genesis, Porsche, Lincoln, Ferrari, Rolls-Royce, and more).

---

## 🔍 Key Insights

- **Ford leads global sales volume** at 7.0M units, followed closely by Mitsubishi and Mazda (4.5M each).
- **Saudi Arabia is the top-performing region** (5.6M units), with UAE, Egypt, Morocco, Kuwait, Oman, Jordan, and Qatar rounding out the top markets — highlighting strong demand across the Middle East & North Africa.
- **Sedans are the fastest-growing car type** (+4.1M units), while SUVs remain the highest-volume category overall (20.67M units).
- **Average price has risen sharply since 2020**, climbing from roughly $1.5M to $3.1M — reflecting broader market inflation and a shift toward higher-value vehicles.
- **Petrol still dominates fuel type** at 39% of sales volume, with Hybrid (25%), Diesel (21%), and Electric (14%) making up the rest — showing gradual but still limited EV adoption.
- **Used vehicles account for 91.42%** of total sales volume versus 8.58% new, underscoring the scale of the used-car market.

---

## 🛠️ Tools Used

- **Power BI Desktop** — data modeling, DAX measures, and interactive visualization
- Data model built on Region, Brand, Car Type, Class, Fuel Type, and Transmission dimensions, with a decomposition tree for multi-level exploration

---

## 📁 Files

- `Global_Automotive_Dashboard.pbix` — Power BI report file
- (Add data source file(s) here, e.g. `Automotive_Sales_Raw_Data.xlsx`)

---

## 📌 Notes

This project was built as a portfolio piece to demonstrate large-scale sales analytics, DAX measure creation, and interactive drill-down design (decomposition tree) in Power BI.
