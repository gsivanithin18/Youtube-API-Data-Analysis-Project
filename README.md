# Youtube-API-Data-Analysis-Project

## Introduction
This repository contains a data analysis project focused on extracting and comparing information from different YouTube channels using the YouTube API. The project aims to provide insights into channel performance by analyzing metrics such as likes, views, comments, and more.

## Data Collection
The data for this analysis was collected using the YouTube API key. The API allows us to retrieve a wide range of information about YouTube channels, videos, and user interactions. The following steps were followed for data collection:

1. **Setting Up API Key:** A valid YouTube API key was obtained by following the API key generation process provided by Google.

2. **API Requests:** Utilizing the API key, requests were made to the YouTube API to fetch data for specific channels.

3. **Data Points:** The key data points extracted from the API responses included likes, views, comments, and other engagement metrics for various videos on each channel.

4. **Data Storage:** The collected data was stored in an organized manner, such as CSV files or a database, to facilitate further analysis.

## Analysis
The analysis focused on comparing different YouTube channels based on their performance metrics. The main objectives of the analysis were:

1. **Performance Metrics Comparison:** Channels were compared in terms of likes, views, comments, and other engagement factors. This comparison provided insights into which channels had higher audience engagement.

2. **Trending Topics:** By analyzing the content of the videos, the project aimed to identify trending topics or themes that attracted more viewers and interactions.

## Key Insights
In this project, we have explored the video data of the 9 most popular Data science/ Data analyst channels and revealed many interesting findings for anyone who are starting out with a Youtube channel in data science or another topic:

- The more likes and comments a video has, the more views the video gets (it is not guaranteed that this is a causal relationship, it is simply a correlation and can work both way). Likes seem to be a better indicator for interaction than comments and the number of likes seem to follow the "social proof", which means the more views the video has, the more people will like it.

- Most videos have between 5 and 30 tags.

- Most-viewed videos tend to have average title length of 30-70 characters. Too short or too long titles seem to harm viewership.

- Videos are usually uploaded on Mondays and Fridays. Weekends and Sunday in particular is not a popular time for posting new videos.

- Comments on videos are generally positive, we noticed a lot "please" words, suggesting potential market gaps in content that could be filled. 

## Usage
To replicate or build upon this analysis, you will need a YouTube API key. You can follow the steps mentioned in the API documentation to generate your own key. After obtaining the API key, you can use the provided Jupyter notebooks to collect and process data from different channels.

## Conclusion
This project demonstrates the process of collecting, processing, and analyzing data from various YouTube channels using the YouTube API. By comparing performance metrics and exploring engagement trends, valuable insights can be gained into the factors influencing channel popularity.
