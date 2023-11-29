# Exploratory-analysis-of-a-movie-data-set

## Introduction
This repository contains a Python script for exploratory data Analysis (EDA) using libraries like Numpy, Pandas, Matplotlib.pyplot and Seaborn. The analysis is applied to a movie dataset in order to discover.

## Code Structure
- **Data Loading and Cleaning:** 
  - Load the movie dataset and perform initial data cleaning.
  - Changed the column name'Capstone' to clean_cap, then converted the non string columns to strings, and the 'Date' to datetime format.
  - Extracted the 'Month_added' and the'year_added' from the date column into a separate column.
  - I standardised the country column by replacing variations with uniform representations using a predefined mapping via regular expression

- **Visualization:**
  - Visualized movie trends, and their release over the years using Seaborn and Matplotlib.
  - Identified the most popular director and countries making the most and least movies.
  - Explored the most popular country-genre mix and countries with the highest average movie duration.

- **Analysis and Insights**
  - Number of movies directed by the most popular director is 2588.
  - Top countries making the most movies are USA,India, United Kingdom and Pakistan, while the least are Iran, West Germany, Greece and Soviet Union.
  - The most popular country-genre mix is ('United State', 'Documentaries')
  - Countries with the highest average movie duration are Croatia, West Germany, Soviet Union and Cameroon.
  - 2018, 2019 and 2020 has the highest number of movies released in  year

- **Bonus Task:**
  - Implemented a function to handle TV series duration.
  - Created random ratings for each movie.

- **Heatmap Visualization:**
    - A corelation matrix.
    - Interpret the heatmap to understand the relationship between various variables.

- **Histogram  Visualization:**
    - A histoplot
    - Displays the distribution of movie durations with 25 bins, a kernel density estimate (kde), and a skyblue color, providing insights into the overall pattern of movie 
     duration in the dataset.

- **Usage**
    -Clone the repository.
    -Install the required dependencies: `pip install -r requirements.txt`.
    -Run the main script

     Feel free to explore the code and adapt it for your own datasets and analysis needs. Contributions are welcome too
