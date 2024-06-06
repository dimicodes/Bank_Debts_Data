# Bank_Debts_Data


## Project Overview

This project involves analyzing bank data to understand debt recovery strategies, expected and actual recovery amounts, and the relationship between these variables and customer demographics. Different debt strategies are employed as the amount of debt increases (by the $1000), our goal is to analyze whether the increased recovery efforts employed on higher debt amounts are worth the efforts. For example, recovery strategy 1 (for debts $1000-$2000) may cost the bank $50 to employ, while recovery strategy 2 (for debts $2000-$3000) may cost the bank $100 to employ- will the actual vs expected recovery amounts cover the costs the bank must spend to employ these recovery strategies?

The main tasks include data exploration, visualization, statistical analysis, and building a predictive model.

## Dataset

The dataset used in this project is `bank_data.csv`, which contains information on customer demographics, recovery strategies, and recovery amounts.

## Key Tasks

1. **Loading and Exploring the Dataset**: Initial exploration of the dataset to understand its structure and contents.
2. **Visualization**: Creating scatter plots to visualize relationships between key variables.
3. **Statistical Analysis**: Performing tests such as Kruskal-Wallis and Chi-Square to identify significant differences between groups.
4. **Predictive Modeling**: Building a linear regression model to predict actual recovery amounts based on expected recovery amounts and other factors.

## How to Run the Project

### Prerequisites

Ensure you have the following Python libraries installed:
- pandas
- matplotlib
- scipy
- statsmodels

