# Restuarant Violation Analysis

This project focuses on predicting inspection scores and classifying the violation risks of establishments using machine learning. Through data exploration, visualization, and predictive modeling, this notebook aims to provide insights and assist in making informed decisions based on inspection data.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Overview](#project-overview)
- [Features](#features)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Mukunj-21/Restaurant-Violation-Analysis.git
2. **Navigate to the project directory**:
    ```bash
   cd repository
3. **Install the required packages**:
   ```bash
    pip install -r requirements.txt

## Usage
To use this notebook, open it in Jupyter and execute the cells sequentially:
```bash
  jupyter notebook final.ipynb
```

**Main Steps in the Notebook**:
1. **Data Loading**: Loads and prepares the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualizes the distribution of inspection scores and explores relationships in the data.
3. **Feature Engineering**: Prepares data specifically for model training and evaluation.
4. **Model Training and Evaluation**: Trains models for both inspection score prediction and violation risk classification.
5. **Visualization**: Provides visual insights into model predictions and feature relationships.

## Project Overview
This project consists of two main tasks:

1. **Inspection Score Prediction**: Predicts the inspection scores of establishments using various features.
2. **Violation Risk Classification**: Classifies establishments based on the likelihood of violations occurring.
The notebook uses machine learning models to achieve these tasks, with an emphasis on interpretability and accuracy.

## Features
1. Data Loading and Cleaning: Prepares the data for analysis.
2. Exploratory Data Analysis (EDA): Provides insights into data distributions and correlations.
3. Model Training:
   Regression model for predicting inspection scores.
   Classification model for predicting violation risk.
4. Evaluation Metrics: Assesses the performance of each model to ensure reliability.
5. Visualization: Displays the distribution of scores and model predictions.

## Requirements
Python 3.x
Jupyter Notebook
pandas
numpy
matplotlib
scikit-learn

Additional dependencies can be installed by running:
```bash
  pip install -r requirements.txt
```

## Contributing
1. Fork the repository
2. Create a new branch (git checkout -b feature-branch)
3. Commit your changes (git commit -am 'Add new feature')
4. Push to the branch (git push origin feature-branch)
5. Create a new Pull Request

## License
This project is licensed under the MIT License. See the LICENSE file for details.
