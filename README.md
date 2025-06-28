# Tweet_Classification

# INTRODUCTION
In today's digital age, where vast amounts of textual data are generated daily on social media platforms, sentiment analysis has become increasingly important for understanding public opinion, customer feedback, and market trends. This project aims to develop a sentiment analysis model using PySpark, a powerful tool for distributed data processing, to classify tweets into positive and negative sentiments.

# OBJECTIVE
The primary objective of this project is to develop a sentiment analysis model using PySpark to classify tweets into positive and negative sentiments. The project involves several key steps: collecting a comprehensive dataset of tweets with sentiment labels, performing extensive data preprocessing to clean and prepare the text data, and extracting meaningful features that can be utilized for machine learning algorithms. Following this, the project aims to train and fine-tune a sentiment classification model using PySpark's MLlib library, employing suitable classification algorithms such as logistic regression or decision trees. The effectiveness of the trained model will be evaluated using appropriate performance metrics to ensure its accuracy and reliability.

# DATA SOURCE
Data source link - https://www.kaggle.com/datasets/kazanova/sentiment140

Data size - 238 MB

This dataset contains 1,600,000 tweets, each annotated with sentiment labels indicating whether the sentiment expressed in the tweet is positive or negative. The dataset includes six fields:

target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)

ids: The id of the tweet ( 2087)

date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)

flag: The query (lyx). If there is no query, then this value is NO_QUERY.

user: the user that tweeted (robotickilldozr)

text: the text of the tweet (Lyx is cool
