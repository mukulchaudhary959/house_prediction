House Price Prediction Project
Introduction
Creating a Machine Learning model to predict the home prices in India. We are going to use the dataset from Kaggle.com.

Below data science concepts are used in this project

Data loading and cleaning
Outlier detection and removal
Feature engineering
Dimensionality reduction
Linear Regression
Technology and tools used in this project

Python
Numpy and Pandas for data cleaning
Sklearn for model building
Jupyter Notebook
Steps
We will first build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com.
Step#1: Import the required libraries
Step#2: Load the data
Step#3: Understand the data
        -drop unnecessary columns
Step#4: Data Cleaning
        - Check for na values
        - Verify unique values of each column
        - Make sure values are correct (eg. 23 BHK home with 2000 Sqrft size is worng)
        - Feature Engineering
        - Dimesionality Reduction
        - Outlier removal using domain knowledge (2bhk price < 3bhk price, size per bhk >= 300 sqft)
        - Outlier removal using standard eviation and mean
        - One Hot encoding
Step#5: Build Machine Learning Model
Step#6: Testing The model
Step#7: Export the model
Step#8: Export any other important info
