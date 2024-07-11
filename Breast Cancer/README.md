
# Breast Cancer Diagnosis App

## Overview

The Breast Cancer Diagnosis App is a machine learning-powered tool designed to aid medical professionals in breast cancer diagnosis. By utilizing a set of measurements, this app predicts the nature of a breast mass, whether benign or malignant. It presents a visual representation of input data through radar charts and displays the predicted diagnosis, along with the probability of being benign or malignant. The app can be used for manual input of measurements or be connected to a cytology lab to fetch data directly from machines. It's important to note that the connection to the laboratory machine is not part of the app itself.

The app was created as a machine learning exercise using the public dataset [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data). It's essential to recognize that this dataset may not be reliable, as this project was developed solely for educational purposes in the field of machine learning and is not intended for professional use.

A live version of the application can be accessed at [Breast Cancer Diagnosis App](https://cancer-predictor-web-app-o8s9qymrznf2gh3acvsbsc.streamlit.app/).

## Installation

To run the Breast Cancer Diagnosis App locally, ensure you have Python 3.6 or higher installed. After that, you can install the necessary packages by running:

```bash
pip install -r requirements.txt
```

This command will install all required dependencies, including Streamlit, OpenCV, and scikit-image.

## Usage

To launch the app, execute the following command:

```bash
streamlit run app/main.py
```

This will open the app in your default web browser. You can upload measurements or data for analysis and adjust various settings to tailor the analysis to your needs. Once you're satisfied with the results, you can export the measurements to a CSV file for further analysis.
