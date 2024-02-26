# Detection of spam from SMS using Sparse mebedding and Logistic Regression

<p>This project implements a machine learning model for detecting spam in SMS messages. It utilizes sparse embedding and logistic regression to classify SMS messages as spam or non-spam.</p>

<h1>Project Description</h1>

<p>Spam messages are unsolicited, unwanted, and often misleading digital communications, commonly encountered in the form of SMS. This project aims to develop a model capable of effectively identifying spam messages to help users protect their privacy and avoid unwanted content.</p>

The model employs the following techniques:

* Sparse Embedding: This technique represents textual data like SMS messages as sparse numerical vectors, capturing the essential features of the text while maintaining efficiency using Spacy.
* Logistic Regression: This is a linear classification algorithm used to predict the probability of a message belonging to the spam class based on its features extracted through sparse embedding.

<h2>Tools:</h2>


* Python 3.x
* NumPy
* Pandas
* Scikit-learn
* optuna
* spacy
