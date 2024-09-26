# Coffee_Sales_analysis

# Objective -
The main objective of this project is to analyze reatil sales data to gain actionable insights that will enhance the performance of the Coffee_Sales.

# About Data -
The dataset contains Date,Time,Cash_type,Card,Coffee_name .The data contains 5 columns and 1134 rows.

# Analysis List-
  1.Sales Analysis -
    This analysis aims to answer the questions of the sales trends of product.The result of this can help use measure the effectiveness
    of each sales strategy the business applies and what modifications are needed togain more sales.

  2.Customer Analysis -
    This analysis to uncover the different Customer, Purchase trends and the profitability of each customer segment.

# Approach Used-

1.Data Wrangling: This the first step where  inspection of data is done to make sure NULL values and missing values are detected and data 
  replacement methods are used to replace, missing or NULL values.
  1.Build a database.
  2.Create table and insert the data.
  3.Select columns with null values in them.there are no null values in our database as in creating the tables,
    we set NOT NULL for each field, hence null values are filtered out.
    
2.Feature Engineering: This will help use generate some new columns from existing ones.
  Add a new column named time_of_day to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day 
  most sales are made.
  Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help 
  answer the question on which week of the day each branch is busiest.
  Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which 
  month of the year has the most sales and profit.
  
3.Exploratory Data Analysis (EDA): Exploratory data analysis is done to answer the listed questions and aims of this project.

4.Conclusion :

# Business Questions to answer

# Sales
1.What are the peak hours for sales?
2.Are there any trends in sales over the days of the week (e.g., weekends vs. weekdays)?
3.Are there any seasonal or date-specific spikes in sales for certain coffee types?

# Product
1.Which coffee type generates the most revenue?
2.Which coffee types contribute the most to overall profit margins?
3.Are there any coffee types that underperform or are rarely purchased?

# Customer
1.Are there any patterns in spending by specific cardholders?
2.How does spending differ between payment types (e.g., card vs. cash)?
















