# Deep Learning Architectures

Implementation of core deep learning architectures from scratch and using PyTorch, including CNNs, RNNs, LSTMs, Transformers, GANs, VAEs and GNNs.

---

## Overview

This repository contains a collection of practical implementations of fundamental neural network architectures developed as part of applied deep learning labs.

The focus is on:
- Understanding internal mechanics of each architecture
- Implementing key components from scratch (e.g. convolution, RNN/LSTM cells, self-attention)
- Training models on controlled tasks and datasets

This is not a benchmark or production-oriented repository, but a technical exploration of model design and behavior.

---

## Architectures

### Convolutional Neural Networks (CNN)
- Naive 2D convolution layer implemented from scratch
- Understanding of convolution mechanics and feature extraction

### Recurrent Neural Networks (RNN / LSTM)
- RNN cell implemented from scratch
- LSTM cell with gating mechanisms (input, forget, output)
- Sequence modeling on synthetic time-series data

### Transformers
- Self-attention mechanism implemented manually
- Transformer encoder applied to sequence classification tasks

### Generative Models

#### Generative Adversarial Networks (GAN)
- Toy GAN for understanding adversarial training dynamics
- MNIST-based generation experiments

#### Variational Autoencoders (VAE)
- VAE implementation with latent variable modeling
- Trained on MNIST for representation learning and generation

### Graph Neural Networks (GNN)
- Graph learning using PyTorch Geometric
- Experiments on Open Graph Benchmark (OGB) datasets

---

## Repository Structure
