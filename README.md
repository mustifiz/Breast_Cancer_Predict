# Breast cancer diagnosis predictor

A machine learning web application that helps medical professionals predict whether a breast mass is benign or malignant based on cytology measurements.

![Breast Cancer Predictor Interface](images/cancer.png)

## Overview

The Breast Cancer Diagnosis app is a machine learning-powered tool designed to assist medical professionals in diagnosing breast cancer. Using a set of measurements, the app predicts whether a breast mass is benign or malignant. It provides a visual representation of the input data using a radar chart and displays the predicted diagnosis and probability of being benign or malignant. The app can be used by manually inputting the measurements or by connecting it to a cytology lab to obtain the data directly from a machine. The connection to the laboratory machine is not a part of the app itself.

The app was developed as a machine learning exercice from the public dataset [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data). Note that this dataset may not be reliable as this project was developed for educational purposes in the field of machine learning only and not for professional use.

The application will be available at:

Local URL: http://localhost:8501
Network URL: http://192.168.178.30:8501


## Installation

You can run this inside a virtual environment to make it easier to manage dependencies. I recommend using `conda` to create a new environment and install the required packages. You can create a new environment called `breast-cancer-diagnosis` by running:

```bash
conda create -n breast-cancer-diagnosis python=3.10 
```

Then, activate the environment:

```bash
conda activate breast-cancer-diagnosis
```

Then, activate the environment:

```bash
conda activate breast-cancer-diagnosis
```

To install the required packages, run:

```bash
pip install -r requirements.txt




## Usage
To start the app, simply run the following command:

```bash
streamlit run app/main.py
```

This will launch the app in your default web browser. You can then upload an image of cells to analyze and adjust the various settings to customize the analysis. Once you are satisfied with the results, you can export the measurements to a CSV file for further analysis.



app/
    main.py          # Main application file
assets/
    style.css        # Custom styling
data/
    data.csv         # Dataset
model/
    model.pkl        # Trained model
    scaler.pkl      # Data scaler
requirements.txt    # Project dependencies

Readme
