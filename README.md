# Coffee Sales Data Analysis Dashboard

## 📊 Project Overview

This project involves analyzing raw coffee sales data to derive actionable business insights. Using **Microsoft Excel**, I transformed raw data into an interactive dashboard that allows stakeholders to visualize sales performance by region, product type, and customer demographics.


## Dashboard Preview

<img width="1919" height="960" alt="Screenshot 2026-02-06 172505" src="https://github.com/user-attachments/assets/88f15ea3-d209-4989-918e-82a9c7c08a2b" />


## 🛠️ Techniques & Formulas Used

### 1. Data Gathering & Transformation
* **Connecting Tables:** Imported raw data from multiple CSV files into Excel.
* **Data Lookup (`XLOOKUP`):** Used to bring in customer details (name, email, country) into the main orders table.
* **Data Lookup (`INDEX`/`MATCH`):** Utilized for dynamic lookup of product information (type, roast, price), allowing one formula to populate multiple columns.
* **Data Cleaning (`IF` functions):** Used nested `IF` statements to convert abbreviated data (e.g., 'Rob') into full descriptive names (e.g., 'Robusta').
* **Formatting:** Applied custom date formats and currency formatting ($) for better readability.

### 2. Data Modeling & Analysis
* **Excel Tables (`Ctrl+T`):** Converted raw data ranges into Excel Tables to ensure dynamic updating of charts when new data is added.
* **Pivot Tables:** Created pivot tables to summarize sales data by time, product type, country, and customer.
* **Grouping:** Grouped raw dates into months and years for trend analysis.

### 3. Visualization & Dashboarding
* **Pivot Charts:** Created line charts for temporal trends and bar charts for categorical comparisons.
* **Interactivity:** Added **Slicers** (for roast type, size, loyalty card) and a **Timeline** to make the dashboard dynamic.
* **Dashboard Layout:** Compiled all visuals onto a single sheet, formatted with custom colors and shapes.
* **Report Connections:** Linked slicers and timelines to all pivot tables so that one selection filters the entire dashboard.

---

## 🚀 Key Dashboard Features
- **Dynamic Timeline:** Analyze sales performance over specific months or years.
- **Roast & Size Filters:** Segment sales data based on roast type (Light, Medium, Dark) and package size.
- **Loyalty Program Analysis:** Instantly compare purchasing behavior between loyalty card holders and non-holders.

---

## 📁 Files
- `coffeeOrdersData.xlsx`: Raw order data.
- `coffeeOrdersProject.xlsx`: The final interactive visual report.
