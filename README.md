# Sales Data Analysis

## Overview

This project aims to analyze sales data of athletic footwear to gain insights into sales trends and performance. The dataset includes information about sales transactions, such as retailer details, product information, sales amounts, and dates.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib (optional for visualization)
## Usage

### 1. Data Preparation:
Ensure that the sales data is available in CSV format.
Load the data into a pandas DataFrame for analysis.
### 2. Data Cleaning and Preparation:
Combine and clean the data from multiple CSV files if necessary.
Check for missing values and handle them appropriately.
Convert data types as needed (e.g., date columns to datetime).
### 3. Analysis:
Determine the total sales for each retailer, region, state, and city.
Calculate the total number of women's athletic footwear sold for each retailer, region, state, and city.
Create a pivot table with 'invoice_date' as the index and 'total_sales' as the values, then resample the data into daily and weekly bins to analyze sales trends.
### 4. Results:
Display the top results, such as the top retailers, regions, and cities with the highest sales, and the top weeks with the most sales.

## Files Included

- athletic_sales_2020.csv: Sales data for the year 2020.
- athletic_sales_2021.csv: Sales data for the year 2021.
- sales_analysis.ipynb: Jupyter Notebook containing the code for data analysis.
- README.md: This README file providing an overview of the project and instructions for usage.

## Instructions for Running the Code

1. Install the required Python packages: pip install pandas numpy matplotlib.
2. Clone or download the repository to your local machine.
3. Open the sales_analysis.ipynb notebook using Jupyter Notebook or any compatible environment.
4. Follow the instructions in the notebook to execute the code cells and perform the analysis.
