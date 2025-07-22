\# Neural Network from Scratch 🧠🧮



This project implements a simple feedforward neural network \*\*from scratch\*\* in Python without using high-level deep learning libraries like TensorFlow or PyTorch.



It demonstrates how core concepts such as \*\*weight initialization\*\*, \*\*forward propagation\*\*, \*\*sigmoid activation\*\*, and \*\*backpropagation\*\* work in a fully manual way.



---



\## ✨ Features



\- Pure Python implementation (no deep learning frameworks)

\- Supports multiple hidden layers

\- Trained on:

&nbsp; - 🌸 Iris Dataset

&nbsp; - ✍️ MNIST Dataset (test sample)

\- Evaluates model performance using accuracy score



---



\## 🗂️ Project Structure



| File | Description |

|------|-------------|

| `generate\_w()` | Initializes weights for all layers |

| `generate\_Nodes()` | Initializes nodes structure with values |

| `sigmoid()` | Sigmoid activation function |

| `forward()` | Implements forward propagation |

| `backward()` | Backpropagation to update weights |

| `iris\_loader()` | Loads and preprocesses Iris dataset |

| `mnist\_loader()` | Loads and preprocesses MNIST dataset |

| `train\_loop()` | Runs the training loop |

| `evaluate()` | Calculates accuracy |



---



\## 📊 Results



\- \*\*Iris Dataset:\*\*  

&nbsp; Accuracy ≈ (example: 96% after 20 iterations, 4 hidden nodes, η=5)



\- \*\*MNIST Dataset:\*\*  

&nbsp; Accuracy ≈ (example: depends on subset size, η=5)



---



\## 🧪 Requirements



\- Python ≥ 3.7

\- `numpy`

\- `pandas`

\- `scikit-learn`



Install them with:

```bash

pip install numpy pandas scikit-learn



