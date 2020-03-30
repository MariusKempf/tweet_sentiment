# tweet_sentiment
Our goal was to train some Neural Networks and Convolutional Networks to classify labelled tweets into positive and negative sentiment. For that, we first compared them to the plug-n-play tool [VADER Sentiment](https://github.com/cjhutto/vaderSentiment "VADER Sentiment") and afterwards tried to improve hyperparameters and architectures to achieve better results. For the needed word embeddings, the Word2VEc and Do2Vec approaches were applied. Furthermore, unlabeled tweets were collected over a period of time to apply the developed model to these instances. Luckily it was possible to detect an obvious change in the twitter-community sentiment over the reviewed period.

The project was realized in the context of a seminar paper during my master studies at KIT. The Jupyter Notebook represents the final report (sorry only in German). This was our first project in this form, so please don´t be too critical.
Credits also go to Adrian Oberfoell from KIT.

## Prerequisites

* Make sure you have a working Jupyter Notebook environment i.e. Anaconda
* There are a couple of packages needed. Install them into your venv by typing:`$ pip install -r requirements.txt`
* Load the Sentiment140 Twitter data into the directory `/data/raw`

All this is not necessary if you only want to read the report. The trained models are not provided - training models by yourself will take quite some time and might be boring.

## Data

The used Twitter data is provided by [Kaggle](https://www.kaggle.com/kazanova/sentiment140 "Sentiment140") - it´s called **Sentiment140** and contains 1.6 Million tweets labelled either positive or negative, the data set is already balanced. The labelling was made automatically by some researchers, they call them "noisy" labels. The corresponding scientific paper can be found [here](https://www-cs.stanford.edu/people/alecmgo/papers/TwitterDistantSupervision09.pdf "Twitter Sentiment Classification using Distant Supervision").

Our trained models are applied on some Twitter data which was collected during TODO and TODO. The tracked hashtags were **#apple** and **#tesla**. The data is provided in the folder TODO. Collecting was made with the python scripts TODO and TODO.
