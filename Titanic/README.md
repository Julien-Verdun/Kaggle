# Titanic project

This repository aims at presenting results on Titanic project.

I used 2 different approachs in order to learn from Titanic data. Both are classifications algorithms :

- sequential neural network
- logistic algorithm

## Main facts

The dataset was **unbalanced** (61% of dissapeared people and only 39% of survivors). To rebalance the dataset, I add as much data as necessary in order to got 50% of disappearance and 50% of survival.

I didn't take all available features. In fact, I didn't see how the name of the passenger,the ticket or cabin number and the boarding city could have an impact on the survival probability.
I only trained my algorithms with the following features :

- the sex
- the class
- the age
- the number of siblings/spouses
- the number of parents/children.

## Main results

The **neural network** worked perfectly and achieved an **accuracy of 100%** without any false positive and false negative (regarding the confusion matrix).

The **logistic algorithm** was less efficient than the first approach but was still very accurate. In fact it worked with an **accuracy of 97%**.
