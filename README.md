# Sentiment Classification - of IMDb User Reviews - using LSTM

As part of model training, we trained three nodels: Simple Neural Network, CNN and LSTM, and concluded that LSTMs are well suited to handle (sequential) text data.


## Summary

- Load IMDb Movie Reviews dataset (50,000 reviews) (source: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- Pre-process dataset by removing special characters, numbers, etc. from user reviews + convert sentiment labels to numbers 1 & 0.
- Import GloVe Word Embedding to build Embedding Dictionary + Use this to build Embedding Matrix for our Corpus
- Model Training using Deep Learning in Keras for Simple Neural Net, CNN and LSTM Models and analyse model performance and results
- Perform predictions on real IMDb movie reviews

