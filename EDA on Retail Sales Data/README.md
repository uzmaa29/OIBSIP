# Retail Sales Exploratory Data Analysis

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a retail sales dataset to uncover patterns in customer behavior, product demand, and sales performance.

The analysis focuses on understanding how factors such as **customer demographics, product categories, and purchase quantity** influence total transaction value.

The goal is to generate insights that can help retail businesses make **data-driven decisions regarding marketing, inventory management, and customer targeting.**

---

# Dataset Description

The dataset contains **1000 retail transactions**.

Each record represents a single customer purchase.

### Features

| Column           | Description                            |
| ---------------- | -------------------------------------- |
| Transaction ID   | Unique identifier for each transaction |
| Date             | Date of purchase                       |
| Customer ID      | Unique identifier for each customer    |
| Gender           | Customer gender                        |
| Age              | Age of the customer                    |
| Product Category | Category of purchased product          |
| Quantity         | Number of units purchased              |
| Price per Unit   | Price of a single product              |
| Total Amount     | Total value of the transaction         |

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# Project Workflow

The analysis followed these steps:

### 1 Data Loading

The dataset was imported using pandas and inspected for structure and data types.

### 2 Data Cleaning

* Converted date column to datetime format
* Checked for missing values
* Verified dataset consistency

### 3 Descriptive Statistics

Basic statistical measures such as mean, median, and standard deviation were calculated to understand spending behavior.

### 4 Time Series Analysis

Monthly sales trends were analyzed to identify fluctuations in revenue over time.

### 5 Customer Analysis

Customer characteristics such as **gender and age groups** were examined to understand purchasing behavior.

### 6 Product Category Analysis

Sales performance across different product categories was analyzed.

### 7 Data Visualization

Multiple visualizations were created including:

* Line charts
* Bar charts
* Scatter plots
* Correlation heatmaps

---

# Key Insights

The analysis revealed several important patterns:

* The **average transaction value is 456**, while the median is much lower, indicating skewed spending behavior.
* Sales fluctuate across months, suggesting possible **seasonal demand patterns**.
* Product categories contribute differently to overall revenue.
* Certain **age groups generate higher sales**, indicating strong demographic influence.
* Higher purchase quantities significantly increase total transaction value.
* A small number of customers contribute disproportionately to total revenue.

---

# Visualizations

The project includes the following visual analyses:

* Monthly sales trend
* Sales by gender
* Sales by product category
* Customer age distribution
* Quantity vs total amount relationship
* Correlation heatmap
* Top 10 customers by spending

---

# Business Recommendations

Based on the findings, several strategic recommendations can be made:

* Focus marketing efforts on **high-performing product categories**.
* Target **age groups with the highest spending patterns**.
* Introduce **loyalty programs for high-value customers**.
* Plan inventory based on **high-demand months**.
* Encourage higher purchase quantities through **bundle offers or discounts**.

---

# How to Run the Project

### 1 Clone the repository

```bash
git clone https://github.com/uzmaa29/retail-sales-eda.git
```

### 2 Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3 Run the notebook

Open the Jupyter Notebook and execute the cells to reproduce the analysis.

---

# Project Structure

```
retail-sales-eda
│
├── data
│   └── retail_sales_dataset.csv
│
├── notebook
│   └── retail_sales_analysis.ipynb
│
├── visuals
│   └── charts and plots
│
└── README.md
```




