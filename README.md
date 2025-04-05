# Algerian-Forest-Fires
This Streamlit app predicts forest fire risk in Algeria based on factors like temperature, humidity, wind speed, and rainfall. It uses a machine learning model and a heuristic function for real-time predictions. Users can visualize historical fire data and input parameters for time-based risk evaluation.

- **Prediction:** Predict fire risk using both a trained machine learning model and a simple heuristic function.
- **Historical Data Visualization:** Visualize past fire risk trends.
- **Interactive UI:** Use sliders to input environmental factors and get real-time predictions.
- **Time-Based Adjustment:** Adjust fire risk predictions based on the time of day (lower risk at night).


## The app will launch in your default web browser where you can:
    - Input various weather parameters (temperature, humidity, wind speed, rainfall, etc.).
    - View a historical fire risk trend visualization.
    - Get a prediction of fire risk based on the input data using the heuristic or ML model.

## How It Works

The app predicts fire risk using both a **machine learning model** and a **heuristic approach** based on environmental factors.

### 1. **Model Prediction**
The app loads a pre-trained machine learning model (`elasticcv_model.pkl`) and uses environmental data to predict the fire risk. Users input features such as temperature, humidity, wind speed, and rainfall, and the model calculates the likelihood of a fire.

## Libraries Used
Numpy
Pandas
Matplotlib & Seaborn
Scikit-learn
Streamlit
