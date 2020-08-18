# Data analysis of the #NoMasks and #StopMasques hashtags on Twitter in July 2020

### How First Draft used Twitter data and Python's Pandas and Regex to analyse the spread of anti-masks hashtags
Carlotta Dotto, First Draft

August 18, 2020

This repository contains data and code supporting a First Draft article (LINK) examining the #NoMasks hashtag trending on Twitter on July 292. Published ---. See below for details.

## Methodology

We gathered 33,450 Twitter posts containing #NoMasks in July 2020. We analysed the trend over time and the top associated hashtags.

We then focused the analysis on the tweets posted on July 14 — the day of the Government announcement that made masks compulsory in shops. 

After filtering out the ‘false positive’ tweets which contained US or Australian focused messages and we manually analysed the 222 resulting posts which gained at least 10 retweets on July 14. 

We then tagged them by ‘pro-masks’ or ‘anti-masks’ categories, and analyzed both groups by top associated hashtags and by total number of retweets and likes by hours.

---

## Data

All data comes from the Twitter API.

### Analysis
⋅[This document](https://github.com/dottocarlotta/antimasks-hashtags-data-analysis/blob/master/NoMasks-analysis.ipynb) walks through the data analysis of #NoMasks in July 2020. It provides reproducible code for parsing out the hashtags in the tweets and for creating key visualizations.

This document reproduces the analysis for the French #StopMasques.


