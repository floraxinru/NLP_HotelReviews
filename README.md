# HotelReviews_SentimentAnalysis

Main tools/concepts used: 
##### Natural Language Processing, Naive Bayes Classifier, bag-of-words model, Pandas, matplotlib

## Abstract

Using Naive Bayes Classifier for sentiment analysis on a dataset with 515K reviews on luxury European hotels, I have obtained a training accuracy of 93.5 percent, and a testing accuracy of 92.5 percent when predicting positive and negative reviews. The most informative words indicating a review to be positive or negative are also found, and positive reviews reflect more on hotel staff and location, while highly negative reviews tend to focus on facilities.

Scatter plots and bubble plots are used to explore the relationship between reviewers' experience level in travelling (leaving multiple reviews) and ratings given, as well as reviewer nationality and ratings. Contrary to my hypothesis, I found that the experienced reviewers tend to leave higher ratings for this dataset. No clear relationship was found between nationality and ratings.

This project is based on my Final Project for Python for Data Science on edx, first submitted in Dec. 2017, using sentiment analysis to analyze 515K European Hotel Reviews.

## Motivation

During the past few years, us consumers rely increasingly heavily on online ratings and reviews when making decisions, especially when travelling to a new destination.

In this project, I am interested in looking for words that are strong indicators of positive or negative reviews through natural language processing and sentiment analysis. This could provide valuable insight to hotel management as well as similar websites collecting ratings to improve their performance and better target certain customers. It can also help fellow travellers understand which words are the most effective when leaving a review for their next stay.

In addition, I want to test the hypothesis that well-seasoned travellers (those with a high number of reviews for different hotels) tend to be more critical and leave lower reviews.

## Dataset

My dataset is the "515K Hotel Reviews Data in Europe" dataset on Kaggle (https:// www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe). The dataset is a .csv file of size 48MB, containing most text. The positive and negative reviews are already in columns. The reviews are all in English, collected from Booking.com from 2015 to 2017.

The dataset contains 515738 reviews for 1493 luxury hotels in Europe.

## Installation and Usage
See also: requirements.txt

## Limitations 

Certain inherent limitations of this dataset include the fact that it only contains English reviews collected on one website (Booking.com), and that the hotels are limited to luxury hotels in Europe. Also the text-based nature of the dataset make it more difficult for nice visualizations.

When identifying experienced travellers based on the number of reviews they wrote in this dataset, I am also neglecting the possibility that some reviewers might have written reviews using different accounts on other websites.

## Further Work

Future work which will provide more insights include building a regression model to predict ratings based on certain words in the reviews, clustering the reviews as well as hotels to look for patterns, and filtering out reviews that could be misleading (“no negatives”) to increase the prediction accuracy of the Naive Bayes Classifier to a number even higher than 92.5%.

I would also like to try different kinds of visualizations and improve the appearance of the current ones. The next visualization to try would be using a Folium map to visualize nationalities of reviewers who gave the highest ratings




