# DA-PROJECT
# Amazon Product Data Analysis

This project provides an analysis of Amazon product data with a focus on price distribution, customer ratings, and top products by review counts. The aim is to derive insights that could assist Amazon sellers and platform managers in making data-driven decisions for pricing, improving customer satisfaction, and identifying high-performing products.

---

## Table of Contents
1. [Dataset Overview](#dataset-overview)
2. [Data Cleaning & Preparation](#data-cleaning--preparation)
3. [Analysis and Insights](#analysis-and-insights)
4. [Key Findings](#key-findings)
5. [How to Use](#how-to-use)
6. [Requirements](#requirements)

---

## Dataset Overview

This dataset includes details of Amazon products, featuring columns like:
- **category**: Product category
- **discounted_price**: Price after discount
- **actual_price**: Original price before any discount
- **rating**: Average customer rating
- **rating_count**: Number of customer reviews

> **Note**: Some columns were cleaned and converted to a usable format for analysis.

---

## Data Cleaning & Preparation

Before conducting the analysis, the dataset was cleaned and prepared through the following steps:
1. **Changing Data Types**: Converted certain columns (e.g., prices, ratings) to numeric formats.
2. **Filling Missing Values**: Replaced missing values in key columns with relevant statistics (e.g., mean for prices).
3. **Removing Duplicates**: Removed any duplicate rows to maintain data integrity.

---

## Analysis and Insights

The following analyses were performed:

### 1. Price Analysis
Calculated the average, minimum, and maximum prices by product category, highlighting price ranges across different categories. This analysis provides insights into the distribution of actual and discounted prices.

### 2. Rating Analysis
Examined the average rating for each product category to understand customer satisfaction levels. Categories with higher average ratings suggest better overall customer satisfaction.

### 3. Top Products by Sales
Identified the top-selling products by assuming that products with more customer reviews (higher `rating_count`) tend to have higher sales. This section highlights the top 10 products with the highest review counts, offering a proxy for popularity.

---

## Key Findings

- **Price Trends**: The dataset reveals clear distinctions between premium and budget-friendly categories based on average discounted and actual prices.
- **Customer Satisfaction**: Higher-rated categories indicate more satisfied customers, while lower ratings may suggest areas for improvement.
- **Top Products**: The products with the highest review counts are likely top-sellers and may provide insights into high-demand items.

---

## How to Use

1. **Clone the Repository** (if running locally):
   ```bash
   git clone <repository-link>
   cd amazon-product-analysis
   ```
2. **Upload the Dataset** to Kaggle or specify its path if running locally.
3. **Run the Notebook** on Kaggle to generate outputs and visualize insights.

---

## Requirements

- **Python 3.x**
- **Libraries**:
  - `pandas`: For data handling and analysis

Install the libraries with:
```bash
pip install pandas
```

---

## License

This project is licensed under the MIT License.

---
