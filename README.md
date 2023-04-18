
Multi Disease Prediction for Heart Disease, Diabetes, and Obesity using Boosting Techniques

This repository contains code and data for a machine learning model that predicts the likelihood of an individual developing heart disease, diabetes, and obesity simultaneously, using boosting techniques.
Data

The data used for this project is sourced from the kaggle dataset, which includes a wide range of health-related information about individuals, including demographics and life style data results. The dataset has been pre-processed to include only the features relevant to heart disease, diabetes, and obesity.
Model

The multi-disease prediction model is built using a boosting approach, specifically the Gradient Boosting Classifier,XGB Boosting Classifier,Ada Boosting Classifier, lightGBM Boosting Classifier,CAT Boosting Classifier algorithm. The model takes in a range of health-related features as input, including demographic information and life style test results, and outputs the predicted likelihood of an individual developing heart disease, diabetes, and obesity simultaneously.
Usage

To use the model, simply run the multi_disease_prediction.py script and provide the necessary input data in the form of a CSV file. The script will output the predicted likelihood of an individual developing heart disease, diabetes, and obesity simultaneously, along with the individual predictions for each disease.
Dependencies

The code in this repository requires the following dependencies:

    scikit-learn
    pandas
    numpy

These can be installed using pip install or any other package manager.
References

For more information on the datasets and methodology used in this project, please see the following references:

    scikit-learn: https://scikit-learn.org/
    pandas: https://pandas.pydata.org/
    numpy: https://numpy.org/

