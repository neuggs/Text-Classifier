# Frank Neugebauer's Text Classifier GitHub

The basic idea is simple: given a bunch of comments that have been either categorized or marked as either controversial (or not, using 0 an 1), build a model to predict whether a new comment is controversial or not. In other words, there are two corpora: one has comments that are categorized (object: predict the category given text), the other has comments that are noted as controversial or not (objective: predict if a given comment is controversial or not).

## Some of what's demonstrated:

* Reading JSON files
* Sampling to increase performance
* Tokenization
* Creating vectors as features
* Logistic regression with different penalities
* Multinomial Naive Bayes
* First, import everything that's needed.

## Requirements

The project is entirely Python and was built using a Jupyter Notebook. Having Anaconda (or similar Python distribution with Jupyter Notebook) is required. A number of libraries are also used, which can be installed using `pip install <LIBRARY_NAME>`. Included in this list are:

* pandas
* numpy
* sklearn.feature_extraction.text TfidfVectorizer
* sklearn.naive_bayes MultinomialNB
* sklearn.linear_model LogisticRegression
* sklearn.model_selection train_test_split
* sklearn.metrics accuracy_score
* nltk.corpus stopwords 
* nltk.tokenize word_tokenize 

For the NLTK stop words, you'll need to run the following Python code (you can run it in the Notebook or from any Python program). It downloads the stopwords.

`import nltk`

`nltk.download('stopwords')`

`nltk.download('punkt')`
