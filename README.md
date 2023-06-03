# micrograd
## A beginner's implementation of Andrej Karpathy's micrograd

This is an implementation of [micrograd](https://github.com/karpathy/micrograd) following Andrej Karpathy's [Neural Networks - Zero to Hero](https://www.youtube.com/watch?v=VMj-3S1tku0) series on YouTube.

## Learning Points from the Video Tutorial
Much of the video tutorial focuses on backpropagation. Some learning points include:
- Basics of backpropagation
- How to use the Chain Rule to calculate local gradients at each input node
- How to build a simple Neural Network from scratch (without using any Deep Learning Framework)

## Files in this repository
- engine.py - implementation of a `Value` class, similar to PyTorch's `Tensor` class
- nn.py - implementation of `Neuron` and `Layer` classes to build a simple Neural Network.
- micrograd.ipynb - notebook with a worked example showing how the backprop engine works