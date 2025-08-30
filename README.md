# Superstore-Sales-Analysis
This is an analysis of retail data

# Superstore Sales Analysis Project

## Project Overview

**Project Title**: SuperStore Analysis  
**Level**: Beginner  
**Database**: dataframe which is denoted as df in this project

This project is designed to demonstrate python skills and techniques typically used by data analysts to explore, clean, and analyze retail sales data. The project involves setting up a superstore sales dataframe, performing exploratory data analysis (EDA). 


## Objectives

1. **Set up a retail sales dataframe**: Create and populate a retail sales dataframe with the provided sales data.
2. **Data Cleaning**: Identify and remove any records with missing or null values.
3. **Exploratory Data Analysis (EDA)**: Perform basic exploratory data analysis to understand the dataset.


## Project Structure

### 1. Dataframe Setup

- **Dataframe Creation**: The project starts by creating a dataframe.
- **Table Creation**: The dataframe is created by importing the pandas library,in order for us to use the read_csv method to read the data into python.


### 2. Data Preprocessing & Cleaning

	
	Data Preprocessing

- **Record Count**: Determine the total number of records in the dataset.
- **Customer Count**: Find out how many unique customers are in the dataset.
- **Category Count**: Identify all unique product categories in the dataset.
- **Null Value Check**: Check for any null values in the dataset and delete records with missing data.
- **Ship Mode Count**:Find out how many unique modes are in the dataset.
- **Segment Count**:Find out how many unique segments in the dataset.
- **City Count**:Find out how many unqiue cities in the dataset.
- **Count of Cities in the State**:Find out how many cities in each state in the dataset.
- **State Count**:Find out how many unique states in the dataset.
- **Region Count**:Find out how many unique regions in the dataset.
- **Product Count**:Find out how many unique products in the dataset.
- **Sub-Category Count**:Find out how many Sub-Categories in the dataset.
- **Category/Subcategory Count**:Find out how many subcategories are in each category in the dataset.


	Data Cleaning
		
- **Create proper date format**:apply the to_datetime method to create proper dates.
- **Convert data types from string to numerical**:apply the astype method to create numerical datatypes.
- **Derive the cost of sales column**:Sale less profits.
- **Reduce dataframe size**:Drop unnecessary columns





### 3. Data Analysis & Findings

The data anlysis is performed in jupyter notebook and i invite you to scrutinise the analysis over there.

## Findings

- **State/City Analysis**:The state with most cities is California(81), however New York(18), with far fewer cities,is the top 2 for sales,which means growth 			                  opportunities are plenty in that state.  
- **High-Value Transactions**: Through our spend/dollar analysis we observed that cellphones and tables are the highest sellers.
- **Sales Trends**: Monthly analysis shows variations in sales, we observed that the final four months of the year are Superstores most busy periods.
- **Customer Insights**: The analysis identifies the top-spending customers and the most popular product categories.



## Conclusion

This project serves as a introduction to python for data analysis, covering dataframe setup, data cleaning, and exploratory data analysis.



## Author - analysethatdata

This project is part of my portfolio, showcasing the python skills essential for data analyst roles. 
