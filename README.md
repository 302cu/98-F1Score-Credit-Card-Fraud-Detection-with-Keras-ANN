# Credit Card Fraud Detection with Keras ANN

## Overview
This Jupyter notebook demonstrates a deep learning approach using an artificial neural network (ANN) with Keras to detect credit card fraud. The notebook explores a dataset containing transactions from European cardholders in September 2013, focusing on identifying fraudulent activities.

## Dataset
The dataset used here includes over one million transactions, with 87,403 identified as fraudulent, which represents 0.172% of the total transactions. It is highly unbalanced in terms of the distribution of legitimate versus fraudulent transactions.

Link to dataset: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud/data)

## Prerequisites
To run this notebook, ensure you have the following Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- tensorflow

## Notebook Content
1. **Data Importation**: Load the dataset into a pandas DataFrame.
2. **Preprocessing**: Prepare the dataset for modeling, including handling missing values, feature scaling, and data splitting.
3. **Exploratory Data Analysis**: Analyze the data to gain insights and understand the nature of fraudulent transactions.
4. **Model Building**: Construct an ANN using Keras to classify transactions as fraudulent or not.
5. **Model Training**: Configure training with callbacks such as early stopping and learning rate reduction based on the validation F1 score.
6. **Model Evaluation**: Evaluate the model's performance on unseen test data and report metrics.

## Usage
- Clone this repository or download the Jupyter notebook.
- Ensure the dataset is located in the same directory as the notebook or adjust the path accordingly in the notebook.
- Run the notebook cells sequentially to reproduce the results.

## Conclusion
The ANN model developed in this notebook achieves a high F1 score, indicating effective identification of fraudulent transactions. It includes techniques like early stopping to prevent overfitting and learning rate adjustments to optimize training.

