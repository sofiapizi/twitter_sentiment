# Twitter Sentiment Analysis
Project Goal
In this Notebook we introduce classification methods to perform Sentiment Analysis on Twitter data. We follow a Neural Network approach and a Transformer based approach, introducing respectively a LSTM Model and a fine tuned DistilBERT language model.

After training the models on the "Sentiment140" training dataset, we test them on tweets pulled by ourselves from the Twitter API v2 in early December 2022. In particular, we make a Sentiment Analysis on tweets mentioning "Elon Musk".

Training Dataset Description - Sentiment140
We use the sentiment140 dataset. It contains 1,600,000 tweets extracted using the twitter API. The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment. Sentiment140 was created by Alec Go, Richa Bhayani, and Lei Huang, who were Computer Science graduate students at Stanford University.

URL
http://help.sentiment140.com/for-students/
