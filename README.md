# ElevateLabs_Task4_Logistic Regression – Breast Cancer Classification

## Objective
  Build a binary classification model using Logistic Regression to predict whether a tumor is Malignant (M) or Benign (B) based on features extracted from breast mass cell nuclei.

  Dataset:https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data


## Tools & Libraries
  -Python 

  -Pandas, NumPy


  -Matplotlib, Seaborn

  -Scikit-learn (LogisticRegression, metrics, preprocessing)

## Steps Performed
1. Data Preprocessing
      -Removed unnecessary columns (id, Unnamed: 32)

  -Converted diagnosis column to binary

  -Checked and handled missing values

2. Feature Scaling

  -Used StandardScaler to normalize all numerical features

3. Feature Scaling

  -Used StandardScaler to normalize all numerical features

4. Model Training

  -Applied LogisticRegression with max_iter=10000 to ensure convergence

5. Model Evaluation

  Evaluated with:

  -Confusion Matrix

  -Classification Report (Precision, Recall, F1-score)

  -ROC Curve and ROC AUC Score

6. Threshold Tuning

  -Demonstrated how changing the classification threshold affects predictions

7. Sigmoid Function Visualization

  -Plotted the sigmoid function to explain how logistic regression outputs probabilities

## Model Performance

  Accuracy       : 97%

  Precision (M)  : 0.98
  Recall (M)     : 0.95

  ROC AUC Score  : 0.997

## Visualizations Included

  -ROC Curve

  -Confusion Matrix (default and threshold-adjusted)

  -Sigmoid function plot


