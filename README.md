# SQL-Project
This project demonstrates an end-to-end Data Cleaning and Exploratory Data Analysis (EDA) process using pure SQL on a dataset of tech industry layoffs.

🗂️ Dataset Overview:
Contains ~1,800 rows and 10 columns

Fields include: company, industry, location, country, total_laid_off, percentage_laid_off, date, stage, and funds_raised_millions

Covers layoffs across multiple countries and years

🧹 Data Cleaning Steps:
Removed duplicates using ROW_NUMBER() and CTEs

Standardized inconsistent entries (e.g. country names, industries)

Trimmed whitespace, removed special characters

Handled missing/null values via logical updates and deletions

Converted string dates to proper DATE format

📈 Exploratory Data Analysis:
Identified top companies by total layoffs

Tracked layoffs over time (monthly and yearly)

Built rolling aggregates with WINDOW FUNCTIONS

Ranked companies per year using DENSE_RANK()

💻 Tools Used:
MySQL

SQL (CTEs, Window Functions, Aggregate Functions, String & Date Functions)

🔗 Project Files:
Data Cleaning Project.sql: All SQL queries for cleaning and preparing the dataset

EDA Project.sql: SQL queries used for exploratory analysis and visual insights

layoffs.csv: Original raw dataset
