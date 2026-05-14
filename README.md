📖 Overview

This project demonstrates time series forecasting using LSTM (RNN) to predict airline passenger trends. It includes data preprocessing, sequence creation, model training, evaluation, and future forecasting.

🎯 Features
Time series preprocessing
Sequence generation for LSTM
Deep learning model with LSTM layers
Performance evaluation (MSE, RMSE, MAE, R²)
Visualization of results
Future prediction (next 5 months)
🛠️ Requirements
pip install numpy pandas matplotlib scikit-learn tensorflow
🚀 Workflow
Data Loading & Preprocessing
Load dataset
Convert dates
Normalize data
Sequence Creation
Create input-output pairs for time series
Model Building
LSTM layers + Dropout + Dense layers
Training
Train model with validation
Evaluation
MSE, RMSE, MAE, R²
Prediction & Visualization
Compare actual vs predicted values
Future Forecasting
Predict next 5 months
💻 Model Architecture
LSTM (128 units, return sequences)
Dropout (0.5)
LSTM (64 units)
Dropout (0.35)
Dense (32, ReLU)
Dense (1 output)
📊 Output
Graph of training vs validation loss
Actual vs predicted passenger plot
Future passenger predictions
📚 Use Cases
Stock price prediction
Sales forecasting
Weather prediction
Demand forecasting
