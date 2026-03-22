# 🔥 Steelproof Temperature Prediction

## 📌 Project Overview

This project aims to predict the final temperature of molten steel in a metallurgical process in order to optimize energy consumption and improve production efficiency.

## 🎯 Business Problem

Steel production requires high energy usage. Accurately predicting temperature helps reduce unnecessary heating, lowering operational costs and improving sustainability.

## 📊 Data Description

The dataset includes multiple sources:

* Arc electrode data
* Gas usage
* Bulk materials
* Wire materials
* Temperature measurements

Data was aggregated by batch (`key`) to create a unified dataset.

## ⚙️ Methodology

* Data cleaning and aggregation
* Feature selection (numeric variables only)
* Train/test split
* Baseline model (DummyRegressor)
* Random Forest model

## 🤖 Models Used

* Dummy Regressor (baseline)
* Random Forest Regressor (final model)

## 📈 Results

* Random Forest significantly outperformed the baseline model
* The model captured nonlinear relationships in the process
* Demonstrates strong potential for industrial optimization

## ⚠️ Limitations

* Lack of time-based features
* Possible missing variables affecting temperature

## 🚀 Future Improvements

* Hyperparameter tuning
* Feature engineering
* Inclusion of temporal dynamics

---

💙 Developed as part of a Data Science project (TripleTen)
