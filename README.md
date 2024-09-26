# spam-detection

This project focuses on building a robust spam detection model using machine learning techniques. The model is designed to classify emails or messages as "spam" or "not spam" based on their content.This project aims to achieve high accuracy in distinguishing spam from legitimate messages.

1) Data Preprocessing
Removed unnecessary characters, punctuation, and stop words.
Converted all text to lowercase.
Tokenized the text into words.
Applied lemmatization to reduce words to their root form.

2) Feature Engineering
Bag-of-Words (BoW): Converted text data into numerical vectors representing word frequency.
TF-IDF (Term Frequency-Inverse Document Frequency): Highlighted important words in the dataset.
N-grams: Captured word sequences to add more context to the features.

3) Model Training
Implemented and trained various machine learning models:
Naive Bayes
Random Forest

4) Evaluation
The models were evaluated using the following metrics:
Accuracy
Precision
Recall
F1-score

5) Results
The best-performing model achieved:
Accuracy: 98%
Precision: 97%
Recall: 96%
F1-Score: 96.5%
