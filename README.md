# Netflix Content Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix dataset to understand patterns and trends in the platform's content library. The analysis explores content types, genres, ratings, duration, release trends, and country contributions.

## Dataset

The dataset contains information about Netflix titles such as:

* Title
* Type (Movie or TV Show)
* Director
* Cast
* Country
* listed_in
* Release Year
* Date Added
* Genre
* Duration
* Rating

## Objectives

The main goals of this project are:

* Analyze the distribution of Movies vs TV Shows
* Understand how Netflix content has grown over time
* Identify the most common genres
* Analyze movie duration and TV show seasons
* Study content ratings distribution
* Identify which countries contribute the most titles

## Key Insights

* Movies dominate the Netflix catalog compared to TV Shows.
* Content additions increased significantly after 2016 and peaked around 2019.
* Most movies have durations between 90 and 120 minutes.
* Most TV Shows have only one season.
* The United States contributes the highest number of titles, followed by India and the United Kingdom.
* International Movies, Dramas, and Comedies are among the most common genres.
* Most Netflix content is rated TV-MA or TV-14, indicating a focus on mature and teenage audiences.

## Tools and Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Structure

```
Netflix-EDA/
│
├── netflix_analysis.ipynb
├── netflix_titles.csv
├── README.md
```

## Conclusion

This analysis provides insights into Netflix’s content strategy and trends. The results highlight the dominance of movies, the growth of content after 2016, and the strong presence of international and drama-based content on the platform.

## Future Improvements

* Create interactive dashboards using Plotly
* Perform advanced analysis on genre trends
* Build a recommendation system
