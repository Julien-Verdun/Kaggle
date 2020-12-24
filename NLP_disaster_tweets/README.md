# Disaster Tweets

This project is based on the Kaggle competition [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started).

The data include for every tweet the content of the tweet and the target, whether the tweet is about a real disaster or not.

## Models

I trained different kind of algorithm on the disaster tweet data, mainly from **sklearn** and also with **keras**.

The tweet's contents are vectorized with the CountVectorizer. I applied the following model :

- Naive Bayes algorithms (Gaussian, Bernoulli and Multinomial Naive Bayes)
- Logistic and Ridge Regression
- tree algorithm (Cart, ID3)
- K-neareast Neighbors
- ensemble method (Bagging, AdaBoost, Random Forest)
  with sklearn.

## Results

The better model is the **Multinomial Naive Bayes** model which reached the preformances below :

- Accuracy score : 0.789
- Recall score : 0.681
- Precision score : 0.793
- F1 score : 0.733.

This model is simple and reach high performances.
