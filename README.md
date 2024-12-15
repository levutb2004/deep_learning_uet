# Deep Learning Final Project
| Họ và Tên           | MSSV      |
|---------------------|-----------|
| Phạm Đăng Phong     | 22022614  | 
| Chu Thân Nhất       | 22022578  | 
| Bàn Hoàng Sơn       | 22022651  | 
| Nguyễn Bảo Sơn      | 22022613  | 
| Cao Đặng Quốc Vương | 22022601  | 
| Lê Nguyên Vũ        | 22022544  | 
## Text multi label classification using LSTM, BiLSTM+CNN and BERT

The BiLSTM+CNN model in this project utilizes pre-trained word embeddings from the PhoW2V model. PhoW2V is a Vietnamese word2vec model trained on a large corpus of Vietnamese text. It provides high-quality word embeddings, which help the BiLSTM+CNN architecture effectively capture semantic relationships in text data.

By using PhoW2V embeddings, our model benefits from the semantic richness encoded in these pre-trained vectors, which improves the model's performance on various natural language processing tasks, including text classification, sentiment analysis, and more. The embeddings are used as input features for the BiLSTM and CNN layers, allowing the model to leverage both sequential and spatial features of the text.

For more details on how PhoW2V was trained and how to use it, please refer to the official [PhoW2V repository](https://github.com/datquocnguyen/PhoW2V).
