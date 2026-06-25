# survival-deep-learning-crc
Deep learning and Cox proportional hazards modelling for survival prediction in colorectal cancer outcomes.
# Deep Learning for Survival Analysis in Colorectal Cancer Outcomes

## Project Overview

This project applies a deep learning neural network to survival analysis data and compares its performance with a traditional Cox Proportional Hazards model.

## Objective

The aim is to predict time-to-event outcomes in colorectal cancer and evaluate whether a neural network-based survival model can provide useful predictive performance compared with a standard Cox PH model.

## Methods

- Data preprocessing and missing-value handling
- Train/test split
- Deep neural network using TensorFlow/Keras
- Custom Cox proportional hazards loss function
- Cox PH baseline model using lifelines
- Model evaluation using concordance index
- Diagnostic metrics including sensitivity, specificity, accuracy, and precision

## Tools and Libraries

- Python
- pandas
- NumPy
- scikit-learn
- TensorFlow/Keras
- lifelines
- statsmodels

## Repository Structure

```text
src/          Python scripts for model training and evaluation
notebooks/    Demonstration notebook
data/         Data information only; real data are not shared
results/      Model performance summaries
