# deep-learning-challenge

Source Data: https://github.com/kellnergp/deep-learning-challenge/blob/main/Resources/charity_data.csv

Primary Project Notebook: https://github.com/kellnergp/deep-learning-challenge/blob/main/AlphabetSoupCharity.ipynb

Optimization Notebook: https://github.com/kellnergp/deep-learning-challenge/blob/main/AlphabetSoupCharity_Optimization.ipynb

Saved Models: https://github.com/kellnergp/deep-learning-challenge/tree/main/Results

## Overview

This project was designed to help create a predictive model to determine whether applicants for aid from the non-profit group Alphabet Soup will successfully use the funding they request.

It uses a neural net deep learning model to make a binary prediction of funding success based on a sample size of approximately 34,000 previous aid grants.

The data was preprocessed to remove irrelevant columns, bin rare variable values, and convert categorical data to numeric for the purpose of modeling.

Tensorflow Keras was used to build and compile a neural net model based on the number of features with the number of layers and neurons set to attempt to generate highly accurate result.

As the initial model fell slightly below 75% accuracy, several further attempts were made to optimize the model and increase its accuracy.
