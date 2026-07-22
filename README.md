# 🛒 Flipkart Product Data Analysis

## 📌 Project Overview

This project focuses on analyzing a Flipkart product dataset to explore product pricing, discounts, categories, brands, ratings, and other product-related attributes.

The objective of this project is to perform Exploratory Data Analysis (EDA) on Flipkart's product catalog and extract meaningful insights related to product pricing, discount patterns, category distribution, brand presence, and product ratings.

This project demonstrates the practical use of Python and data analysis techniques to clean, transform, analyze, and visualize real-world e-commerce product data.

---

## 🎯 Project Objectives

* Analyze the distribution of products across different categories.
* Identify products with the highest and lowest retail prices.
* Compare retail prices with discounted prices.
* Analyze discount patterns across products.
* Identify brands with the highest number of products.
* Analyze product ratings and overall ratings.
* Explore the distribution of Flipkart Advantage products.
* Identify popular product categories and subcategories.
* Extract meaningful insights from product-level data.

---

## 🛠️ Technologies & Tools

* **Python**
* **Pandas** – Data cleaning, manipulation, and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization
* **Jupyter Notebook** – Interactive data analysis

---

## 📂 Dataset

The dataset contains information about Flipkart products and includes approximately **20,000 product records**.

### Key Features

| Column                    | Description                                                   |
| ------------------------- | ------------------------------------------------------------- |
| `uniq_id`                 | Unique identifier of the product record                       |
| `crawl_timestamp`         | Date and time when the product data was collected             |
| `product_url`             | URL of the product page                                       |
| `product_name`            | Name of the product                                           |
| `product_category_tree`   | Hierarchical product category information                     |
| `pid`                     | Product identification number                                 |
| `retail_price`            | Original retail price of the product                          |
| `discounted_price`        | Price after discount                                          |
| `image`                   | Product image URL                                             |
| `is_FK_Advantage_product` | Indicates whether the product is a Flipkart Advantage product |
| `description`             | Product description                                           |
| `product_rating`          | Product rating information                                    |
| `overall_rating`          | Overall product rating                                        |
| `brand`                   | Product brand                                                 |
| `product_specifications`  | Detailed product specifications                               |

---

## 🔍 Data Analysis Process

### 1. Data Loading

* Imported the dataset using Pandas.
* Examined the dataset structure, shape, and data types.
* Identified important columns for analysis.

### 2. Data Cleaning

* Checked for missing values.
* Handled inconsistent and unavailable rating values.
* Cleaned product category information.
* Processed categorical and numerical columns.
* Checked duplicate records where required.

### 3. Exploratory Data Analysis (EDA)

Performed analysis on:

* Product categories
* Product brands
* Retail prices
* Discounted prices
* Discount patterns
* Product ratings
* Flipkart Advantage products

### 4. Data Visualization

Created visualizations using Matplotlib and Seaborn to identify patterns and trends in the product dataset.

---

## 📊 Key Analysis Areas

### 💰 Price Analysis

Compared the `retail_price` and `discounted_price` to understand product pricing and price differences.

### 🏷️ Discount Analysis

Analyzed the difference between retail and discounted prices to understand discount patterns across products.

### 📦 Category Analysis

Explored the product category hierarchy to understand the distribution of products across different categories and subcategories.

### 🏢 Brand Analysis

Identified brands with the highest number of products listed in the dataset.

### ⭐ Rating Analysis

Analyzed available product ratings and overall ratings to understand rating patterns among products.

### 🚚 Flipkart Advantage Analysis

Compared Flipkart Advantage products with other products to understand their distribution within the dataset.

---

## 💡 Key Learnings

Through this project, I gained practical experience in:

* Data cleaning and preprocessing using Pandas.
* Handling missing and inconsistent data.
* Working with hierarchical categorical data.
* Extracting information from complex category columns.
* Performing Exploratory Data Analysis (EDA).
* Using `groupby()`, `value_counts()`, and aggregation functions.
* Creating effective visualizations using Matplotlib and Seaborn.
* Extracting meaningful insights from real-world e-commerce product data.

---

## 📁 Project Structure

```text
Flipkart-Product-Data-Analysis/
│
├── Flipkart_Product_Analysis.ipynb
├── flipkart_products.csv
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the project folder in Jupyter Notebook or JupyterLab.
3. Open `Flipkart_Product_Analysis.ipynb`.
4. Make sure the dataset is placed in the correct directory.
5. Install the required Python libraries if needed.
6. Run the notebook cells sequentially.

---

## 📌 Conclusion

This Flipkart Product Data Analysis project demonstrates how Python-based data analysis and visualization techniques can be applied to real-world e-commerce product data.

The analysis provides insights into product categories, pricing, discount patterns, brands, ratings, and Flipkart Advantage products. It showcases the data analysis workflow, from data cleaning and Exploratory Data Analysis to visualization and insight generation.

---

## 👩‍💻 Author

**Niharika Gaur**

Aspiring Data Analyst | Python | SQL | Advanced Excel | Power BI

---

⭐ If you found this project useful, feel free to explore the repository and share your feedback!
