# Project Overview

> **Chips Sales Performance Analysis.**

> A fast food outlet want to understand customer purchasing behavior and product performance across its chips market. 
The business has transcation-level sales data that can be used to identify the most valuable customer segment, understand product performance, 
and track changes in consumer spending over time.

> This project aims to answer the following **business questions**:

1.   Which customer segment generates the most revenue?
2.   Which pack sizes are most popular among consumers?
3.   Which chips brand brings in the highest sales revenue?
4.   Are customers spending more per packet over time?


> **Project Objective**:

> This project aims to identify the key drivers of chips sales & customer spending, so as to enable the business to 
make data-driven decisions regarding its customers, chips products, and pricing.

**Dataset**

The analysis combines transaction-level sales data with customer information.

Key variables include:

DATE — transaction date

PROD_QTY — quantity purchased

TOT_SALES — total transaction sales

BRAND — chips brand

PCK_SIZE — packet size in grams

PREMIUM_CUSTOMER — customer segment

**Data Preparation**

The analysis included:

Converting Excel serial dates to datetime.

Checking both datasets for missing values.

Investigating duplicate records.

Investigating extreme values in product quantity.

Creating derived measures such as spend per packet.

Aggregating sales by customer segment, packet size, brand, and week.

**Tools & Technologies**

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

**Project Structure**

chips-sales-analysis/
│
├── chips_sales_analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore

**Author**

Edi Kanyua