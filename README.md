# Titanic Data Analysis

This repository contains the code and analysis for the Titanic dataset as part of my data science internship with Prodigy Infotech.

## Overview

In this project, I performed data cleaning and exploratory data analysis (EDA) on the Titanic dataset to uncover patterns and insights related to the survival of passengers.

## Data Cleaning Process

- **Handled Missing Values:**
  - Filled missing values in the `Age` column with the median age.
  - Replaced missing values in the `Embarked` column with the most common port of embarkation.
  - Created a new feature `Has_Cabin` to indicate whether a cabin number was known.
- **Converted Categorical Variables to Numerical:**
  - Converted `Sex` to numerical values: `0` for male and `1` for female.
  - Transformed `Embarked` to numerical values: `0` for S, `1` for C, and `2` for Q.

## Exploratory Data Analysis (EDA)

- **Survival Rate by Sex:**
  - Visualized survival rates, showing that females had a higher survival rate compared to males.
- **Survival Rate by Pclass:**
  - Analyzed survival rates across different passenger classes, revealing that passengers in the 1st class had the highest survival rate.
- **Age Distribution by Survival:**
  - Plotted the age distribution, indicating that younger passengers had a higher chance of survival.
- **Fare Distribution by Survival:**
  - Examined fare distribution, showing that passengers who paid higher fares were more likely to survive.
- **Correlation Matrix:**
  - Created a correlation matrix to identify relationships between numerical variables, providing insights into which factors were most strongly associated with survival.

## Getting Started

To run the notebook, you will need to install the following libraries:

```sh
pip install pandas seaborn matplotlib
