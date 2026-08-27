# Micrograd from Scratch

A custom, scalar-level autograd engine and neural network library built from scratch in python

This project implements backpropagation over a dynamically built computational graph to train a simple Multi-Layer Perceptron (MLP). It was built to develop a first-principles understanding of neural network calculus and gradient descent.

**Core Features:**
* Custom `Value` object class with engineered dunder methods (`__add__`, `__mul__`, etc.) to track mathematical operations.
* Topological sorting algorithm to execute the backward pass and apply the chain rule automatically.
* Graphviz integration to visually render the forward/backward computational trees.
* A custom neural network module (`Neuron`, `Layer`, `MLP`) trained using standard gradient descent.

Acknowledgments
This project was built by following Andrej Karpathy's exceptional "Neural Networks: Zero to Hero" series. Rebuilding this autograd engine was an active exercise to deeply internalize the calculus, chain rule mechanics, and topological sorting algorithms that power modern deep learning.
