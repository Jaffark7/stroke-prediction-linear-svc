# Stroke Prediction with LinearSVC

This repository contains an educational machine learning project demonstrating a complete supervised classification pipeline using **LinearSVC** and the **Stroke Prediction Dataset** from Kaggle.

The notebook walks through all essential steps of an ML workflow:

## What this project covers

- Loading a real-world healthcare dataset  
- Handling missing values  
- Encoding categorical features (OneHotEncoder)  
- Scaling numeric features (StandardScaler)  
- Building a clean preprocessing + model Pipeline  
- Training a LinearSVC classifier  
- Evaluating the model using:
  - Accuracy
  - Confusion matrix
  - Precision, recall, F1-score  

## Goal of the project

This repository is intended for **learning and teaching purposes**, serving as a simple but complete example of how to build, train, and evaluate a supervised classification model using scikit-learn.

## Technologies Used

- Python  
- Pandas  
- scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

## Results Summary

The model achieved strong overall accuracy (≈95%), but detecting stroke cases remains challenging due to data imbalance. Future work may include:

- Class balancing techniques  
- Hyperparameter tuning  
- Trying non-linear models (SVC with RBF kernel)  
- Comparing with Logistic Regression or Random Forest  

---

To view the full implementation, open the notebook:
`stroke_prediction_linear_svc.ipynb`
