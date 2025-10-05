# SpotifyTrackAnalysis
"Spotify Track Analysis EDA Project"

*Presented by:* Anshika Pandey , 
Team: Data Minds

## Overview

This project performs an Exploratory Data Analysis (EDA) on the Spotify Tracks Dataset, which contains millions of tracks with various audio features such as danceability, energy, loudness, valence, and tempo.
The goal is to explore how these musical attributes influence a song’s popularity and uncover meaningful insights from the data.

## Objectives

To explore the Spotify dataset and identify which audio features influence a song’s popularity the most.

## Team Members

# Anshika Pandey

Dipanjan Halder

Ekadashi Sardar

Nilanjana Saren

##  Preparation & Setup

Project Initialization: Import essential Python libraries — pandas, numpy, matplotlib, seaborn

Data Acquisition: Load Spotify dataset into the notebook

Data Cleaning: Detect and handle missing values

Data Validation: Ensure dataset is clean, consistent, and reliable

##  Initial Data Exploration

Explore dataset structure using .info(), .shape(), .describe()

Identify numerical, categorical, and temporal variables

Conduct an initial data overview using .head()

#  Core Analysis
## Univariate Analysis

Numerical: Histograms, Boxplots, and Density plots

Categorical: Bar charts, Count plots

## Key Findings:
Most tracks released after 2010

Popularity is highly right-skewed

Majority are upbeat (high energy, danceable songs)

Most tracks are non-acoustic and in 4/4 time signature

## Bivariate Analysis

 * Explored relationships such as:

* Energy vs Popularity

* Danceability vs Popularity

* Loudness vs Popularity

* Acousticness vs Popularity

* Found that energetic, rhythmic songs tend to be more popular.

  # Multivariate Analysis
*  Correlation heatmap and pairplots used

* Strong positive correlation between:
* ## Energy ↔ Loudness

* ## Danceability ↔ Valence
* Weak correlation between popularity and most other features → shows multiple factors influence song success.

  # Insights Summary

  ## Popularity
*   Majority of tracks score below 30 in popularity.

*   Only a few tracks go viral (above 60).

##   Duration

* Average song length: 3–4 minutes

* Strong negative correlation between duration and popularity
* Extremely short or long tracks tend to be less popular


##  Audio Features

* High Energy (0.6–0.8) and Danceability dominate.

* Valence shows balanced emotional diversity (sad to happy tones).

  ## Language

  *  English dominates (47.5%), followed by Tamil, Korean, and Hindi
 ## Tempo Patterns

*   Most languages maintain consistent moderate tempo (100-140 BPM median)
*  Fast songs dominate high popularity clusters
*  High popularity songs span 80-200 BPM range

## Repository Structure


README.md (This file)
presentation anshika.pdf (Complete presentation with visualizations)
Spotify2005.ipynb (Jupyter Notebook with analysis code - if available)

# Conclusion


This Spotify Track Analysis shows that energetic, loud, and danceable songs tend to be more popular, while acoustic and instrumental tracks are less favored. The findings highlight listeners’ preference for lively and engaging music on Spotify.


   

   


