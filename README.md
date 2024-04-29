# Netflix PowerBI Dashboard

## Overview

This project focuses on creating a dynamic PowerBI dashboard utilizing a dataset containing the list and metadata of all TV shows and movies available on Netflix. The dataset, sourced from Kaggle, consists of approximately 7000 entries gathered from the IMDb website.

## Dataset

The dataset, named Netflix_list.csv, serves as the primary data source for this project. It contains detailed information about TV shows and movies available on Netflix, including titles, genres, ratings, number of votes, and more.

## Process

The process begins with importing the Netflix_list.csv file into PowerBI for analysis and visualization. Two additional tables are created to enhance the functionality and aesthetics of the dashboard:

1. **Calculations Table**: This table serves as a placeholder for new calculations and measures that are derived from the dataset.

2. **z_Rating Group Formatting Table**: This table is utilized for configuring fill color and font color settings to achieve a dynamic look for the dashboard.

Data cleaning techniques are applied to the dataset to remove unnecessary data and ensure data quality. DAX functions, particularly the Switch() function, are employed to group together categories in various tables for better organization and analysis.

## Goals

The primary objectives of the Netflix PowerBI dashboard include:

- Provide filters for distinguishing between movies and TV shows.
- Display average ratings and number of votes for each title.
- Present average ratings by genre for insightful analysis.
- Visualize ratings distribution across different countries using a choropleth map.
- Showcase a dynamic list of movies and TV shows with cover images, plot summaries, and ratings for enhanced user engagement.

## Usage

To replicate or explore the dashboard:

1. Download or clone the repository.
2. Open the PowerBI file (Netflix_Dashboard.pbix) using PowerBI Desktop.
3. Explore the dataset, visualizations, and filters to gain insights into Netflix TV shows and movies.


Credits: https://www.youtube.com/@PowerBIBro ( YT- https://www.youtube.com/watch?v=InYxu2h7o6I&ab_channel=PowerBIBro)

Kaggle: https://www.kaggle.com/datasets/snehaanbhawal/netflix-tv-shows-and-movie-list 

Netflix Branding: https://brand.netflix.com/en/assets/logos/
