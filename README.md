# Project Title
Polynomial Regression Models for the Flow Problem

## Description
This repository contains the polynomial regression models developed for our flow problem study. The dataset, calculated from all combinations of input flow parameters, is provided to implement and test polynomial regression. The code allows prediction of output variables for arbitrary combinations of input parameters.

## Dataset
The dataset includes all combinations of six input flow parameters (Ha, M, m, beta, Sc_N, Sc_{O_{2}}) at three levels (low, middle, high), along with the corresponding 4 response variables (skin friction coefficients , Sherwood number, and Motile micro-organism density number). This dataset is used to train and validate the polynomial regression models.
##  Features
- Polynomial regression of orders 1–5 implemented using Python and scikit-learn.
- Derived quadratic expressions for predicting outputs from inputs.
- Code for training, evaluating, and predicting the response variables.
