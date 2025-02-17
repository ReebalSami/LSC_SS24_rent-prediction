# Mietpreisvorhersage Project

This project focuses on predicting rental prices using various machine learning models. It was conducted by Theresia Rupprecht, Janina Urner, Ana Angulo Ariza, and  Reebal Sami as part of a Master's course module "Learning and soft computing" at Fachhochschule Wedel.

## Environment

Please make sure to set up a new virtual environment. For this purpose you can use the following commands:

```sh
pyenv local 3.10.14
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the data cleaning notebook.

## Data

The dataset is sourced from the real estate platform Immoscout24, containing rental listings for residential spaces in Germany from 2018 and 2019. It includes 49 different attributes, allowing for comprehensive analyses.

The dataset for the notebook is stored in the `data.zip` folder. To unzip the data folder directly in the terminal run

```sh
unzip data.zip
```

## Objective of the project

The main goal of this project is to develop a model that can accurately predict rental prices. This aims to help tenants identify fair rental prices and enable landlords to set market-appropriate prices. The focus is specifically on rental prices for students up to 2000€.

## Chapters

- **Exploratory Data Analysis (EDA)**: Includes data cleaning, feature engineering, and data visualization.
- **Modeling**: Various regression models were developed and evaluated, including Linear Regression, Lasso Regression, Random Forest, Gradient Boosting, and XGBoost.
- **Hyperparameter Tuning**: Optimizing the models to improve prediction accuracy.

## Summary

This project demonstrates that machine learning can be effectively used for rental price prediction. By focusing on specific price segments, particularly rental prices for students up to 2000€, more accurate and relevant predictions were achieved.