---
layout: project
title: "Neural Networks from Scratch"
subtitle: "Building deep learning architectures using only NumPy"
date: "September 2023 - November 2023"
status: "completed"
domain: machine-learning
image: "/images/NeuralNetworks.jpg"
github: "https://github.com/jasonp02/neural-networks"
---

## Overview
Implemented common neural network architectures (MLP, CNN, RNN, LSTM, Transformer) 
using only NumPy, without autograd. This project was undertaken to develop a deep
understanding of how neural networks work at their core, without the abstractions
provided by modern frameworks.

## Technical Details
• Implemented backpropagation from first principles
• Built optimizers (SGD, Adam) and activation functions
• Created custom loss functions and metrics
• Developed data preprocessing pipelines
• Implemented various layer types (Dense, Conv2D, LSTM cells)

<div class="tech-stack">
  <span class="tech-tag">Python</span>
  <span class="tech-tag">NumPy</span>
  <span class="tech-tag">Mathematics</span>
  <span class="tech-tag">Deep Learning</span>
</div>

## Key Learnings
• Deep understanding of tensor operations and neural network fundamentals
• Importance of efficient matrix operations for performance
• Debugging complex mathematical operations
• Value of testing in mathematical software

## Challenges & Solutions
The biggest challenge was implementing backpropagation for complex architectures
like LSTM and Transformers. This was solved by breaking down the computation
graphs and implementing thorough unit tests for each component. 