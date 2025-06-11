# text-classification
This project builds a text classification model using the famous 20 Newsgroups dataset. 
It applies both Naive Bayes and Support Vector Machines (SVM) to classify news articles into categories using natural language processing.

📁 Dataset
Uses fetch_20newsgroups from scikit-learn.

Contains news articles across 20 topics (e.g., sports, politics, science).

🔍 Workflow
Preprocessing text with CountVectorizer and TfidfTransformer.

Train a Naive Bayes classifier and evaluate accuracy.

Build a Pipeline for streamlined preprocessing and model training.

Train and compare an SVM classifier using SGDClassifier.

🧰 Technologies Used
Python

Scikit-learn (CountVectorizer, TfidfTransformer, MultinomialNB, SGDClassifier, Pipeline)

NumPy

✅ Applications
News categorization

Email spam filtering

Sentiment analysis

