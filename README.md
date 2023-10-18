# EEG_seizures_pred

Seizure forecasting from EEG dataset released by Kaggle ( https://www.kaggle.com/c/seizure-prediction ) 

Strategy:
- Baseline model with basic signal processing engineering (Variance of the acquisition channels) and logistic regression
- Features engineering to get more robust seizures' predictors ( based on literature, i.e. https://pubmed.ncbi.nlm.nih.gov/24416133/ )
- Recurrent Neural Network with Long-Short Term Memory (RNN LSTM) for seizure forecasting, no features engineering.

The ML based approach outperforms the other. 