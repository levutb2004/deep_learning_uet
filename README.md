# Deep Learning Final Project
Text multi label classification using LSTM, BiLSTM+CNN and BERT

The BiLSTM+CNN model in this project utilizes pre-trained word embeddings from the PhoW2V model. PhoW2V is a Vietnamese word2vec model trained on a large corpus of Vietnamese text. It provides high-quality word embeddings, which help the BiLSTM+CNN architecture effectively capture semantic relationships in text data.

By using PhoW2V embeddings, our model benefits from the semantic richness encoded in these pre-trained vectors, which improves the model's performance on various natural language processing tasks, including text classification, sentiment analysis, and more. The embeddings are used as input features for the BiLSTM and CNN layers, allowing the model to leverage both sequential and spatial features of the text.

For more details on how PhoW2V was trained and how to use it, please refer to the official [PhoW2V repository](https://github.com/datquocnguyen/PhoW2V).
