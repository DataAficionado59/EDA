# Zomato EDA (Exploratory Data Analysis)

This project involves an Exploratory Data Analysis (EDA) of Zomato's restaurant data. The analysis includes data preprocessing, visualization, and insights to understand various aspects of restaurant ratings, cost distributions, and country-wise statistics.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Data Exploration](#data-exploration)
- [Key Analysis](#key-analysis)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)

## Introduction
The Zomato EDA project aims to provide insights into restaurant trends, including country-based analysis of ratings, average cost for two, and customer feedback. This analysis can help identify key factors that affect ratings and dining preferences across different countries.

## Requirements
- Python 3.7 or above
- Jupyter Notebook
- Python libraries:
  - Pandas
  - Matplotlib
  - Seaborn
  - NumPy

## Installation
1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd Zomato-EDA
# Data Exploration

The dataset includes features such as:

- **Country**: Location of the restaurant
- **Aggregate Rating**: Customer rating on Zomato
- **Rating Color and Rating Text**: Visual representations of ratings
- **Average Cost for Two**: Average dining cost for two people

## The EDA Workflow

1. **Loading and Cleaning the Dataset**: Prepare the data for analysis by handling missing values and ensuring consistency in formats.
2. **Analyzing Categorical Variables**: Explore categorical features like country and rating.
3. **Visualizing Correlations**: Investigate relationships between cost, rating, and country.

## Key Analysis

### 1. Country Analysis
- Identifying countries with the most restaurants.
- Analyzing countries with the highest average dining costs.

### 2. Rating Analysis
- Determining average ratings across countries.
- Visualizing ratings using color-coded representations.

### 3. Cost Analysis
- Comparing the average cost for two people across countries.
- Identifying patterns in countries with higher dining costs.

## Visualizations

The notebook uses a variety of plots to present insights:

- **Bar Charts**: Used for visualizing average costs and ratings per country.
- **Pie Charts**: Show proportions of different ratings.
  - The `autopct='%1.2f%%'` parameter is used to display percentages with two decimal places.
- **Horizontal Bar Charts**: Improve readability for categorical analysis.

## Conclusion

The EDA provides insights into Zomato's data, revealing trends in dining costs and customer preferences across countries. These findings can be valuable for restaurateurs and marketers targeting specific regions.

## Acknowledgments

- Zomato for providing the dataset.
- **Matplotlib** and **Seaborn** for visualization support.
