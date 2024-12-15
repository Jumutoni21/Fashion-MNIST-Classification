Fashion-MNIST-Classification

**Project Overview**

This project implements a Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset using both Python and R. 
The model architecture consists of six layers, designed to effectively learn and categorize fashion items.

**How to Run the Code**

**Python**

Ensure Python is installed (version 3.6 or higher).

Install the required libraries: pip install keras tensorflow numpy.

Run python index.py to train the model and make predictions.

**R**

Install R and RStudio.

Install the necessary libraries by running the following commands:

install.packages("keras")

install.packages("tensorflow")

Open index.R in RStudio and run the code.

**Code Explanation**

The CNN consists of:

Three Convolutional Layers with ReLU activation

Two MaxPooling layers for down-sampling

A Dense layer followed by a final Softmax layer for classification

**Output**

Predictions are made on two test images from the Fashion MNIST dataset.
