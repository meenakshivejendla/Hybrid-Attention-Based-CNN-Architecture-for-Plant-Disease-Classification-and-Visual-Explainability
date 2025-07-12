# Hybrid Attention-Based CNN Architecture for Plant Disease Classification and Visual Explainability

## Overview

This repository contains the implementation of a hybrid attention-based Convolutional Neural Network (CNN) designed for plant disease classification. The model not only achieves high accuracy in identifying various plant diseases but also provides visual explainability through attention mechanisms, helping users understand which parts of the image contribute most to the classification decision.

---

## Features

- **Hybrid Attention Mechanism:** Combines spatial and channel-wise attention to enhance feature representation.
- **Plant Disease Classification:** Supports multiple disease categories with high accuracy.
- **Visual Explainability:** Generates attention maps highlighting disease-affected regions on leaves.
- **End-to-End Training:** Easily trainable on standard plant disease datasets.
- **Modular Codebase:** Flexible architecture for experimentation and extension.

---

## Getting Started

### Prerequisites

- Python 3.7+
- PyTorch 1.7+
- torchvision
- numpy
- matplotlib
- OpenCV (optional, for image processing)
- scikit-learn

Install dependencies with:

```bash
pip install torch torchvision numpy matplotlib opencv-python scikit-learn
