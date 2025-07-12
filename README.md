# Iris Flower Classifier

A simple machine learning project that trains a Logistic Regression model on the classic Iris dataset to classify iris species based on petal dimensions. The repository includes data preprocessing, model training, evaluation, and visualization of decision boundaries.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Evaluation](#evaluation)
- [Visualization](#visualization)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Description

This project demonstrates how to build a simple classification model using scikit-learn. We use a Logistic Regression classifier to predict iris species (setosa, versicolor, virginica) based on petal length and petal width. The code covers data loading, train-test splitting, feature scaling, model training, performance evaluation, and plotting decision boundaries.

## Features

- Load the Iris dataset from `scikit-learn`  
- Split data into training and test sets (80/20)  
- Standardize features using `StandardScaler`  
- Train a one-vs-rest Logistic Regression model  
- Evaluate precision and display classification report  
- Visualize decision boundaries with Matplotlib

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/iris-flower-classifier.git
   cd iris-flower-classifier
