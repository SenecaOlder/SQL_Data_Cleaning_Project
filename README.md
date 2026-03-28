# SQL Data Cleaning Project

## Overview
A comprehensive SQL data cleaning project using a Nashville housing dataset. 
The raw data contained multiple quality issues that made it difficult to 
use for analysis or reporting. This project identifies and resolves each 
issue systematically, transforming messy source data into a clean, 
analysis-ready table.

## Key Cleaning Operations
1. Reformatted SaleDate column by removing unnecessary time data
2. Populated missing PropertyAddress values using a self-join on ParcelID
3. Split combined address fields into separate columns for street, city, 
   and state using SUBSTRING and PARSENAME
4. Standardized inconsistent values in the SoldAsVacant column 
   from Y/N to Yes/No using CASE logic
5. Identified and removed 104 duplicate rows using ROW_NUMBER 
   with PARTITION BY across key fields
6. Dropped unnecessary columns after splitting and converting data

## Skills Demonstrated
Data formatting, data type conversion, handling missing data via self-join, 
data normalization, CASE logic, duplicate removal with CTEs and ROW_NUMBER, 
SUBSTRING and PARSENAME for string manipulation, schema alteration

## Tools
SQL Server (T-SQL)

## Notes
This project was completed as part of a graduate-level data analytics 
portfolio to demonstrate practical SQL data cleaning capabilities 
on a real-world dataset.
