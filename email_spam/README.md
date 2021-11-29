# Email Spam Detection

Build a model to detect spam emails.

Project link: https://www.kaggle.com/bagavathypriya/email-spam-dataset

## Machine Learning Arena
  - Natural Language Processing (NLP)
 
## Major Libraries Used
  - NLTK
  - sklearn
  - wordcloud
  - pandas
  - seaborn, maltplotlib

## Overview
  - Load dataset and perform exploratory analysis (shape, output distribution, data integrity etc.)
  - Text preprocessing (remove punctuation, tag, special characters, digits -> tokenization -> remove stopwords)
  - Create wordcloud on overall text, spam, and regular emails.
  - Spam detection model:
    - Bag of Words (CountVectorizer) with Gradident Boosting
    - TF-IDF with Multinominal Naive Bayes
