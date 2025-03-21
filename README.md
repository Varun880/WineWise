# WineWise
Explores regression and classification to predict white wine quality. Four notebooks handle EDA, Preprocessing, Regression and Classification

## Tasks
- **Regression Task:** Predicting the continuous quality score of wines.
- **Classification Task:** Classifying wines into two categories (e.g., good or bad quality) based on a threshold.

## Models Used
### Regression Models
- **Linear Regression**
- **Random Forest Regression**
- **Support Vector Regression (SVR)**
- **XGBoost Regression**
- **Decision Tree Regression**
- **Artificial Neural Network (ANN) Regression**

### Classification Models
- **Logistic Regression**
- **Random Forest Classifier**
- **Support Vector Classification (SVC)**
- **Naive Bayes**
- **Decision Tree Classifier**
- **Artificial Neural Network (ANN) Classifier**

## Results
### Regression Results
The best-performing model for regression was **XGBoost Regression**, achieving the lowest MSE (0.3495), lowest RMSE (0.5912), and highest R² (0.5488).
### Classification Results
The best-performing model for classification was **Random Forest Classifier**, achieving the highest accuracy (0.86) and AUC-ROC (0.9061). Below is its detailed classification report:
precision    recall  f1-score   support
0       0.93      0.88      0.90       753
1       0.66      0.79      0.72       227
accuracy                           0.86       980
macro avg       0.80      0.83      0.81       980
weighted avg       0.87      0.86      0.86       980
