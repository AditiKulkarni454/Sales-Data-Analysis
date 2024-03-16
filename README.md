# Electronics Store Sales Analysis Project

## Introduction
This project utilizes Python Pandas and Matplotlib libraries to analyze 12 months worth of sales data from an electronics store. The dataset includes information on purchases broken down by month, product type, cost, and purchase address. The primary objectives are to clean the data, answer high-level business questions, and conduct exploratory data analysis to derive insights.

## Installation
To run this project, ensure you have Python 3 installed along with the following libraries:
- Pandas
- NumPy
- Matplotlib

## Data Cleaning
Tasks involved in data cleaning include:
- Dropping NaN values from the DataFrame
- Removing rows based on specific conditions
- Changing the data types of columns (e.g., to_numeric, to_datetime, astype)

## Business Questions
1. **Best Month for Sales**: What was the best month for sales, and how much revenue was generated during that month?
2. **Top Selling City**: Which city sold the most products?
3. **Optimal Advertisement Timing**: What time should advertisements be displayed to maximize the likelihood of customers buying products?
4. **Frequently Sold Together Products**: Which products are most often sold together?
5. **Best Selling Product Analysis**: Which product sold the most, and why do you think it sold the most?

## Exploratory Data Analysis (EDA)
The EDA process involves:
- Concatenating multiple CSV files to create a new DataFrame (using `pd.concat`)
- Adding columns to the DataFrame
- Parsing cells as strings to create new columns (using `.str`)
- Using the `.apply()` method for specific operations
- Utilizing `groupby` to perform aggregate analysis
- Visualizing results through bar charts and line graphs
- Labeling graphs for clarity

## Conclusion
Through this analysis, we aim to provide insights into sales trends, customer behavior, and product performance, which can inform business strategies and decision-making processes.


