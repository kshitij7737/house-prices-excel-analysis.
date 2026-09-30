# House Prices Dataset Analysis

## Introduction

This project is a Week 2 Excel and Data Exploration assignment based on the House Prices dataset.

The work focuses on understanding the dataset, checking data quality, exploring relationships between house characteristics and sale price, comparing different groups, identifying unusual observations, and presenting the results using Excel tables, formulas, and visualizations.

The assignment includes both the Practice Work and the Business Problems provided in the course material.

## Dataset

The dataset contains 1,460 house records and 81 variables.

Some of the main variables used in the analysis are:

- OverallQual
- OverallCond
- Neighborhood
- YearBuilt
- YearRemodAdd
- TotalBsmtSF
- GrLivArea
- GarageCars
- GarageArea
- BedroomAbvGr
- FullBath
- Fireplaces
- YrSold
- SalePrice

SalePrice is used as the target variable throughout the analysis.

## Practice Work

The Practice Work covers the following analyses:

1. Identifying the number of rows and columns in the dataset.
2. Classifying variables as Numerical, Categorical, or Ordinal.
3. Identifying SalePrice as the target variable.
4. Calculating missing values for all columns and identifying data-quality concerns.
5. Calculating descriptive statistics for SalePrice.
6. Exploring OverallQual in relation to SalePrice.
7. Comparing Neighborhood with average SalePrice and the number of houses.
8. Exploring the relationship between GrLivArea and SalePrice using a scatter plot and correlation.
9. Exploring TotalBsmtSF, GarageCars, and GarageArea in relation to SalePrice.
10. Comparing SalePrice across YrSold.
11. Examining SalePrice distributions using a box-and-whisker plot.
12. Identifying unusually high or low SalePrice observations using the IQR method.
13. Creating a correlation matrix for selected numerical variables.
14. Writing observations for the charts created.
15. Recording the Excel formulas and methods used for the analysis.

## Descriptive Statistics

The completed analysis of SalePrice produced the following results:

| Statistic | Result |
| --- | --- |
| Count | 1,460 |
| Sum | 264,144,946 |
| Average | 180,921.1959 |
| Median | 163,000 |
| Minimum | 34,900 |
| Maximum | 755,000 |
| Standard Deviation | 79,442.5029 |

## Missing-Value Analysis

Missing values were checked across all columns.

The analysis considered both blank cells and "NA" entries when calculating missing values. Columns with missing data were identified for data-quality attention, including variables related to lot frontage, alley access, masonry veneer, basement characteristics, electrical system, fireplaces, garages, pools, fences, and miscellaneous features.

## Outlier Analysis

SalePrice was also examined using the interquartile range (IQR) method.

The calculated values were:

- Q1 = 129,975
- Q3 = 214,000
- IQR = 84,025
- Lower Bound = 3,937.5
- Upper Bound = 340,037.5

Using these bounds, 61 observations were identified above the upper IQR limit, while no observations were below the lower limit.

## Business Problems

The workbook also explores the 12 Business Problems from the assignment.

### 1. Factors Associated with House Sale Price

The analysis examines SalePrice in relation to variables such as OverallQual, GrLivArea, TotalBsmtSF, GarageCars, GarageArea, and YearBuilt using summary statistics, scatter plots, and correlation analysis.

### 2. House Quality and Sale Price

SalePrice is compared across different OverallQual levels using grouped summaries and visualizations, including distribution analysis.

### 3. Neighborhood and House Prices

Neighborhood categories are compared using sale-price summaries and house counts to understand differences between locations.

### 4. House Size and Sale Price

The relationship between house size and SalePrice is explored using GrLivArea, 1stFlrSF, 2ndFlrSF, and TotalBsmtSF.

### 5. House Age and Sale Price

YearBuilt and YearRemodAdd are examined in relation to SalePrice using visual and grouped analysis.

### 6. Garage Capacity and Sale Price

The analysis compares SalePrice across GarageCars values and examines the relationship between GarageArea and SalePrice.

### 7. House Features and Price Distribution

Features such as bedrooms, bathrooms, fireplaces, basement area, and porch areas are explored in relation to SalePrice.

### 8. Common House and Property Types

The frequency of categories such as HouseStyle, BldgType, Foundation, RoofStyle, and Heating is explored using frequency tables and charts.

### 9. Unusual or Extreme House Prices

Very high and very low SalePrice observations are identified and examined alongside other house characteristics.

### 10. Sale Price by Year

SalePrice is compared across YrSold using grouped summaries and visualizations, including a line chart.

### 11. Data-Quality Problems

The dataset is checked for missing values and variables with substantial missingness are identified.

### 12. House-Price Prediction Preparation

SalePrice is identified as the target variable and selected variables are explored as potential predictors for a future house-price prediction problem.

## Excel Functions and Methods Used

The project uses a range of Excel functions and analysis tools, including:

- COUNT
- SUM
- AVERAGE
- MEDIAN
- MIN
- MAX
- STDEV.S
- COUNTIF
- COUNTBLANK
- AVERAGEIF
- QUARTILE.INC
- FILTER
- LARGE
- SMALL
- IQR calculations
- Data Analysis – Correlation
- Remove Duplicates
- Conditional Formatting

## Visualizations Used

The analysis includes several types of Excel visualizations:

- Column charts
- Line charts
- Scatter plots
- Box-and-whisker plots
- Correlation heatmap
- Frequency charts

These visualizations were used to compare groups, examine relationships, understand distributions, and identify patterns in the data.

## Key Observations

Some of the main patterns observed during the analysis were:

- SalePrice generally increases as OverallQual increases.
- GrLivArea has a positive relationship with SalePrice.
- Houses in different neighborhoods have different average sale prices.
- Garage capacity and garage area show positive relationships with sale price.
- Basement area is also positively related to SalePrice.
- SalePrice varies across different selling years.
- The distribution of SalePrice contains some unusually high observations.
- Missing values are concentrated in particular variables rather than being evenly distributed across the dataset.

These observations describe patterns found in the dataset and do not by themselves establish causal relationships.

## Learning Outcomes

Through this project, I gained practical experience in:

- Working with a real-world dataset in Excel.
- Understanding different types of variables.
- Performing data-quality checks.
- Calculating descriptive statistics.
- Creating grouped summaries.
- Using correlation analysis.
- Creating and interpreting different types of charts.
- Identifying outliers using the IQR method.
- Using Excel functions for data analysis.
- Presenting findings clearly from tables and visualizations.

## Conclusion

This project provided a complete introduction to exploratory data analysis using Excel.

Starting with the structure and quality of the dataset, the analysis progressed to descriptive statistics, group comparisons, relationship analysis, visualization, outlier detection, and preparation for a possible house-price prediction problem.

Overall, the project helped develop practical skills in using Excel to explore data, identify meaningful patterns, and communicate analytical findings clearly.

