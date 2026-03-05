**Deep Learning Email Spam Classifier**
This project implements an end-to-end Natural Language Processing (NLP) pipeline to classify emails as "Spam" or "Ham" (Safe). By utilizing a Long Short-Term Memory (LSTM) architecture, the model goes beyond simple keyword matching to understand the sequential context and intent behind email text.

- Project Overview
As part of my ongoing studies in Robotics and Intelligent Systems, I developed this project to master the fundamentals of text preprocessing, word embeddings, and recurrent neural network architectures.

- Key Features
Text Preprocessing: Custom cleaning pipeline to handle punctuation removal and tokenization.
Semantic Embeddings: Uses a 32-dimensional embedding space to map word relationships.
Sequential Learning: An LSTM layer with 16 hidden units to capture long-range dependencies in text.
Optimized Training: Implements EarlyStopping and ReduceLROnPlateau callbacks to prevent overfitting and fine-tune the learning rate.

- Technical Stack
Language: Python
Environment: Google Colab 
Libraries: TensorFlow, Keras, Pandas, NumPy, Scikit-learn

- Learning Outcomes
Through this project, I gained a deeper understanding of:
Distributional Semantics: How high-dimensional vectors (Embeddings) allow computers to "mathematically" relate words like "Win" and "Prize".
Temporal Dependencies: Why LSTMs are superior to standard Feed-Forward networks for text, as they maintain a "memory" of previous tokens.
Training Dynamics: The importance of monitoring validation loss to trigger early stopping, ensuring the model generalizes well to unseen data.


