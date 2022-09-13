# Identify-disaster-tweets-ML

The project is an NLP Notebook solution for [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started) Kaggle competition. 

The problem is that we need to determine if a user’s tweet indicates a disaster is taking place somewhere or not based on the tweet's text. The task is to let the machine predict efficiently the nature of the tweet either disastrous or not. Obliviously, it is a binary classification problem. Given a sample of labeled tweets with disastrous or nondisastrous labels, it is required to build a machine learning model that can learn and differentiate between the two labels and predict the correct label for any new tweet with the highest possible accuracy, recall, and F score.

I needed to perform data exploration to check missing values and duplicates and analyze the features that I'll include, Then I applied a preprocessing phase to clean tweets' text and Tokenization with TFIDF vectorizer to be all set for building models.

I built 4 models using sklearn python library which are Logistic regression, SVM, Decision trees, and KNN. Finally, I compared them based on the previously mentioned metrics.

The following figure illustrates the project's workflow:
![download](https://user-images.githubusercontent.com/43493601/189835866-7c5e747b-6e39-433e-9024-3277a677781f.jpg)

For full details, please refer to my [Kaggle Notebook here](https://www.kaggle.com/mohamedelsaadany/identify-disaster-tweets-ml)
