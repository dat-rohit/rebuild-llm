# LLMs From Scratch


This is my personal training repository where I follow along with Sebastian Raschka's "Large Language Models From Scratch" book to understand the fundamental concepts behind LLMs.
Goal is to understand tokenization, attention, transformer architecture.

> **Note**: This is an incomplete work in progress implementation meant for educational purposes only. For the official and complete implementation, please refer to the [original repository](https://github.com/rasbt/LLMs-from-scratch).

## Repository Structure

### Chapter 2: Data Preparation
Implementation of basic text processing and tokenization techniques:
- Text loading and preprocessing
- Tokenization implementation

### Chapter 3: Attention Mechanism
Deep dive into the attention mechanism implementation:
- Computing attention scores with dot product attention
- Multi-head attention with trainable weights
- Causal attention masking for autoregressive models

### Chapter 4: GPT Architecture
Complete implementation of a GPT-style model:
- Token and positional embeddings
- Layer normalization
- Feed-forward network with GELU activation
- Transformer blocks

### Chapter 5: Training Pipeline
Training utilities and procedures:
- Data loading and batch preparation
- Token processing utilities
- Training configuration


Citation
```
Raschka, Sebastian. Build A Large Language Model (From Scratch). Manning, 2024. ISBN: 978-1633437166.
```
