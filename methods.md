---
title: "Methods"
layout: default
nav_order: 3
has_children: false
---
# Methods
### We preprocess waveform data, extract key features, balance classes, train multiple ML models, and evaluate performance.

## Catboost

The CatBoost model was trained to classify the high_avse label using processed data.
Since approximately 98% of the data was labeled as true for high_avse, SMOTE was applied
to balance the dataset by generating synthetic samples for the minority class. The default
model configuration achieved an accuracy of 96.5\%. To improve performance, hyperparameter
tuning was performed using RandomizedSearchCV, along with feature importance analysis and
cross-validation to check for overfitting. These optimizations increased the model's accuracy
to 99.4%.

## XGBoost

## LightGBM

## Random Forest
