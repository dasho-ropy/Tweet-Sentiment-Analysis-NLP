# Tweet-Sentiment-Analysis-NLP

The sentiment analysis model is based on character level indexing of text and their embeddings which are fed on the neural network classifier. 

The data is preprocessed into texts, along with the exclusion of all unnecessary words which do not have any language defined. 

These texts are then converted into character level processed sequences using Keras Tokenizer and padding into sequences of length as max length of tweets i.e 200. 
The neural network has:
Activation function tanh
Hidden layers of size as 204, 105
Adam optimizer

Labels:-
0 – positive
1 – neutral
2 – negative
