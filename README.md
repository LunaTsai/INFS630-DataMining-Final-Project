# Crime Data Classification with Decision Tree
This project demonstrates how to build and visualize a Decision Tree Classifier using the Scikit-Learn library to predict arrests based on crime data.

## Overview
This repository contains a Python script that performs the following steps:

(1)Import Libraries: 
Utilizes **pandas** for data manipulation, **scikit-learn** for machine learning, and additional libraries for visualization.
(2)Load Dataset: 
Reads a CSV file containing cleaned crime data into a DataFrame.
(3)Data Preprocessing:
Converts the 'District' column to string type.
Identifies and **one-hot encodes** categorical variables.
Integrates the encoded data back into the main DataFrame.
(3)Model Training: 
Creates and trains a **Decision Tree Classifier** on the training data.
(4)Model Evaluation: 
Uses the trained model to predict on the test set and calculates the accuracy of the predictions.
(5)Visualization: 
Visualizes the decision tree structure using Graphviz and displays it within the notebook.
