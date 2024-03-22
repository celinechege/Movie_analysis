# Exploratory Data Analysis for Microsoft's New Movie Studio
## 1. Introduction
The entertainment industry, particularly the movie sector, is known for its dynamic nature and continuous evolution. In light of technological advancements, major tech companies like Microsoft are considering opportunities in movie production. Microsoft aims to leverage data-driven insights to effectively establish its presence in the film industry.

## 2. Business Problem
Microsoft intends to enter the movie industry by establishing its own movie studio. However, lacking expertise in movie production, they require insights into successful movie characteristics, such as genres, budgets, and ratings. The objective is to explore existing movie data to identify trends and patterns that can guide Microsoft's decisions on the types of films to produce.

## 3. Key Guidelines
a) Characteristics of Successful Movies: Analyze successful movies in terms of genres, budgets, and ratings.
b) Influence of Various Factors: Understand how factors like release date, runtime, and production budget affect a movie's box office performance.

### Methods:
1. Data Exploration and Cleaning: Explore datasets, handle missing values, duplicates, and inconsistencies.
2. Data Analysis: Perform exploratory data analysis using pandas f0r data manipulation and analysis.
3. Visualization: Create visualizations (e.g., bar charts, scatter plots) to highlight trends and patterns in the data.
4. Business Recommendations: Formulate actionable recommendations based on the insights derived from the data analysis.

## 4. Importing Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt 
import seaborn as sns
import gzip

## 5. Loading and Exploring Data
### 5.1 BOM Movies Dataset
The dataset contains information about movie titles, studios, domestic and foreign gross earnings, and release years.

### 5.2 Movie Budgets Dataset
This dataset includes details on movie titles, release dates, production budgets, domestic and worldwide gross earnings.

### 5.3 Movie Reviews Dataset
The dataset comprises movie reviews from various critics, including their ratings and publication details.

## 6. Data Cleaning and Preparation
Handled missing values and inconsistencies.
Converted relevant columns to appropriate data types.
Prepared the data for analysis by dropping irrelevant rows and columns.

## 7. Data Analysis
Explored the distribution of movie releases over the years.
Analyzed profit/loss trends in the movie industry.
Investigated the influence of production budgets on movie profitability.

## 8. Data Visualization
Utilized visualizations such as histograms and scatter plots to depict trends and patterns in the data.
Illustrated the distribution of movie releases and profit/loss trends over the years.

## 9. Findings
Identified key insights and trends in the movie industry.
Provided actionable recommendations for Microsoft's movie studio based on the analysis.

## 10. Conclusion
Through comprehensive exploratory data analysis, this project aims to assist Microsoft in making informed decisions regarding its entry into the movie industry. By leveraging data-driven insights, Microsoft can optimize its strategies and enhance its competitiveness in the dynamic film market.