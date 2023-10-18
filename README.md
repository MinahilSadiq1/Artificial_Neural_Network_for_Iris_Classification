# Artificial_Neural_Network_for_Iris_Dataset
This project explores the use of different neural network architectures on the Iris dataset to classify flower species. The dataset is sourced from Kaggle.

## Table of Contents:
- [Installation](#installation)
- [Usage](#usage)
- [Model Architectures](#model-architectures)
- [Results](#results)

## Installation:
Ensure you have the required libraries installed:
- `numpy`
- `keras`
- `scikit-learn`
- `IPython`
You can install them using pip:
```bash
  pip install numpy
```
But mostly in Google colab, these libraries are availabe and requirements are satisfied. But in case, any library does not found, you can downnload it using "pip" statement just shown in above line.

## Usage:
Clone this repository to your local machine using this command: 
```bash
git clone https://github.com/MinahilSadiq1/Artificial_Neural_Network_for_Iris_Dataset.git
```

## Model Architecture:
Three neural network architectures are develp in it using different combinations of activation functions:
For all three architectures, at Input layer ReLU is used , and for Output layer Softmax is used , but for first architecture, we used Sigmoid activation at hidden layer, for second architecture, we used Tanh at hidden layer. And for third, we used Linear activation function at hidden layer.

### Sigmoid Model:
Input layer with 10 neurons (ReLU activation)
Hidden layer with 8 neurons (Sigmoid activation)
Output layer with 3 neurons (Softmax activation)

### Tanh Model:
Input layer with 10 neurons (ReLU activation)
Hidden layer with 8 neurons (Tanh activation)
Output layer with 3 neurons (Softmax activation)

### Linear Model:
Input layer with 10 neurons (ReLU activation)
Hidden layer with 8 neurons (Linear activation)
Output layer with 3 neurons (Softmax activation)

## Results
The models' performance is evaluated on a test set. After training and evaluating each architecture, you should see a summary of the accuracies for each activation function.
