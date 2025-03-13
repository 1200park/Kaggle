# Kaggle

# Smoking Prediction Ensemble Model

## Overview
This project aims to predict smoking status using an ensemble of machine learning models. The approach involves training multiple models, optimizing their weights, and combining predictions to improve accuracy.

## Process
1. **Data Preprocessing**: Load and clean the dataset.
2. **Cross-validation**: Use K-Fold cross-validation to split the dataset.
3. **Model Training**:
   - Train multiple models including XGBoost, LightGBM, CatBoost, and Artificial Neural Networks (ANN).
4. **Hyperparameter Optimization**: Utilize Optuna for optimal model parameters.
5. **Ensemble Learning**:
   - Use stacking and weighted averaging to combine predictions.
   - Optimize weight allocation for ensemble using Optuna.
6. **Feature Importance Analysis**: Visualize feature contributions using XGBoost and LightGBM.
7. **Final Prediction**: Generate and save predictions for submission.


## Author
[Passion Raccoon]
