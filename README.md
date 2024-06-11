# INFS630-DataMining-Final-Project
Crime Data Classification with Decision Tree
This project demonstrates how to build and visualize a Decision Tree Classifier using the Scikit-Learn library to predict arrests based on crime data.

Overview
This repository contains a Python script that performs the following steps:

Import Libraries: Utilizes pandas for data manipulation, scikit-learn for machine learning, and additional libraries for visualization.
Load Dataset: Reads a CSV file containing cleaned crime data into a DataFrame.
Data Preprocessing:
Converts the 'District' column to string type.
Identifies and one-hot encodes categorical variables.
Integrates the encoded data back into the main DataFrame.
Dataset Splitting: Divides the data into training and testing sets to facilitate model evaluation.
Model Training: Creates and trains a Decision Tree Classifier on the training data.
Model Evaluation: Uses the trained model to predict on the test set and calculates the accuracy of the predictions.
Visualization: Visualizes the decision tree structure using Graphviz and displays it within the notebook.
