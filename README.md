# Water Quality Analysis Project 🌊

## Overview
This project analyzes drinking water quality data using machine learning to classify water samples. 🔍

## Technologies Used 🛠️
- Python 3.x
- pandas & numpy
- matplotlib & seaborn
- scikit-learn
- scipy

## Quick Start 🚀
```python
# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

## Data Processing Steps 🔄
1. Data cleaning and preprocessing
2. Feature transformation
3. Handling class imbalance
4. Model training and evaluation

## Models Implemented 🤖
- Random Forest Classifier (Selected as final model)
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

## Key Features 📊
- Water quality parameters:
  - Residual Free Chlorine
  - Turbidity
  - Fluoride
  - Coliform
  - E.coli

## Results 📈
Multiple models were tested, with Random Forest Classifier chosen as the final model due to its superior performance:
- Random Forest(RF): Highest accuracy (95%+)
- SVM: Good but lower than RF
- KNN: Lower accuracy than RF
- Decision Tree: Lower accuracy than RF

## Model Selection ⭐
Random Forest was selected as the final model because:
- Highest accuracy among all tested models
- Better handling of feature importance
- Good performance with our dataset size
- Robust against overfitting
