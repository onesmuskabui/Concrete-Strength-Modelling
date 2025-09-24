Concrete Compressive Strength

Author: Onesmus Kabui

Introduction

This project analyzes the relationship between mixture components of concrete and its compressive strength. The goal is to build predictive models that explain how materials such as cement, water, slag, fly ash, and curing age contribute to the final strength of concrete. Accurate prediction is important for construction safety, material efficiency, and cost management.

Dataset

Source: UCI Machine Learning Repository

Size: 1,030 rows, 9 variables

Features:

Cement, Blast Furnace Slag, Fly Ash, Water, Superplasticizer

Coarse Aggregate, Fine Aggregate, Age (days)

Target: Concrete Compressive Strength (MPa)

Methods

Programming language: R

Libraries: tidyverse, caret, ggplot2, readxl

Approach:

Data cleaning and preparation

Train/test split (80/20)

Multiple linear regression

Model evaluation using R², RMSE, and residual plots

Findings

The linear regression model explains about 63% of the variance in compressive strength (R² = 0.63).

The average prediction error (RMSE) is about 10 MPa.

Cement, age, blast furnace slag, fly ash, and superplasticizer are the most influential predictors.

Water has a significant negative effect when used excessively.

Coarse and fine aggregates were not statistically significant.

Conclusion

The model provides a fair baseline for predicting compressive strength but leaves room for improvement. Nonlinear terms or interaction effects could capture more variability. The analysis confirms the importance of cement content and curing time in producing strong concrete.

How to Run

Clone the project and open the .qmd in RStudio.

Install the required packages:

install.packages(c("tidyverse", "caret", "readxl", "ggplot2"))


Run the script to reproduce the analysis and plots.
