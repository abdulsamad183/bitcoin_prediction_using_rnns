# Bitcoin Opening Price Prediction

This project aims to predict the opening price of Bitcoin in USD using an LSTM (Long Short-Term Memory) neural network. The model is trained on historical Bitcoin opening prices from February 15th, 2017 to November 6th, 2021, and tested against actual prices from November 7th, 2021 to February 15th, 2022, spanning 100 days.

## Project Overview

The main goal of this project is to leverage deep learning techniques to forecast the opening price of Bitcoin. LSTM networks are particularly suitable for time series forecasting due to their ability to capture long-term dependencies and patterns.

## Dataset

The dataset used for this project consists of historical Bitcoin opening prices in USD. It spans from February 15th, 2017 to February 15th, 2022.

## Model Training

The LSTM model is trained using the historical opening prices of Bitcoin. The training data ranges from February 15th, 2017 to November 6th, 2021. During training, the model learns to predict the opening price based on past price data.

## Model Evaluation

The trained model is evaluated on its ability to predict Bitcoin opening prices for the period from November 7th, 2021 to February 15th, 2022. Evaluation metrics such as mean squared error (MSE) is calculated to assess the accuracy of the predictions. The final mean squared error achieved is 0.0007303872262127697.

## Results

The results of the model are plotted between actual bitcoin price and predicted bitcoin price.

## Getting Started

To replicate the experiment or explore the code:

1. Clone this repository.
2. Install the necessary dependencies.
3. Run the provided scripts or notebooks to train the model and evaluate its performance.

## Dependencies

- Python 3.x
- TensorFlow
- NumPy
- Pandas
- Matplotlib (for visualization)

## Files Description

- `train_model.ipynb`: Jupyter notebook containing the code for model training.
- `test_model.ipynb`: Jupyter notebook containing the code for model evaluation.
- `train.csv`: CSV file containing the historical Bitcoin opening prices for training.
- `test.csv`: CSV file containing the historical Bitcoin opening prices for testing.


