# 📷📸📺📻 Youtube-Statistics-Project

## Project Description
A movie production company just completed a movie set and want to upload the movie to the youtube channel. The company was conflicted on if they should upload it as a standalone movie or upload break it down into series/seasons. They want an analytical insight on this dilemma and they reached out to me. 

### Key Questions
- What video length tends to have the most engagement on youtube?
- What are the trending video title keywords and hashtags?
- Based on view count and recent post time, what videos tend to do well?

This project aims to utilize artificial intelligence and data analytics tools (Python, Power BI) to throw more illumination into the the video trends of youtube and how to make decisions in the nearest future for the movie company.

## Methodology

- The data for this project was extracted from the youtube API for top engagement videos posted in Nigeria for the last 12 months.
- The data was cleaned and preprocessed using python pandas.
- The major keywords and hashtags from each video was extracted, and pre-processed using tokenization and vectorization in python natural language processing and natural language processing  python libraries like NLTK, Scikit-Learn, TfidfVectorizer, re, wordcloud, etc.
- These keywords and hashtags were then grouped together based on similarity thereby classifying each videos into clusters of 4 (Cluster 0, 1, 2, 3 or 4).
- These clusters were then aggregated and insights were generated using python and power bi. Python for individual charts while power bi for advanced interactive dashboards.


## Key Insights

- Top 1000 most popular videos in Nigeria for the last 12 months
- Duration counts for each of these most popular videos.
- What duration range of videos tends to have the most view count?
- What tags or video keywords tends to do the most according to engagement?
- Express the duration ranges in percentage to figure out what duration ranges tends to perform the most?


## Conclusion
- Majority of popular videos in Nigeria and between 3 hours and below.
- About 71% of them are below 10mins long.
- The major keywords/tags in order of engagement are as follows;
    - Cluster 4: funny, short, viral, shortvideo, comedy, episode, family, shorts, live
    - Cluster 1: trending, funniest, dance
    - Cluster 2: official, video, music, visualizer
    - Cluster 0: movies, 2024, nigerian, latest, full, love
    - Cluster 3: new, yoruba, drama, nollywood

- Link to the full interactive dashboard: [Link to hosted dashboard](https://dee-ui.github.io/git-page/)



Thank you for reading! Feel free to connect with me for further discussions.

# Acknowledgments
- Author: [Dauda Agbonoga](mailto:daudaagbonoga@gmail.com)
- Youtube API
