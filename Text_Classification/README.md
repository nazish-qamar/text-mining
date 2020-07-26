# Text Classification
The task is to build a text classification model of the work of two authors obtained from Gutenberg corpus

## Steps followed:
* Loading a file from Gutenberg corpus
* Splitting into train and test set
* Obtaining binary document-term matrix and training a logistic classifier with the author as target.
* Obtaining a document-term matrix of counts and training a logistic classifier with the author as target
* Obtaining a tf-idf scores document-term matrix and training a logistic classifier.
* Text Classification with the three models on the test data
* Obtaining the confusion matrices for the three different models
* Obtaining accuracy and f1-score for the three different models.

## Other output files
* binary_document_term_matrix.csv
* document_term_matrix_of_counts.csv
* document_tfidf_matrix.csv