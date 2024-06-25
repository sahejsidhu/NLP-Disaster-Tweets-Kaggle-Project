The goal of this project is to build a machine learning model that can predict whether a given tweet is 
about a real disaster or not. The subfield of machine learning it utilizes is Natural Language Processing (NLP) 
which is used for text classification. The specific machine learning model used is a Recurrent Neural Network (RNN) 
with Long Short-Term Memory (LSTM) layers. 
The dataset used contains tweets, each with the following features:
`id`: Unique identifier for each tweet
`text`: The text of the tweet
`location`: The location from which the tweet was sent (may be blank)
'keyword`: A keyword from the tweet (may be blank)
`target`: (only in the training set) Denotes whether a tweet is about a real disaster (1) or not (0)
The dataset is divided into `train.csv`, `test.csv`, and `sample_submission.csv`.
