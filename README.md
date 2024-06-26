# Predicting Car Prices

## Project Overview

The certification I recently earned required the successful completion of two timed exams and a practical component. For the practical exam, I was given a hypothetical scenario in which my manager (Head of Data Science) gave me an assignment that was requested by another business leader (Product Manager). I was provided with instructions and a dataset to analyze, and had to provide a written report including code and output. Additionally, I recorded a presentation to give a high-level overview of my analysis and findings.

This repo contains my written report (.ipynb) and the corresponding dataset (.csv) and instructions (.pdf) from the practice practical exam. I am sharing this as a portfolio project for the purpose of demonstrating my Python and communication skills.

## Installation and Setup

### Code and Resources Used

- **Editor**: JupyterLab 4.0.11
- **Python Version**: 3.12.3

### Python Packages Used
- Data Manipulation:
  - `pandas` 2.2.2
  - `numpy` 1.26.4
  - `scipy` 1.13.0
- Data Visualization:
  - `matplotlib` 3.8.4
  - `seaborn` 0.13.2
- Machine Learning and Statistics:
  - `scikit-learn` 1.4.2
  - `statsmodels` 0.14.2

## Data

### Project Files
- **instructions.pdf**: instructions provided by the certification organization
- **toyota.csv**: dataset provided by the certification organization
- **kucharczyk_predicting_car_prices.ipynb**: my written report including code and output

### Data Exploration, Preparation, Analysis, and Results

I performed exploratory data analysis, data preparation, and regression using Python to predict used car prices. K-fold cross-validation and grid search were used for model selection and hyperparameter tuning. The random forest model achieved a root-mean-squared error of 1210.38 GBP, R<sup>2</sup> value of 0.96, and predicted 78% of prices within 10% of their actual values. The written report (.ipynb) provides all details relating to data exploration, preparation, analysis, and results.

## References

The certification organization that provided the dataset and instructions can be found in the instructions (.pdf).