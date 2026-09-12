# rb_gpt
A character-level GPT (Generative Pre-trained Transformer) language model built from scratch in PyTorch. This project implements core Transformer architecture concepts—including Multi-Head Self-Attention, causal masking, layer normalization, and residual connections—trained on custom text data.

Decoder-Only Transformer Architecture: Custom implementation of Multi-Head Self-Attention (Head, MultiHeadAttention) with causal masking to prevent attending to future tokens.

Token & Positional Embeddings: Combines learned token embeddings with spatial positional embeddings.

Training & Evaluation Pipeline: Features full evaluation steps estimating train and validation loss over specified iterations.

Checkpointing & Early Stopping: Built-in mechanisms to track best validation loss, automatically save model states (.pt), and trigger early stopping if the model begins to overfit or stops improving.

Text Generation Interface: Simple generation function that samples top next-token probabilities given a starting context sequence.
