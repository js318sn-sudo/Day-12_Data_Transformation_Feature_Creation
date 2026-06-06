# Day 11: Advanced Pandas - GroupBy, Merge, Pivot & Multi-Table Analysis

## Project Overview

This project demonstrates advanced data analysis techniques using the Pandas library. Multiple datasets are combined and analyzed to generate meaningful business insights through GroupBy operations, aggregation functions, transformations, filtering, merge operations, and pivot tables.

## Objectives

- Load and explore multiple datasets.
- Perform data inspection and validation.
- Apply GroupBy operations for data summarization.
- Group data using multiple columns.
- Use aggregation functions for statistical analysis.
- Apply transformation methods on grouped data.
- Filter groups based on business conditions.
- Perform Inner Merge and Outer Merge operations.
- Conduct multi-table analysis using merged datasets.
- Create Pivot Tables for summarized reporting.
- Generate visualizations and business insights.

## Datasets Used

### customers.csv
Contains customer information.

Columns:
- CustomerID
- CustomerName
- City
- Age
- Gender

### products.csv
Contains product information.

Columns:
- ProductID
- ProductName
- Category
- Price

### orders.csv
Contains order transaction information.

Columns:
- OrderID
- CustomerID
- ProductID
- Quantity
- Amount
- OrderDate

## Concepts Implemented

### Data Exploration
- head()
- info()
- describe()
- shape
- isnull()
- duplicated()

### GroupBy Operations
- Single Column Grouping
- Multiple Column Grouping
- Aggregation Functions
- Transform Methods
- Group Filtering

### Merge Operations
- Inner Merge
- Outer Merge
- Multi-Table Merge

### Pivot Tables
- Customer-wise Sales Analysis
- Category-wise Revenue Analysis

### Business Analysis
- Top Customers
- Revenue by Category
- Best Selling Products
- Sales Performance Analysis

### Data Visualization
- Revenue by Category
- Top Customers
- Best Selling Products

## Key Insights

- Identified high-value customers based on total spending.
- Analyzed category-wise revenue generation.
- Determined best-selling products using quantity sold.
- Compared customer purchasing behavior.
- Generated summarized reports using pivot tables.

## Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

## Project Structure

Day-11_Advanced_Pandas_Assessment/

├── advanced_pandas_report.ipynb

├── customers.csv

├── products.csv

├── orders.csv

└── README.md

## Learning Outcomes

Through this project, the following advanced Pandas concepts were practiced:

- DataFrame Manipulation
- GroupBy Analysis
- Aggregation Techniques
- Transform Functions
- Filtering Operations
- Data Merging
- Multi-Table Analysis
- Pivot Tables
- Data Visualization
- Business Insight Generation

## Conclusion

This project successfully demonstrates advanced Pandas techniques for analyzing multiple datasets and generating meaningful business insights through grouping, aggregation, merging, pivot table creation, and visualization.
