# App Reviews Sentiment Analysis

## Overview
This repository contains the Sentiment Analysis of application's reviews.

App Reviews Sentiment Analysis means evaluating and understanding the sentiments expressed in user reviews of mobile applications (apps). It involves using data analysis techniques to determine whether the sentiments in these reviews are positive, negative, or neutral. 

## Process We Can Follow :
App Reviews Sentiment Analysis is a valuable tool for app developers and businesses to understand user feedback, prioritize feature updates, and maintain a positive user community.

Below is the process we can follow for the task of app reviews sentiment analysis:

1. The first step is to gather a dataset of app reviews.
2. Then, perform EDA by analyzing the length of the reviews and their ratings, etc.
3. Then, label the sentiment data using tools like Textblob or NLTK.
4. Understand the overall distribution of sentiments (positive, negative, neutral) in the dataset.
5. Explore the relationship between the sentiments and the ratings given.
6. Analyze the text of the reviews to identify common themes or words in different sentiment categories.

## Dataset
So, the process starts with collecting an app reviews dataset. I found an ideal dataset for this task. You can download the dataset from [here](https://statso.io/sentiment-analysis-case-study/).

## Libraries used
- **Pandas** : For data manipulation and analysis.
- **Matplotlib & Seaborn** : For data visualization.
- **TextBlob** : For label the data with sentiments.
TextBlob provides a polarity score ranging from -1 (very negative) to 1 (very positive) for a given text. We can use this score to classify each review’s sentiment as positive, neutral, or negative. You can install it by executing the pip command mentioned below in your terminal or command prompt:

    - pip install textblob

- **WordCloud** : For a text analysis to identify common words in each sentiments.


## Screenshots
![Rating Distribution](https://github.com/koladiyadhruvin/App-Reviews-Sentiment-Analysis/blob/main/Rating%20%20Dist.png)

![Review Length Distribution](https://github.com/koladiyadhruvin/App-Reviews-Sentiment-Analysis/blob/main/Review%20length%20Dist.png)

![Sentiment Distribution](https://github.com/koladiyadhruvin/App-Reviews-Sentiment-Analysis/blob/main/Sentiment%20dist.png)

![wordcloud](https://github.com/koladiyadhruvin/App-Reviews-Sentiment-Analysis/blob/main/wordclod.png)

## Summary
So, App Reviews Sentiment Analysis is a valuable tool for app developers and businesses to understand user feedback, prioritize feature updates, and maintain a positive user community. It involves using data analysis techniques to determine whether the sentiments in these reviews are positive, negative, or neutral. I hope you liked this project on App Reviews Sentiment Analysis using Python.
