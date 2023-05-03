# Marketing And Sales Dataset Analysis

This project performs exploratory data analysis (EDA) on a sales dataset using the pandas, numpy, matplotlib, and seaborn libraries. The script reads in the dataset, drops irrelevant columns, handles missing values, changes data types, and creates visualizations to explore relationships between different variables in the data.

## Requirements

To run this project, the user needs to have Python 3 installed on their system, as well as the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scipy.stats

## Data Cleaning and Preprocessing

The first part of the script reads in the data from the CSV file and performs some initial data cleaning by converting the 'Calendardate' column to a datetime format and creating two new columns to extract the month and year from the 'Calendardate' column. It then drops irrelevant columns, handles missing values, and changes data types.

## Basic Statistics and Cross-Tabulation

The second part of the script provides some basic statistics on the 'Client Type' column using value_counts() and creates a cross-tabulation table using crosstab() to examine the relationship between 'Number of Competition' and 'Client Type'.

## Groupby and Correlation Analysis

The third part of the script groups the data by 'Number of Competition' and 'Client Type' and calculates the mean values for the other variables in the dataset using groupby(). It also calculates the correlation coefficients between 'Amount Collected' and the other variables in the dataset using corr().

## Visualization

Finally, the script creates two correlation analysis tables using seaborn to visualize the relationship between 'Amount Collected' and the other variables in the dataset. 

## Insights

This script provides an example of how a data analyst can use Python to extract insights from a dataset, perform statistical analyses, and create visualizations to communicate those insights effectively. The insights obtained from this analysis can help businesses make data-driven decisions and plan strategies accordingly.

## Implementation Details 

1. Importing the necessary libraries
2. Reading in the dataset and performing initial data cleaning
3. Basic statistics and cross-tabulation
4. Groupby and correlation analysis
5. Visualization

Overall, this project provides a useful example of how data analysis and visualization can be used to gain insights into sales data and inform business decisions.

