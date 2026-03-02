# Global COVID-19 Data Tracker & Trend Analyzer

## Project Overview

This project analyzes global COVID-19 data using **NumPy** and **Pandas** to understand trends in cases, deaths, and other metrics.
The goal is to clean the dataset, analyze time-based patterns, calculate moving averages, identify peak case days, and explore relationships between variables.

## Dataset

Dataset used: **COVID-19 Clean Complete Dataset**

The dataset contains daily information about:

* Confirmed cases
* Deaths
* Recovered cases
* Active cases
* Country and date information

## Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Project Workflow

### 1. Data Loading

The dataset is loaded using Pandas.

### 2. Data Cleaning

* Converted `Date` column to datetime format
* Handled missing values using `fillna(0)`
* Filtered data for specific countries

### 3. Time-Wise Aggregation

Data is grouped by date to analyze daily COVID trends.

### 4. Daily Case Calculation

Daily new cases are calculated using the difference between consecutive confirmed case values.

### 5. Moving Average (7-Day)

A **7-day moving average** is calculated using NumPy to smooth daily fluctuations in case counts.

### 6. Peak Case Analysis

The highest number of daily cases and the date on which they occurred are identified.

### 7. Country Comparison

Data from multiple countries (India, US, Brazil) is filtered to compare trends.

### 8. Correlation Analysis

Correlation between confirmed cases and deaths is calculated to understand their relationship.

## Key Insights

* COVID-19 cases show strong growth patterns over time.
* The correlation between confirmed cases and deaths is **very strong**, indicating a close relationship between the two metrics.
* Moving averages help identify overall trends by smoothing daily fluctuations.

## Project Structure

```
covid-data-tracker
│
├── data
│   └── covid_19_clean_complete.csv
│
├── notebooks
│   └── covid_analysis.ipynb
│
├── outputs
│   └── india_covid_analysis.csv
│
└── README.md
```

## Skills Demonstrated

* Data cleaning using Pandas
* Time-series analysis
* Statistical analysis with NumPy
* Moving average calculations
* Correlation analysis
* Data filtering and aggregation
