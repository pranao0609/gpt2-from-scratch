# GPT2: Rebuilding Transformers from the Ground Up

This project is a faithful reimplementation of OpenAI's GPT-2 architecture entirely from scratch, based on the original paper _"Language Models are Unsupervised Multitask Learners"_ (Radford et al., 2019).

Unlike pre-built libraries, this code constructs each component — from attention mechanisms to multi-layer decoder stacks — using basic building blocks, providing a deep understanding of how modern language models actually work.

---

## Key Features

- Pure implementation of GPT-2
- Implemented using PyTorch from scratch
- Follows architecture described in GPT-2 paper
- Modular, readable codebase
- Supports training and text generation
- Tokenizer (basic or Byte-Pair Encoding)
- Configurable hyperparameters

---

## Architecture Overview

The model includes:
- Token and positional embeddings
- Multi-head self-attention with masking
- Layer normalization and residual connections
- Feed-forward (MLP) sublayers
- Stacked decoder-only transformer blocks

---

