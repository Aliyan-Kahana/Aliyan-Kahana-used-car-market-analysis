Aliyan-Kahana-Portfolio-

A comprehensive data analysis project examining a used car dataset of over one million rows processed via a single-file workflow, leveraging Python, SQL, Excel, and Power BI to uncover pricing trends, registration age distribution, brand market shares, and engine specifications.

🐍 Python Data Pipeline & Preprocessing
Jupyter Notebook: used_car_price_prediction.ipynbcontains data preprocessing, EDA, and feature engineering.
Data Ingestion: Efficiently loaded and processed a massive dataset containing over 1,000,000 rows into memory within a single-file workflow framework.
Feature Engineering: Transformed raw attributes into actionable metrics, such as calculating registration age and processing engine specifications for better statistical evaluation.
Data Cleaning & Preprocessing Pipeline
# Inspect data structure, non-null counts, and data types\ndf.info()
# Fix column names
# Remove duplicate rows
# Remove extra spaces
# Standardize text and numeric columns
# Fix spelling errors and inconsistent categories
# Fix data types
# Handle invalid values
# Handle missing values and outliers
# Drop unnecessary columns
# Create new useful columns (feature engineering)
# Verify categories
# Check final dataset
Used Cars Market Analysis & Price Prediction
Project Overview
Description: A comprehensive data analysis project examining a used car dataset of over one million rows processed via a single-file workflow.
Objective: Leverage Python to clean, analyze, and build predictive insights into pricing trends, registration age distribution, brand market shares, and engine specifications.
Project Structure
Main Script: used_car_price_prediction.ipynb contains the core Jupyter Notebook for data preprocessing, exploratory data analysis (EDA), feature engineering, and model implementation.
Tech Stack & Libraries
Language: Python
Data Manipulation & Cleaning: Pandas, NumPy
Data Visualization: Matplotlib
Key Features & Insights
Large-Scale Processing: Handled data processing for over 1,000,000 rows efficiently within a single-file workflow framework.
Data Hygiene: Cleaned and standardized raw string features, handled missing values, and managed outliers to ensure data integrity.
Statistical Visualization: Generated charts using Matplotlib to uncover key pricing determinants, depreciation trends, and automotive brand distribution.
Usage
Clone Repository: git clone https://github.com/aliyan-kahana/Aliyan-Kahana-Portfolio.git
Run Environment: Launch Jupyter Notebook using jupyter notebook used_car_price_prediction.ipynb
🛢️ SQL Data Analysis & Business Queries
SQL Script: cars.sql
Query Capabilities & Business Logic
Aggregations & Filtering: Used COUNT, AVG, GROUP BY, and HAVING to find the number of cars and average price per brand, and fuel types with average mileage above 18 kmpl.
Conditional Logic: Used CASE WHEN to classify cars into No Risk, Low Risk, and High Risk based on accident history.
Window Functions: Used ROW_NUMBER, DENSE_RANK, AVG() OVER, and NTILE to find the top 2 priciest cars per brand, rank cities by listings, compare each car's price to its city average, and split prices into quartiles by owner type.
CTEs: Used WITH to find brands with above-average horsepower, compare automatic vs. manual prices for each model, and count missing values.
Type: Distributed under the MIT License (see LICENSE for details).
📊 Power BI Interactive Dashboards & Analytics
Dashboard Overview: Comprehensive visual analysis tracking pricing trends, registration age, brand market shares, and engine specifications for used cars.
Key Power BI Features & Modeling
Data Modeling & DAX: Built custom DAX measures for Total Listings, Average Price, Average Kms Driven, Average Age, Average Horsepower, Average Engine CC, Average Mileage, First Owner Count, Accident Free %, Active Models Count, and Active Cities Count.
Interactive Filtering & Slicers: Enabled dynamic cross-filtering by city, fuel type, transmission, registration age, brand/model, owner type, accidents, seats, and number of doors.
Executive Visualizations: Designed custom visual layouts highlighting market pricing drivers, regional distribution, and brand-level listings and prices.
📈 Excel Analytics & Market Reporting
Excel File: Download Used Cars Analysis Excel File
Advanced Formulas & Pivot Tables
Data Retrieval & Cleaning: Applied XLOOKUP to retrieve values from the dataset, such as the price of the first Octavia, without modifying source data.
Aggregations & Summaries: Built interactive Pivot Tables to aggregate market prices across different car brands, registration age, and kms-driven brackets, and used AVERAGEIFS, COUNTIFS, and SUMPRODUCT formulas for targeted calculations, such as the average price of petrol BMWs and the number of Delhi cars with 0 accidents.
KPI Formatting & Charts: Created conditional formatting rules and custom charts to highlight key pricing trends, market share distribution, and depreciation metrics.
Key Insights
Executive Pricing & Depreciation: Tracked 1,000,000 used car listings showing an average valuation of 1.01M, highlighting a steady price depreciation curve against vehicle registration age.
Engine & Performance Metrics: Analyzed engine specifications across 39 active models, recording an average horsepower of 120.54 and 1.51K engine CC mapped across different fuel types and brands.
Vehicle Condition & Ownership: Evaluated accident history and ownership impact, revealing that first-owner cars make up 599K listings and accident-free vehicles maintain a higher average valuation.
Regional Inventory Distribution: Mapped inventory across 8 cities (including Delhi, Hyderabad, and Mumbai) plus 80,000 listings with an unknown city, detailing regional volume and brand-level market shares.
Dashboard Screenshots
1. Executive Overview and Price Dynamics

Executive Overview

2. Engine & Performance Specifications

Engine & Performance

3. Vehicle Feature and Condition Analysis

Vehicle Feature and Condition

4. Used Car Inventory & Regional Price Overview

Inventory & Regional Overview 📊 Excel Analysis & Dashboards

Excel File: Download Used Cars Analysis Excel File
Advanced Formulas & Pivot Tables
Data Retrieval & Cleaning: Applied XLOOKUP to retrieve values from the dataset, such as the price of the first Octavia, without modifying source data.
Aggregations & Summaries: Built interactive Pivot Tables to aggregate market prices across different car brands, registration age, and kms-driven brackets, and used AVERAGEIFS, COUNTIFS, and SUMPRODUCT formulas for targeted calculations, such as the average price of petrol BMWs and the number of Delhi cars with 0 accidents.
KPI Formatting & Charts: Created conditional formatting rules and custom charts to highlight key pricing trends, market share distribution, and depreciation metrics.
Used Car Market Data Analysis & Intelligence Portfolio

A comprehensive data analysis project examining a dataset of 1,000,000 used car records. This repository covers end-to-end data manipulation, SQL database queries, advanced Excel financial modeling and pivot analysis, and interactive Power BI executive dashboards.

🛠️ Tech Stack & Tools
Python: Data preprocessing, cleaning, text standardization, and missing value handling using Pandas, NumPy, and Matplotlib.
SQL: Database management and complex queries (CTEs, window functions, subqueries, and multi-table joins) executed via SQLite and MySQL Workbench.
Microsoft Excel: Advanced formulas (XLOOKUP, INDEX/MATCH, AVERAGEIFS, SUMPRODUCT, IF/OR), Pivot Tables, and interactive charts.
Power BI: Multi-page interactive executive dashboards featuring custom DAX measures, KPI cards, and dynamic navigation.

📊 Dataset & Schema

Data Overview: Processed a dataset containing 1,000,000 used car listings with 16 columns.
File Access: Download Used Cars Analysis Excel File

📊 Excel Analysis & Dashboards

Data Retrieval & Cleaning: Applied XLOOKUP, INDEX/MATCH, and VLOOKUP to retrieve values from the dataset, such as the price of the first Octavia, without altering source inputs.
Aggregations & Summaries: Built multi-variable Pivot Tables to analyze pricing metrics across brands, registration age, and kms-driven brackets, and used AVERAGEIFS, SUMPRODUCT, COUNTIFS, and SUMIFS formulas for targeted calculations.
Risk Modeling & Formatting: Implemented conditional formatting rules and logical formulas (IF, OR) to categorize high-risk listings based on accident counts and mileage thresholds.
Excel Screenshots
1. Advanced Formulas & Calculations

Formulas Preview

2. Pivot Tables & Summary Layouts (Part 1)

Pivot Tables 1 Preview

3. Pivot Tables & Summary Layouts (Part 2)

Pivot Tables 2 Preview

4. Advanced Pivot Charts & Distributions

Pivot Charts Preview

Key Metrics
Total Rows: ~1,000,000
Total Columns: 16
Key Attributes: Car Brands & Models, Engine CC, Horsepower, Registration Age, Pricing, and Mileage
