# Netflix Data Analysis Project

# Overview

This project analyzes Netflix content data using Python, focusing on exploratory data analysis (EDA) and visualization to derive insights about Netflix's content library.

# Tools and Libraries That are Used

•  Python 3.x
•  Pandas: Data manipulation and analysis
•  NumPy: Numerical computations
•  Matplotlib: Basic data visualization
•  Seaborn: Advanced statistical visualizations
•  WordCloud: Text visualization

# Dataset Used

The analysis uses the "netflix_titles.csv" dataset, which contains information about:

•  Show ID
•  Content Type (Movie/TV Show)
•  Title
•  Director
•  Cast
•  Country (The data could be changed for this column based on the version of the program.)
•  Date Added
•  Release Year
•  Rating
•  Duration
•  Categories
•  Description

# Data Preprocessing Steps

•  Data Loading: Imported the dataset using pandas
•  Initial Exploration:
•  Checked dataset shape (6234 rows x 12 columns)
•  Examined first 10 entries
•  Reviewed column names
•  Data Cleaning:
•  Identified null values
•  Created a clean copy of the dataset
•  Removed null values
•  Handled date formatting
•  Added new date-related columns (day, month, year)

# Analysis and Visualizations

1. Content Distribution

•  Created countplots to visualize the distribution of content types (Movies vs. TV Shows)
•  Generated a pie chart showing the percentage split between Movies and TV Shows

2. Rating Analysis

•  Analyzed content ratings distribution
•  Created visualizations showing:
•  Rating counts
•  Relationship between content type and ratings
•  Percentage distribution of ratings

3. Word Cloud Visualizations

# Created word clouds for:

•  Countries of content origin
•  Cast members
•  Directors
•  Content categories

# Key Findings

•  The dataset contains information about 6,234 unique titles
•  There are more movies than TV shows in the Netflix library
•  Content is categorized into 14 different rating categories
•  There's significant diversity in content origin, cast, and directors

# How to Run

•  Install required libraries:
pip install pandas numpy matplotlib seaborn wordcloud
•  2. Load the Netflix dataset
•  Run the Jupyter notebook cells sequentially

# Future Improvements

•  Add time-based analysis of content additions
•  Include sentiment analysis of descriptions
•  Add interactive visualizations
•  Analyze content duration patterns
•  Study correlation between different variables

# Author
    Raam Phogat
