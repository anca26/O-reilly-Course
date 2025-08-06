# O-reilly-Course
This repository contains a collection of Jupyter notebooks developed throughout a structured machine learning course. Each notebook explores different ML models, techniques, and preprocessing strategies.

## Housing Price Prediction Project

This project implements a full end-to-end machine learning pipeline to predict housing prices based on California housing data. It includes advanced preprocessing, custom feature engineering, model training, evaluation, and hyperparameter tuning, all built using `scikit-learn`.

### Highlights:
- Custom pipelines with ratio features, log transforms, and geographic similarity via RBF + KMeans
- Usage of various models (LiniarRegression, DecisionTreeRegressor, RandomForest), evaluated via cross-validation
- RMSE confidence intervals estimated via bootstrap resampling (scipy.stats.bootstrap)
- Modular, reusable components following scikit-learn’s API 
