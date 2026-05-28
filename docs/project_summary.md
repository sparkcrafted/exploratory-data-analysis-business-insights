# Project Summary

## Project Title

**Multi-Dataset EDA for Business Insights**

## Overview

This project applies exploratory data analysis to three structured datasets: housing prices, Netflix titles, and New York City Airbnb listings. The goal is to demonstrate how data cleaning, inspection, visualization, and interpretation can be used to better understand different types of business and consumer datasets.

Rather than focusing on predictive modeling, this project emphasizes the early-stage analytical work that helps analysts understand data quality, identify patterns, detect outliers, and develop practical insights before building dashboards, models, or recommendations.

## Project Objectives

The project was designed to demonstrate the following objectives:

- Load and inspect multiple real-world datasets
- Identify missing values and data quality issues
- Explore numerical and categorical variables
- Detect outliers and unusual patterns
- Use visualizations to communicate trends and distributions
- Interpret findings in a business-oriented context
- Organize the project into a clean, reproducible GitHub portfolio structure

## Datasets

This project uses three CSV datasets stored in the `data/raw/` folder.

| Dataset | File Name | Analytical Focus |
|---|---|---|
| Housing Price Dataset | `House_Price.csv` | Housing price patterns, numerical relationships, outliers, and correlation analysis |
| Netflix Titles Dataset | `netflix_titles.csv` | Streaming content trends by type, release year, rating, country, and category |
| NYC Airbnb Dataset | `AB_NYC_2019.csv` | Listing prices, room types, neighborhoods, availability, and geographic patterns |

## Methods

The project follows a standard exploratory data analysis workflow.

### 1. Data Loading and Inspection

Each dataset was loaded into Python using Pandas. The initial review included checking dataset shape, column names, data types, sample records, and summary statistics.

### 2. Missing Value Review

The project examines missing values to understand where data quality issues may affect interpretation. This step helps identify which fields may require cleaning, imputation, exclusion, or cautious interpretation.

### 3. Numerical Analysis

Numerical variables were reviewed using descriptive statistics and distribution plots. This helped identify ranges, central tendencies, skewness, and possible outliers.

### 4. Categorical Analysis

Categorical variables were analyzed through counts, proportions, and visual summaries. This helped identify common categories, dominant groups, and differences across segments.

### 5. Visualization

The project uses visualizations to make patterns easier to interpret. These include distribution charts, count plots, boxplots, correlation heatmaps, and other exploratory visuals.

### 6. Business Interpretation

Findings were interpreted in plain language to connect technical observations to practical business questions. The emphasis is on what the patterns suggest and why they matter.

## Analysis Sections

## Housing Price Analysis

The housing analysis explores property-related variables and price patterns. The analysis reviews the distribution of housing prices, potential outliers, and relationships between numerical variables.

Key focus areas include:

- Sale price distribution
- Outlier detection
- Correlation among housing variables
- Variables that may be useful for future predictive modeling
- Data quality issues that may affect housing analysis

This section demonstrates how EDA can support early-stage real estate or housing market analysis.

## Netflix Content Analysis

The Netflix analysis explores the composition of titles in the streaming catalog. The analysis reviews content type, release year, ratings, countries, and listed categories.

Key focus areas include:

- Movie versus TV show distribution
- Release year trends
- Rating distribution
- Country-level content patterns
- Genre or category patterns

This section demonstrates how EDA can support media catalog analysis and content strategy review.

## NYC Airbnb Analysis

The Airbnb analysis explores short-term rental listings across New York City. The analysis reviews price, room type, neighborhood group, availability, and geographic patterns.

Key focus areas include:

- Price distribution
- Borough and neighborhood differences
- Room type distribution
- Availability patterns
- Potential pricing outliers
- Location-based listing trends

This section demonstrates how EDA can support marketplace analysis and location-based business insights.

## Tools and Libraries

This project was completed using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Positron

## Key Skills Demonstrated

This project demonstrates the following data analytics skills:

- Exploratory data analysis
- Data cleaning and inspection
- Missing value analysis
- Outlier detection
- Summary statistics
- Numerical variable analysis
- Categorical variable analysis
- Data visualization
- Correlation analysis
- Business-oriented interpretation
- Multi-dataset project organization
- Reproducible GitHub repository structure

## Key Outputs

The project produces visual outputs stored in the `images/` folder. These visuals are intended to support the project README and make the analysis easier to review.

Potential outputs include:

- Housing price distribution chart
- Housing correlation heatmap
- Netflix content type distribution chart
- Netflix titles by release year chart
- Airbnb price distribution chart
- Airbnb neighborhood group price chart
- Airbnb room type distribution chart

## Business Value

Exploratory data analysis is one of the most important steps in an analytics workflow. It helps analysts understand what is in the data before moving into modeling, dashboarding, or decision-making.

This project shows how EDA can help answer practical questions such as:

- What patterns are visible in the data?
- Are there missing values or outliers that need attention?
- Which variables appear most important?
- How do patterns differ across categories or locations?
- What insights can be communicated to nontechnical stakeholders?

By applying the same analytical workflow across three different datasets, the project demonstrates flexibility and repeatability in approaching new data problems.

## Portfolio Relevance

This project is included as a portfolio project because it demonstrates practical data analysis skills that are useful across many business settings.

It complements machine learning projects by showing the foundation that comes before modeling: understanding the dataset, identifying problems, visualizing relationships, and interpreting findings.

The project is especially relevant for roles or freelance work involving:

- Data analysis
- Business intelligence
- Data cleaning
- Exploratory reporting
- Dashboard preparation
- Analytics storytelling
- Early-stage data science workflows

## Repository Structure

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
│
├── notebook/
│   └── multi-dataset-eda-business-insights.ipynb
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore