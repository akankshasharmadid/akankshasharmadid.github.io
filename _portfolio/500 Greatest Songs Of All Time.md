---
title: "Analysis of Greatest 500 Songs Of All Time"
excerpt: "The analysis is conducted on the greatest 500 songs of all time. The dataset is taken from Kaggle.<br/>"

---


- [Github Code Repository](https://github.com/akankshasharmadid/500GreatestSongsOfAllTime)

## Introduction



## About Dataset

### Context
Rolling Stone is an American monthly magazine that focuses on popular culture. It was founded in San Francisco, California, in 1967 by Jann Wenner, and the music critic Ralph J. Gleason. And here are their top 500 picks as the greatest songs of all time.

### Content
The dataset includes 500 songs with attributes such as title, description, artist, etc.

### Acknowledgements
The data is taken from Kaggle: (https://www.kaggle.com/datasets/omarhanyy/500-greatest-songs-of-all-time)

## Exploratory Data Analysis

The dataset comprises songs curated by the Rolling Stone magazine. Exploring the chart-toppers from each year provides insights into the musical landscape of that time.

![Songs Trend Over Years](/images/SongChartTrend.png)


Examining the sentiment of songs released during each year can offer valuable insights into evolving public perceptions and attitudes toward music.


![Songs Trend Over Years](/images/SongSentimentOverYears.png)

Let's find the top 10 artists whose songs made it into the charts

![Top 10 Artist whose song made it onto the charts](/images/Top10Artist.png)

We can see that the Beatle's songs were the ones that made it to the charts a lot of times. It's important to see what's the trend of that over time. 

![Beatles Song Chart Trend](/images/BeatlesSongTrend.png)

Let's also find out the streak of the chart songs over the years and what's the distribution of those. 


![Streak in Weeks](/images/StreakinWeeks.png)

Let's find out the name of the songs which are having streak in weeks greater than 30 weeks. 


+-----------------------+------------------+-----------------+
|         Title         |      Artist      | Streak In Weeks |
+-----------------------+------------------+-----------------+
|        Hey Ya!        |     OutKast      |       32.0      |
| How Deep Is Your Love |     Bee Gees     |       33.0      |
|    Come Go With Me    | The Dell-Vikings |       31.0      |
|    Ignition (Remix)   |     R. Kelly     |       42.0      |
|  Under the Boardwalk  |   The Drifters   |       33.0      |
|   Since U Been Gone   |  Kelly Clarkson  |       46.0      |
|       The Twist       |  Chubby Checker  |       39.0      |
+-----------------------+------------------+-----------------+
