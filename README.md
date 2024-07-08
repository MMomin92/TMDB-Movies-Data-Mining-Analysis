# TMDB-Movies-Data-Mining-Analysis

## Project Overview

This project was a collaborative effort to analyze the TMDB 5000 movies dataset and uncover insights into the factors influencing movie revenue and profitability. Our analysis included data processing, cleaning, regression analysis, decision tree modeling, and association rule mining.

## Project Objectives

- Identify key factors that contribute to a movie's financial success.
- Understand the impact of different variables like budget, popularity, and runtime on movie revenue.
- Explore patterns and relationships between movie genres and profitability.

## Team Members

- Muqsit Momin
- Prakhar Jain
- Siddha Deshpande

## Analysis Process

### Data Processing and Cleaning
We began by cleaning the data to handle missing values and ensure consistency. This involved:
- Replacing zero values in the budget and revenue columns with NaNs and removing rows with NaNs.
- Parsing genres from JSON format into a list of genre names.
- Converting release dates to a datetime format and extracting the release year.

### Regression Analysis
We conducted both linear and multiple linear regression analyses to understand how various factors such as budget, popularity, and runtime impact movie revenue. Using scikit-learn and statsmodels, we were able to derive insights into the relationships between these variables.

### Decision Tree Modeling
To identify key predictors of movie profitability, we built decision tree models using scikit-learn. This allowed us to visualize and understand the decision paths that lead to profitable movies.

### Association Rule Mining
We applied association rule mining with the mlxtend library to uncover interesting patterns and relationships between movie genres and profitability. This helped us identify genre combinations that are likely to be more profitable.

## Results and Insights

Our analysis revealed several key insights:
- **Budget and Revenue**: There is a positive correlation between a movie's budget and its revenue, but other factors also play significant roles.
- **Popularity**: Movies with higher popularity scores tend to generate higher revenue.
- **Genres**: Certain genre combinations are more likely to result in profitable movies.

## Graphic on Findings

[Graphic TMDB Movies Analysis.pdf](https://github.com/MMomin92/TMDB-Movies-Data-Mining-Analysis/blob/614f860cc5870e4f4ba93ab9175951c804e34046/Graphic%20TMDB%20Movies%20Analysis.pdf)

## Final Report

For a detailed explanation of our analysis, findings, and additional visualizations, please refer to our [Final Report]([link-to-final-report](https://github.com/MMomin92/TMDB-Movies-Data-Mining-Analysis/blob/847fa6991fee5b4231d4297ec78066529f93329a/Final%20Report%20TMDB%20Movies%20Analysis.pdf)).


