# Attention Is All You Need

This Jupyter notebook implements a basic bigram language model from scratch using PyTorch. It demonstrates the fundamentals of language modeling by training on Shakespeare's text and generating new sequences.

## Prerequisites

- Python 3.x
- PyTorch
- Jupyter Notebook

## Notebook Flow

1. **Data Loading**: Downloads and loads Shakespeare's text dataset.
2. **Preprocessing**: Encodes text into tokens, creates training/validation splits, and defines batch generation.
3. **Model Definition**: Builds a BigramLanguageModel with token and position embeddings.
4. **Training**: Trains the model using cross-entropy loss and AdamW optimizer.
5. **Generation**: Uses the trained model to generate new text sequences.

## How to Run

1. Install dependencies: `pip install torch`
2. Open the notebook: `jupyter notebook gpt_scratch.ipynb`
3. Execute cells sequentially to follow the flow above.

## Key Concepts

- Character-level tokenization
- Embedding layers for tokens and positions
- Bigram prediction with softmax
- Autoregressive text generation