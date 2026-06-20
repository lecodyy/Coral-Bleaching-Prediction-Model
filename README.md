# Predicting Coral Bleaching Severity Using Machine Learning

## Overview
This project explores how ocean conditions, such as sea surface temperature, thermal heat stress, and turbidity, relate to coral bleaching severity. The goal is to build a neural network that classifies reef sites into bleaching severity categories based on these environmental conditions.

## Dataset
- **Source:** [Coral Reef Global Bleaching (Kaggle)](https://www.kaggle.com/datasets/mehrdat/coral-reef-global-bleaching)
- **Size:** ~41,000 observations, 62 columns
- **Coverage:** 93 countries, 1980–2020
- **Target variable:** `Percent_Bleaching`
- **Key features:** `ClimSST`, `Temperature_Mean`, `SSTA`, `SSTA_DHW`, `TSA`, `TSA_DHW`, `Turbidity`, `Windspeed`, `Depth_m`, `Distance_to_Shore`, `Exposure`

> Note: The dataset CSV is not included in this repo. Download it directly from the Kaggle link above and place it in the project folder as `coral.csv`.


## Current Progress
- [x] Environment setup (Anaconda, VSCode, Jupyter Notebook)
- [x] Dataset selected and loaded
- [ ] Exploratory data analysis
- [ ] Data cleaning
- [ ] Baseline model
- [ ] Neural network
- [ ] Evaluation and write-up

## Tools
- Python
- Jupyter Notebook / VSCode
- pandas, (planned: matplotlib/seaborn, scikit-learn, TensorFlow)