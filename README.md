# Heart Disease Classification using Decision Tree (CART)

## Project Overview
This project applies **Decision Tree (CART)** classification on the Heart Disease dataset.  
It includes preprocessing, model training, evaluation, and comparison with **KNN**.  
The goal is to explore split criteria (Gini vs Entropy), impurity measures, and workflow best practices.


## Workflow
1. **Data Preprocessing**
   - Removed duplicates
   - Applied one-hot encoding for categorical features
   - Train/test split setup

2. **Model Training**
   - Implemented Decision Tree (CART)
   - Compared Gini Index vs Entropy criteria

3. **Evaluation**
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1-score, ROC-AUC
   - Cross-validation for stability

4. **Comparison**
   - Benchmarked CART against KNN
   - Documented differences in performance and split criteria

## Results
- CART achieved strong classification performance with interpretable splits.
- KNN provided a useful baseline for comparison.
- Feature importance highlighted key predictors (e.g., age, cholesterol, etc.).
