# 🚀 Mini Project : Diabetes Detection using XGBoost, Neural Networks, and Logistic Regression : 

This project aims to detect the likelihood of diabetes in individuals using machine learning models, specifically **XGBoost** and **Artificial Neural Networks (ANNs)** and **Logistic regression**. The dataset used is the well-known **Pima Indians Diabetes Dataset**.

## 📊 Dataset Description

This dataset is used to predict whether or not a patient has diabetes, based on given features/diagnostic measurements.
- **Source:** [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Only female patients are considered, all at least 21 years old, of Pima Indian heritage.

### Input Features:
- **Pregnancies**: Number of times pregnant
- **GlucosePlasma**: Glucose concentration measured 2 hours after an oral glucose tolerance test
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **Skin**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body Mass Index (weight in kg / (height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function (genetic predisposition)
- **Age**: Age in years

### Output:
- **Diabetes** status: 0 (no diabetes) or 1 (diabetes)

## 🛠️ Technologies Used

- **Python**
- **NumPy, Pandas** – Data Manipulation
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – Preprocessing and Model Evaluation
- **XGBoost** – Gradient Boosting Model
- **Keras (TensorFlow backend)** – Deep Learning with ANNs

## 📌 Project Workflow

1. **Data Cleaning & Preprocessing**
   - Handled zero-values in critical columns like Glucose and BMI.
   - Normalized the data using MinMaxScaler.

2. **Model 1: XGBoost Classifier**
   - Tuned for maximum accuracy.
   - Evaluated using accuracy score and classification report.

3. **Model 2: ANN (Keras)**
   - 3-layered dense network with ReLU and sigmoid activation.
   - Compiled with binary cross-entropy loss and Adam optimizer.

4. **Performance Evaluation**
   - Accuracy, Confusion Matrix, and Classification Reports used.
   - Compared both models for robustness.

## 🚀 Results : 

- **XGBoost Accuracy:** ~79%
- **ANN Accuracy:** ~78%
- Both models showed promising predictive capabilities, with XGBoost slightly outperforming ANN.

## 📈 Visualization : 

- Correlation Heatmaps
- Distribution plots for target variable
- Loss and Accuracy Curves for ANN

## Run the notebook : 

jupyter notebook "Diabetes Detection Using XGBoost and ANNs.ipynb"

