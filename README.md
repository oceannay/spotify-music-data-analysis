# Spotify Top Songs Data Analysis

This project explores top Spotify tracks from 2010–2019 using R, focusing on genres, audio features, and popularity patterns over time.

## 📊 Dataset

- Source: “Top Spotify Songs from 2010–2019 by Year” (public dataset on Kaggle, linked in the notebook). 
- Key variables include:
  - `title`, `artist`, `top genre`, `year`
  - Audio features such as `bpm`, `nrgy` (energy), `dnce` (danceability), `dB` (loudness), `live`, `val` (valence), `dur`, `acous`, `spch`, and `pop` (popularity).

## 🧠 Objectives

- Identify the most common and most popular genres in the dataset.  
- Understand how audio features (e.g., energy, danceability, valence) relate to track popularity.  
- Visualize trends across years in both genre representation and song characteristics.

## 🛠️ Tools & Libraries

- R with:
  - `tidyverse` for data manipulation and cleaning  
  - `ggplot2` for visualizations  
  - `gridExtra` for arranging multiple plots. 

## 🔍 Methods

- Load and inspect the dataset, create a clear data dictionary for all variables.  
- Group and summarize tracks by `top genre` to find the most frequent genres and their distribution.  
- Use `ggplot2` to build charts illustrating:
  - Genre counts
  - Relationships between popularity and audio features such as danceability, energy, and valence.

## 💡 Insights at the High Level

- The analysis highlights which genres dominate the charts in the 2010s and how their audio characteristics differ.  
- Popular tracks tend to cluster around specific ranges of danceability, energy, and valence, reflecting what performs well on streaming platforms.[attachment:1]

## 📂 How to Use

- Open the R notebook/script in RStudio or a similar environment.  
- Ensure the `data/spotify_top_music.csv` file is available in the expected path.  
- Install required packages (`tidyverse`, `ggplot2`, `gridExtra`) and run all cells to reproduce the analysis and plots.
