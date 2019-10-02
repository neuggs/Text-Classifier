# Frank Neugebauer's Text Classifier GitHub

The basic idea is simple: given two sets of data, predict an outcome for each. One set is a bunch of comments that have been marked as either controversial (or not, using 0 an 1). With that data, build a model to predict whether a new comment is controversial or not. The other set of data has a bunch of comments that have been categorized by topic (e.g., 'video_games'). WIth that data, build a model to predict the category of new comments.

## Some of what's demonstrated:

* Reading JSON files
* Sampling to increase performance and evenly sample source data
* Pipelines
* Logistic regression
* Multinomial Naive Bayes

## Requirements

The project is entirely Python and was built using a Jupyter Notebook. Having Anaconda (or similar Python distribution with Jupyter Notebook) is required. A number of libraries are also used, which can be installed using `pip install <LIBRARY_NAME>`. Included in this list are:

* pandas
* sklearn.feature_extraction.text TfidfVectorizer
* sklearn.naive_bayes MultinomialNB
* sklearn.linear_model LogisticRegression
* sklearn.model_selection train_test_split
* sklearn.metrics accuracy_score

