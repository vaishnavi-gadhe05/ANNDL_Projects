# MNIST Classification using CNN, MLP and Reinforcement Learning (DQN)

## Project Description

This project performs a comparative study of three different learning paradigms applied to the MNIST handwritten digit classification problem:

| Model                              | Type                   |
| ---------------------------------- | ---------------------- |
| Convolutional Neural Network (CNN) | Supervised Learning    |
| Multi-Layer Perceptron (MLP)       | Supervised Learning    |
| Deep Q-Network (DQN)               | Reinforcement Learning |

### Goal

To analyze and compare the performance of supervised learning models (CNN, MLP) with a reinforcement learning approach (DQN) for image classification.

---

## Dataset

* Dataset: MNIST Handwritten Digits
* Source: TensorFlow / Keras
* Total Images: **70,000**

  * Training: **60,000**
  * Testing: **10,000**

### Features:

* Image size: **28 × 28 pixels**
* Grayscale images
* Labels: Digits (0–9)

---

## Data Preprocessing

* Normalization: Pixel values scaled to range [0,1]
* CNN Input: Reshaped to (28, 28, 1)
* MLP Input: Flattened to (784)
* Labels: One-hot encoded

---

## Technology Stack

* Programming Language: Python
* Libraries:

  * NumPy
  * Matplotlib
  * TensorFlow / Keras
  * Collections (deque)
  * Random

---

## Models Implemented

### 1. Convolutional Neural Network (CNN)

* Uses convolution layers for feature extraction
* Captures spatial patterns in images
* Highly effective for image classification

---

### 2. Multi-Layer Perceptron (MLP)

* Fully connected neural network
* Uses flattened image input
* Simpler compared to CNN

---

### 3. Deep Q-Network (DQN - Reinforcement Learning)

* Uses Q-learning approach
* Agent learns through reward-based interaction
* Includes:

  * Replay buffer (deque)
  * Epsilon-greedy strategy
  * Exploration vs exploitation

---

## Steps Involved

1. Import Libraries
2. Load MNIST Dataset
3. Data Preprocessing
4. Data Visualization
5. Build CNN Model
6. Build MLP Model
7. Implement DQN Agent
8. Train Models
9. Evaluate Performance
10. Compare Results

---

## Performance Evaluation

* Accuracy
* Loss
* Model comparison

---

## Results

* CNN performs best due to spatial feature extraction
* MLP gives decent performance but lacks spatial awareness
* DQN demonstrates learning via rewards but is less efficient for classification tasks

---

## Execution Process

1. Open the notebook in Jupyter Notebook or Google Colab
2. Install required libraries
3. Run all cells sequentially
4. Observe outputs and model comparisons

---

## Conclusion

* CNN is the most suitable model for image classification tasks
* MLP is simpler but less powerful
* Reinforcement Learning (DQN) is better suited for sequential decision problems rather than direct classification

---

## Applications

* Handwritten digit recognition
* Image classification systems
* Deep learning model comparison studies

---

## Author

Vaishnavi Gadhe

B-tech - Artificial Intelligence and Data science

