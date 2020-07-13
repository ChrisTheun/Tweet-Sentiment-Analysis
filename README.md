The goal of this project is to see whether it is possible to predict the sentiment of replies to customer support tweets based solely on the text of said customer support tweet.
The analysis is conducted using @SpotifyCares tweets extracted from the 'Customer Support on Twitter' dataset retrieved from https://www.kaggle.com/thoughtvector/customer-support-on-twitter.
A naive Bayes classifier is first trained upon Python's Natural Language Toolkit's (NLTK) sample tweets to generate positive and negative sentiment labels for tweets by and replies to @SpotifyCares.
Afterwards, another naive Bayes classifier predicts the sentiment of the replies to the Spotify customer service tweets by using the processed text of the customer service tweet as a featureset.

The text processing and sentiment analysis is based on Shaumik Daityari's excellent blogpost on Twitter sentiment analysis using the NLTK library.
https://www.digitalocean.com/community/tutorials/how-to-perform-sentiment-analysis-in-python-3-using-the-natural-language-toolkit-nltk