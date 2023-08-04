# Bollywood Movies Data Visualization Project

## Introduction

This repository contains code and scripts to visualize the Bollywood dataset. The dataset includes various features related to Bollywood movies, such as release date, genre, budget, box office collection, and YouTube statistics. The primary aim of this project is to provide meaningful insights through visualizations that can help understand trends, patterns, and correlations within the data.

## Dataset Overview

The Bollywood dataset (`bollywood.csv`) consists of the following columns:

- `SlNo`: Serial number (int64)
- `Release Date`: Date of movie release (datetime64[ns])
- `MovieName`: Name of the movie (object)
- `ReleaseTime`: Release time details (object)
- `Genre`: Genre of the movie (object)
- `Budget`: Budget of the movie in INR (int64)
- `BoxOfficeCollection`: Box office collection in INR (float64)
- `YoutubeViews`: Number of YouTube views for the trailer (int64)
- `YoutubeLikes`: Number of YouTube likes for the trailer (int64)
- `YoutubeDislikes`: Number of YouTube dislikes for the trailer (int64)

### Dataset Statistics

- Total Rows: 149
- Total Columns: 10
- Total Entries: 1490
- Memory Usage: 10.0+ KB

## Requirements

- Python 3.x
- pandas
- Matplotlib
- Seaborn

You can install these packages using the following command:

```bash
pip install -r requirements.txt
