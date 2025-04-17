# Hawaii’s Precipitation Time Series Forecasting Using Recurrent Neural Networks

This project develops a **Recurrent Neural Network (RNN)** model to forecast precipitation in **Hawaii** based on historical time series data. The model captures temporal patterns in precipitation using deep learning techniques, with the goal of improving climate and environmental planning.

## 🌧️ Objective

To forecast future precipitation levels in Hawaii by training a time series model on historical data from 1939 to 2024 using Recurrent Neural Networks.

## 📅 Data

- **Source**: National Centers for Environmental Information (NCEI)
- **File**: `Hawaii_precipitation_1939_2024.xlsx`
- The dataset contains monthly precipitation records over an 85-year period.

## 🧠 Methodology

- **Preprocessing**: 
  - Load and clean the Excel dataset
  - Normalize values
  - Structure data into sequences for RNN input

- **Model Architecture**:
  - A basic RNN model implemented using Keras or PyTorch
  - Input: sequences of past precipitation values
  - Output: predicted precipitation for the next time step(s)

- **Evaluation**:
  - Model performance assessed using RMSE and MAE
  - Comparison between different sequence lengths and model parameters

## 🛠️ How to Run

1. **Clone this repository**:

```bash
git clone https://github.com/your-username/hawaii-precipitation-rnn.git
cd hawaii-precipitation-rnn
