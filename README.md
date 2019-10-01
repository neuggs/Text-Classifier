## Frank Neugebauer's Text Classifier GitHub

The basic idea is simple: given a bunch of comments that have been marked as either controversial (or not, using 0 an 1), build a model to predict whether a new comment is controversial or not.

#Some of what's demonstrated:

* Reading JSON files
* Sampling to increase performance
* Tokenization
* Creating vectors as features
* Logistic regression with different penalities
* Multinomial Naive Bayes
* First, import everything that's needed.
