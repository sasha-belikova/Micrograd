# Micrograd

A simple implementation of the **Micrograd** algorithm in Python, built to understand how automatic differentiation and backpropagation work under the hood.

## What is Micrograd?

Micrograd is a small automatic differentiation engine that calculates gradients using backpropagation.

Instead of manually calculating derivatives, the program builds a computational graph of operations and then propagates gradients through this graph using the chain rule.


## Project Structure

```text
Micrograd/
│
├── value.py
├── neuron.py
├── graph_visual.py
└── requierments.txt
```

## Installation

```bash
git clone https://github.com/sasha-belikova/Micrograd.git
cd Micrograd
```
```bash
pip install -r requierments.txt
```

## Reference

This implementation is based on the ideas presented in Andrej Karpathy's **Micrograd** project and his *Neural Networks: Zero to Hero* tutorial.
