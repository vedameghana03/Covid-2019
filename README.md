# Covid-2019

# COVID-19 Data Analysis

This project involves performing data analysis on COVID-19 data using Python and the pandas library.

## Dataset

The dataset used is `Covid 19 data.csv`. It contains information about COVID-19 cases, including dates, states, regions, confirmed cases, deaths, and recovered cases.

## Project Goals

The primary goals of this project are to analyze the COVID-19 dataset using pandas. Specific operations include:

1.  Finding the number of confirmed, deaths, and recovered cases in each region.
   
2.  Removing records where the number of confirmed cases is less than 10.
   
3.  Determining the region with the maximum number of confirmed cases.
   
4.  Determining the region with the minimum number of death cases.
   
5.  Finding the number of confirmed, deaths, and recovered cases reported from India.
   
6.  Sorting the data by confirmed cases in ascending order.
   
7.  Sorting the data by recovered cases in descending order.

## Libraries Used

* pandas
* seaborn
* matplotlib.pyplot

## Code Description

1.  **Import pandas:** The pandas library is imported for data manipulation and analysis.
   
2.  **Load the dataset:** The dataset is loaded into a pandas DataFrame.
   
3.  **Data Exploration:**
   * The code calculates the count of non-null values for each column.
   * The code calculates the sum of null values for each column.
   * A heatmap is generated to visualize null values.
4.  **Analyze Cases by Region:**
   * The code groups the data by region and calculates the sum of confirmed, deaths, and recovered cases for each region.
   * The code identifies the top 10 regions with the highest number of confirmed cases.
5.  **Data Filtering:**
   * Records with confirmed cases less than 10 are removed from the dataset.
6.  **Identify Extreme Cases:**
   * The region with the maximum number of confirmed cases is determined.
   * The region with the minimum number of death cases is determined.
7.  **Filter Data for India:**
   * The data is filtered to show records specifically for India.
8.  **Data Sorting:**
   * The data is sorted by confirmed cases in ascending order.
   * The data is sorted by recovered cases in descending order.

## Results

* The number of confirmed, deaths, and recovered cases were calculated for each region. [cite: 6, 7, 8, 9, 10, 11, 12]
   
* Records with less than 10 confirmed cases were removed. [cite: 13, 14, 15]
   
* The region with the maximum confirmed cases was identified. [cite: 18, 19, 20]
   
* The region with the minimum death cases was identified. [cite: 22, 23]
   
* Data for India was extracted. [cite: 26, 27]
   
* The data was sorted by confirmed and recovered cases. [cite: 34, 35, 36, 37]

## Code Snippets

### Load Dataset

```python
import pandas as pd
data = pd.read_csv("C:/Users/gvrk1/Downloads/Covid 19 data.csv")
