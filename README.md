[<img src="https://github.com/jast92/final-DE-music-in-corona-times/blob/main/graphics/presentation_impact_corona_mainstream_music_germany.png">](https://github.com/jast92/final-DE-music-in-corona-times/blob/main/presentation/presentation_impact_corona_mainstream_music_germany.pdf)

# final-DE-music-in-corona-times

This is my final project for the "Data Analytics" Bootcamp of Ironhack Berlin in 2020. If you are interested in other Data Science projects which I have worked on, feel free to browse my [GitHub profile](https://github.com/jast92/).

#### Project Status: [Completed]

## Project Intro

2020 was a year of drastic changes due to the worldwide Corona health crisis. The life of all people around the world has been affected by this crisis. I wanted to know whether this crisis has left a footstamp on the German mainstream music in audio or lyrics. For this purpose I looked at Top 100 charts released between January and November of the years 2018-2020 to find out which kinds of songs were consumed most by Germans. 

### Methods Used
* Webscraping / API
* Data cleaning and wrangling
* Data Visualization
* Sentiment analysis (VADER)

### Technologies
* Python
  * Pandas
  * Matplotlib
  * Numpy
  * Spotipy
  * NLTK
  * Langdetect
  * Sklearn
  * SpotiPy
  * Lyricsgenius
* Jupyter
* Tableau

## Information over dataset
The dataset consists of information of 1,868 songs which have been first released in the German Top 100 music charts between January 2008 and November 2020.
The data was collected from different data sources. I used information from www.offiziellecharts.de to determine which songs had been in the Top 100 charts of each week in the observation period. The Spotify API was used to enrich the data with information about audio features of the songs. The lyrics of the songs were gathered through the Lyrics Genius API.

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

- Data collection
- Data processing/cleaning
- Data exploration/descriptive statistics
- Statistical modeling
- Writeup/reporting

## Getting Started

1. The folder [**top100**](https://github.com/jast92/final-DE-music-in-corona-times/tree/main/top100) contains all the jupyter notebooks and raw files of all German Top 100 charts which were scraped from [www.offiziellecharts.de](https://www.offiziellecharts.de).
2. In the folder [**analysis**](https://github.com/jast92/final-DE-music-in-corona-times/tree/main/analysis) you can find all the jupyter notebooks which I used to conduct my analysis.
3. [**tableau**](https://github.com/jast92/final-DE-music-in-corona-times/tree/main/tableau) contains the Tableau files which I partly used for my analysis.
4. The graphics created in the analysis using Matplotlib can be found in the folder [**graphics**](https://github.com/jast92/final-DE-music-in-corona-times/tree/main/graphics).
5. All the files containing the dataframes can be found as CSV and PKL in the [**files**](https://github.com/jast92/final-DE-music-in-corona-times/tree/main/files) folder.
6. If you want to find out what my findings where, I invite you to take a look at my [**presentation**](https://github.com/jast92/final-DE-music-in-corona-times/tree/main/presentation).


## Analysis optimization
When you feel intrigued by my analysis and you want to collaborate to make this analysis even better, feel free to reach out to me (contact information see below)!


## Contributor

**[Janek Stein](https://www.linkedin.com/in/janekstein/)**
