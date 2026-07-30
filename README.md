 # PyTorch & Deep Learning Study Lab

  Welcome! This repository is a personal learning archive for studying
  deep learning fundamentals and their implementation in PyTorch.

  The main purpose of this study is to build a solid foundation for exploring
  computer architecture for AI, including AI accelerators and hardware–software
  co-design. Designing efficient AI hardware requires an understanding of how
  deep learning models, tensor operations, and mathematical computations are
  represented and executed at the software level.

  > Course Credit and Acknowledgement
  >
  > This repository is a personal study fork of
  > Deep Learning Zero to All — Season 2 (PyTorch) (https://github.com/deeplearningzerotoall/PyTorch),
  > created by the Deep Learning Zero to All contributors.
  >
  > The original source code, exercises, course structure, and educational
  > materials belong to their respective authors. My study notes, code changes,
  > and execution results are recorded separately through the commit history.

  ———

  ## Repository Objectives

  - AI Hardware–Software Understanding: Connect high-level PyTorch operations
    and backpropagation algorithms with their underlying hardware execution.

  - Core Fundamentals: Develop an intuitive and mathematical understanding of
    tensors, automatic differentiation, optimization, and other fundamental deep
    learning concepts.

  - Hands-on Implementation: Practice implementing models in PyTorch, ranging
    from basic regression and classification to CNNs and RNNs.

  - Code and Concept Notes: Document implementation details, mathematical
    derivations, observations, and execution behavior directly in Jupyter
    Notebooks.

  ———

   ## Learning Roadmap and Topics

  > The roadmap below follows the original curriculum of
  > [Deep Learning Zero to All — Season 2 (PyTorch)](https://github.com/deeplearningzerotoall/PyTorch).

  ### Part 1: Machine Learning and PyTorch Basics

  - **Lab 01-1:** Tensor Manipulation 1
  - **Lab 01-2:** Tensor Manipulation 2
  - **Lab 02:** Linear Regression
  - **Lab 03:** A Deeper Look at Gradient Descent
  - **Lab 04-1:** Multivariable Linear Regression
  - **Lab 04-2:** Loading Data
  - **Lab 05:** Logistic Regression
  - **Lab 06:** Softmax Classification
  - **Lab 07-1:** Tips
  - **Lab 07-2:** MNIST Introduction

  ### Part 2: Neural Networks

  - **Lab 08-1:** Perceptron
  - **Lab 08-2:** Multilayer Perceptron
  - **Lab 09-1:** ReLU
  - **Lab 09-2:** Weight Initialization
  - **Lab 09-3:** Dropout
  - **Lab 09-4:** Batch Normalization

  ### Part 3: Convolutional Neural Networks

  - **Lab 10-0:** Introduction to Convolutional Neural Networks
  - **Lab 10-1:** Convolution
  - **Lab 10-2:** MNIST CNN
  - **Lab 10-3:** Visdom
  - **Lab 10-4-1:** ImageFolder 1
  - **Lab 10-4-2:** ImageFolder 2
  - **Lab 10-5:** Advanced CNN — VGG
  - **Lab 10-6-1:** Advanced CNN — ResNet 1
  - **Lab 10-6-2:** Advanced CNN — ResNet 2
  - **Lab 10-7:** Next Steps with CNNs

  ### Part 4: Recurrent Neural Networks

  - **Lab 11-0:** Introduction to Recurrent Neural Networks
  - **Lab 11-1:** RNN Basics
  - **Lab 11-2:** RNN Hihello and Character Sequences
  - **Lab 11-3:** Long Sequences
  - **Lab 11-4:** RNN Time Series
  - **Lab 11-5:** RNN Sequence-to-Sequence
  - **Lab 11-6:** PackedSequence

  ## Environment Setup

  The exercises are performed in an isolated and reproducible Docker environment.

  - Framework: PyTorch
  - Runtime: Docker Desktop with the WSL 2 backend
  - Development Interface: Jupyter Notebook
  - Python Environment: Anaconda / Conda
  - Container Image: deeplearningzerotoall/pytorch

  The Docker environment and its dependencies originate from the course project.
  Changes made while completing the exercises are maintained in this fork as
  personal study records.
