# Fish Growth Prediction, Optimal water identification and Fish Growth and Water Quality Forecasting

## Project Overview
This project focuses on forecasting daily water quality parameters and fish growth metrics in aquaponic systems for the next month.
It also focuses on predicting the fish length and weight from the water quality variables.
It also identifies the optimal water quality conditions that promote the best growth for the fish.
The model predicts fish length, and weight using the water quality variables.
The model forecasts parameters such as temperature, pH, dissolved oxygen, fish length, and weight using historical data. 
It applies **Principal Component Analysis (PCA)** for dimensionality reduction and a **Long Short-Term Memory (LSTM)** neural network for time-series forecasting. 
It also all

## Features
- **EDA**: Explore the dataset to identify any outliers and to 
- **Dimensionality Reduction**: PCA reduces data dimensions while retaining essential variance.
- **Time-Series Forecasting**: LSTM predicts trends for a 30-day horizon.

## Libraries Used
- **Python 3.8+**
- **NumPy**: Data manipulation.
- **Pandas**: Data preprocessing.
- **Matplotlib**: Data visualization.
- **scikit-learn**: PCA, data scaling and Regression model implementation.
- **TensorFlow/Keras**: LSTM implementation.

## Files in Repository
- **`Project.ipynb`**: Jupyter Notebook containing the implementation, from data preprocessing to forecasting.
- **`Dataset`**: A folder containing the CSV files for each aquaponic fish pond.
- **`README.md`**: Documentation of the repository.

## How to Run the Project
1. **Clone the Repository**:  
    git clone <repo_url>
    cd <repo_name>

2. **Install Dependencies**:  
    pip install numpy pandas matplotlib scikit-learn tensorflow

3. **Run the Jupyter Notebook**:  
    jupyter notebook Project.ipynb


