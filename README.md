# Predicting_app_review_sentiment
Using NLP techniques to predict review sentiment for a dating app

* This analysis uses NLP techniques to predict review sentiment for a dating app. The data used in the analysis are publicly available on Kaggle here: https://www.kaggle.com/datasets/shivkumarganesh/bumble-dating-app-google-play-store-review.

* After feature engineering had been applied, the review text was processed to remove emojis, punctuation and stop words. The text was also stemmed and converted to lower case.

* A Tfidf vectorizer was applied to prepare the data for modelling and three models were trained on the dataset. These were a MultiNomial Naive Bayes, a Logistic Regression and a Random Forest. Hyperparameters were also tuned for the latter two models.

* The aim here was to optimise the Recall metric for the negative reviews class so that the dating app could identify as many negative reviews as possible and respond accordingly. The MultiNomial Naive Bayes model was the most successful in this regard and resulted in a Recall score of 92% for identifying negative reviews.

* In a live setting, this model would allow the company to identify negative reviews faster, solve customer problems and increase customer satisfaction.
