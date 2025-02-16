# Shallow Neural Network for Binary Classification
This project implements a shallow neural network for binary classification using the Diabetes dataset from sklearn. The neural network consists of one hidden layer with 4 neurons and uses ReLU as the activation function. The output layer uses the sigmoid function for classification. The model is trained using binary cross-entropy loss and evaluated on a test set for accuracy. The code is optimized for readability and conciseness.

## Features:
- Uses the load_diabetes dataset for binary classification.
- Binarizes the target variable based on its median.
- Applies standardization to improve training convergence.
- Trains the model using gradient descent with backpropagation.
- Displays loss at intervals during training and provides test accuracy.

## Output Example:
Epoch 0, Loss: 1.4011

Epoch 1000, Loss: 0.4206

Epoch 2000, Loss: 0.4219

Epoch 3000, Loss: 0.3890

Epoch 4000, Loss: 0.3799

Epoch 5000, Loss: 0.3849

Epoch 6000, Loss: 0.3838

Epoch 7000, Loss: 0.3825

Epoch 8000, Loss: 0.3758

Epoch 9000, Loss: 0.3776

Test Accuracy: 0.75


The model achieved a test accuracy of 75%, indicating good performance for binary classification on the given dataset. The loss gradually decreases over time, showing effective learning during training.

