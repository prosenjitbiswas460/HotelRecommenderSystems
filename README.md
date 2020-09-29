# HotelRecommenderSystems
Content based Recommender systems with NLP. The idea is to recommend hotels to a user based on the descriptions of hotels, upon feeding a hotel name.
The data used is a public data set of makemytrip.com. The model used here is an NLP tfvectorizer model along with cosine similarities.
The description of a property is first preprocessed, lemmatized, tokenized, then n-grams are generated and finally converted into a tfidf matrix.
This matrix helps in computing cosine similarities between to descriptions of the corresponding properties/ hotels.
Finally we visualize this and get a set of recommended hotels.

The data can be found at - https://data.world/promptcloud/hotels-on-makemytrip-com
Please note- The visualizations are done in plotly,hence only the static versions of them can be seen on github. To get the best experience, please clone/ download the repo and remove "png" argument from fig.show("png") or view them on https://nbviewer.jupyter.org/
