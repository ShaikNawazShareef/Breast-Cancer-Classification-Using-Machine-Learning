# 🎗️ Breast Cancer Classification Using Machine Learning

## 📌 Project Overview
This project focuses on predicting breast cancer classifications using Supervised Machine Learning algorithms. The Breast Cancer dataset is used to train and evaluate multiple classification models to identify whether a tumor is **Benign or Malignant**.

## 🎯 Project Objectives
- 🧹 Perform data preprocessing and cleaning.
- 🔍 Handle missing values.
- 🔢 Convert categorical data into numerical values.
- 🤖 Train multiple Machine Learning classification models.
- 📊 Evaluate and compare model performance.

## 🛠️ Technologies Used
- 🐍 Python
- ☁️ Google Colab
- 🐼 Pandas
- 🔢 NumPy
- 🤖 Scikit-learn
- 📈 Matplotlib

## 📂 Dataset
**Dataset Name:** `breast-cancer.data`

The dataset contains patient-related features used to predict breast cancer classification.

## ⚙️ Data Preprocessing
1. 📤 Upload the dataset using Google Colab.
2. 📖 Read the CSV file using Pandas.
3. 🔍 Check missing values using `isna()`.
4. 🧹 Handle missing values using `SimpleImputer`.
5. 🔠 Convert categorical values into numerical values using `LabelEncoder`.
6. 🎯 Separate input features (X) and target variable (Y).
7. ✂️ Split the dataset into training and testing sets using `train_test_split`.

## 🤖 Machine Learning Models

This project implements **7 model configurations using 6 different classification algorithms**.

| 🔢 No. | 🤖 Model | ⚙️ Configuration |
|---|---|---|
| 1 | Perceptron | L1 Regularization |
| 2 | Logistic Regression | Default |
| 3 | Decision Tree | Entropy |
| 4 | Decision Tree | Gini (CART) |
| 5 | Support Vector Machine (SVM) | Polynomial Kernel |
| 6 | K-Nearest Neighbors (KNN) | K = 3 |
| 7 | Gaussian Naive Bayes | GaussianNB |

## 📊 Model Evaluation Metrics
The models are evaluated using the following performance metrics:

- 🎯 Accuracy Score
- 📋 Confusion Matrix
- 🔍 Precision Score
- 📈 Recall Score
- ⚖️ F1 Score

Both training and testing accuracy are calculated to understand model performance.

## ✂️ Train-Test Split
- 🟦 Training Data: 70%
- 🟩 Testing Data: 30%
- 🔄 Random State: 2

## 🔄 Project Workflow
1. 📤 Dataset Upload
2. 📖 Data Loading
3. 🔍 Missing Value Detection
4. 🧹 Data Cleaning
5. 🔠 Label Encoding
6. 🎯 Feature and Target Separation
7. ✂️ Train-Test Splitting
8. 🤖 Model Training
9. 🔮 Model Prediction
10. 📊 Performance Evaluation
11. 🏆 Model Comparison

## 📦 Libraries Installation

```bash
pip install pandas numpy scikit-learn matplotlib
```

## 🚀 How to Run
1. 📥 Clone this repository.
2. 📓 Open the project in Google Colab or Jupyter Notebook.
3. 📤 Upload the `breast-cancer.data` dataset.
4. ▶️ Execute the notebook cells sequentially.
5. 📊 Review the model accuracy and evaluation results.

## 📝 Conclusion
This project demonstrates the implementation of multiple Supervised Machine Learning classification algorithms for breast cancer classification.

It provides practical experience in:
- Data preprocessing
- Handling missing values
- Feature encoding
- Model training and prediction
- Model evaluation and comparison

## 👨‍💻 Author
Nawaz Shareef Shaik
**Machine Learning Project – Breast Cancer Classification**

⭐ If you find this project useful, don't forget to star the repository!
