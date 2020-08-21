# Data analysis of the #NoMasks and #StopMasques hashtags on Twitter in July 2020

### How First Draft used Twitter data and Python's Pandas and Regex to analyse the spread of anti-masks hashtags
Carlotta Dotto, First Draft

August 18, 2020

This repository contains data and code supporting a [First Draft article](https://firstdraftnews.org/latest/coronavirus-how-pro-mask-posts-boost-the-anti-mask-movement) examining the #NoMasks hashtag trending on Twitter on July 292. Published on August 21, 2020. See below for details.

## Methodology

We gathered 33,450 Twitter posts containing #NoMasks in July 2020 and 1660 posts with the French hashtag #StopMasques between July 20 and August 4. 

We analyzed the trend over time and parsed out the most common hashtags in the tweets.

We then focused the analysis on the tweets posted on July 14 — the day of the UK Government announcement that made masks compulsory in shops. 

After filtering out the false positive tweets that contained US- or Australian-focused messages, we manually analyzed the 222 resulting posts that gained at least a little traffic — more than 10 retweets — on July 14. 

We then tagged them based on whether they were  “Pro-Masks” or “Anti-Masks” and analyzed both groups by top associated hashtags and by the total number of retweets and likes per hour.

---

## Data

[Data](https://github.com/dottocarlotta/antimasks-hashtags-data-analysis/tree/master/data) was scraped from the Twitter API.

### Analysis

• [This document](https://github.com/dottocarlotta/antimasks-hashtags-data-analysis/blob/master/NoMasks-analysis.ipynb) walks through the data analysis of #NoMasks in July 2020. It provides reproducible code for parsing out the hashtags in the tweets and for creating key visualizations.

• This document reproduces the analysis for the French #StopMasques.


