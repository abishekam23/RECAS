# Deep Learning Project on Household Power Consumption

This project focuses on analyzing household power consumption data using deep learning techniques. The main objective is to explore the dataset, preprocess the data, and build a predictive model using TensorFlow and Keras.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Results](#results)
- [License](#license)

## Project Overview

This project analyzes the **Household Power Consumption** dataset to predict energy consumption patterns. The notebook contains steps to preprocess the data, perform exploratory data analysis, and build a deep learning model.

## Dataset

The dataset used in this project is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption). It includes various measurements of electric power consumption in one household with a one-minute sampling rate for almost 4 years.

- **Source**: UCI Machine Learning Repository
- **File Name**: `household_power_consumption.csv`
- **Attributes**:
  - Date and time
  - Global active power
  - Global reactive power
  - Voltage
  - Global intensity
  - Sub metering 1, 2, and 3

## Installation

To run this project, you'll need to install the following dependencies:

```bash
pip install keras.utils np_utils
```
You can install other necessary packages by running:
```bash
pip install <package-name>
```

## Exploratory Data Analysis

The notebook includes an extensive Exploratory Data Analysis (EDA) section that covers:

- Overview of the dataset structure (df.info())
- Checking for missing values (df.isnull().sum())
- Visualizing data distributions and trends using Matplotlib and Seaborn

## Modeling
The deep learning model is built using TensorFlow and Keras. Key steps include:

- Data Preprocessing: Handling missing values, feature engineering, and normalization.
- Model Architecture: Designing a neural network with layers like Dropout for regularization.
- Model Training: Splitting the data into training and testing sets, and training the model using appropriate loss functions and optimizers.

## Results

The results section of the notebook includes the following:

- Model evaluation metrics (accuracy, loss)
- Visualization of the model's performance over time
- Interpretation of results and potential areas for improvement

## License
This project is licensed under the MIT License - see the LICENSE file for details.
