Data Transformation and Feature Creation

Project Overview

This project demonstrates data transformation and feature creation using Python. A structured sales dataset is used to generate meaningful business insights using Pandas operations.

The main goal is to convert raw data into useful analytical information by creating new features and performing analysis.

Objectives

- Load and explore dataset
- Perform data transformation
- Create new features from existing data
- Apply Pandas functions like map, apply, applymap
- Generate simple business insights

Dataset Description

The dataset contains sales transaction details:

- OrderID
- CustomerName
- Product
- Category
- Quantity
- Price
- Discount
- Region

Feature Creation

New columns created from existing data:

- TotalSales = Quantity * Price
- DiscountAmount = TotalSales * Discount
- FinalAmount = TotalSales - DiscountAmount
- Profit = FinalAmount * 0.20
- RegionCode created using map function
- RevenueCategory created using apply function

Techniques Used

- map function for encoding values
- apply function for conditional logic
- applymap concept for element wise operations
- groupby for grouped analysis

Analysis Performed

- Category wise sales analysis
- Region wise sales analysis
- Product performance analysis
- Revenue category distribution

Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

Project Structure

Day-12_Data_Transformation_Feature_Creation/

├── Transformation.ipynb
├── sales_data_large.csv
└── README.md

Conclusion

This project demonstrates how raw sales data can be transformed into meaningful insights using feature creation and data analysis techniques in Python.
