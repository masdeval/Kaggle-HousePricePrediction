Introduction

In this article we are going to discuss our work on predicting House Prices. This is a classic regression problem in which we aim to predict the selling price of a house given its attributes. The motivation in doing such analysis is to provide real estate firms accurate information about expected values of properties. After creating the seven models, we conduct an evaluation of each model by comparing its accuracy. This work is organized in the following way:

    Methodology
    Understanding and cleaning the data
    Regression Models
    Linear Regression
        Ordinary Least Squares
        Ridge
        Lasso
        Elastic Net
    Suport Vector Machine
    Neural Network
    Random Forests
    Discussion

Methodology

As we are dealing with a regression problem, an appropriate metric is the Root Mean Squared Error or RMSE. The methodology we followed is:

    Each method trained using 5-fold cross-validation.
    Final RMSE is calculated based on the average results of all training steps.

Using cross-validation is a common way to assess the predictive performance of the models and to judge how they perform outside the sample (and assess their generalization strength).
