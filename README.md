# Airline-Tweet-Sentiment-Analysis

The airline industry had a very hard time post-COVID to sustain its business due to the long haul. It is very important for them to make sure they exceed customer expectations. The best way to evaluate performance is through customer feedback. You are given a dataset of airline tweets from real customers.

A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").

Understanding the Dataset:

The dataset contains many columns out of which below are the most important ones-
1. airline_sentiment - defines the sentiment of the tweet
2. negative_reason - the reason for the negative feedback (if negative)
3. Text - tweet text content
4. tweet_location - location from which the tweet was posted

Steps to perform:
1. Load dataset - https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment
2. Clean, preprocess data and EDA
3. Vectorise columns that contain text
4. Run Classification model to classify - positive, negative, or neutral
5. Evaluate model
