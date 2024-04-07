
# Gold Price Prediction using Machine Learning with Python

## Overview

This repository contains a Python script to predict gold prices using machine learning. The script utilizes historical gold price data obtained from Yahoo Finance, performs data preprocessing, trains a linear regression model, and visualizes the predictions against the actual gold prices.


## About the Project

The main objective of this project is to predict gold prices based on historical price data using a linear regression model. The script fetches historical gold price data from Yahoo Finance, calculates daily returns, and trains a linear regression model to predict future returns.

## Dataset

The dataset used in this project is historical gold price data obtained from Yahoo Finance, covering the period from January 1, 2001, to June 27, 2023.

## Getting Started

### Prerequisites

Before running the script, ensure you have the following installed:

- Python (3.x recommended)
- pandas
- numpy
- yfinance
- scikit-learn
- matplotlib

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/gold-price-prediction.git
cd gold-price-prediction
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

## Data Collection and Preprocessing

The script fetches historical gold price data from Yahoo Finance, calculates daily returns, and removes any missing values to prepare the data for model training.

## Model Training and Prediction

A linear regression model is trained using the lagged daily returns as the independent variable and the current daily returns as the dependent variable. The trained model is used to predict future returns.

## Visualization

The script visualizes the actual and predicted gold prices using matplotlib to provide a clear comparison between the model's predictions and the actual prices.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## IMAGES


![image](https://github.com/AISHWARYAAU/Gold-Price-Prediction-using-ML/assets/91381783/7c765e9a-0aaa-49c2-9b65-680bcb406364)


