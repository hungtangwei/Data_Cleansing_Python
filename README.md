# Data_Cleansing_Python
Analyze dataset, find and fix the problems in the data.

## Introduction
For this assessment, you are required to write Python (Python 2/3) code to analyze your dataset, find and fix the problems in the data. The input and output of this task are shown below:

Table 1. The input and output of the task

Input:
- dirty_data.csv 
- outlier_data.csv 
- missing_data.csv

Output:
- dirty_data_solution.csv 
- outlier_data_solution.csv 
- missing_data_solution.csv

Exploring and understanding the data is one of the most important parts of the data wrangling process. You are required to perform graphical and/or non-graphical EDA methods to understand the data first and then find the data problems. You are required to:
- ● Detect and fix errors in dirty_data.csv
- ● Detect and remove outlier rows in outlier_data.csv
(outliers are to be found w.r.t. delivery_fee attribute)
- ● Impute the missing values in missing_data.csv

As a starting point, here is what we know about the dataset in hand:

The dataset contains Food Delivery data from a restaurant in Melbourne, Australia. The restaurant has three branches around CBD area. All three branches share the same menu but they have different management so they operate differently.

Each instance of the data represents a single order from said restaurant.

## Task:
1. The output ​csv​ files ​must ​have the exact same columns as the input.
2. There is at least one anomaly in the dataset from each category of the data anomalies (i.e.,
syntactic, semantic, and coverage).
3. In the file ​<GroupName>_dirty_data.csv, a​ ny row can carry no more than one anomaly. (i.e.
there can only be one anomaly in a single row and all anomalies are fixable)
4. There are no data anomalies in the file ​<GroupName>_outlier_data.csv, ​only outliers. Similarly, there are no data anomalies other than missing value problems in the file
<GroupName>_missing_data.csv
5. There are three types of meals:
- a. Breakfast - served during morning (8am - 12pm),
- b. Lunch - served during afternoon (12:00:01pm - 4pm)
- c. Dinner - served during evening (4:00:01pm - 8pm)
Each meal has a distinct set of items in the menu (ex: breakfast items can't be served during
lunch or dinner and so on).
6. A useful python package to solve a linear system of equations is ​numpy.linalg
7. Delivery fee is calculated using a different method for each branch. The fee depends linearly (but in different ways for each branch) on:
- a. weekend or weekday (1 or 0) - as a continuous variable
- b. time of the day (morning 0, afternoon 1, evening 2) - as a continuous variable
- c. distance between branch and customer
  If a customer has loyalty, they get a 50% discount on delivery fee
8. The restaurant uses Djikstra algorithm to calculate the shortest distance between customer and restaurant. (explore ​networkx python package for this or alternatively find a way to implement the algorithm yourself)
9. As EDA is part of this assessment, no further information will be given publicly regarding the data.

## Authors

Tangwei, Hung

## Contact
hung.tangwei@gmail.com
