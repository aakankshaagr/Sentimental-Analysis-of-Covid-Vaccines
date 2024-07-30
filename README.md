# Sentiment Analysis of COVID-19 Vaccine Tweets

## Project Overview

This project performs sentiment analysis on tweets related to COVID-19 vaccines. Using a dataset from Kaggle, the analysis involves data cleaning, sentiment categorization using TextBlob, and visualization of the results. The goal is to understand public sentiment towards various COVID-19 vaccines.

## Dataset

The dataset contains tweets about COVID-19 vaccines, which includes fields like text, date, user location, and source.

## Steps Involved

1. **Data Loading and Inspection**: The dataset is loaded and basic information about the data is inspected.
2. **Data Cleaning**: Tweets are cleaned by removing hashtags, URLs, user handles, multiple spaces, and special characters. Stop words are also removed.
3. **Sentiment Analysis**: Sentiment analysis is performed using TextBlob, categorizing tweets into Positive, Negative, and Neutral sentiments.
4. **Visualization**: Word clouds and bar charts are used to visualize the most common words and sentiment distribution.
5. **Vaccine-Specific Analysis**: Sentiment analysis is broken down by specific vaccines, such as Pfizer, Moderna, Covaxin, Sputnik, and Covishield. Rolling averages of sentiment polarity over time are plotted for each vaccine.

## Key Observations

- **Geographical Distribution**: The dataset shows the geographical distribution of tweets, with the highest number of tweets coming from certain key locations.
- **Tweet Sources**: A variety of sources are used to post tweets, with the most common ones being visualized.
- **Sentiment Distribution**: The majority of tweets are Neutral, followed by Positive and Negative sentiments.
- **Common Words**: Word clouds reveal the most frequently used words in Positive, Negative, and Neutral tweets.
- **Vaccine Sentiment**: Sentiment analysis specific to different vaccines shows varying levels of public opinion over time. Pfizer and Moderna have a significant amount of positive sentiment, while others show mixed results.

## Summary

This project provides valuable insights into public sentiment towards different COVID-19 vaccines using Twitter data. The analysis shows that while there is a substantial amount of neutral sentiment, positive sentiment is also prevalent, particularly for vaccines like Pfizer and Moderna. This information can be useful for health organizations and policymakers to address public concerns and improve communication strategies.

