# Daily Rainfall Prediction Using LSTM

## Project Overview
A deep learning project that predicts daily rainfall for one selected district using the IMD Rainfall Dataset 2022.

## Objectives
1. Load the dataset, handle missing values, and normalize rainfall measurements.
2. Convert daily observations into a time series and create input sequences using the previous seven days.
3. Develop an LSTM sequential learning model.
4. Train using a chronological 80:20 split and evaluate with MAE and RMSE.
5. Plot actual versus predicted rainfall and predict rainfall for seven future dates.

## Technologies
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- TensorFlow and Keras

## Methodology
The monthly district-wise rainfall measurements are converted into daily observations. Missing values are handled, and rainfall is normalized using Min-Max scaling. An LSTM model learns from the previous seven days to predict the next day's rainfall.

The model is evaluated on a later chronological test period using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Outputs
- Cleaned daily rainfall dataset
- Actual versus predicted rainfall graph
- Training and validation loss graph
- Seven-day future rainfall predictions
- Test and forecast CSV files
- Trained LSTM model

## Dataset
IMD Rainfall Dataset 2022 on Kaggle:

https://www.kaggle.com/datasets/ankitgaikar1995/imd-rainfall-dataset-2022

## How to Run
1. Open `IMD_Rainfall_Prediction.ipynb` in Google Colab.
2. Upload the downloaded dataset ZIP and extract the CSV, or adjust the dataset path to your environment.
3. Run the notebook.
4. Review the evaluation metrics, graphs, and forecast files.

## Limitations
The model uses a limited historical period. Forecasts are experimental estimates and are not official weather predictions. Results depend on the selected district and dataset quality.
