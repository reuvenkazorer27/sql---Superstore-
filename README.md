# Superstore Analysis

This repository contains a comprehensive analysis of a Superstore dataset, performed using Python and Jupyter Notebooks. The goal of this project is to showcase SQL skills by analyzing a large dataset to extract meaningful insights.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Row Description](#row-description)
- [Analysis](#analysis)
  - [Sales by Year](#sales-by-year)
  - [Sales by Category](#sales-by-category)
  - [Profit Analysis](#profit-analysis)
  - [Subcategory Performance](#subcategory-performance)
  - [Discount Analysis](#discount-analysis)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

In this project, I have analyzed various aspects of the Superstore dataset. Key insights and visualizations are generated using SQL queries, pandas, and matplotlib. The analysis covers:
- Sales trends by year, month, and region.
- Profit breakdowns by category, subcategory, and segment.
- Performance comparisons between different sales channels, shipping modes, and cities.
- Detailed analysis of discounts and their impact on sales and profits.

The analysis also includes forecasted values for specific metrics, providing insights for future performance.

## Dataset

The dataset used for this analysis is publicly available on Kaggle. It includes detailed transactional data for a retail store, including sales, profits, and product information.

You can find the dataset here: [Superstore Dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/data)

### Row Description
The dataset contains the following columns:

- **Row ID**: Unique ID for each row.
- **Order ID**: Unique Order ID for each customer.
- **Order Date**: Date when the product was ordered.
- **Ship Date**: Date when the product was shipped.
- **Ship Mode**: Shipping mode specified by the customer.
- **Customer ID**: Unique ID to identify each customer.
- **Customer Name**: Name of the customer.
- **Segment**: The segment to which the customer belongs (e.g., Consumer, Corporate, Home Office).
- **Country**: Country of residence of the customer.
- **City**: City of residence of the customer.
- **State**: State of residence of the customer.
- **Postal Code**: Postal code of the customer's location.
- **Region**: Region where the customer belongs (e.g., Central, East, West).
- **Product ID**: Unique ID of the product.
- **Category**: Category of the product ordered (e.g., Furniture, Office Supplies).
- **Sub-Category**: Subcategory of the product ordered (e.g., Chairs, Binders).
- **Product Name**: Name of the product.
- **Sales**: Sales revenue from the product.
- **Quantity**: Quantity of the product ordered.
- **Discount**: Discount applied to the product.
- **Profit**: Profit (or loss) incurred from the sale.

## Analysis

### Sales by Year
The project provides an analysis of total sales for each year in the dataset. The year-over-year performance is displayed, highlighting trends and patterns over time.

### Sales by Category
Sales data is aggregated and analyzed by product categories. The top categories are determined by total sales, and insights into their performance are provided.

### Profit Analysis
Profitability is assessed at both the category and subcategory levels. The project calculates the total profit and profit percentage for each category and subcategory.

### Subcategory Performance
For each category, we drill down into the performance of individual subcategories. The top-performing subcategories are listed, with a focus on profit generation.

### Discount Analysis
The impact of discounts on sales and profit is analyzed by segment and category. The relationship between discount percentages and profitability is explored.

