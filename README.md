# MNIST_HANDWRITTEN_DIGITS_PCA
Predictive Modeling

Recognition of hand-written digits using PCA on MNIST dataset

This project was implemented with two other colleagues.

Principal Component Analysis allows us to get the essence of larger datasets by transforming them into small datasets by using statistical measures, allowing us to easily visualize and analyze the data and at the same time, minimizing the information loss.

Along with high dimensionality, images contain lot of patterns. PCA helps in retaining such patterns and improves the computational speed by reducing the dimensions.

A parallelization approach like multithreading was implemented while working on the dataset for PCA.

Since the dataset is of an image, it is a high dimensional one as images contains pixel values in the form of matrix.

There were 60,000 samples for training and 10,000 for testing.

Each image was of size 28*28 pixels which was flattened to 784 dimensions.

Our target variable’s a categorical variable with 10 classes labelled 0 to 9.

Since the images were in grey scale, it were converted into binary by normalizing(i.e., dividing it by 255. Gray scale image pixel value = 0 to 255).

A simple neural network model was implemented as a part of our architecture where we used 6 layers: 3 dense and 3 dropout.

An accuracy of 98% was achieved.

To run the model, download the data set, run the ipynb notebook. Please install the required libraries before running the model.

The dataset was downloaded from https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

The columns were renamed from pixel0 to pixel783 for an easy interpretation.
