# Electronics Gadgets Sales Analysis Using Pandas & Matplotlib

This project aims to analyze sales data of electronics gadgets to derive actionable insights for business improvement. The data exploration and analysis are conducted using Python programming language with pandas for data manipulation and matplotlib for visualization.

## Table of Contents
1. [Installation](#installation)
2. [Data Cleaning](#data-cleaning)
3. [Data Exploration](#data-exploration)
4. [Business Questions](#business-questions)
5. [Conclusion](#conclusion)

## Installation
# Installation

1. To run this project, you need to have Jupyter Notebook installed on your system. If you haven't installed it yet, you can follow the [official documentation](https://jupyter.readthedocs.io/en/latest/install.html) for installation instructions.
2. You also need to have the Pandas library installed. If you haven't installed it yet, you can refer to the [official Pandas documentation](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html) for installation instructions.


## Data Cleaning
- **Drop NaN values**: Remove rows with missing values using the `dropna()` method.
- **Change column types**:
- Convert columns to numeric type using `pd.to_numeric()`.
- Convert columns to datetime type using `pd.to_datetime()`.

## Data Exploration
1. **Load Data**: Load the sales data into a pandas DataFrame.
2. **Best Month for Sales**: Determine the best month for sales and the total earnings for that month.
3. **City with Most Sales**: Identify the city that sold the most products.
4. **Optimal Advertisement Time**: Find the best time to display advertisements to maximize the likelihood of customer purchases.
5. **Products Sold Together**: Determine which products are most often sold together.
6. **Top-Selling Product**: Identify the product that sold the most and analyze potential reasons for its high sales.

## Business Questions
1. What was the best month for sales? How much was earned that month?
2. What city sold the most product?
3. What time should we display advertisements to maximize the likelihood of customer’s buying product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

## Conclusion
This project provides valuable insights into the sales performance of electronics gadgets. The analysis can be used to make data-driven decisions for improving marketing strategies, inventory management, and overall business growth.
