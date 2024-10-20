# Cats vs Dogs Classification with SVM

This project implements a Support Vector Machine (SVM) to classify images of cats and dogs from the Kaggle dataset. The project includes data preprocessing, feature extraction, model training, and evaluation. 

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Introduction

The aim of this project is to create a machine learning model that can accurately classify images as either a cat or a dog. A Support Vector Machine (SVM) is used for its robustness in binary classification tasks, making it suitable for this dataset.

## Dataset

The dataset used in this project is the Cats vs Dogs dataset from Kaggle. It contains 25,000 images of cats and dogs, which are divided into a training set and a testing set.

- **Dataset Link**: [Kaggle Cats vs Dogs Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)

You will need to sign up for a Kaggle account to access the dataset.

## Installation

### Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- OpenCV
- Jupyter Notebook (optional)

### Install Dependencies

Install the required Python packages using pip:

Ensure you have all necessary dependencies installed. You can create a `requirements.txt` file with:

```
numpy
pandas
scikit-learn
opencv-python
```

## Usage

### Data Preprocessing

1. Download and extract the dataset from Kaggle.
2. Place the images in the `data/train` directory for training and `data/test` directory for testing.
3. Run the data preprocessing script to resize images and extract features.

### Train the SVM Model

Run the training script to train the SVM model on the preprocessed data:

### Evaluate the Model

Run the evaluation script to test the model's accuracy on the test data:

## Results

The SVM model achieved high accuracy in classifying the images. Detailed results, including precision, recall, and F1 score.


---
