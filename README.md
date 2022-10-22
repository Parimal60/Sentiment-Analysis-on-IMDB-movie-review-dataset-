# Sentiment-Analysis-on-IMDB-movie-review-dataset-

Sentiment Analysis on IMDB movie review dataset using Glove Embeddings and LSTM 

1) Total 50,000 IMDB movie reviews having balanced positive and negative sentiments. 
2) Text processing steps: 1) Converting text into lower case 2) Removing stopwords 3) Removing HTML tags 4) Removing punctuations 
3) Used Keras tokenizer to map each word from vocabulary to an unique index. 
4) Used pretrained Glove embeddings of 100 dimension for each word in vocabulary.  
5) Deep learning network used consists of a Embedding layer to map words to a embedding (Glove in this case), then LSTM layers and finally to get a single proability output a single unit with a sigmoid activation. 
6) Used binary cross entropy to train the model, used early stopping with obvious Adam optimizer. 
7) Got the Accuracy of 85.64 % on test review data. 
  
