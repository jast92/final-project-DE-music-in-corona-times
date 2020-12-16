# midterm-project

This project is a contribution to the "Data Analytics" Bootcamp of Ironhack Berlin in 2020. If you are interested in other Data Science projects which I have worked on, feel free to browse my [GitHub profile](https://github.com/jast92/).

#### Project Status: [Active]

## Project Intro

2020 was a year of drastic changes due to the worldwide Corona health crisis. The life of all people around the world has been affected by this crisis. I wanted to know whether this crisis has left a footstamp on the German mainstream music in audio or lyrics. For this purpose I looked at Top 100 charts released in the years 2018 - 2020 (1st week of December) to find out which songs were consumed most by Germans. 

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization

### Technologies
* Tableau
* Python
  * Pandas
  * Matplotlib
  * Numpy
  * Seaborn
* Spotipy
* NLTK
* Langdetect
  * Sklearn
* Jupyter

## Information over dataset
The dataset consists of information of a little under 2,000 songs which have been first released in the German Top 100 music charts between January 2008 and November 2020.
The data was collected from different data sources. I used information from www.offiziellecharts.de to determine which songs had been in the Top 100 charts of each week in the respective period. The Spotify API was used to enrich the data with information about audio features of the songs. The lyrics of the songs were gathered through the Lyrics Genius API.

### These are the definitions of data points provided:

* id: Unique identification number for a given song
* artist: name of the artist
* title: title of the song
* year: year of first appearance in the Top 100 charts
* month: month of first appearance in the Top 100 charts
* week: week of first appearance in the Top 100 charts
* totalweeksincharts: Number of weeks a song was in the charts in the observed period
* total2018weeksincharts: Number of weeks a song was in the charts in the year 2018
* total2019weeksincharts: Number of weeks a song was in the charts in the year 2019
* total2020weeksincharts: Number of weeks a song was in the charts in the year 2020
* danceability
* energy
* key
* loudness
* mode
* speechiness
* acousticness
* instrumentalness
* liveness
* valence
* tempo
* duration_ms
* time_signature
* spotify-id
* track_href
* analysis_url
* uri
* lyrics: raw lyrics imported from Lyrics Genius
* lang: language of the lyrics



## Needs of this project

- Data exploration/descriptive statistics
- Data processing/cleaning
- Statistical modeling
- Writeup/reporting

## Getting Started

1. For a first overview of the data, you can find a visual analysis of the data on my [Tableau profile](https://public.tableau.com/profile/janek.stein#!/).
2. The original (raw) data can be found [here](https://github.com/jast92/midterm-project/tree/main/data).
3. MySQL scripts to set up new database with original data and queries for creating more insights out of the raw data can be found [here](https://github.com/jast92/midterm-project/tree/main/sql-queries).
4. The Jupyter Notebook with all the data processing/cleaning steps as well as all iterations of applying different models to make predictions can be found (ending "iterations") as well as a cleaner final version with the most significant models (ending "final") [here](https://github.com/jast92/midterm-project/tree/main/jupyter-notebooks).


## Optimization of models
When you feel intrigued by my analysis and you want to collaborate to make the models even better, feel free to reach out to me (contact information see below)!


## Contributor

**[Janek Stein](https://www.linkedin.com/in/janekstein/)**
