Overview

This project focuses on cleaning and preparing the Nashville Housing dataset using SQL for analysis and visualization.

Dataset

NashvilleHousing – Property sales data including addresses, sale dates, prices, and ownership details.

Key Cleaning Steps

Standardized sale date format

Filled missing property addresses using parcel IDs

Split property and owner addresses into separate columns

Converted Y/N values to Yes/No in the SoldAsVacant field

Removed duplicate records

Dropped unused columns to simplify the dataset

SQL Concepts Used

UPDATE, ALTER TABLE

String functions (SUBSTRING, CHARINDEX, PARSENAME)

CASE statements

Joins

CTEs and window functions (ROW_NUMBER)

Data cleaning and transformation

Output

A clean, structured housing dataset ready for analysis, reporting, or visualization.
