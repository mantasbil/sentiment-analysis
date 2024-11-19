# Sentiment Analysis

In this project sentiment analysis is performed for [tweets about US airlines](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment). Tweets are classified into three grouos based on sentiment: positive, neutral and negative.

Sentiment analysis was performed in two ways:
1. Using pretrained lexicons (Vader and TextBlob).
2. Vectorizing text with BagOfWords and applying machine learning classification models (Logistic Regression, K-Neareast Neighbors and Support Vector Machines).

It was found out that vectorizing text and applying classification models performed much better on the given data than using lexicons. Logistic regression and support vector classifier produced best classification results with logistic regression having best general accuracy and SVC being the best at recognizing negative tweets.
