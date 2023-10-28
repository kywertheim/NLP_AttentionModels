# NLP_AttentionModels

Context: I completed these guided programming exercises during the Coursera course entitled Natural Language Processing with Attention Models.

1. C4_W1_Assignment.ipynb: This notebook records the steps taken to build an English-to-German neural machine translation model. The decoder (LSTMs) uses the scaled dot product attention mechanism to access the entire encoded input sentence returned by the encoder (LSTM). Tokenisation is based on subword representations. Training is assisted by bucketing. Decoding is based on sampling or Minimum Bayes Risk decoding.

2. C4_W2_Assignment.ipynb: This notebook records the steps taken to build a text summariser. The model is a transformer decoder using the masked self-attention (autoregressive or causal attention) mechanism.

3. C4_W3_Assignment.ipynb: This notebook records the steps taken to build a question answering system. The model is a transformer encoder (BERT).

4. C4_W4_Assignment.ipynb: This notebook records the steps taken to build a chatbot. The model is a reformer: a transformer decoder enhanced by reversible layers and locality sensitive hashing.
