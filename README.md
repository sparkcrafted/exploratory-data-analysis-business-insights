# Multi-Dataset EDA for Business Insights

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## Project Overview

This project applies exploratory data analysis techniques across three real-world datasets involving housing prices, Netflix content, and New York City Airbnb listings.

The purpose of the project is to demonstrate how data cleaning, summary statistics, visualization, and pattern analysis can be used to better understand different types of business and consumer datasets. Each dataset is analyzed separately, but the overall project shows a consistent workflow for moving from raw data to interpretable insights.

The project focuses on:

- Cleaning and inspecting structured datasets
- Identifying missing values and outliers
- Exploring numerical and categorical variables
- Creating visualizations to reveal patterns
- Translating findings into business-oriented insights

## Datasets Analyzed

This project includes three datasets:

| Dataset | Focus Area | Main Analytical Purpose |
|---|---|---|
| `House_Price.csv` | Housing prices | Explore price patterns, outliers, and relationships among housing variables |
| `netflix_titles.csv` | Streaming content | Analyze Netflix content by type, release year, rating, genre, and country |
| `AB_NYC_2019.csv` | Airbnb listings | Explore price, location, room type, availability, and neighborhood-level patterns |

## Business Questions

This project explores questions such as:

- What patterns exist in housing prices and housing-related variables?
- Are there outliers or unusual values that may affect housing analysis?
- How is Netflix content distributed across movies and TV shows?
- What trends appear in Netflix release years, ratings, and content categories?
- How do Airbnb listing prices vary across boroughs and room types?
- Which neighborhoods or listing types appear most active in the Airbnb market?
- How can exploratory data analysis support better business understanding before modeling?

## Methods Used

The project uses a standard exploratory data analysis workflow:

1. Load and inspect each dataset
2. Review column names, data types, and dataset structure
3. Identify missing values
4. Generate descriptive statistics
5. Explore numerical and categorical variables
6. Detect outliers and unusual values
7. Create visualizations
8. Interpret patterns in business context

## Key Skills Demonstrated

This project demonstrates the following data analytics skills:

- Data loading with Pandas
- Data inspection and profiling
- Missing value analysis
- Outlier detection
- Summary statistics
- Categorical data analysis
- Numerical data analysis
- Data visualization
- Correlation analysis
- Business-oriented interpretation
- Multi-dataset exploratory analysis
- Reproducible project organization

## Tools and Libraries

This project was completed using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Positron

## Project Structure

```text
multi-dataset-eda-business-insights/
│
├── data/
│   ├── raw/
│   │   ├── House_Price.csv
│   │   ├── netflix_titles.csv
│   │   └── AB_NYC_2019.csv
│   │
│   └── README.md
│
├── docs/
│   └── project_summary.md
│
├── images/
│   ├── housing_price_distribution.png
│   ├── housing_correlation_heatmap.png
│   ├── netflix_content_type_distribution.png
│   ├── netflix_titles_by_year.png
│   ├── airbnb_price_distribution.png
│   ├── airbnb_neighborhood_group_prices.png
│   └── airbnb_room_type_distribution.png
│
├── notebook/
│   └── multi-dataset-eda-business-insights.ipynb
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore