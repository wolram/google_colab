# google_colab — Machine Learning exercises on Google Colab

A collection of machine learning exercises from Google's ML Crash Course, implemented as Jupyter notebooks on Google Colab.

## Notebooks

### Linear Regression — Chicago Taxi Fare Prediction

`ml/cc/exercises/linear_regression_taxi.ipynb`

Trains a linear regression model to predict taxi fares in Chicago using a real dataset from the City of Chicago Taxi Trips (May 2022 subset).

Topics covered:

- Loading and exploring a dataset with pandas
- Descriptive statistics and correlation matrix analysis
- Training a single-feature linear regression model (trip miles)
- Experimenting with hyperparameters (learning rate, epochs, batch size)
- Training a two-feature model (trip miles + trip minutes)
- Comparing experiments using RMSE and loss curves
- Making and validating predictions

## Tech Stack

- Python 3
- TensorFlow / Keras
- pandas, NumPy, Matplotlib, Plotly
- google-ml-edu
- Google Colab

## Getting Started

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run the setup cells to install dependencies
3. Follow the instructions in each section
