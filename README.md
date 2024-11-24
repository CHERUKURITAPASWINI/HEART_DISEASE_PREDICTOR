# HEART_DISEASE_PREDICTOR USING EDA & CLASSIFICATION

# Project Overview:

This project uses Python, pandas, and scikit-learn to analyze the framingham.csv dataset, which contains heart disease risk factors and outcomes. Key tasks include data preprocessing, exploratory data analysis (EDA), and classification.

# Dependencies/ Requirements
Before running the code, ensure the following libraries are installed:
- Python (3.7+)
- pandas
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn (imblearn)

Install these dependencies using pip:
  ```bash
  pip install pandas matplotlib seaborn scikit-learn imbalanced-learn
  ```
- All required dependencies are listed in the `requirements.txt` file.
- To install the dependencies, use the following command:
  ```bash
  pip install -r requirements.txt
  ```
# Implementation Steps:

1) Import Data: Load and visualize the dataset.
2) Explore and Visualize: Handle missing values, compute basic statistics, and create visualizations.
3) Feature Selection by PCA: Reduce dimensionality with Principal Component Analysis (PCA).
4) Train/Test Split: Divide the dataset into training (80%) and testing (20%) sets.
5) Resampling: Apply SMOTE, ADASYN, and RandomUnderSampler to address class imbalance.
6) Pipeline and Accuracy Measurement: Build classifiers (Logistic Regression, Decision Tree, KNN, SVM) with resampling, tune hyperparameters with GridSearchCV, and measure accuracy.
7) Print Results: View accuracy scores and classification reports in the Jupyter Notebook.

