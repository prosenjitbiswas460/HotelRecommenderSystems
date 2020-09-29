# HotelRecommenderSystems
Content based Recommender systems with NLP. The idea is to recommend hotels to a user based on the descriptions of hotels, upon feeding a hotel name.
The data used is a public data set of makemytrip.com. The model used here is an NLP tfvectorizer model along with cosine similarities.
The description of a property is first preprocessed, lemmatized, tokenized, then n-grams are generated and finally converted into a tfidf matrix.
This matrix helps in computing cosine similarities between to descriptions of the corresponding properties/ hotels.
Finally we visualize this and get a set of recommended hotels.

