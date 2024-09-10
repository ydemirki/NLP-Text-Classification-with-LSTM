# NLP Text Classification with LSTM

This repository contains a simple implementation of an LSTM (Long Short-Term Memory) model for text classification. The model processes sequences of tokenized text and predicts the class label.

## Model Structure

- **Embedding Layer**: Converts input tokens into dense vector representations of size `embedding_dim`.
- **LSTM Layer**: Processes the sequence of word embeddings and captures long-term dependencies using LSTM units with a hidden size of `hidden_dim`.
- **Fully Connected Layer**: Maps the final LSTM hidden state to the output classes (`output_dim`).

## Loss Function and Optimizer

- **Loss Function**: Cross-Entropy Loss for multi-class classification.
- **Optimizer**: Adam optimizer.

