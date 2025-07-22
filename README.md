# Neural Network from Scratch 🧠🧮

This project implements a simple feedforward neural network **from scratch** in Python without using high-level deep learning libraries like TensorFlow or PyTorch.

It demonstrates how core concepts such as **weight initialization**, **forward propagation**, **sigmoid activation**, and **backpropagation** work in a fully manual way.

---

## ✨ Features

- Pure Python implementation (no deep learning frameworks)
- Supports multiple hidden layers
- Trained on:
  - 🌸 Iris Dataset
  - ✍️ MNIST Dataset (test sample)
- Evaluates model performance using accuracy score

---

## 🗂️ Project Structure

| File | Description |
|------|-------------|
| `generate_w()` | Initializes weights for all layers |
| `generate_Nodes()` | Initializes nodes structure with values |
| `sigmoid()` | Sigmoid activation function |
| `forward()` | Implements forward propagation |
| `backward()` | Backpropagation to update weights |
| `iris_loader()` | Loads and preprocesses Iris dataset |
| `mnist_loader()` | Loads and preprocesses MNIST dataset |
| `train_loop()` | Runs the training loop |
| `evaluate()` | Calculates accuracy |

---

## 📊 Results

- **Iris Dataset:**  
  Accuracy ≈ (example: 96% after 20 iterations, 4 hidden nodes, η=5)

- **MNIST Dataset:**  
  Accuracy = **100%** after 20 iterations, learning rate = 5, number of hidden nodes = 4, and 3 layers.

---

## 🧪 Requirements

- Python ≥ 3.7
- `numpy`
- `pandas`
- `scikit-learn`

Install them with:
```bash
pip install numpy pandas scikit-learn
