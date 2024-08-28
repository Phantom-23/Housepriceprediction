# House Price Prediction Using Machine Learning

This project aims to predict house prices using various machine learning algorithms. The dataset used contains information about housing prices in California, along with other related features such as location, age of the house, number of rooms, and more.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Features](#features)
- [Modeling](#modeling)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

This project explores different machine learning algorithms to predict the median house value in California districts based on various features such as the number of rooms, population, median income, and proximity to the ocean.

## Installation

To get started, clone this repository and install the required dependencies:

```bash
git clone "https://github.com/Phantom-23/Housepriceprediction"
cd house-price-prediction
```

Ensure that you have Jupyter Notebook or JupyterLab installed to run the notebook.

## Usage

1. Load the dataset by running the first few cells of the notebook.
2. Preprocess the data by handling missing values.
3. Explore the data through visualization and summary statistics.
4. Implement and evaluate different machine learning models.
5. Predict house prices using the trained models.

To run the notebook, use the following command:

```bash
jupyter notebook house_price_prediction.ipynb
```

## Dataset

The dataset used in this project is a California housing dataset with the following features:

- `longitude`: Longitude of the location
- `latitude`: Latitude of the location
- `housing_median_age`: Median age of the houses in the district
- `total_rooms`: Total number of rooms in the district
- `total_bedrooms`: Total number of bedrooms in the district
- `population`: Population in the district
- `households`: Number of households in the district
- `median_income`: Median income of households in the district
- `median_house_value`: Median house value in the district
- `ocean_proximity`: Proximity of the location to the ocean

## Features

- **Data Cleaning**: Handling missing values.
- **Exploratory Data Analysis (EDA)**: Visualization of data to understand patterns and correlations.
- **Feature Engineering**: Creating new features or modifying existing ones to improve model performance.
- **Modeling**: Implementation of various machine learning algorithms, including:
  - Linear Regression
  - Decision Trees
  - Random Forest Regression
  - Others (as explored in the notebook)

## Modeling

The notebook explores different machine learning models, evaluates their performance, and compares them using metrics like RMSE, R-squared, and MAE.

## Results

The results of the models are analyzed, and the best-performing model is highlighted. The notebook includes visualizations of predictions versus actual values, and other relevant metrics.

## Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.
