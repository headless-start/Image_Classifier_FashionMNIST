# Fashion MNIST Image Classification

This project demonstrates the loading, preprocessing, and visualization of the Fashion MNIST dataset using TensorFlow and Keras. It prepares the dataset for training machine learning models to classify fashion items into different categories. The dataset consists of grayscale images of clothing items, and each image is labeled with one of ten classes.

# Project Overview

Dataset: Fashion MNIST
Images: 28x28 pixel grayscale images of fashion items (e.g., T-shirts, shoes, dresses).
Classes: 10 categories of clothing items:
  1. T-shirt/top
  2. Trouser
  3. Pullover
  4. Dress
  5. Coat
  6. Sandal
  7. Shirt
  8. Sneaker
  9. Bag
  10. Ankle boot

# How It Works

1. Loading the Dataset
The Fashion MNIST dataset is loaded using the keras.datasets.fashion_mnist API, which returns the training and testing datasets. The training set contains 60,000 images, and the test set contains 10,000 images.

2. Preprocessing the Data
The pixel values of the images are normalized by dividing them by 255 to scale them to the range [0, 1].
The images are then prepared for visualization and model input.

3. Visualization
The first image from the training dataset is displayed.
A grid of 25 training images is shown with their corresponding labels.

4. Labels
The labels represent the type of clothing item in each image. For instance:

0: T-shirt/top
1: Trouser
2: Pullover
... and so on.

# Sample Visualizations

1. First Image in the Dataset:
The first image from the training set is displayed with a color bar, showing the raw pixel data.

3. Grid of 25 Training Images:
A 5x5 grid of the first 25 training images is displayed, with each image labeled according to its class (T-shirt, trouser, dress, etc.).


# System Requirememnts

1.Python 3.6+
2. TensorFlow 2.x (Ensure version of Tensorflow compatible with cuDNN library.)
3. TensorFlow Datasets
4. Matplotlib
5. Pillow (PIL)
6. TensorFlow Docs (optional for visualization)

