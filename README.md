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

## Variables

>EIN and NAME—Identification columns<br>APPLICATION_TYPE—Alphabet Soup application type<br>AFFILIATION—Affiliated sector of industry<br>CLASSIFICATION—Government organization classification<br>USE_CASE—Use case for funding<br>ORGANIZATION—Organization type<br>STATUS—Active status<br>INCOME_AMT—Income classification<br>SPECIAL_CONSIDERATIONS—Special consideration for application<br>ASK_AMT—Funding amount requested<br>IS_SUCCESSFUL—Was the money used effectively

## Results

- Preprocessing
 1. The only target variable in the dataset is `IS_SUCCESSFUL`.
 2. The features which contribute to the analysis include: `APPLICATION_TYPE`, `AFFILIATION`, `CLASSIFICATION`, `USE_CASE`, `ORGANIZATION`, `STATUS`, `INCOME_AMT`, `SPECIAL_CONSIDERATIONS`, and `ASK_AMT`.
 3. `EIN` and `NAME` are both identifications for the specific businesses that received funding in the past. As such, they do not contribute directly to the success of the funding and therefor are neither targets nor features.
- Compiling, Training, and Evaluating the Model
 1.
 2.
 3.
