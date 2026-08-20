# Deep Learning Overview

## What is Deep Learning?

Deep Learning is a subset of machine learning that uses neural networks with many layers (hence "deep") to learn representations of data.

## Neural Network Architecture

```text
Input Layer → Hidden Layer(s) → Output Layer
  (x₁)      ┌─────────────┐     (ŷ)
  (x₂)  →   │  Weights &   │  →  (ŷ)
  (x₃)      │  Biases      │     (ŷ)
             └─────────────┘
```

## Key Concepts

- **Activation Functions** — ReLU, Sigmoid, Tanh, Softmax
- **Backpropagation** — Algorithm for training neural networks
- **Gradient Descent** — Optimization method
- **Dropout** — Regularization technique

## Popular Architectures

| Architecture | Use Case |
|-------------|----------|
| CNN | Image recognition, computer vision |
| RNN / LSTM | Sequential data, time series |
| Transformer | NLP, now dominant in almost all domains |
| GAN | Image generation |
| Diffusion Models | Image/video generation |

## Frameworks

- [PyTorch](https://pytorch.org/) — Dynamic computation graph
- [TensorFlow](https://www.tensorflow.org/) — Production-ready
- [JAX](https://github.com/google/jax) — High-performance computing

---

!!! note "My Notes"
    Add your personal study notes, experiment logs, and paper summaries here as you progress.
