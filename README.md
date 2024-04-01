# Support Vector Machine (SVM) Implementation for Salary Prediction

## Overview
This project implements a basic Support Vector Machine (SVM) algorithm to predict salaries based on position levels. The dataset used for this project is `position_salaries.csv`.

## Requirements
- Python 3.x
- Jupyter Notebook or Google Colab
- Libraries: pandas, numpy, scikit-learn, matplotlib

## Dataset
The dataset `position_salaries.csv` contains information about different job positions and their corresponding salaries. It consists of two columns: "Position Level" (independent variable) and "Salary" (dependent variable).

## Implementation
1. **Data Preprocessing:**
   - Load the dataset using pandas.
   - Split the dataset into features (X) and target variable (y).
   - Perform feature scaling if necessary.

2. **Model Training:**
   - Implement an SVM regression model using scikit-learn.
   - Train the model on the training data.

3. **Model Evaluation:**
   - Predict the salaries using the trained model.
   - Evaluate the model's performance using appropriate metrics (if applicable).

4. **Visualization:**
   - Visualize the dataset using scatter plot.
   - Plot the regression line to visualize the model's predictions.

## Usage
1. **Google Colab:**
   - Upload the notebook file (`SVM_Salary_Prediction.ipynb`) to Google Colab.
   - Execute the cells in the notebook sequentially to load the data, train the model, and visualize the results.

2. **Jupyter Notebook:**
   - Install Jupyter Notebook and required libraries.
   - Open the notebook file (`SVM_Salary_Prediction.ipynb`) using Jupyter Notebook.
   - Run the cells in the notebook to execute the code.

## Results
- The SVM model successfully predicts the salaries based on position levels.
- The visualization shows the dataset and the regression line representing the model's predictions.

## Author
Veera Prathap


