# Predicting Rainfall Using a PyTorch Neural Network

## Overview
This project uses a 3-layer PyTorch neural network to predict next-day rainfall based on weather data from the **[Weather Dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)**. The model was trained and evaluated on an 80-20 train-test split, achieving an accuracy of **78%**.

## Key Steps:
- **Data Preprocessing**: Cleaned and processed the dataset, converting categorical values to binary and handling missing values.
- **Model Building**: Developed a neural network using PyTorch with 3 layers to predict whether it will rain the next day.
- **Training**: Trained the model using **BCELoss** and **Adam optimizer** for 1000 epochs.
- **Evaluation**: Achieved a test accuracy of **78%** using a custom accuracy calculation function.

## Technologies Used:
- **PyTorch** for building and training the neural network.
- **Pandas** for data preprocessing.
- **Sklearn** for train-test split.

## Usage:
1. Clone the repository and install necessary dependencies.
2. Preprocess the data and convert it into PyTorch tensors.
3. Train the model by running the training loop.
4. Save and load the model for inference.
5. Evaluate the model on test data to get the accuracy.

