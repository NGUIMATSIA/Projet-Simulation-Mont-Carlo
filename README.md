# Monté-Carlo simulation

## Log-Linear Model Data Sampling and Estimation

This project focuses on log-linear models applied to a vector X that takes values in {0, 1}^d. In this model, the probability of observing a certain x is determined by the equation:

log P(X = x) = α + ∑ β_i * x_i + ∑ γ_ij * x_i * x_j

### Objectives

1. Propose and implement an algorithm to sample data from this log-linear model, considering fixed values of β_i. Additionally, explore methods to assess the mixing properties of the sampling algorithm.
2. Investigate the relationship between α and the other parameters in the model. Examine the challenges this poses for parameter estimation based on data.
3. Address the estimation challenge raised in point 2 by implementing the exchange algorithm proposed in the paper [link to the paper](https://arxiv.org/pdf/1206.6848.pdf).
4. Bonus: Apply the developed algorithms and methods to estimate this type of log-linear model on real datasets such as UCBAdmissions or Titanic.

### Implementation

The project will be implemented using python. The codebase will consist of modules or functions to perform the following tasks:

- Data sampling from the log-linear model with fixed values of β_i.
- Assessing the mixing properties of the sampling algorithm.
- Estimating the parameters of the log-linear model using the exchange algorithm.
- Applying the developed methods to real datasets for model estimation.

### Usage

The file **Projet_sans_optimisation** contents all the projet and some comments

### Contributions

Franki NGUIMATSIA TIOFACK, Firas BENKHALIFA and Antonio Sasaki
