                                          Product Reviews - Self-Attention

## Project Overview
This project implements a self-attention mechanism on an e-commerce product reviews dataset.

## Objectives
- Tokenize product reviews
- Build a vocabulary
- Convert words to token IDs
- Apply an Embedding layer
- Calculate Q, K, and V
- Calculate QKᵀ
- Apply scaling and Softmax
- Calculate Attention × V
- Visualize attention weights using a heatmap
- Identify words receiving the highest attention

## Technologies
- Python
- TensorFlow
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Main Concept
The project demonstrates the Self-Attention mechanism:

Attention(Q,K,V) = Softmax(QKᵀ / √dₖ)V
