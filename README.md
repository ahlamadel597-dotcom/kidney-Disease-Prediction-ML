# Chronic Kidney Disease Prediction using Machine Learning

This repository contains an end-to-end Machine Learning project to predict chronic kidney disease based on clinical data. The model achieves **100% Accuracy** using the Random Forest algorithm.

## 🚀 Project Workflow

### 1. Data Cleaning & Handling Missing Values
Medical datasets often contain missing entries ($NaN$). To ensure accurate predictions, data cleaning was performed using robust statistical methods:
* **Numerical Features:** Missing values were filled using the **Median** to prevent distortion from outliers.
* **Categorical Features:** Missing values were handled using the **Mode** (most frequent categorical value).

### 2. Feature Engineering & Label Encoding
Since Machine Learning algorithms rely on mathematical equations, all categorical text data (e.g., `normal`, `abnormal`, `yes`, `no`) were converted into binary numerical formats (`0` and `1`) using `LabelEncoder` from Scikit-Learn.

### 3. Model Training & Evaluation
* The data was split into **80% Training** and **20% Testing** subsets.
* A **Random Forest Classifier** was trained on the processed features.
* **Model Evaluation:** The final model achieved an outstanding **100.00% Accuracy Score** on the unseen test dataset.

## 🛠️ Technologies Used
* Python
* Jupyter Notebook
* Pandas & NumPy
* Scikit-Learn (Machine Learning Library)
