# Comparative analysis of two index

## Introduction
The objective of this analysis is to compare the performance of two stock indices in the context of daily returns and trading volumes. Through a detailed analysis of historical data, we aim to highlight key differences and similarities between these two indices using statistical tools and graphical visualizations.

## Data
The data used in this analysis includes daily closing prices and trading volumes for a period of 10 years, considering only business days. The indices analyzed are:
- **S&P 500**: Represented by the DataFrame `df`
- **EURO STOXX 50**: Represented by the DataFrame `df1`

- ### Description of Variables
- **Date**: The observation date.
- **Open**: The opening price of the index.
- **High**: The highest price of the index on the observation date.
- **Low**: The lowest price of the index on the observation date.
- **Close**: The closing price of the index.
- **Volume**: The daily trading volume.

## Methodology
The analysis is structured in several phases:
1. **Calculation of Monthly Percentage Returns**: Using the percentage change in the closing price between the last days of two consecutive months.
2. **Calculation of Annual Percentage Returns**: Using the percentage change in the closing price between the last days of two consecutive years.
3. **Calculation of Average Daily Returns**: Using the percentage change in the closing price between consecutive days, broken down by index and day of the week.
4. **Calculation of Trading Volumes**: Analysis of daily trading volumes for each index.
5. **Data Visualization**: Creation of box plot charts to visualize the distribution of daily returns and trading volumes.
6. **Highlighting Extreme and Average Values**: Identification and representation of maximum, minimum, and average values in the box plot charts.

## Analysis Objectives
- **Comparison of Daily, Monthly and Annual Returns**: Analyze the distribution of daily returns for each index and compare their performances.
- **Comparison of Trading Volumes**: Examine daily trading volumes and identify any patterns or significant differences between the two indices.
