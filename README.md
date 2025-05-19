# 📉 Global Layoffs Analysis (2020–2023)

This project is based on the **Layoffs.csv** dataset from [AlexTheAnalyst's Data Analyst Portfolio Project]((https://www.youtube.com/watch?v=rGx1QNdYzvs&list=PLUaB-1hjhk8FE_XZ87vPPSfHqb6OcM0cF)). It explores layoffs around the world between 2020 and 2023, with a focus on cleaning and preparing the data using **PostgreSQL**.

## 🗂️ Dataset Overview

- **Source:** Layoffs.csv (via AlexTheAnalyst)
- **Period:** 2020–2023
- **Columns include:**
  - company
  - company_location
  - industry
  - total_laid_off
  - percentage_laid_off
  - stage
  - country
  - date_laid_off
  - funds_raised_millions

## 🧹 Data Cleaning Steps

Data cleaning was performed using **PostgreSQL**, including the following tasks:

- Removed rows with missing company names or dates
- Converted date fields to proper `DATE` format
- Standardized text (e.g., capitalization and spacing in country and industry names)
- Handled null values and empty strings
- Removed duplicate records

## 🧰 Tools Used

- PostgreSQL  
- DBeaver (SQL IDE)  
- Excel (for preliminary inspection)

## 📌 Key Learnings

- Data cleaning techniques in SQL
- Handling missing and inconsistent data
- Preparing datasets for analysis and visualization
- Importance of clean and structured data

## 📁 Repository Contents

- `layoffs.csv` – Original dataset
- `Data Cleaning Project.sql` – SQL script used for data cleaning
- `README.md` – Project documentation

## 🙌 Credits

Project inspired by [AlexTheAnalyst’s Data Analyst Portfolio Project](https://www.youtube.com/@AlexTheAnalyst).
