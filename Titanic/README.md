# Titanic project

This repository aims at presenting results on Titanic project.

I used several approachs in order to learn from Titanic data. All those technics are classifications algorithms :

- Sequential Neural Network
- Logistic Regression
- Support Vector Machines
- tree classifiers (CART and Random Forest)

## Main facts

The dataset was **unbalanced** (61% of dissapeared people and only 39% of survivors). To rebalance the dataset, I add as much data as necessary in order to get 50% of disappearance and 50% of survival.

I didn't take all available features. In fact, I didn't see how the name of the passenger,the ticket or cabin number and the boarding city could have an impact on the survival probability.
I only trained my algorithms with the following features :

- the sex
- the class
- the age
- the number of siblings/spouses
- the number of parents/children.

## Main results

- **Neural Network** : 78%
- **Logistic Regression** : 78%
- **SVM** : 77%
- **CART tree** : 77%
- **Random Forest** : 78%

The **first submission** resulted in a score of 77%, the second one a bit lower, 72%.

## Improvement ways

I think a way to improve my predictions is to take more features into account (for example the title (mr, miss, mrs)).
