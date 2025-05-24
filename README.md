# 🏠 House Market Analysis with Power BI

This project presents an end-to-end housing market analysis dashboard using **Power BI** and **Google BigQuery**. It covers data extraction, cleaning, transformation, DAX calculations, and dashboard creation for insightful real estate trends.

## 📁 Project Structure

- `House Analysis.pbix` — Main Power BI dashboard file
- `House Analysis.pdf` — Exported report for quick viewing
- `README.md` — Project overview and documentation

## 🎯 Objective

To analyze real estate market trends by region, house type, sales channel, and time using:
- Google BigQuery for backend data querying
- Power BI for visual analytics
- DAX for custom measures

## 🔧 Tools & Technologies

- Google Cloud Platform (BigQuery)
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query Editor
- SQL for BigQuery
- GitHub for version control

## 📊 Key Dashboards & KPIs

### 1. Sales Performance
- YOY Sales Growth by Sales Type
- Median Sales Price Change by Region
- Total Sales, Units Sold (12-month)

### 2. Regional Analysis
- Sales by Region
- Average Price per SQM
- Offer vs Purchase Price Comparison

### 3. House Type Analysis
- Avg Offer & Purchase Price by House Type
- Area vs Price Scatter Plot
- Key Influencers on Purchase Price

## 📈 DAX Highlights

- `YOY Sales Growth` using `CALCULATE`, `YEAR`, `MAX`, `IF`, `BLANK`
- `Median Sales Price Change` using `MEDIANX`, `FILTER`, `YEAR`
- `Last 12 Month Sales` using `DATESINPERIOD`
- `Sales by Region` using `ALLEXCEPT`

## 🚀 How to Run

1. Open `House Analysis.pbix` in Power BI Desktop
2. Refresh data (if connected to BigQuery)
3. Explore the report pages

> Note: To replicate, you may need a BigQuery dataset and setup a free GCP account
