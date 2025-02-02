Next-Word Prediction using BiLSTM
📌 Overview
This project implements a Next-Word Prediction model using a Bidirectional Long Short-Term Memory (BiLSTM) network. The model is trained on the Medium dataset to predict the most probable next word in a given sentence.

🔍 Features
Uses BiLSTM for sequence prediction
Trained on the Medium dataset
Implements tokenization, padding, and text preprocessing
Supports real-time next-word suggestions

📂 Dataset
The dataset used in this project is the Medium dataset, which consists of articles and textual data from the Medium platform. It is preprocessed for training the BiLSTM model.


🏗️ Technologies Used
Python
TensorFlow/Keras
Natural Language Processing (NLP)
Tokenization (Tokenizer API)
NumPy & Pandas


📊 Model Performance
The model achieves Perplexity: 5.754250081730516 on the validation dataset.
Fine-tuning techniques like dropout, learning rate scheduling, and different embeddings were explored.


✨ Future Improvements
Enhance accuracy with transformer-based models (e.g., GPT, BERT).
Expand dataset for better generalization.
Deploy as a web API or integrate into applications.
