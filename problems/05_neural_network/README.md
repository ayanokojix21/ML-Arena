# 05 Neural Network

## Goal

Build a small feed-forward neural network and compare with a library implementation.

## Dataset

Use `problems/05_neural_network/dataset.csv` (already committed).

- Source: UCI Wine Quality (id=186)
- Shape: 6497 rows, 13 columns
- Targets: `quality` (original score) and `quality_binary` (derived, 1 if quality >= 7 else 0)

This task intentionally uses a non-image tabular dataset.

## Suggested Beginner Issues

- Exploration: Feature scaling checks with loss/accuracy behavior plots.
- Scratch: Implement forward pass, loss, and backprop basics.
- Library: Train MLP baseline with sklearn or PyTorch.

## Target Files by Task Type

- Exploration: exploration/exploration.ipynb
- Scratch training: scratch/training.ipynb
- Library training: library/training.ipynb
