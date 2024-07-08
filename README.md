# Correlation-Py-Project
This is a Python pproject. It aims to analyze the relationship between the advertising budget and the revenue generated by each country.

# Correlation Analysis of Advertising Budget and Revenue by Country

## Overview
This project aims to analyze the relationship between the advertising budget and the revenue generated by each country. The dataset used includes various metrics related to advertising and sales performance. The focus is on understanding how advertising expenditure correlates with purchase revenue across different markets.

### Table of Contents
Project Objectives
Data Description
Methodology
Results
Conclusion
Files in Repository
Usage
Future Work
License
Contact

## Project Objectives
Analyze the correlation between advertising budget and purchase revenue across different countries.
Identify and assess the impact of outliers on the correlation analysis.
Provide insights into the relationship dynamics for strategic business decisions.

## Data Description
The dataset used in this project includes the following key variables:
Country: The country where the advertising and sales occur.
Cost: The advertising expenditure.
Purchase Revenue: The revenue generated from purchases.
Other Metrics: Additional metrics like 'Ecommerce Purchases', 'Checkouts', 'New Users', 'Add to Carts', 'Bounce Rate', and 'Views per User'.

## Methodology
### Data Preparation:
Import and clean the dataset.
Convert relevant columns to appropriate data types.
Handle missing or incorrect data values.
Outlier Identification and Analysis:

Identify the US as an outlier due to its significantly higher values compared to other countries.
Analyze the impact of including and excluding the US on the correlation.
Correlation Analysis:

Calculate and visualize the Pearson correlation matrix for the full dataset.
Repeat the correlation analysis after excluding the outlier.
Visualization:

Use scatter plots and regression lines to show relationships.
Generate heatmaps to visualize the correlation matrices.
Results
Correlation with Outlier (US included): The correlation between advertising budget and purchase revenue is exceptionally high (0.99).
Correlation without Outlier (US excluded): The correlation drops to 0.51, indicating a moderate relationship for the rest of the countries.

## Conclusion
Even though the US is an outlier with significantly higher advertising costs and revenues, it should be included in the analysis because it represents a major portion of both advertising spend and sales. When the US is excluded, the correlation between advertising spend and purchase revenue drops substantially, suggesting that the high correlation observed is largely driven by the US market. This highlights the need for tailored strategies for different markets and emphasizes the US's unique impact on overall trends.

### Files in Repository
correlation_analysis.ipynb: Jupyter Notebook containing the complete analysis, including data preparation, correlation calculations, and visualizations.
data/: Directory containing the dataset (Ensure you replace this with your actual dataset location or upload instructions).
README.md: This README file.
