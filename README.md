# Spotify Music Analysis
Script to analyze and compare your Spotify music playlist with the top 100 songs of 2018

I used the Spotipy library for this analysis

<h1>Objective</h1>
This led me to try to answer two questions using data from Spotify:
<ol>
  <li>What does my music playlist look like?</li>
  <li>Are there particular audio attributes that are common among hit songs?</li>
</ol>

<h1>Tools</h1>
Luckily, there are really simple tools out there to help us connect to Spotify, retrieve data and then visualise it.

We will be using Python 3 as the programming language, Spotipy, the Python library that allows you to connect to the Spotify Web API and we will use plot.ly and Seaborn for data visualisation.

<h1>Dataset</h1>
At the end of each year, Spotify compiles a playlist of the songs streamed most often over the course of that year and this playlist has 100 tracks. The dataset I used was already available on Kaggle: https://www.kaggle.com/nadintamer/top-spotify-tracks-of-2018
