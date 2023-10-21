# Project 5

## Overview
This project aims to explore and analyze a comprehensive dataset containing information about various video games, including their user and expert reviews, genres, platforms, historical sales data, and Entertainment Software Rating Board (ESRB) ratings. The primary objective is to identify patterns and insights that can determine the success factors behind video games.

Given the dataset up to December 2016, the goal is to plan effective advertising campaigns for the upcoming year, 2017. While the data focuses on 2016, the techniques and insights obtained from this analysis are transferable to various scenarios and timeframes.

## Dataset
The dataset, sourced from `moved_games.csv`, contains the following columns:
- `Name`: Name of the game.
- `Platform`: The gaming platform (e.g., Wii, NES, GB).
- `Year_of_Release`: The year the game was released.
- `Genre`: Genre of the game.
- `Sales Data`: Sales information segmented by region (North America, Europe, Japan, and Other).
- `Critic_Score`: Score given by critics.
- `User_Score`: Score provided by users.
- `Rating`: ESRB rating indicating the age appropriateness of the game content.

## Tasks and Analyses Performed
1. **Data Loading**: Loaded the dataset with 16,715 game entries and 11 attributes.
2. **Data Preprocessing**:
   - Converted all column names to lowercase for uniformity.
   - Adjusted data types of columns where necessary.
   - Addressed and managed missing values in various columns.
4. **Data Analysis**: Conducted exploratory data analysis to derive patterns in sales, user preferences, and other metrics.
5. **User Profile Analysis**: Derived user profiles for different regions to understand regional game preferences.
6. **Hypothesis Testing**: Performed statistical tests to ascertain significant differences in user ratings across platforms and genres.

## Tools and Libraries Used
- Jupyter Notebook
- Python with libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, etc.

## Conclusion
The comprehensive analysis provides a deep dive into video game sales, user preferences, and critical metrics that influence a game's success. These findings offer valuable insights for planning future advertising campaigns and predicting potential best-sellers.

For more details, please refer to the `project_5.ipynb` notebook and the accompanying dataset `moved_games.csv`.
