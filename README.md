# Used Car Market Analysis
A comprehensive data analysis project examining a used car dataset of over one million rows, leveraging Python, SQL, Excel, and Power BI to uncover pricing trends, registration age distribution, brand market shares, and engine specifications.
## 🐍 Python Data Pipeline & Preprocessing

* **Jupyter Notebook**: [`used_car_price_prediction.ipynb`](./used_car_price_prediction.ipynb) contains data cleaning, outlier checks (EDA), and missing-value handling.
* **Data Ingestion**: Efficiently loaded and processed a massive dataset containing over 1,000,000 rows into memory using Pandas.
* **Data Preparation**: Standardized text and numeric columns, converted invalid values to missing, filled missing engine specifications with group medians, and dropped unnecessary columns for better statistical evaluation.

## Data Cleaning & Preprocessing Pipeline

* `# Inspect data structure, non-null counts, and data types: df.info()`
* `# Remove duplicate rows`
* `# Remove extra spaces`
* `# Standardize text and numeric columns`
* `# Fix spelling errors and inconsistent categories`
* `# Fix data types`
* `# Handle invalid values`
* `# Handle missing values and check outliers`
* `# Drop unnecessary columns`
* `# Verify categories`
* `# Check final dataset`
* `# Load the clean table into MySQL`

# Used Cars Market Analysis

## Project Overview
* **Description**: A comprehensive data analysis project examining a used car dataset of over one million rows.
* **Objective**: Leverage Python to clean and analyze the data, and uncover insights into pricing trends, registration age distribution, brand market shares, and engine specifications.

## Project Structure
* **Main Script**: `used_car_price_prediction.ipynb` contains the core Jupyter Notebook for data cleaning, outlier checks (EDA), and loading the clean data into MySQL.

## Tech Stack & Libraries
* **Language**: Python
* **Data Manipulation & Cleaning**: Pandas, NumPy
* **Data Visualization**: Matplotlib
* **Database Connection**: SQLAlchemy, PyMySQL

## Key Features & Insights
* **Large-Scale Processing**: Handled data processing for over 1,000,000 rows efficiently using Pandas.
* **Data Hygiene**: Cleaned and standardized raw string features, handled missing values, and checked outliers to ensure data integrity.
* **Statistical Visualization**: Generated charts using Matplotlib to show category distributions and outlier counts across fuel type, brand, registration age, transmission, and model.

## Usage
* **Clone Repository**: `git clone https://github.com/Aliyan-Kahana/Aliyan-Kahana-used-car-market-analysis.git`
* **Run Environment**: Launch Jupyter Notebook using `jupyter notebook used_car_price_prediction.ipynb`
## 🛢️ SQL Data Analysis & Business Queries

* **SQL Script**: [`cars.sql`](./cars.sql)
* **Database**: MySQL (table `cars`, loaded from Python)

## Query Capabilities & Business Logic
- **Aggregations & Filtering**: Used `COUNT`, `AVG`, `GROUP BY`, and `HAVING` to find the number of cars and average price per brand, and fuel types with average mileage above 18 kmpl.
- **Conditional Logic**: Used `CASE WHEN` to classify cars into No Risk, Low Risk, and High Risk based on accident history.
- **Window Functions**: Used `ROW_NUMBER`, `DENSE_RANK`, `AVG() OVER`, and `NTILE` to find the top 2 priciest cars per brand, rank cities by listings, compare each car's price to its city average, and split prices into quartiles by owner type.
- **CTEs**: Used `WITH` to find brands with above-average horsepower, compare automatic vs. manual prices for each model, and count missing values.
## 📊 Power BI Interactive Dashboards & Analytics

* **Dashboard Overview**: Comprehensive visual analysis tracking pricing trends, registration age, brand market shares, and engine specifications for used cars.

## Key Power BI Features & Modeling

* **Data Modeling & DAX**: Built KPI measures for Total Listings, Average Price, Average Kms Driven, Average Age, Average Horsepower, Average Engine CC, Average Mileage, First Owner Count, Accident Free %, Active Models Count, and Active Cities Count.
* **Interactive Filtering & Slicers**: Enabled dynamic cross-filtering by city, fuel type, transmission, registration age, brand/model, owner type, accidents, seats, and number of doors.
* **Executive Visualizations**: Designed custom visual layouts highlighting price trends by registration age, the impact of accidents on price, regional distribution, and brand-level listings and prices.

## Key Insights

* **Executive Pricing & Depreciation**: Tracked 1,000,000 used car listings showing an average valuation of 1.01M, highlighting a steady price depreciation curve against vehicle registration age (about 1.59M for 1-year-old cars to about 0.53M for 25-year-old cars).
* **Engine & Performance Metrics**: Analyzed engine specifications across 39 active models, recording an average horsepower of 120.54 and 1.51K engine CC mapped across different fuel types and brands.
* **Vehicle Condition & Ownership**: Evaluated accident history and ownership impact, revealing that first-owner cars make up 599K listings and accident-free vehicles (741K listings) maintain a higher average valuation (about 1.02M with 0 accidents vs. about 0.65M with 5 accidents).
* **Regional Inventory Distribution**: Mapped inventory across 8 cities (including Delhi, Hyderabad, and Mumbai, plus 80,000 listings with an unknown city), detailing regional volume and brand-level listings.

## Dashboard Screenshots

### 1. Executive Overview and Price Dynamics
![Executive Overview](https://github.com/Aliyan-Kahana/Aliyan-Kahana-used-car-market-analysis/raw/main/images/Screenshot%202026-09-01%20101353.png)

### 2. Engine & Performance Specifications
![Engine & Performance](https://github.com/Aliyan-Kahana/Aliyan-Kahana-used-car-market-analysis/raw/main/images/Screenshot%202026-09-01%20101402.png)

### 3. Vehicle Feature and Condition Analysis
![Vehicle Feature and Condition](https://github.com/Aliyan-Kahana/Aliyan-Kahana-used-car-market-analysis/raw/main/images/Screenshot%202026-09-01%20101530.png)

### 4. Used Car Inventory & Regional Price Overview
![Inventory & Regional Overview](https://github.com/Aliyan-Kahana/Aliyan-Kahana-used-car-market-analysis/raw/main/images/Screenshot%202026-09-01%20101641.png)

# Used Car Market Data Analysis & Intelligence Portfolio

A comprehensive data analysis project examining a dataset of 1,000,000 used car records. This repository covers end-to-end data manipulation, SQL database queries, Excel pivot analysis, and interactive Power BI executive dashboards.

---

## 🛠️ Tech Stack & Tools

* **Python**: Data preprocessing, cleaning, text standardization, and missing value handling using Pandas, NumPy, and Matplotlib.
* **SQL**: Database queries (aggregations, `CASE WHEN`, CTEs, and window functions) executed in MySQL.
* **Microsoft Excel**: Formulas (`XLOOKUP`, `INDEX/MATCH`, `AVERAGEIFS`, `SUMPRODUCT`, `IF/OR`), Pivot Tables, and interactive charts.
* **Power BI**: 4-page interactive executive dashboards featuring KPI measures and slicers.

---

## 📊 Dataset & Schema

* **Data Overview**: Processed a single dataset containing 1,000,000 used car listings across 16 columns.
* **File Access**: [Download Used Cars Analysis Excel File](https://drive.google.com/uc?export=download&id=1rFVI-xMbblhBJ3QsIJj-b6ml6cCaoiYc)

---

## 📊 Excel Analysis & Dashboards

* **Data Retrieval**: Applied `XLOOKUP`, `INDEX/MATCH`, and `VLOOKUP` to retrieve values from the dataset without altering source inputs.
* **Aggregations & Summaries**: Built Pivot Tables to analyze pricing metrics across brands, cities, registration age, and kms-driven brackets. Used `AVERAGEIFS`, `COUNTIFS`, and `SUMPRODUCT` formulas for targeted calculations, such as the average price of petrol BMWs and the number of Delhi cars with 0 accidents.
* **Risk Flag**: Used a logical formula (`IF`, `OR`) to mark cars with more than 2 accidents or more than 300,000 kms driven as High Risk.

### Excel Screenshots

#### 1. Advanced Formulas & Calculations
![Formulas Preview](https://github.com/Aliyan-Kahana/Aliyan-Kahana-used-car-market-analysis/raw/main/excel%20images/Screenshot%202026-09-01%20102705.png)

#### 2. Pivot Tables & Summary Layouts (Part 1)
![Pivot Tables 1 Preview](https://github.com/Aliyan-Kahana/Aliyan-Kahana-used-car-market-analysis/raw/main/excel%20images/Screenshot%202026-09-01%20102726.png)

#### 3. Pivot Tables & Summary Layouts (Part 2)
![Pivot Tables 2 Preview](https://github.com/Aliyan-Kahana/Aliyan-Kahana-used-car-market-analysis/raw/main/excel%20images/Screenshot%202026-09-01%20102754.png)

#### 4. Advanced Pivot Charts & Distributions
![Pivot Charts Preview](https://github.com/Aliyan-Kahana/Aliyan-Kahana-used-car-market-analysis/raw/main/excel%20images/Screenshot%202026-09-01%20102803.png)

## Key Metrics

* **Total Rows:** ~1,000,000
* **Total Columns:** 16
* **Key Attributes:** Car Brands & Models, Engine CC, Horsepower, Registration Age, Pricing, and Mileage

## License

* **Type**: Distributed under the MIT License (see `LICENSE` for details).
