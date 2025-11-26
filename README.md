# Predicting Hypertension Susceptibility Through Machine Learning

![Clinical image](https://assets.healthpartners.com/is/image/healthpartners/brand-identity/photography/stock/lifestyle/work/getty200489720-2000x666.jpg?wid=2000)

**Overview**  
This project demonstrates how machine learning can predict a patient's hypertension class across five clinically-relevant categories: Normal, Elevated, Stage 1, Stage 2, and Hypertensive Crisis. The analysis uses a modified version of the dataset by Md Raihan Khan from Kaggle.

**Tech stack**
- Python, Jupyter Notebooks  
- pandas, NumPy  
- scikit-learn, statsmodels (where applicable)  
- Seaborn, Matplotlib for visualization

**Objectives**
1. Build a reproducible pipeline for preprocessing, feature engineering, stratified sampling, and modeling.  
2. Compare classical ML models (Logistic Regression, SVM, Random Forest) and a feedforward ANN.  
3. Evaluate clinically meaningful metrics and produce visual diagnostics for stakeholders.

**Dataset**
Source: `khan1803115/hypertension-risk-model-main` on Kaggle. (modified for this study)

**Notebooks**
- `Data Collection and Preprocessing.ipynbb` — EDA, missing values, class distribution, feature correlations
  
Model training, hyperparameter tuning, cross-validation 
- `Logistic Regression.ipynb` — Logistic Regression Implementation 
- `Random Forest.ipynb` — Random Forest implementation 
- `Support Vector Machine.ipynb` — Support Vector Machine Implementation

**Key Results (example)**  
The models were evaluated using accuracy, precision, recall, and F1-score to determine the best-performing classifier. Results showed that the Support Vector Machine (SVM) model achieved the highest performance, obtaining an overall accuracy of 89%, making it the most effective approach for multi-class hypertension prediction in this study.

The Random Forest classifier produced the lowest performance scores, while Logistic Regression delivered mid-range results, performing better than Random Forest but below SVM.

These results demonstrate that SVM is well-suited for handling the dataset's feature patterns and class boundaries. The findings support health professionals by improving early recognition of hypertension categories and contribute to greater public awareness of hypertension risks.
