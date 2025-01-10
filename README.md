# Fashion MNIST Image Classification

This project demonstrates the loading, preprocessing, and visualization of the Fashion MNIST dataset using TensorFlow and Keras. It prepares the dataset for training machine learning models to classify fashion items into different categories. The dataset consists of grayscale images of clothing items, and each image is labeled with one of ten classes.

# Project Overview

Dataset: Fashion MNIST
Images: 28x28 pixel grayscale images of fashion items (e.g., T-shirts, shoes, dresses).
Classes: 10 categories of clothing items:
  T-shirt/top
  Trouser
  Pullover
  Dress
  Coat
  Sandal
  Shirt
  Sneaker
  Bag
  Ankle boot

# How It Works

1. Loading the Dataset
The Fashion MNIST dataset is loaded using the keras.datasets.fashion_mnist API, which returns the training and testing datasets. The training set contains 60,000 images, and the test set contains 10,000 images.

2. Preprocessing the Data
The pixel values of the images are normalized by dividing them by 255 to scale them to the range [0, 1].
The images are then prepared for visualization and model input.

3. Visualization
The first image from the training dataset is displayed.
A grid of 25 training images is shown with their corresponding labels.
