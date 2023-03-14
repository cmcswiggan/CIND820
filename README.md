# CIND820
Capstone Project Code and Data Repository

The tentative steps for the project are to test three cases of text preprocessing on three models and evaluate the model performance
the models in question are as follows:
    - simple count based classifier
    - Multinomial Naive Bayes
    - SVM
    
Source data is included in this repository and all models are linked to this dataset as SMS_spam_dataset.

Python notebook files correspond to each model (simple, NB, and SVM) with 3 cases for each.
Case 1 uses no text preprocessing steps, Case 2 tokenizes the sms messages and removes stopwords
Case 3 includes the steps from Case 2 and lowercasing, special character and punctuation removal.

Lemmatization is conducted on each case.
