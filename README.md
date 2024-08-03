# Conformal-Prediction-Cpmparison


## Overview
This repository contains scripts for conducting conformal prediction analysis, aiming to evaluate the robustness and reliability of prediction intervals generated by various statistical models under different data conditions.

## Features
- **Data Simulation**: Generates homoscedastic, heteroscedastic, and heteroscedastic sparse datasets to simulate real-world data complexities.
- **Conformal Prediction Strategies**: Implements multiple conformal prediction methods using MAPIE, including standard split, jackknife, cross-validation, and Conformal Quantile Regression (CQR).
- **Model Training**: Leverages machine learning models such as Random Forest, Neural Networks, and Ridge Regression.
- **Results Visualization**: Includes advanced plotting configurations to ensure clear and informative visual comparisons of prediction interval metrics.

## Dependencies
The script requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scikeras`
- `tensorflow`


## Usage

1. **Data Preparation**: The `DATA_Preparation.py` script processes real data to ensure it's ready for analysis. It formats and cleans the data to fit the requirements of subsequent predictive modeling.

2. **Run Real Data**: The `Run_Real_Data.py` script applies conformal prediction methods to the prepared real data, evaluating the performance of these methods in realistic scenarios.

3. **Several Runs**: The `Several_Runs.py` script is designed to perform multiple runs on simulated data. This script is useful for statistical analysis and to ensure the robustness and consistency of the prediction methods across various iterations.

4. **Single Run**: The `Single_Run.py` script focuses on a detailed single run analysis, providing deeper insights with additional metrics. This script allows for a thorough evaluation of conformal prediction methods in a controlled environment.

## Results
Results are presented as a series of bar charts, each saved as an image file in the project directory. These charts compare coverage and average width metrics, providing a visual assessment of each conformal prediction method's performance.
