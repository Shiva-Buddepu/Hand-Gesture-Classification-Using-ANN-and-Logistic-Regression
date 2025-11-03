# Hand Gesture Classification Using ANN and Logistic Regression

This project focuses on classifying **hand gestures (digits 0–9)** using **Logistic Regression** and **Artificial Neural Networks (ANNs)**.  
It demonstrates the evolution from traditional machine learning to deep learning techniques on a **custom Sign Language dataset**.

---

## Project Workflow

### 1. Data Overview
- Loaded and visualized `.npy` image data.
- Checked dataset balance and dimensions.

### 2. Logistic Regression Implementation
- Built a custom computation graph.
- **Steps:**
  - Initialize parameters  
  - Forward propagation  
  - Sigmoid activation  
  - Compute loss and cost function  
  - Backpropagation  
  - Parameter updates using gradient descent  
- Compared results with `sklearn`’s built-in Logistic Regression model.

### 3. Artificial Neural Network (ANN)
- Implemented from scratch a **2-layer neural network**:
  - Input → Hidden (ReLU) → Output (Sigmoid)
- Defined:
  - Weight and bias initialization  
  - Forward and backward propagation  
  - Cost function and updates  
  - Prediction and accuracy computation

### 4. Deep Learning with Keras
- Built a multi-layer ANN using **Keras Sequential API**.
- Tuned hyperparameters such as epochs, learning rate, and batch size.
- Evaluated model accuracy and loss across multiple runs.

---
## Dataset Overview

- **Dataset Source:** [Kaggle – Deep Learning Tutorial for Beginners](https://www.kaggle.com/code/kanncaa1/deep-learning-tutorial-for-beginners/input)
- **Image Size:** 64 × 64  
- **Color Space:** Grayscale  
- **File Format:** `.npy`  
- **Number of Classes:** 10 (Digits: 0–9)  
- **Number of Participants:** 218  
- **Samples per Participant:** 10  
- **Additional Info:** Includes a new 27-class sign language dataset with diverse backgrounds for further experiments.

---
