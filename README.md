# Retail-Sales-Analysis-Excel-Dashboard
A comprehensive Excel dashboard analyzing $620k in retail sales across North America, featuring multi-channel performance tracking and regional profitability insights.

# REPORT VIEW
<img width="1316" height="546" alt="Image" src="https://github.com/user-attachments/assets/3cbc8111-213c-4233-acbc-6fcd7e2fc19f" />

## 📊 Project Overview
This repository contains a comprehensive retail sales dataset and analysis framework designed for business intelligence and data visualization. The project tracks multi-channel sales performance across North America, providing insights into profitability, customer behavior, and regional trends.

The primary goal of this project is to demonstrate data transformation, pivot table analysis, and dashboarding capabilities using Excel and Python-friendly datasets.

[Image of a professional business intelligence dashboard with sales charts and KPIs]

## 📁 File Descriptions
* **`Dataset.csv`**: The raw transactional data containing 2,026 records. It includes details such as Order IDs, Product Categories, Sales, COGS, and Profits.
* **`ANALYSIS.csv`**: A processed file containing aggregated summaries, including performance metrics by country, sales channel, and payment method.

## 📈 Key Performance Indicators (KPIs)
Based on the provided data, the business achieves the following metrics:
* **Total Revenue:** $620,209.63
* **Total Profit:** $270,274.34
* **Profit Margin:** 43.6%
* **Top Performing Region:** Canada
* **Leading Category:** Soccer

## 🔍 Data Structure
The core dataset comprises 22 columns covering four main dimensions:

| Dimension | Features |
| :--- | :--- |
| **Temporal** | Order Date, Weekday, Month, Year |
| **Geographic** | City, Country |
| **Product** | Product Name, Category, Unit Price |
| **Financial** | Sales, COGS, Profit, Payment Type |

### Sample Data Snippet
| Order Date   | Country   | Category    | Product                              |   Sales |   Profit |
|:-------------|:----------|:------------|:-------------------------------------|--------:|---------:|
| 2020-12-31   | USA       | Golf        | Glove It Women's Mod Oval Golf Glove |   37.98 |    16.96 |
| 2020-12-31   | USA       | Soccer      | Mercurial Vapor 12 Academy Cleats    |  133.37 |    48.78 |
| 2020-12-31   | USA       | Electronics | Smart watch                          |  370    |   120.91 |
| 2020-12-30   | USA       | Golf        | Glove It Women's Imperial Golf Glove |   37.98 |    14.34 |
| 2020-12-29   | USA       | Electronics | Smart watch                          |  370    |   120.91 |

##  Analysis Highlights
1.  **Channel Performance:** Online sales contribute significantly more to the total revenue compared to In-Store purchases.
2.  **Regional Insights:** Strong market presence in Canada and the USA, with detailed city-level performance tracking.
3.  **Seasonality:** The data allows for deep dives into monthly and weekday sales trends to optimize staffing and inventory.

## 🛠 Tools & Technologies
* **Excel:** Used for initial data organization and pivot table analysis.
* **Python (Pandas):** Utilized for data cleaning and metric validation.
* **Markdown:** For professional documentation and reporting.

---
*Developed for professional portfolio demonstration in Data Analysis and Business Intelligence.*
