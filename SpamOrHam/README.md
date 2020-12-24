# SPAM or HAM project

This repository aims at presenting results on [SMS spam collection dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset).

This project consists in creating a spam classifier with the labelled SMS examples in the dataset (4825 ham SMS and 747 spam SMS).

I tried few methods on this dataset and especially the **Naive Bayes** method which consists in predicting a label regarding the conditionnal probability of each word in the SMS.

I implemented this **Naive Bayes** method from scratch (with a homemade vectorizer, bayes probabiliy calculation and cross validation method) and I compared the results to the **sklearn** method :

- Naive Bayes algorithms (Gaussian, Bernoulli and Multinomial Naive Bayes)
- Logistic Regression
- tree algorithm (Cart, ID3)
- ensemble method (Bagging, AdaBoost, Random Forest)
  with sklearn.

The first approach is available on the notebook `spam_naives_bayes_from_scratch.ipynb`.
The sklearn models are available on the notebook `spam.ipynb`.

## Main results

- Naive Bayes from scratch :
  - Accuracy : 87.0
  - F1-score : 92.1
  - Precision : 87.3
  - Recall : 97.6
- sklearn Multinomial Naive Bayes :
  - Accuracy : 97.2
  - F1-score : 95.7
  - Precision : 96.7
  - Recall : 94.7

The results given by the sklearn Naive Bayes are a little higher than the results given by the algorithm from scratch.
In fact, the performances are increased by some optimisations, especially in the sentence vectorizer function. The function I implemented from scratch are not optimized with stop words, plural words and so on. The CountVectorizer function from sklearn is optimized and gives better vector to represent a sentence.
