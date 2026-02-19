# Artificial Neural Network Practice — Problem Statement

## Objective

The objective of this exercise is to understand the working principle of a single neuron (Perceptron) and how an Artificial Neural Network performs binary classification by learning from data.

Instead of using deep learning frameworks, the model must be implemented using basic Python and mathematical operations to observe the learning behavior of a neural unit.

---

## Problem Description

Design and implement a simple Artificial Neural Network (Single Layer Perceptron) that can learn and classify a logical gate pattern.

The model should:

1. Take two binary inputs (x1, x2)
2. Compute weighted sum
3. Apply activation rule
4. Produce a binary output (0 or 1)

The network must learn to represent the **AND logical gate**.

---

## Dataset

| x1 | x2 | Expected Output |
| -- | -- | --------------- |
| 0  | 0  | 0               |
| 0  | 1  | 0               |
| 1  | 0  | 0               |
| 1  | 1  | 1               |

---

## Tasks to Perform

1. Initialize random weights and bias
2. Compute weighted sum:
   z = w1·x1 + w2·x2 + b
3. Apply step activation function
4. Compare predicted output with expected output
5. Update weights based on error
6. Train the perceptron for multiple epochs
7. Calculate classification accuracy
8. Plot the decision boundary

---

## Expected Outcome

After training, the perceptron should correctly classify all input combinations of the AND gate.
The decision boundary plotted on a 2D graph should linearly separate class 0 and class 1.

---

## Learning Outcome

By completing this experiment, the learner should understand:

* What a neuron does mathematically
* How weights influence prediction
* Concept of bias
* Linear separability
* Why single layer networks cannot solve XOR
* Meaning of a decision boundary in machine learning

---

## Extension (Optional)

* Test the model on OR gate
* Try XOR gate and analyze failure
* Replace step function with sigmoid activation
* Implement multi-layer perceptron

---
