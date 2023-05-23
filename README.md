# Russian Alcohol Consumption Analysis

This project aims to analyze the patterns and trends in Russian alcohol consumption. The dataset used contains information on various types of alcoholic beverages, including wine, beer, vodka, champagne, and brandy, across different regions and years.

## Dataset

The dataset, named "russian_alcohol_consumption.csv", is included in the "Data Set" directory. It provides detailed information on alcohol sales for each year and region. The dataset contains the following columns:
- `year`: The year of the data record.
- `region`: The name of the region.
- `wine`: Sales volume of wine in liters.
- `beer`: Sales volume of beer in liters.
- `vodka`: Sales volume of vodka in liters.
- `champagne`: Sales volume of champagne in liters.
- `brandy`: Sales volume of brandy in liters.

## Analysis Steps

1. Data Cleaning: The dataset is checked for missing values, and any gaps in the data are addressed using appropriate techniques such as mean imputation.

2. Exploratory Data Analysis: Various visualizations, including histograms and line plots, are used to analyze the distribution and trends in alcohol sales over time. Insights into the consumption patterns of different alcohol types are derived from these visualizations.

3. Top-Selling Alcohol Types and Regions: The project identifies the top-selling alcohol types and regions based on mean sales. This analysis provides valuable information on popular alcohol choices and the geographical preferences of consumers.

## Dependencies

The project requires the following dependencies:
- Python 3
- pandas
- numpy
- matplotlib
- seaborn

