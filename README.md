# Air Pollution Data Prediction
 All the codes for the air pollution data prediction

# Talcher Dataset for PM10

| Model       | RMSE        | MAE | MAPE | Parameters (Opti, Loss) |
| ----------- | ----------- | ----| ---- | ------------------------ |
| BiGRU      | 82.19       |76.6 | 32.86 | Adam, MSE | 
| BiLSTM      | 43.221       |32.318| 13.91| RMSProp, MSE |
| CNN      | 89.65      | 80.416| 38.016| SGD, MSE |
| LSTM      |88.39       |86.4| 40.03| SGD, MSE |
| CLAE      | 15.927       |14.09| 6.6522| (RMSProp, MAE) (Adam,MSE)|

# Talcher Dataset for PM2.5

| Model       | RMSE        | MAE | MAPE | Parameters (Opti, Loss) |
| ----------- | ----------- | ----| ---- | ---------- |
| BiGRU      | 70.72    |61.259 | 22.60|    RMSProp, MSE |
| BiLSTM      | 75.072       |64.923| 28.931| RMSProp, MAE | 
| CNN      | 53.37      | 42.71| 18.978| SGD, MSE|
| LSTM      | 36.21       |28.07| 11.94| RMSProp, MAE|
| CLAE      | 21.50       |19.048| 7.243|  (RMSProp, MAE) (Adam,MSE)|


# Beijing Dataset for PM10

 1. BiGRU
 2. BiLSTM
 3. CNN
 4. CNNLSTMAutoencoder
 5. GRU
 6. LSTM
 7. SVR

 
 
