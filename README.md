# Diabetes Prediction using Machine Learning

## Overview
This project aims to predict the likelihood of a person having diabetes using machine learning models trained on medical diagnostic data. The dataset includes key health indicators such as glucose levels, blood pressure, BMI, and age.

## Dataset
- **Source:** Pima Indians Diabetes Dataset from Kaggle.
- **Features:** Includes attributes like glucose level, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, age, and outcome (diabetes presence).
- **Preprocessing:** 
  - Handled missing values using mean/mode imputation.
  - Standardized numerical features for better model performance.

## Methodology
1. **Exploratory Data Analysis (EDA):** 
   - Analyzed feature distributions and correlations.
   - Visualized relationships between features and diabetes diagnosis.

2. **Feature Engineering:** 
   - Scaled numerical data using StandardScaler.
   - Applied feature selection techniques to improve model efficiency.

3. **Model Training & Evaluation:**  
   - Trained various classification models: 
     - Logistic Regression
     - Random Forest
     - Support Vector Machine (SVM)
     - XGBoost
   - Evaluated models using accuracy, precision, recall, and F1-score.

## Results
- Achieved **85% accuracy** with the Random Forest model.
- Identified glucose levels and BMI as key predictors of diabetes.
- Developed an interactive confusion matrix to visualize classification performance.

## Technologies Used
- **Programming Languages:** Python
- **Libraries & Frameworks:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning Models:** Logistic Regression, Random Forest, SVM, XGBoost
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC

## Future Improvements
- Collect a more diverse dataset for better generalization.
- Implement deep learning models (e.g., ANN) for improved accuracy.
- Deploy the model as a web app using Flask or Streamlit.
