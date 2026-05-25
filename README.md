# Predicting Abalone Age Using Statistical Learning

This project develops and evaluates multiple regression-based statistical learning models to predict abalone age using physical measurements. The analysis applies diagnostic testing, logarithmic transformations, subset selection methods, and bootstrap stability analysis to compare model performance and robustness.

## Tools and Methods

- R
- Quarto
- Linear Regression
- AIC/BIC Model Selection
- Exhaustive Subset Selection
- Bootstrap Stability Analysis
- ggplot2
- tidyverse
- caret
- leaps
- broom
- GGally

## Key Findings

- Logarithmic transformations improved model assumptions and residual behaviour
- Strong multicollinearity was identified among physical measurement variables
- A reduced model excluding Diameter achieved comparable predictive performance with improved robustness
- The final selected model achieved an adjusted R-squared of approximately 0.64

## Live Report

[View Live Report](https://stacyngo2007.github.io/abalone-statistical-learning/)

## Dataset

UCI Abalone Dataset  
https://archive.ics.uci.edu/ml/datasets/abalone

## Author

Viet Bao Ngo  
University of Sydney
