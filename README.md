# 🌍 World Food Production Strategic Analysis (1992-2022)

## 📌 Project Overview
This project provides a comprehensive, interactive analysis of global food production over three decades. Using verified data from **FAOSTAT**, the dashboard tracks the production volumes of 24 essential food commodities, visualizes geographic distribution, and forecasts future growth trends up to 2030.

## 🚀 Key Technical Features
* **Predictive Analytics:** Implemented time-series forecasting to project production growth until 2030.
* **Advanced Filtering:** Integrated a dynamic **Text Search Slicer** for instant querying by Country or Food Product.
* **Interactive Mapping:** Global heatmap showing production intensity by country.
* **Dynamic KPIs:** Real-time calculation of total and current production metrics.

## 📊 Business Insights
* **Total Production Volume:** 158.58bn tonnes over the analyzed period.
* **Current Global Output:** Approximately 6.47bn tonnes annually.
* **Regional Powerhouses:** Asia leads global production, followed by the Americas.
* **Strategic Growth:** Production is forecasted to peak near 6.5bn tonnes by 2030.

## 🛠️ Technical Stack & Skills
* **Power BI Desktop:** Dashboard design, UI/UX optimization, and visualization.
* **DAX (Data Analysis Expressions):** Developed custom measures to aggregate large datasets and create dynamic KPIs.
* **Power Query:** Data cleaning, transformation, and normalization of FAO datasets.
* **Data Modeling:** Established relationships between geographical and production tables.

## 📐 DAX Logic Examples
To ensure data accuracy, I utilized custom DAX measures such as:
- `Total Production = SUM('Production_Data'[Quantity])`
- `Product Variety Count = DISTINCTCOUNT('Production_Data'[Food Products])`

## 📸 Dashboard Preview
![Global Food Production Dashboard](https://github.com/fatemadaher1993-source/World-Food-Production-Analysis/blob/main/Screen%20Shot%202026-01-14%20at%2021.36.55.png)


