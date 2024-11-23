# Fake-news-detection
Predicting fake news using machine learning
## Dataset Description

#### train.csv: A full training dataset with the following attributes:

#### title: the title of a news article

#### author: author of the news article

#### text: the text of the article; could be incomplete

#### label: a label that marks the article as potentially unreliable

#### 1: unreliable

#### 0: reliable

## Data Pre-Processing 
Data is cleaned for any missing values.

Stemming: Stemming is the process of reducing a word to its base or root form, often by removing suffixes or prefixes. Eg:'running','runs','runner' root word: run

Converting textual data into numerical data.

Tfidfvectorizer:It stand for term frequency-inverse document frequency.TF-It counts the number of times a particular word is repeating in a paragraph.The number of repetition tells the importance of that word in text and it assign a number. IDF-It measures how unique and important a term is.

## Training our model and checking accuracy score

Model is trained on training data and accuracy score is calculated.

The predictive model we trained has an accuracy of 98% on training data and 97% on test data.We used logistic regression has it is the good choice for binary data.
