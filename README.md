## MNIST-Digit-Recognition

This is a mini project which will analyse the data in a MNIST dataset which stores pixel intensity values instead of being as an image, and it will predict which digit the given set of pixel values can indicate.

-------------------------------------------------------------------------------------------------------------------------------------

## Pre-requisites

For this project, a good understanding of the working of basic machine learning models like linear regression, softmax regression, logistic regression is expected to be able to understand the code. Also a basic understanding of the pandas library, the process of data cleaning must have been understood. Also basic knowledge on the working of neural networks and its respective pre-requisities. 

-------------------------------------------------------------------------------------------------------------------------------------

## Usage 

This project can be used to predict the handwritten digits based on pixel data, hence if images with raw pixel data are present, it can be used here. 

-------------------------------------------------------------------------------------------------------------------------------------

## Description

This project demonstrates a fundamental deep learning workflow:
1.  **Loading and Preparing Data:** Reads image pixel data from CSV files.
2.  **Building a Model:** Creates a sequential neural network with dense layers.
3.  **Training the Model:** Trains the network on the training dataset.
4.  **Making Predictions:** Evaluates the model's performance by making predictions on the test set.

The model is a multi-class classifier that predicts a digit from 0 to 9 based on a 28x28 pixel image.

-------------------------------------------------------------------------------------------------------------------------------------

## Technologies Used
* **TensorFlow & Keras:** For building and training the neural network.
* **NumPy:** For efficient numerical operations.
* **Pandas:** For loading and handling the initial data from CSV files.
* **Matplotlib:** For visualizing the data.
* **Jupyter Notebook:** As the development environment.

-------------------------------------------------------------------------------------------------------------------------------------

## How to Use
1.  Ensure you have all the required libraries installed (`tensorflow`, `numpy`, `pandas`, `matplotlib`).
2.  Clone this repository.
3.  Place the MNIST `train.csv` and `test.csv` files in the same directory.
4.  Run the `neuralnetworksproject.ipynb` notebook in a Jupyter environment. The notebook will handle data loading, model training, and prediction.

-------------------------------------------------------------------------------------------------------------------------------------

## Model Architecture
The model is a simple sequential network with the following layers:

* **Input Layer:** Flattens the 28x28 image into a 784-element vector.
* **Hidden Layer 1:** Dense layer with 25 neurons and **ReLU** activation.
* **Hidden Layer 2:** Dense layer with 15 neurons and **ReLU** activation.
* **Output Layer:** Dense layer with 10 neurons (one for each digit) and **Softmax** activation.

  
# Attributions

Digit Recognition Pixel Values Dataset - by Wasiq Ali on Kaggle 






