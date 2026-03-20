# Spotify Songs Exploratory Data Analysis (EDA)

This repository contains a comprehensive exploratory data analysis of a Spotify songs dataset. The project explores various song attributes to understand popularity trends, genre characteristics, and correlations between musical features like energy, loudness, and acousticness.

## Project Overview
The goal of this analysis is to uncover insights into what makes a song popular on Spotify and how different musical genres differ in their audio characteristics.

## Key Findings
- **Energy and Loudness:** There is a strong positive correlation (0.68), indicating that more energetic songs tend to be louder.
- **Acousticness vs. Energy:** A moderate negative correlation (-0.54) exists, showing that highly acoustic songs generally have lower energy levels.
- **Danceability and Mood:** A moderate positive correlation (0.33) between danceability and valence suggests that more danceable songs often convey a more positive mood.
- **Popularity Drivers:** Most audio features showed very weak linear correlations with `track_popularity`, suggesting that popularity might be driven by external factors (marketing, artist fame) rather than purely musical attributes.
- **Genre Insights:** The analysis highlights average popularity scores across different genres, identifying which playlist genres (e.g., Pop, Latin, R&B) currently dominate the charts.

## Dataset
The dataset used in this analysis includes over 32,000 tracks with 23 columns, featuring:
- **Metadata:** Track name, artist, album, and release date.
- **Audio Features:** Danceability, energy, loudness, speechiness, acousticness, instrumentalness, liveness, valence, and tempo.
- **Target Variable:** Track popularity.

## Visualizations
The analysis includes several key visualizations:
- **Popularity Distribution:** A histogram showing the spread of popularity scores across the dataset.
- **Genre Comparisons:** Bar plots comparing average popularity across various playlist genres.
- **Correlation Heatmap:** A visual representation of the relationships between different audio features.

## Requirements
To run the notebook, you will need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn

## Usage
1. Clone this repository.
2. Ensure you have the `spotify_songs[1].csv` dataset in the project directory.
3. Open and run the `Spotify_songs_analysis.ipynb` Jupyter notebook.

## Author
Pranav
