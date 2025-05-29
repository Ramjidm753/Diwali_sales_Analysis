# 🪔 Diwali Sales Analysis

A data analysis project using Python (Pandas, Seaborn, Matplotlib) to explore customer behavior, popular products, and regional sales trends during the Diwali festive season.

## 📊 Project Overview

This project analyzes Diwali sales data to uncover valuable business insights such as:

- Gender-wise and age-wise purchase behavior
- Top-selling product categories and product IDs
- Region/state-wise sales and order volume
- Occupation and marital status influence on purchasing

The analysis is presented using various visualizations (bar plots, count plots) to make the insights easy to interpret.

## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📁 Dataset

The dataset used is a cleaned CSV file titled `Diwali Sales Data.csv`, containing the following key features:
- Gender, Age Group, Marital Status, Occupation
- Product Category, Product ID
- Purchase Amount and Order Count
- State (region)

## 🧹 Data Cleaning

- Removed null values and blank columns
- Converted data types (e.g., `Amount` to `int`)
- Renamed columns for readability
- Filtered out invalid entries

## 📈 Key Visualizations

- Gender distribution and sales amount
- Age group vs. total amount spent
- Top 10 states by number of orders and total amount
- Marital status and gender-wise spending
- Occupation-wise and product category-wise sales
- Top 10 most sold products

## 🖼️ Sample Graphs

> 📌 To include graphs here, save the images in a folder like `images/` and embed them below:

```markdown
### Gender-wise Sales Distribution
![Gender Sales](images/gender_sales.png)

### Top 10 States by Total Orders
![Top States Orders](images/top_states_orders.png)
