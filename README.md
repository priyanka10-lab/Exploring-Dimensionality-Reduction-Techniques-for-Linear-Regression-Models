# Exploring-Dimensionality-Reduction-Techniques-for-Linear-Regression-Models

This project aims to explore the impact of dimensionality reduction techniques on the performance of linear regression models. The dataset used contains 491 predictors (X1, X2, ..., X491) and a dependent variable (Y).

In Step 1, linear regression models are built by gradually increasing the number of predictors. The determination coefficient (R-squared) is calculated for each model. The objective is to identify the minimum number of predictors required to achieve a determination coefficient above 90% (0.9). This value is referred to as n_orig.

In Step 2, the project employs Principal Component Analysis (PCA) as a dimensionality reduction method. PCA transforms the original predictors into a set of uncorrelated variables known as principal components. These components are then reordered based on their importance. The aim is to determine the smallest number of PCA factors needed to attain a determination coefficient above 90%. This value is denoted as n_PCA.

The model dimensionality reduction is calculated as the difference between n_orig and n_PCA. Furthermore, the determination coefficient of the model utilizing the n_PCA most important PCA factors is obtained.
