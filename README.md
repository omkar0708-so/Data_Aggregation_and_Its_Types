Data Aggregation and Its Types – Data Mining Practical
Practical: Data Aggregation in Data Mining
Objective

To understand and implement Data Aggregation techniques in Data Mining, including:

Basic Aggregation (sum, mean, count, min, max)

Multi-level Aggregation

Time Aggregation (monthly, quarterly, yearly)

Spatial Aggregation (region-wise and city-wise)

🛠 Tools & Technologies Used

Python

Pandas Library

Jupyter Notebook / VS Code

📖 Description

Data aggregation is a key step in data mining that involves collecting and summarizing data to provide meaningful insights.

This practical demonstrates different types of aggregation using a sample sales dataset and Python's Pandas library.

📂 Dataset Description

The dataset contains the following attributes:

Region – Geographic region

City – City name

Product – Product category

Sales – Sales amount

Quantity – Quantity sold

Date – Date of transaction

🔹 1️⃣ Basic Aggregation

The following aggregation operations are performed:

✅ Total sales by region (Sum)

✅ Average sales and quantity by product (Mean)

✅ Count of sales records by region

✅ Minimum and maximum sales by region

🔹 2️⃣ Multi-Level Aggregation

Sales data is aggregated using multiple attributes:

Sales by Region and Product

Resetting index for better readability

This helps in deeper data analysis across multiple dimensions.

🔹 3️⃣ Time Aggregation

Time-based aggregation is performed using the Date column:

📅 Monthly sales aggregation

📅 Quarterly sales aggregation

📅 Yearly sales aggregation

This helps analyze sales trends over different time periods.

🔹 4️⃣ Spatial Aggregation

Spatial aggregation is performed based on geographic attributes:

🌍 Total sales by Region

🏙 Total sales by City

🌍🏙 Combined aggregation by Region and City

This is useful for geographic performance analysis.

📊 Sample Output

Monthly, quarterly, and yearly sales totals

Region-wise and city-wise sales summaries

Aggregated tables using groupby() and resample() functions

✅ Conclusion

This practical demonstrates how data aggregation simplifies large datasets and helps extract meaningful insights.

Time-based and spatial aggregation techniques are especially useful for:

Trend analysis

Business intelligence

Geographic data analysis

Decision-making support

👨‍🎓 Author

Omkar Thakur
Course / Subject: Data Mining
