# 🛒 Walmart Sales Analysis (2010–2012)

> A data analytics project that explores Walmart store sales trends, identifies seasonality patterns, and generates actionable business insights using Python.

---

## 📌 Brief One-Line Summary

Analyzed three years of Walmart sales data to uncover trends, seasonal patterns, and store performance insights using Python and data visualization.

---

## 📌 Table content

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Tools and Technologies](#tools-and-technologies)
- [Methods](#methods)
- [Key Insights](#key-insights)
- [Dashboard / Output](#dashboard--output)
- [Results & Conclusion](#results--conclusion)
- [Author](#author)
- [Acknowledgements](#acknowledgements)




---


## Overview

This project focuses on analyzing historical Walmart sales data from 2010 to 2012. The dataset contains weekly sales figures for multiple stores and departments, along with economic indicators such as fuel prices, CPI, unemployment, and holiday information.

Some months were missing from the raw dataset, which required careful cleaning and preprocessing before analysis. After preparing the data, exploratory data analysis (EDA) was performed to understand how sales changed over time and what factors influenced revenue.

The goal was to convert raw transactional data into meaningful business insights that can help improve forecasting, inventory planning, and strategic decision-making.

---

## Problem Statement

Retail businesses generate large volumes of sales data, but raw numbers alone do not provide useful insights.

The objective of this project was to answer the following business questions:

- Which stores generate the highest and lowest sales?
- How do sales change over time?
- Are there seasonal or holiday-related spikes in revenue?
- How do external factors like fuel price, CPI, and unemployment relate to sales?
- What trends can help Walmart improve planning and forecasting?

---

## Dataset

- **Source:** Walmart Historical Sales Dataset (Kaggle)
- **Time Period:** February 2010 to October 2012
- **Records:** Weekly sales observations across multiple Walmart stores
- **Key Features:**
  - Store
  - Date
  - Weekly_Sales
  - Holiday_Flag
  - Temperature
  - Fuel_Price
  - CPI
  - Unemployment

> Note: Some months were missing in the original data and were handled during preprocessing.

---

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- ChatGPT 

---

## Methods

1. Data Loading and Inspection
2. Data Cleaning and Missing Value Handling
3. Date Conversion and Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Trend and Seasonality Analysis
6. Correlation Analysis
7. Visualization and Interpretation

---

## Key Insights

- Certain stores consistently outperformed others in total sales.
- Sales increased significantly during holiday periods.
- Clear seasonal patterns were visible across the three-year period.
- Economic variables such as unemployment and fuel price showed measurable relationships with sales.
- Missing months did not prevent identification of long-term trends after preprocessing.

---

## Dashboard / Output

The project includes several visualizations, including:

- [Holiday vs Non-Holiday](images/Holiday.png)
- [Unemployment_Ranges](images/Unemployment_Ranges.png)
- [Weekly Sales by Temperature Category and Holiday Status](images/Weekly_Sales.png)
- [bottom5](images/bottom5.png)
- [temperature_range](images/temperature_range.png)
- [top5](images/top5.png)
  
These charts help stakeholders quickly understand business performance and trends.

---

## Results & Conclusion
The analysis revealed strong seasonal sales patterns and significant differences in store performance. Holiday periods had a noticeable positive impact on revenue, while economic indicators provided additional context for understanding fluctuations.
This project demonstrates how Python can be used to transform raw retail data into meaningful business insights that support better operational and strategic decisions.

---

## Author

Aditi Shah

An aspiring data analyst passionate about turning raw data into actionable insights.

---

## Acknowledgements

This project was developed as part of my data analytics learning journey. I used python.org⁠� and guidance from chatgpt.com⁠� to better understand data cleaning, analysis, and visualization techniques.

---
