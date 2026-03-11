# Seq2Seq Text Summarizer

This project is a simple implementation of an **abstractive text summarization model using a Seq2Seq architecture with attention**, built from scratch in **PyTorch**. The purpose of this project is to understand how encoder–decoder models work before moving on to more advanced architectures like Transformers.

The model takes a piece of text as input and tries to generate a shorter summary of it. It uses a **Bidirectional GRU encoder**, an **attention mechanism**, and a **GRU decoder** to generate the summary word by word.

## What I implemented

* Seq2Seq architecture using RNNs
* Bahdanau-style attention
* Custom vocabulary and tokenization
* Attention Mask for Padding tokens 
* Batched training with padding
* Training loop using PyTorch
* Attention Heatmaps

## Tools used

* Python
* PyTorch
* NLTK
* Jupyter Notebook

## Goal of this project

The main goal of this project was to **learn how seq2seq models and attention work internally** by implementing everything from scratch instead of using pretrained models or high-level libraries. This project is mainly for **learning and experimentation**, not a production-level summarization system.
