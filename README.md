# Data analysis of the #NoMasks and #StopMasques hashtags on Twitter in July 2020

### How First Draft used Twitter data and Python's Pandas and Regex to analyse the spread of anti-masks hashtags
Carlotta Dotto, First Draft

This repository contains data and code supporting a [First Draft article](https://firstdraftnews.org/latest/coronavirus-how-pro-mask-posts-boost-the-anti-mask-movement) examining the #NoMasks hashtag trending on Twitter on July 292. Published on August 21, 2020.

## Methodology

We gathered 46,170 tweets and retweets containing the #UnitedAgainstJehad hashtag between May 13 and May 17. 

We used Python's Pandas to analyse the main actors, to extract their creation dates and select the most common hashtags in the tweets and accounts' bio. 

Network analysis was performed on Gephi, resizing the nodes based on the in-degree (pict 1) and out-degree values (pict 2). We used the «ForceAtlas 2» layout to bring accounts that frequently mentioned each other closer together. 

---

## Data

[Data](https://github.com/dottocarlotta/antimasks-hashtags-data-analysis/tree/master/data) was scraped from the Twitter API.

## Analysis

• [This document](https://github.com/dottocarlotta/antimasks-hashtags-data-analysis/blob/master/NoMasks-analysis.ipynb) walks through the data analysis of #UnitedAgainstJehad hashtag. It provides reproducible code for parsing out the hashtags in the tweets and for creating key visualizations.



