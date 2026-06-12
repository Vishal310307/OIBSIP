# Online Retail Sales Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on an online retail transaction dataset to understand sales trends, customer behaviour, and product performance.

The goal is to generate business insights that can help improve sales strategy and decision-making.

---

## Dataset

Dataset: Online Retail Dataset

The dataset contains transaction records including:

- Invoice number
- Product information
- Quantity purchased
- Invoice date
- Unit price
- Customer ID
- Country

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning

The following preprocessing steps were performed:

- Removed missing values
- Removed duplicate transactions
- Converted InvoiceDate into datetime format
- Removed invalid transactions with zero/negative quantity
- Removed zero/negative prices
- Created Revenue column using:

Revenue = Quantity × Unit Price

---

## Key Business Metrics

| Metric | Value |
|---|---:|
| Total Revenue | £8,887,208.89 |
| Total Orders | 18,532 |
| Average Order Value | £479.56 |
| Unique Customers | 4,338 |

---

## Analysis Performed

### 1. Monthly Revenue Analysis

Identified sales trends over time.

Key finding:
- November 2011 generated the highest monthly revenue.

![Monthly Revenue](images/monthly_revenue.png)

---

### 2. Country Analysis

Identified top-performing markets.

Key finding:
- United Kingdom contributed the majority of revenue.

![Country Revenue](images/country_revenue.png)

---

### 3. Product Analysis

Analyzed products based on revenue and quantity sold.

Key finding:
- PAPER CRAFT, LITTLE BIRDIE was the highest revenue-generating product.

![Product Revenue](images/product_revenue.png)

---

### 4. Customer Analysis

Analyzed customer spending behaviour.

Key finding:
- A small group of customers contributed significantly to revenue.

![Customer Revenue](images/customer_revenue.png)

---

## Business Recommendations

- Promote high-performing products more aggressively.
- Create loyalty programs for high-value customers.
- Increase marketing campaigns during low-sales months.
- Maintain inventory for popular products.
- Expand successful strategies from top-performing countries.

---

## Conclusion

This analysis provides insights into sales trends, customer behaviour, and product performance. The findings can support better business decisions and improve revenue growth.
