# Spotify Exploratory Data Analysis 2023

<img src="https://github.com/user-attachments/assets/e3f0937a-771f-4cf1-a2ca-ea1f03adc646" width=50% height=50%>

## Description
A data analysis project focused on exploring and analyzing Spotify music data to gain insights on various trends, patterns, and relationships among artists, genres, tracks, and other attributes. This project is built using Python, with libraries such as Pandas and Matplotlib to perform data manipulation, cleaning, and visualization.

## Table of Contents

- [About the Project](#about-the-project)
- [Libraries Used](#libraries-used)
- [Installation & Usage](#install)
- [Insights](#insights)
- [Change Logs](#changelog)
- [Functions Documentation](#functions-documentation)
- [References](#references)
- [Author](#author)

## About the Project

The goal of this project is to analyze Spotify data to derive meaningful insights about music trends, artist collaborations, track popularity, and other interesting patterns. The data is cleaned, transformed, and visualized to provide clear insights. Potential analysis includes:

- Popularity and trend analysis for artists, tracks, and genres.
- Insights into collaboration patterns between artists.
- Analysis of track features such as tempo, energy, and mood over time.


## Libraries Used

- **Python**
  - **Pandas**: Data manipulation and cleaning
  - **NumPy**: Numeric computations
  - **Matplotlib & Seaborn**: Data visualization
  - **Jupyter Notebook**: Interactive development environment
<h2 id = 'install'> 
Installation & Usage
</h2>

1. Clone the repository:
```bash
git clone https://github.com/krlsbrre/Spotify-Data-Analysis.git
```
2. Open Jupyter Notebook
```bash
jupyter notebook
```
3. Navigate into the project directory in Jupyter Notebook
4. Click SPOTIFY.ipynb
5. Run the cells in sequence to load, clean, and analyze the Spotify dataset.

## Insights
- Basic Descriptive Statistics
  - Trend of the distributions of released_year and artist_count?
    - The trend for the artist_count is decreasing
      ![image](https://github.com/user-attachments/assets/a7395acf-60d2-4a57-a42d-1904e8c6ee89)
    - The trend for the released_year is increasing
      ![image](https://github.com/user-attachments/assets/930bd50f-e080-4a07-9ee6-b6244ff49849)
- Top performers
  - Which track has the highest number of streams?
    - Blinding Lights by The Weeknd
  - Who are the top 5 most frequent artists based on the number of tracks in the dataset?
    - ![image](https://github.com/user-attachments/assets/7531514f-8ff0-4eb0-8e7d-10d90c53a4b1)
- Temporal Trends
  - Number of releases increases over time (By year)
  - January has the highest number of releases in a year
    - As the months go by, the number of releases decreases with **december** having the least releases
- Genre and Music Characterists
  - Which attributes seem to influence streams the most?
    - Speechiness influences the streams the most with it having the strongest negative correlation
  - Is there a correlation between danceability_% and energy_%? How about valence_% and acousticness_%?
    - Between danceability and energy percentages, there is a weak positive correlation
    - Between valence and acousticness, there is a weak negative correlation
- Platform Popularity
  - How do the numbers of tracks in spotify_playlists, spotify_charts, and apple_playlists compare?
    - Spotify has the highest number of tracks
  - Which platform seems to favor the most popular tracks?
    - The most popular tracks favors the platform Spotify as it has the most number of playlists
- Advanced Analysis
  - Based on the streams data, can you identify any patterns among tracks with the same key or mode (Major vs. Minor)?
    - ![image](https://github.com/user-attachments/assets/d2f6400f-d7f4-445a-8b23-74a2d28a0bb1)
    - The trends for the tracks with the same key or mode are both decreasing
      - Key - (C# to A): Decreasing
      - Mode - (Major to Minor): Decreasing
  - Do certain genres or artists consistently appear in more playlists or charts? 
    - **The Weeknd** consistently appears in playlists while **Taylor Swift** consistently appears in charts 
## **Changelog**

- See the [`Releases`](https://github.com/krlsbrre/Spotify-Data-Analysis/releases) for details.

## Functions Documentation
- Navigate to the [`wiki`](https://github.com/krlsbrre/Spotify-Data-Analysis/wiki/Functions-documentation) of this project

## References
- Navigate to the [`wiki`](https://github.com/krlsbrre/Spotify-Data-Analysis/wiki/References) of this project

## Author

- [@krlsbrre - Karlos Louis M. Sabarre - 2ECE-A - 2023184838](https://www.github.com/krlsbrre)
