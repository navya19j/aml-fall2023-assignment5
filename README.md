# LeNet-5 CNN on CIFAR-10

**Columbia University — Applied Machine Learning (Fall 2023), Homework 5**

Implements LeNet-5 from scratch in PyTorch and trains it on CIFAR-10 for multi-class image classification.

## Contents

- `AML_HW5_Questions.ipynb` — full implementation: model definition, training loop, evaluation, plots

## Setup

```bash
pip install torch torchvision jupyter matplotlib

jupyter notebook AML_HW5_Questions.ipynb
```

Requires Python 3.8+. GPU recommended but not required for this scale.

## Topics

- LeNet-5 architecture (conv → pool → conv → pool → fc → fc → fc)
- Training on CIFAR-10 (10-class, 50k train / 10k test)
- Loss curves, accuracy reporting, hyperparameter analysis
