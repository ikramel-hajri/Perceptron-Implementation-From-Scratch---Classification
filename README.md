# Perceptron-Implementation-From-Scratch---Classification
Implementation the Perceptron model to predict the form of a cancer (1: malignant, 0: benign), based on 7 features. The data set has 10,000 records. Each record has 7 quantitative features. The name of the target variable is “cancer_form”.

# Cancer Classification Project

## Overview

This repository hosts a cancer classification project that utilizes a Perceptron model for binary classification. The goal of this project is to predict whether a given set of features corresponds to a benign or malignant tumor. The model is trained on a labeled dataset of cancer samples and their respective features.

## Project Structure

The project is organized into the following sections:

- **Data Loading and Preprocessing**: In this section, we load and preprocess the dataset, which involves feature scaling and data splitting into training, validation, and testing sets.

- **Perceptron Model Implementation**: This section defines the components of the Perceptron model, including the sigmoid activation function and binary cross-entropy loss function.

- **Training the Perceptron**: The Perceptron model is trained using the training set, with updates to model parameters performed through gradient descent.

- **Model Evaluation**: The trained model is evaluated on the testing set using accuracy, precision, recall, and F1 score metrics.

