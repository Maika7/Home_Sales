## Home Sales Analysis with PySpark

## Overview
This project uses **PySpark** to analyze a dataset of home sales. The analysis involves querying key metrics, creating temporary views, partitioning data, and caching for optimized performance.

## Dataset
The dataset used in this analysis is `home_sales_revised.csv`, containing home sales data with features like:
- Sale price
- Number of bedrooms and bathrooms
- Year built
- Home views
- Square footage

## Key Objectives
1. Load the dataset into a PySpark DataFrame.
2. Perform SQL-based queries to:
   - Calculate average prices by year and home features.
   - Identify trends based on view ratings and other attributes.
3. Optimize queries using caching and partitioning.
4. Compare runtimes of cached and uncached operations.
5. Export results and insights for further use.

## Tools and Technologies
- **Python**
- **PySpark**
- **Google Colab**
- **Spark SQL**

## Analysis Steps
1. **Data Loading**:
   - The dataset was loaded into a PySpark DataFrame using `spark.read.csv`.

2. **Temporary View Creation**:
   - A temporary view `home_sales` was created for SQL-based analysis.

3. **SQL Queries**:
   - Average prices for specific home configurations.
   - Trends in home prices by view ratings.
   - Optimized runtime comparisons using caching.

4. **Caching and Partitioning**:
   - The dataset was cached and partitioned by `date_built` for performance improvements.

## Results
- Generated insights into home sales trends based on key features.
- Optimized query performance with caching and partitioning.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone <repository-url>
