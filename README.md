# Netflix Movies & TV Shows EDA

## Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Netflix Movies & TV Shows** dataset. The primary goal of this analysis is to uncover insights about the available content on Netflix, including details about genres, ratings, release years, content type (movie or TV show), and other factors that could give valuable insights into Netflix's catalog.

The dataset used in this project contains a list of movies and TV shows available on Netflix.

## Dataset

The dataset is available on Kaggle and includes the following columns:

- `show_id`: Unique identifier for each movie or TV show.
- `type`: Type of the content (Movie or TV Show).
- `title`: The title of the movie or TV show.
- `director`: Director of the content.
- `cast`: Main actors/actresses.
- `country`: The country where the content was produced.
- `date_added`: The date when the content was added to Netflix.
- `release_year`: The year the content was released.
- `rating`: The content's rating (e.g., PG, PG-13, R).
- `duration`: Duration of the content (for movies: in minutes, for TV shows: number of seasons).
- `genre`: Genre of the content (e.g., Action, Drama, Comedy).
- `description`: Short description of the content.

### Source

The dataset is available on **Kaggle** and can be accessed from the following link:
- [Netflix Movies & TV Shows Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## Analysis Summary

### 1. **Data Cleaning and Preprocessing**
- **Handling Missing Values**: Removed any rows with missing data where necessary.
- **Date Conversion**: Converted `date_added` to a proper datetime format.
- **Type Conversion**: Converted `release_year` and `duration` to numeric formats for easier analysis.
  
### 2. **Exploratory Data Analysis (EDA)**
   - **Content Type Distribution**: Examined the distribution of movies vs. TV shows on Netflix.
   - **Top Countries**: Analyzed which countries have the highest number of movies and TV shows available.
   - **Genre Analysis**: Visualized the distribution of different genres across Netflix's catalog.
   - **Ratings Analysis**: Investigated the distribution of content ratings and their relationship to content type (Movies vs. TV Shows).
   - **Content Release Trends**: Identified trends in the release years of Netflix content.
   - **Duration Analysis**: Investigated the duration of movies vs. TV shows and their distribution over time.

### 3. **Key Insights**
- **Content Type**: Netflix has a large number of movies compared to TV shows, but the number of TV shows has been steadily increasing over the years.
- **Popular Genres**: Action, Drama, and Comedy are the top genres on Netflix.
- **Top Countries**: The United States, India, and the United Kingdom have the most Netflix content available.
- **Rating Trends**: Most of the content on Netflix is rated either PG or TV-MA, showing the wide range of audience preferences.
- **Release Year Trends**: A significant rise in Netflix Originals and content added to the platform from 2015 onwards.
  
---

## Installation

To run this project and replicate the analysis, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Jeffrin-Webster/eda-kaggle-datasets
