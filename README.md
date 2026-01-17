# Practical: Data Aggregation in Data Mining

## Objective
To understand and implement **Data Aggregation** techniques in Data Mining, including:
- Basic aggregation (sum, mean, count, min, max)
- Multi-level aggregation
- **Time Aggregation** (monthly, quarterly, yearly)
- **Spatial Aggregation** (region-wise and city-wise)

---

## Tools & Technologies Used
- Python
- Pandas library
- Jupyter Notebook / VS Code

---

## Description
Data aggregation is a key step in data mining that involves collecting and summarizing data to provide meaningful insights.  
This practical demonstrates different types of aggregation using a sample sales dataset.

---

## Dataset Description
The dataset contains the following attributes:
- **Region**: Geographic region
- **City**: City name
- **Product**: Product category
- **Sales**: Sales amount
- **Quantity**: Quantity sold
- **Date**: Date of transaction

---

## 1. Basic Aggregation
The following aggregation operations are performed:
- Total sales by region (Sum)
- Average sales and quantity by product (Mean)
- Count of sales records by region
- Minimum and maximum sales by region

---

## 2. Multi-Level Aggregation
Sales data is aggregated using multiple attributes:
- Sales by **Region and Product**
- Index reset for better readability

---

## 3. Time Aggregation
Time-based aggregation is performed using the `Date` column:
- **Monthly sales aggregation**
- **Quarterly sales aggregation**
- **Yearly sales aggregation**

This helps in analyzing sales trends over different time periods.

---

## 4. Spatial Aggregation
Spatial aggregation is performed based on geographic attributes:
- Total sales by **Region**
- Total sales by **City**
- Combined aggregation by **Region and City**

---

## Sample Output
- Monthly, quarterly, and yearly sales totals
- Region-wise and city-wise sales summaries
- Aggregated tables using Pandas `groupby()` and `resample()` functions

---

## Conclusion
This practical demonstrates how data aggregation simplifies large datasets and helps extract meaningful insights.  
Time and spatial aggregation are especially useful for trend analysis and geographic data analysis in data mining.

---

## Author
Omkar Thakur 
Course / Subject: Data Mining  
