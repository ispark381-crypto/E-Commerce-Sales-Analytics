# E-Commerce Sales Analytics

## 1. Project Overview

This project focuses on analyzing an e-commerce customer behavior and sales dataset to identify sales patterns, customer trends, product performance, and business opportunities.

The project covers the complete data analytics workflow, including data preparation, exploratory data analysis (EDA), data visualization, Power BI dashboard development, and business insights.

---

## 2. Problem Statement

E-commerce businesses generate large amounts of customer and sales data. Without proper analysis, it can be difficult to identify high-performing products, understand customer behavior, monitor sales trends, and make data-driven business decisions.

This project analyzes e-commerce sales and customer behavior data to discover useful patterns and provide recommendations that can support better business decisions.

---

## 3. Dataset

The project uses a real-world e-commerce customer behavior and sales dataset.

**Dataset:** E-Commerce Customer Behavior & Sales Analysis

**Number of records:** 17,049

**Number of columns:** 18

The dataset contains information such as:

* Order ID
* Customer ID
* Date
* Age
* Gender
* City
* Product Category
* Unit Price
* Quantity
* Discount Amount
* Total Amount
* Payment Method
* Device Type
* Session Duration
* Pages Viewed
* Returning Customer Status
* Delivery Time
* Customer Rating

---

## 4. Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* Power BI
* Git
* GitHub
* CSV files

---

## 5. Data Cleaning and Preparation

The dataset was inspected and prepared before performing analysis.

The following steps were performed:

* Checked dataset dimensions and column names.
* Checked data types.
* Checked for missing values.
* Checked for duplicate records.
* Converted the Date column into a proper datetime format.
* Validated important numerical ranges.
* Checked categorical values.
* Sorted the dataset by date.
* Saved the cleaned dataset as a separate CSV file.

### Data Quality Results

* Missing values: **0**
* Duplicate rows: **0**
* Invalid dates: **0**
* Dataset after cleaning: **17,049 rows × 18 columns**

The detected statistical outliers were retained because their values were within reasonable business ranges.

---

## 6. Exploratory Data Analysis

EDA was performed using Python and Pandas.

The analysis included:

* Descriptive statistics
* Category-wise sales analysis
* Payment method analysis
* Device type analysis
* Monthly sales analysis
* Correlation analysis
* Outlier detection
* Customer rating analysis
* Delivery time analysis

### Key Business Metrics

| Metric                  |          Value |
| ----------------------- | -------------: |
| Total Sales             | ₹21,779,052.59 |
| Total Orders            |         17,049 |
| Total Quantity Sold     |         51,341 |
| Average Customer Rating |           3.90 |
| Average Delivery Time   |      6.50 days |
| Average Order Value     |      ₹1,277.05 |

---

## 7. Data Visualizations

Five meaningful visualizations were created using Matplotlib:

1. Total Sales by Product Category
2. Monthly Sales Trend
3. Total Sales by Payment Method
4. Total Sales by Device Type
5. Average Delivery Time by Product Category

The generated visualization files are available in the `visualizations` folder.

---

## 8. Power BI Dashboard

An interactive Power BI dashboard was developed to provide a visual summary of the analysis.

### Dashboard Features

* Total Sales KPI
* Total Orders KPI
* Total Quantity KPI
* Sales by Product Category
* Sales by Payment Method
* Sales by Device Type
* Monthly Sales Trend
* Product Category slicer
* Month slicer

The Power BI dashboard file is available in the `power_bi` folder.

---

## 9. Business Insights

### 1. Electronics is the highest-performing category

Electronics generated approximately **₹10.48 million** in sales and was the largest contributor to overall revenue.

### 2. Home & Garden is the second-highest category

Home & Garden generated approximately **₹4.02 million** in sales, making it another important revenue-generating category.

### 3. Books has the lowest sales contribution

Books generated approximately **₹0.36 million**, indicating comparatively lower demand.

### 4. Average Order Value

The average order value is approximately **₹1,277.05**, providing a useful benchmark for evaluating sales performance.

### 5. Customer satisfaction

The average customer rating is approximately **3.9 out of 5**, indicating generally positive customer satisfaction.

### 6. Delivery performance

The average delivery time is approximately **6.5 days**, showing relatively consistent delivery performance across the dataset.

### 7. Outliers

Statistical outliers were found mainly in Discount Amount, Total Amount, and Unit Price. These observations were retained because they were within reasonable business ranges.

---

## 10. Recommendations

### Recommendation 1: Focus on high-performing categories

The business should maintain strong inventory and targeted marketing campaigns for Electronics and Home & Garden because they contribute the highest sales.

### Recommendation 2: Improve low-performing categories

Categories such as Books, Food, and Beauty can be promoted using targeted discounts, product bundles, seasonal campaigns, and personalized offers.

### Recommendation 3: Monitor discounts and high-value transactions

High-value transactions and large discounts should be monitored to ensure that promotional strategies remain profitable.

---

## 11. Project Structure

```text
E_Commmerce_Sales_Analytics
│
├── dataset
│   ├── ecommerce_customer_behavior_dataset_v2.csv
│   ├── ecommerce_customer_behavior_cleaned.csv
│   └── power_bi_dashboard_data.csv
│
├── notebook
│   └── ecommerce_customer_behavior_analysis.ipynb
│
├── power_bi
│   └── Ecommerce_Sales_Analytics_Dashboard.pbix
│
├── report
│   └── task7_report.docx
│
├── visualizations
│   ├── sales_by_product_category.png
│   ├── monthly_sales_trend.png
│   ├── sales_by_payment_method.png
│   ├── sales_by_device_type.png
│   └── average_delivery_time_by_category.png
│
└── README.md
```

---

## 12. Conclusion

This project demonstrates the complete process of performing data analytics on an e-commerce dataset. The data was cleaned and validated using Python, followed by exploratory data analysis and visualization.

A Power BI dashboard was developed to present important business metrics and trends interactively. The analysis identified high-performing and low-performing product categories, sales patterns, customer satisfaction levels, and delivery performance.

The project demonstrates how data analytics, visualization, and business intelligence tools can be combined to transform raw e-commerce data into meaningful business insights and recommendations.
