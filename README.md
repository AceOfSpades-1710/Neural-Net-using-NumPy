# MNIST Neural Network from Scratch (NumPy Only)

This project implements a simple feedforward neural network **from scratch** using only **NumPy**, to classify handwritten digits from the **MNIST dataset**. No high-level libraries like TensorFlow or Keras are used—just raw Python and NumPy to build and train the model.

## 🔍 Project Overview

The goal of this project is to understand the fundamentals of how neural networks work internally by manually implementing:

- Forward propagation
- Backpropagation
- Weight and bias updates
- Mini-batch gradient descent
- Activation functions (ReLU, Sigmoid, Softmax)
- Loss functions (Cross-Entropy)

This educational project focuses on **clarity** and **comprehensibility**, offering a hands-on understanding of the mechanics behind training a neural network.

## 📊 Results

- Achieved a **final accuracy of 88.47%** on the MNIST test dataset.
- This was obtained after several iterations of optimization and parameter tuning.
- No external ML frameworks were used—everything was coded manually using NumPy.

## 🧠 Network Architecture

- Input Layer: 784 neurons (28x28 pixels flattened)
- Hidden Layers: 1 or 2 layers with adjustable neurons (e.g., 128, 64)
- Output Layer: 10 neurons (one for each digit 0–9)
- Activations: ReLU (hidden), Softmax (output)
- Loss Function: Cross-Entropy

## ⚙️ Requirements

- Python 3.x
- NumPy
- Matplotlib (optional, for visualizations)

You can install dependencies via:

```bash
pip install numpy matplotlib
```

---
## 🧪 Screenshots

![Screen Shot 2025-05-30 at 1 16 47 AM](https://github.com/user-attachments/assets/74dd9bb0-55cc-4c06-b0d1-748857a22995)

![Screen Shot 2025-05-30 at 1 17 03 AM](https://github.com/user-attachments/assets/32aaadcb-c084-400d-b1ec-38eb76d4e1c7)

![Screen Shot 2025-05-30 at 1 17 24 AM](https://github.com/user-attachments/assets/04a5ae98-50a8-4d56-bc60-445c4f2c2c0d)



