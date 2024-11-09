# Data Processing with Pandas
This project demonstrates how to use Python, pandas, and regular expressions (regex) to perform common data manipulation tasks such as: <br/> 
- Reading CSV/Excel files <br/> 
- Sorting and Filtering Data <br/> 
- Grouping Data using groupby <br/> 

# Project Overview
In this notebook, we use pandas, a powerful Python library for data analysis, to load datasets from CSV and Excel files. We then perform common data processing operations such as sorting, filtering, and aggregating data. We also leverage the re module to perform regex operations to clean and manipulate the data where necessary.

# Key Operations
## 1. Reading CSV and Excel Files
We start by loading data from CSV or Excel files into pandas DataFrames for further analysis. The pandas.read_csv() and pandas.read_excel() functions allow us to read these files into structured data.

## 2. Sorting
After loading the data, we sort the data based on specific columns using the sort_values() method. This helps in organizing data for further analysis or presentation.

## 3. Filtering
Applied conditional filters to the data to select specific rows that meet certain criteria, such as filtering out rows based on a column value or regex pattern matching.

## 4. Groupby Operations
Using the groupby() method, we aggregate data based on certain columns. This is useful for performing summary statistics, such as counting or averaging values for each group.

## 5. Using Regex with pandas
Regular expressions are applied with the help of pandas’ str.contains() and str.replace() functions to match patterns in text columns. This allows us to filter or clean textual data based on specific patterns.

# Kaggle Dataset Link
**Link:** [(https://www.kaggle.com/datasets/abcsds/pokemon?resource=download)]

# Requirements
Before running the Jupyter notebook, ensure you have the following dependencies installed:

- **pandas:** For data manipulation
- **openpyxl:** Required for reading and writing Excel files
- **re:** Python’s built-in regular expression module

To install the necessary packages, use the following:
pip install pandas openpyxl


