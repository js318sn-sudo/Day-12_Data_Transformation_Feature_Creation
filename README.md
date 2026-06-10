# DATA TRANSFORMATION AND FEATURE CREATION PROJECT

PROJECT OVERVIEW

This project demonstrates data transformation and feature engineering using Python. A structured sales dataset is used to convert raw data into meaningful analytical insights using Pandas.

The objective is to clean, transform, and analyze data to support business decision-making.

OBJECTIVES

- Load and explore dataset
- Perform data transformation and validation
- Create new derived features
- Apply Pandas functions including map, apply, applymap, and groupby
- Perform structured data analysis
- Generate business insights

DATASET DESCRIPTION

The dataset contains the following fields:

- OrderID: Unique identifier for each transaction
- CustomerName: Name of the customer
- Product: Product purchased
- Category: Product category
- Quantity: Number of units purchased
- Price: Price per unit
- Discount: Discount applied
- Region: Sales region

FEATURE CREATION

The following features were created:

- TotalSales = Quantity * Price
- DiscountAmount = TotalSales * Discount
- FinalAmount = TotalSales - DiscountAmount
- Profit = FinalAmount * 0.20
- RegionCode created using map function
- RevenueCategory created using apply function

## Language Used

Python

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- CSV Files

TECHNIQUES USED

Pandas Operations:
- map() for categorical encoding
- apply() for conditional feature creation
- applymap() for element-wise transformation
- groupby() for aggregation and analysis

ANALYSIS PERFORMED

- Category-wise sales analysis
- Region-wise sales analysis
- Product-wise performance analysis
- Revenue category distribution analysis

VISUALIZATION

- Bar chart representation using Matplotlib for category-wise sales

TOOLS AND TECHNOLOGIES

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

PROJECT STRUCTURE

Day-12_Data_Transformation_and_Feature_Creation/

├── Data_Transformation_&_Feature_Creation.ipynb
├── sales_data_large.csv
└── README.md

KEY INSIGHTS

- Electronics category generates higher revenue compared to furniture
- Regional distribution impacts total sales performance
- Discounts significantly affect final revenue values
- Revenue categorization helps in business segmentation

CONCLUSION

This project demonstrates a complete workflow of data transformation and feature engineering. It shows how raw transactional data can be converted into structured insights using Python and Pandas.
