# Spotify-Artists-EDA
Exploratory Data Analysis on Spotify artist streaming data using pandas, matplotlib, and seaborn - cleaning inconsistent columns, imputing missing values, and visualizing genre and streaming trends

#Overview

This project explores a dataset of Spotify artists and their streaming performance. The goal was to clean a messy real-world dataset, handle missing values without dropping rows, and surface insights around genre popularity, solo vs. group artist performance, and the relationship between different types of streams.

#Dataset

The dataset includes the following fields (after cleaning):

1. Artist — Artist name
2. Primary Genre — Main genre associated with the artist
3. Artist Type — Solo or Group
4. Language — Primary language of the artist's music
5. Total Streams — Total streams (in millions)
6. Lead Streams — Streams as lead artist (in millions)
7. Solo Streams — Streams as a solo artist (in millions)
8. Feature Streams — Streams as a featured artist (in millions)

#Tools & Libraries

1. Python
2. pandas — data loading, cleaning, transformation
3. NumPy — numerical operations
3. Matplotlib — chart building
4. Seaborn — statistical visualizations

#Workflow

- Load the data — read the raw CSV and inspect its structure
- Explore — check shape, dtypes, and summary statistics
- Clean — standardize inconsistent column names
- Handle missing values — linear interpolation on stream-count columns rather than dropping rows
- Analyze — sort, correlate, and group the cleaned data
- Visualize
  - Number of artists by genre
  - Solo vs. group artist distribution
  - Top 10 most-streamed artists
  - Correlation heatmap across stream metrics

#Key Insights

- Certain genres dominate the artist pool, while others are long-tail with only a handful of artists.
- Solo and group artists show different streaming patterns worth investigating further.
- Lead, solo, and feature streams correlate differently with total streams — useful for understanding what drives an artist's overall reach.

#Author

Part of an ongoing Python / Data Analytics portfolio — built to demonstrate data cleaning, EDA, and visualization skills using pandas, matplotlib, and seaborn.
