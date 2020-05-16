# IMDb_NLP_Classifier
Sentiment Analysis of IMDb Reviews via Recurrent Neural Networks

Classification model that performs sentiment analysis on IMDb reviews. The model is build utilizing a LSTM Recurrent Neural Network that classifies a review as being either positive or negative. 

The datatset contains 25,000 reviews from the movie rating platform IMDb, where each review has been preprocessed and labeled as either positive or negative. Each review is encoded by integers that represent how common a word is in the dataset. For example, an integer encoding of 4 means that the word in question is the 4th most common word in the dataset.

The IMDb dataset can be directly imported from keras.datasets. 
