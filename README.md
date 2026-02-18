# Neural Network From Scratch (ANN Basics)

This repository contains my practice implementation of fundamental Artificial Neural Network (ANN) concepts using Python.  
The goal of this project was to understand *how a neural network actually learns*, rather than just using libraries like TensorFlow or PyTorch.

Instead of training on large datasets, I implemented and visualized learning using logical gate classification (AND gate) — a classical starting point in neural network research.

---

## 📌 Concepts Covered
- Perceptron Logic
- Binary Classification
- Decision Boundary
- Linear Separability
- Activation behavior
- Accuracy calculation
- Visualization using Matplotlib

---

## 🧠 What I Learned
This project helped me understand:

• How a neuron makes decisions  
• How input features affect classification  
• Why activation functions matter  
• What a decision boundary actually represents  
• Why early neural networks failed on non-linear problems (like XOR)

---

## 📊 Problem Statement
We simulate a neuron that classifies input pairs (x1, x2) into binary output using an AND logical gate.

| x1 | x2 | Output |
|----|----|------|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

The model attempts to learn a separating line (decision boundary) that correctly classifies the points.

---

## 📈 Visualization
The decision boundary is plotted using Matplotlib to observe how the classifier separates classes in 2D feature space.

---

## 🛠 Tech Stack
- Python
- Numpy
- Matplotlib
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository
   git clone https://github.com/alaukikpachauri/neural-network-from-scratch.git
2. Install dependencies
   pip install -r requirements.txt
3. Run the notebook
   jupyter notebook Ann_assignment.ipynb


---

## 📁 Repository Structure

neural-network-from-scratch/

├── notebooks/
   └── ann_perceptron_and_gate.ipynb


├── docs/
   └── PROBLEM_STATEMENT.md

├── README.md

├── requirements.txt

└── .gitignore


---

## 🔮 Future Work
- Implement XOR classification
- Add sigmoid activation
- Multi-layer perceptron
- Backpropagation
- Gradient descent visualization

---

## 👨‍💻 Author
**Alaukik Pachauri**

Aspiring Machine Learning Engineer | Learning Neural Networks, Transformers & AutoML



