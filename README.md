📊 Data Analysis of Spotify & YouTube

📌 Overview

This project explores the relationship between Spotify streaming data and YouTube video statistics using a combined dataset. The goal is to understand music consumption trends across two major platforms, identify top-performing artists, tracks, and channels, and uncover patterns in user engagement.

The notebook performs:

Data cleaning & preprocessing

Handling missing values

Exploratory Data Analysis (EDA)

Visualizations (pie charts, bar plots, heatmaps)

Insights on top artists, tracks, and channels

📂 Dataset

The dataset used in this analysis is:
Spotify Youtube Dataset.csv

Columns include:

Track – Song name

Artist – Artist name

Stream – Number of Spotify streams

Views – YouTube views

Likes – YouTube likes

Comments – YouTube comments

Album_type – Type of album (e.g., single, album)

Channel – YouTube channel name

⚙️ Technologies Used

Python 3

Pandas – Data manipulation

NumPy – Numerical analysis

Matplotlib / Seaborn – Visualizations

📈 Analysis & Visualizations

Data Cleaning

Dropped unnecessary columns (Unnamed: 0, Url_spotify, Uri, Url_youtube)

Handled missing values in Likes and Comments

Top Artists by Views

Grouped data by artist and calculated total YouTube views

Identified top 10 most-viewed artists

Most Streamed Tracks

Sorted songs by Spotify streams

Highlighted top 10 tracks

Album Type Distribution

Visualized with a pie chart

Top Channels by Views

Bar plot showing top 5 YouTube channels

Correlation Heatmap

Showed relationships between streams, views, likes, and comments
