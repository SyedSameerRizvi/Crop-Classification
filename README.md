# Crop Classification through Deep Learning

## Overview
In agriculture, the precise recommendation of crops is pivotal in ensuring optimal yield and sustainability. This project leverages deep learning techniques to classify crops based on various soil and environmental factors.

## Problem Statement
The goal of this project is to classify crops using a deep learning model, providing farmers and agricultural experts with data-driven recommendations for optimal crop selection.

## Dataset
The dataset used in this project contains information about key factors affecting crop yield, including:
- **Nitrogen**
- **Phosphorus**
- **Potassium**
- **Temperature**
- **Humidity**
- **pH Value**
- **Rainfall**
- **Crop (target variable)**

The dataset can be found in the `Crop_Recommendation.csv` file.

## Evaluation Metrics
The model's performance is evaluated using the following metrics:
1. Classification Report
2. Confusion Matrix
3. Accuracy Score

## Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Building and training a deep learning model
- Visualizing results and performance metrics

## Tools and Libraries
This project requires the following Python libraries:
- `matplotlib`
- `seaborn`
- `plotly`
- `pandas`
- `numpy`
- `scikit-learn`
- `tensorflow`
- `ipykernel`
- `nbformat==5.10.4`

You can install the required libraries using the following command:
```bash
pip install -r requirements.txt
```

## Usage
- Load the dataset and explore its features.
- Preprocess the data and split it into training and testing sets.
- Build a deep learning model using TensorFlow and Keras.
- Train the model and evaluate its performance using the evaluation metrics mentioned above.
