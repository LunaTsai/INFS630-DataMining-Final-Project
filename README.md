# Crime Data Classification using Decision Tree
This is the final project for the course, INFS630 Data Mining. I leveraged Decision Tree model to predict crime occurance in chicago area, which can help the police officers to improve crime prevention strategies.

## What I have learned:
This repository contains a Python script that performs the following steps:

### Import Libraries: 
Utilizes **pandas** for data manipulation, **scikit-learn** for machine learning, and additional libraries for visualization.
### Load Dataset: 
Reads a CSV file containing cleaned crime data into a DataFrame.
### Data Preprocessing:
Converts the 'District' column to string type.
Identifies and **one-hot encodes** categorical variables.
Integrates the encoded data back into the main DataFrame.
### Model Training: 
Creates and trains a **Decision Tree Classifier** on the training data.
### Model Evaluation: 
Uses the trained model to predict on the test set and calculates the accuracy of the predictions.
### Visualization: 
Visualizes the decision tree structure using Graphviz and displays it within the notebook.
