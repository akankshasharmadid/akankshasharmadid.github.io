---
title: "Analysis of Greatest 500 Songs Of All Time"
excerpt: "The analysis is conducted on the greatest 500 songs of all time. The dataset is taken from Kaggle.<br/>"

---



## Introduction

In this analysis, we will explore the top 500 greatest songs of all time, as curated by Rolling Stone magazine. This dataset provides an intriguing opportunity to examine the popularity of songs from the past and observe how the musical landscape has transformed over the years. The analysis aims to shed light on the changing trends in music, highlight renowned artists, and offer insights into the historical context of these influential songs. Through this exploration, we hope to provide a deeper understanding of the evolution of musical preferences and the artists who have left a lasting impact on the industry.

## About Dataset

### Context
Rolling Stone is an American monthly magazine that focuses on popular culture. It was founded in San Francisco, California, in 1967 by Jann Wenner, and the music critic Ralph J. Gleason. And here are their top 500 picks as the greatest songs of all time.

### Content
The dataset includes 500 songs with attributes such as title, description, artist, etc.

### Acknowledgements
The data is taken from Kaggle: (https://www.kaggle.com/datasets/omarhanyy/500-greatest-songs-of-all-time)

## Exploratory Data Analysis

Let's examine the decades in which songs were released and analyze the trends. Which era saw the greatest prominence of songs, and in which decade did songs make a lasting impact? 

![Songs Trend Over Years](/images/SongChartTrend.png)

### Observations:

- No songs from the period 1910 to 1950 made it to the list of Rolling Stone's greatest songs. Investigating the possible reasons behind this could be an intriguing topic for future exploration.
- Notably, there is a peak in the number of songs during the mid-1960s. Further investigation will be conducted to uncover the factors contributing to this peak.
- It's noteworthy that there are very few songs from the 2000s on the list. This observation raises concerns as it may suggest a decline in the music industry during that era.

### Design Choice:

- Used a line graph to illustrate the trend over the years, aiding in the visualization of the number of songs released in each decade.
- The x-axis labels are strategically spaced, revealing only the decade on the graph for better clarity.
- Both the x and y-axis labels are presented clearly, facilitating easy interpretation of the chart.
- The text specifying that no songs from that era made it to the charts is straightforward and effectively communicates the absence of entries from that particular time frame on the list. This enhances the informational value of the graph.



Let's explore the sentiment of the songs, as this analysis provides valuable insights into the evolving public perceptions and attitudes toward music by examining the sentiment of songs released each year.

![Songs Trend Over Years](/images/SongSentimentOverYears.png)

### Observations:

- No songs from the period 1910 to 1950 made it to the list of Rolling Stone's greatest songs. Investigating the possible reasons behind this could be an intriguing topic for future exploration.
- Notably, there is a peak in the number of songs during the mid-1960s. Further investigation will be conducted to uncover the factors contributing to this peak.
- It's noteworthy that there are very few songs from the 2000s on the list. This observation raises concerns as it may suggest a decline in the music industry during that era.

### Design Choice:

- Used a line graph to illustrate the trend over the years, aiding in the visualization of the number of songs released in each decade.
- The x-axis labels are strategically spaced, revealing only the decade on the graph for better clarity.
- Both the x and y-axis labels are presented clearly, facilitating easy interpretation of the chart.
- The text specifying that no songs from that era made it to the charts is straightforward and effectively communicates the absence of entries from that particular time frame on the list. This enhances the informational value of the graph.


Let's find the top 10 artists whose songs made it onto the charts

![Top 10 Artist whose song made it onto the charts](/images/Top10Artist.png)

We can see that the Beatle's songs were the ones that made it to the charts a lot of times. It's important to see what's the trend of that over time. 

![Beatles Song Chart Trend](/images/BeatlesSongTrend.png)

Let's also find out the streak of the chart songs over the years and what's the distribution of those. 


![Streak in Weeks](/images/StreakinWeeks.png)

Let's find out the name of the songs which are a streak in longer than 30 weeks. 



![Top Chartered Songs](/images/TopSongsMostStreak.png)


Now, let's see what kind of words are mostly used as a title for the song. 

![Most Frequent Words Used in Song Titles](/images/WordCloudSongs.png)

