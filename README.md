# Layoffs Dataset Data Cleaning Project

## Introduction

This project focuses on the data cleaning and preprocessing of the "Layoffs 2022" dataset, sourced from Kaggle. The dataset contains information about various layoffs that occurred in 2022 across different companies and industries.

### Project Overview

The primary goal of this project is to prepare the dataset for further analysis by addressing common data quality issues. This involves:

1. **Removing Duplicates**: Identifying and eliminating duplicate rows to ensure the integrity and accuracy of the dataset.
2. **Standardizing Data**: Ensuring consistency in categorical data fields such as industry and country, and correcting inconsistencies and formatting errors.
3. **Handling Null Values**: Evaluating and addressing null values in key columns to facilitate accurate analysis and reporting.
4. **Column and Row Cleanup**: Removing unnecessary columns and rows that do not contribute to the analysis or are redundant.

### Steps Taken

1. **Staging Table Creation**: A staging table was created to work with the raw data, preserving the original dataset for reference and recovery.
2. **Duplicate Removal**: Implemented queries to identify and delete duplicate rows based on a comprehensive set of columns.
3. **Data Standardization**: Addressed issues such as null values, empty strings, and inconsistent categories. This included standardizing industry names and country names.
4. **Date Formatting**: Converted date columns from string format to DATE format to ensure proper date handling and analysis.

### Objective

By cleaning and standardizing the data, this project aims to enhance the quality and usability of the dataset, making it ready for exploratory data analysis (EDA) and further statistical or machine learning modeling.

Feel free to explore the cleaned dataset and use it for any analytical purposes or further investigations.

---

