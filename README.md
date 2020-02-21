# Product-Matching
This repository tackles the task of sequence-matching using various NLP approaches such as neural language modelling, information retrieval,  and count based TF-IDF approach. 

The first notebook prepares retailer online data of more than seventy thousand webpages from a web-scrapping tool. It displays the text data manipulation from web requests.

The second notebook contains the preparation of retailer and manufacturer mapped data for further modelling. Data cleaning and exploration is used here.

Third notebook is a baseline model which uses a character level TF-IDF model to calculate the validate the accuracy of the model using an information retrieval system.

Fourth notebook uses an LSTM encoder-decoder model with Attention mechanism to transform retailer sequences to manufacture sequences. An Information Retrieval system is designed using TF-IDF and Doc2Vec system validate the sequence transformation. The information retrieval system is designed using cosine similarity and returns most similar sequences based on the scores.
