# 🧠 Diabetes Detection Using XGBoost and Artificial Neural Networks (ANNs)

This project aims to detect the likelihood of diabetes in individuals using machine learning models, specifically **XGBoost** and **Artificial Neural Networks (ANNs)**. The dataset used is the well-known **Pima Indians Diabetes Dataset**.

## 📊 Dataset

- **Source:** [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Attributes:** 8 features including Glucose, BMI, Age, etc.
- **Target:** Outcome (0 = No Diabetes, 1 = Diabetes)

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

## 🚀 Results

- **XGBoost Accuracy:** ~79%
- **ANN Accuracy:** ~78%
- Both models showed promising predictive capabilities, with XGBoost slightly outperforming ANN.

## 📈 Visualization

- Correlation Heatmaps
- Distribution plots for target variable
- Loss and Accuracy Curves for ANN
