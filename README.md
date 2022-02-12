# Spam Classification Using Word2vec Embeddings and LSTM

A group of Google researchers developed word2vec in 2013, and it has become
the foundation of NLP that is also incorporated in BERT. Word2vec provides
an efficient method to represent words as vectors in a lower-dimensional
space. The word2vec will generate a vector consisting of
floating points for each word in a text corpus. 

The task is to transform the text words to vectors using a neural network consisting of an input layer, a hidden layer. This neural network concise the of an output layer that has the same dimension as the input layer, with no activation function.  The kind of neural network like word2vec is called autoencoder.

We will use the word2vec embeddings model to prepare the data text to classification the task of the urls text into two categories: urls that mean spam contents or no spam contents. Some of the best classifier text models are neural networks like recurrent NN of type LSTM (Long Short Term Memory). In the first step, we make data analysis, data clean, and features engineering. To the second step, we should be building the word2vec embeddings model to feed the LSTM classification model
