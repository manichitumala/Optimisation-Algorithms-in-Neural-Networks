# 📘 Optimisation Algorithms in Neural Networks

This repository presents a comparative study of optimisation algorithms used in neural network training. The project was developed as part of a machine learning coursework assignment and focuses on understanding how different optimisation methods influence model performance.

---

## 🎯 Project Overview

Training a neural network involves minimising a loss function through gradient-based optimisation. The choice of optimisation algorithm plays a critical role in determining:

- convergence speed  
- training stability  
- model accuracy  
- quality of learned decision boundaries  

This project investigates and compares three widely used optimisation algorithms:

- **Stochastic Gradient Descent (SGD)**  
- **RMSprop**  
- **Adam (Adaptive Moment Estimation)**  

Both theoretical explanations and experimental results are used to analyse how these algorithms behave in practice.

---

## 📊 Objectives

The main objectives of this project are:

- To understand how optimisation algorithms update neural network parameters  
- To compare convergence behaviour using loss curves  
- To evaluate model performance using classification accuracy  
- To visualise decision boundaries for better interpretability  
- To provide practical guidance for selecting optimisation methods  

---

## 🧪 Dataset

The experiments are conducted using the `make_moons` dataset from Scikit-learn.

- Non-linear dataset  
- Two interleaving classes  
- Suitable for visualising complex decision boundaries  

---

## 🧠 Model Architecture

A Multilayer Perceptron (MLP) is implemented **from scratch using NumPy** to ensure transparency and understanding of the training process.

- Input layer: 2 features  
- Hidden Layer 1: 16 neurons (ReLU activation)  
- Hidden Layer 2: 16 neurons (ReLU activation)  
- Output Layer: 1 neuron (Sigmoid activation)  

The architecture is kept constant across all experiments to ensure a fair comparison between optimisation algorithms.

---

## ⚙️ Optimisation Algorithms

### 🔹 Stochastic Gradient Descent (SGD)
- Uses a fixed learning rate  
- Simple and computationally efficient  
- Can exhibit unstable and slow convergence  

---

### 🔹 RMSprop
- Uses adaptive learning rates  
- Improves stability during training  
- Handles varying gradient magnitudes effectively  

---

### 🔹 Adam
- Combines momentum and adaptive learning rates  
- Fast and stable convergence  
- Performs best in most practical scenarios  

---

## 📈 Experimental Results

The algorithms are evaluated using:

- **Training loss curves** → to analyse convergence behaviour  
- **Test accuracy** → to measure model performance  
- **Decision boundaries** → to visualise learned patterns  

### Key Findings

- Adam achieved the fastest convergence and highest accuracy  
- RMSprop provided stable and consistent learning  
- SGD was slower and required careful tuning  

These results highlight the importance of choosing an appropriate optimisation algorithm when training neural networks.

---

## 📂 Repository Structure
