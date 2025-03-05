# Global Company Layoffs

## 📌 Project Overview
This project focuses on cleaning and analyzing a dataset of global company layoffs using SQL. The dataset includes information on companies, industries, locations, and layoff statistics.

## 🗂 Dataset Information
The dataset contains the following columns:
- `company`: Name of the company
- `location`: Location of the company
- `industry`: Industry sector
- `total_laid_off`: Number of employees laid off
- `percentage_laid_off`: Percentage of workforce affected
- `date`: Layoff date
- `stage`: Company growth stage
- `country`: Country of operation
- `funds_raised_millions`: Total funds raised (in millions)

## 🔧 Data Cleaning Steps
The data cleaning process involved:
1. **Removing Duplicates** - Identified and removed duplicate records.
2. **Standardizing Data** - Trimmed extra spaces, fixed inconsistent naming.
3. **Handling Missing Values** - Filled missing industry data using existing company information.
4. **Formatting Dates** - Converted date column from text to a proper `DATE` format.
5. **Dropping Unnecessary Columns** - Removed unwanted columns after processing.

## 📜 SQL Queries
All SQL scripts used for cleaning the dataset are stored in the **SQL folder**.

## 🚀 How to Use
To run the SQL queries:
1. Load the dataset into your database.
2. Use the provided SQL scripts to clean and standardize the data.
3. Analyze the cleaned dataset for insights.
.

## 🏷 Technologies Used
- **SQL**
- **MySQL**
- **Data Cleaning & Analysis**

