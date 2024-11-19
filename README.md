# Fish Growth Prediction, Optimal water identification and Fish Growth and Water Quality Forecasting

## Project Overview
This project focuses on addressing the problem of aquaponic fish ponds being vulnerable to fish shortages and potential business failure. It solves this by forecasting daily water quality parameters and fish growth metrics in aquaponic systems for the next month. It also focuses on predicting the fish length and weight from the water quality variables.It also identifies the optimal water quality conditions that promote the best growth for the fish.The model predicts fish length, and weight using the water quality variables. The model forecasts parameters such as temperature, pH, dissolved oxygen, fish length, and weight using historical data.It applies **Principal Component Analysis (PCA)** for dimensionality reduction, a **Long Short-Term Memory (LSTM)** neural network for time-series forecasting and a **Regression Model** for predicting fish length and weight based on water quality variables and values.

## Dataset

The dataset used for this project is the **Sensor-Based Aquaponics Fish Pond Dataset**, available on Kaggle. It contains time-series data on water quality and fish growth parameters.

[Dataset Link](https://www.kaggle.com/datasets/ogbuokiriblessing/sensor-based-aquaponics-fish-pond-datasets)

If the dataset is downloaded independently, create a folder in the project directory named Dataset and place the CSV files in this folder.

## Features
- **EDA**: Explore the dataset to identify any outliers and get a sense of the structure and shape of the data.
- **Data Preprocessing**: Modify the data to ensure it can be used effectively and accurately when training the different models.
- **Regression Model**: The regression model predicts the fish length and weight based on the water quality variables.
- **Optimal Water Quality Identifier**: Identifies the values of the water quality variables that yielded the most growth in the fish.
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
- **`COS 781 Project Report.pdf`**: A PDF file that contains the report of the project.
- **`Aquaponics Fish Pond_u21529583.zip`**: A ZIP file containing all the project files.
- **`README.md`**: Documentation of the repository.

## How to Run the Project
1. **Install Python**: 
    Ensure Python 3.8 or later is installed. Download it from [Python.org](https://www.python.org/).
2. **Install Jupyter Notebook**: 
    Install with:  
    pip install notebook  
    OR  
    install from the website:    
    [Jupyter notebook download Link](https://jupyter.org/install)  
    and follow the instructions
3. **Install Dependencies**:
    Install dependencies using:  
    pip install numpy pandas matplotlib scikit-learn tensorflow
4. **If Cloning from GitHub Repo**:  
    Clone this repository to your local machine:  
    git clone https://github.com/AdamOsb/781-Project  
    **If using the dowloaded ZIP file**
    Extract the files into a directory
5. **Run the Jupyter Notebook**: 
    Navigate to the repository/extracted folder and open the notebook:  
    jupyter notebook Project.ipynb


