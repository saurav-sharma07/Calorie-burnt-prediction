# Calories Burnt Prediction

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
This project aims to predict the number of calories burnt during physical activities using machine learning techniques. The model is trained on a dataset with 8 features and uses the XGBoost regressor to provide accurate predictions.

## Dataset
The requried dataset is imported from Kaggle. 
Which contains two files:
  1. Calories.csv
  2. Excercise.csv

## Features
- **Age:** Age of the individual (years)
- **Gender:** Gender of the individual (Male/Female)
- **Height:** Height of the individual (cm)
- **Weight:** Weight of the individual (kg)
- **Duration of activity:** Time duration of the physical activity (minutes)
- **Heart rate:** Average heart rate during the activity (beats per minute)
- **Temperature:** Environmental temperature (°C)

## Model
The model uses the **XGBoost regressor**, a powerful and efficient implementation of gradient boosted decision trees. This model is chosen for its high performance and accuracy in regression tasks.

## Results
The model's performance is evaluated using various metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²). The results are promising and demonstrate the model's ability to predict calorie burns accurately.
