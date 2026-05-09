# part-1-neural-network-analysis

# Neural Network Fundamentals and Training Behavior Analysis

## Objective
The goal of this project is to build and analyze a simple feed-forward neural network using a supervised learning dataset. The project demonstrates:

- Data preprocessing
- Neural network training
- Forward propagation
- Backpropagation
- Hyperparameter experimentation
- - Model evaluation

---

## Dataset
Dataset used: `customer_churn_nn.csv`

The dataset contains customer-related information and predicts whether a customer will churn or not.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## Steps Performed

### 1. Dataset Understanding
- Loaded dataset
- - Checked dataset shape
- Verified missing values
- Examined target variable distribution
- Generated statistical summary

### 2. Data Preprocessing
- Encoded categorical variables
- Scaled numerical features
- Split data into train/test sets

### 3. Neural Network Model
- Input Layer
- Hidden Layers
- ReLU activation
- Sigmoid output layer
- - Binary Crossentropy loss
- Adam optimizer

### 4. Evaluation
- Accuracy
- Loss curves
- Confusion matrix
- Classification report

### 5. Hyperparameter Experiments
Compared:
- Number of layers
- Number of neurons
- Learning rate
- Batch size
- - Activation functions

---

## Results Summary

| Experiment | Accuracy |
|---|---|
| Baseline Model | 85.1% |
| More Neurons | 86.3% |
| Lower Learning Rate | 84.5% |
| Extra Hidden Layer | 87.2% |

---

## Final Reflection

### Role of Weights and Biases
Weights determine the importance of input features, while biases help shift activation values to improve learning flexibility.

### Why Activation Functions are Required
Activation functions introduce non-linearity, enabling neural networks to learn complex patterns.

### Learning Rate Effect
- Too high → unstable training and overshooting
- Too low → very slow convergence

### Underfitting vs Overfitting
The baseline model showed slight underfitting initially. Increasing model complexity improved performance. Excessive epochs slightly increased validation loss, indicating mild overfitting.

---
