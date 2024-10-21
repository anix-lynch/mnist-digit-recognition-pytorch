# mnist-digit-recognition-pytorch
# Handwritten Digit Recognition Using PyTorch

This project uses a deep neural network built with PyTorch to recognize handwritten digits from the MNIST dataset. The MNIST dataset contains 70,000 images of handwritten digits, split into a training set of 60,000 images and a test set of 10,000 images.

## Project Overview

Deep neural networks simulate the way the human brain learns by example. Using a dataset of handwritten digits, the network can learn to recognize patterns and features in the images to classify them correctly.

In this project:

- Data is loaded from the **MNIST** dataset.
- A **deep neural network** is implemented using PyTorch.
- Images from the dataset are visualized using **Matplotlib**.
- The network is trained on 60,000 training images and evaluated on 10,000 test images.
- Performance metrics are generated to evaluate the accuracy of the model.

## Key Features

- **Dataset**: The MNIST dataset with 70,000 grayscale images of size 28x28 pixels, representing digits from 0 to 9.
- **Neural Network**: A deep learning model with multiple layers of neurons, built using PyTorch.
- **Image Visualization**: Matplotlib is used to display some sample images from the MNIST dataset.
- **Model Training**: The network is trained on the dataset using PyTorch's automatic differentiation and optimization features.
- **Testing and Evaluation**: The trained model is tested on the test set, and accuracy is measured.

## Tech Stack

- **PyTorch**: For building and training the deep neural network.
- **Matplotlib**: For visualizing images from the MNIST dataset.

## How to Run

1. Load the MNIST dataset.
2. Preprocess and prepare the data.
3. Build the deep neural network using PyTorch.
4. Train the network on the training set and evaluate its performance on the test set.
5. Visualize sample images and predictions.
