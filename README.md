# 📊 Machine Learning Projects

A collection of machine learning models developed for various real-world classification problems. Each project includes data preprocessing, model training, evaluation, and predictions using industry-standard ML tools and best practices.

---

## 📁 Projects

### 1. 🎬 Movie Genre Classification

**Notebook**: `Movie-Genre-Classification.ipynb`  
**Objective**: Predict the genre of a movie based on its plot summary.  
**Dataset**: IMDb Genre Classification Dataset  
**Tech Stack**:
- Data Cleaning (Regex, Lowercasing)
- Feature Engineering using `TfidfVectorizer`
- Models: Logistic Regression, Naive Bayes, SVM
- Label Encoding
- Performance Evaluation: Classification Report, Accuracy Score

**Status**: ✅ Completed  
**Output**: `predicted_genres.csv` with predicted genres for test movies.

---

### 2. 📉 Customer Churn Prediction

**Notebook**: `Customer-Churn-Prediction.ipynb`  
**Objective**: Predict whether a customer will leave a telecom company.  
**Dataset**: Telecom Customer Data  
**Tech Stack**:
- Exploratory Data Analysis
- Feature Encoding (Label + OneHot)
- Model: Deep Learning using TensorFlow/Keras
- Evaluation: Accuracy, Loss Curves (Epoch Monitoring)

**Status**: ✅ First Epoch Completed  
**Next Step**: Hyperparameter tuning and regularization

---

### 3. 💳 Credit Card Fraud Detection

**Notebook**: `Credit-Card-Fraud-Detection.ipynb`  
**Objective**: Identify fraudulent credit card transactions.  
**Dataset**: Credit Card Fraud Dataset (imbalanced classes)  
**Tech Stack**:
- Handling Imbalanced Data with `SMOTE` / `class_weight`
- Models: Logistic Regression, Random Forest, XGBoost
- Evaluation Metrics: Precision, Recall, F1-score, ROC-AUC
- Visualization: Confusion Matrix, ROC Curve

**Status**: ✅ Completed  
**Goal**: Maximize recall for fraud detection.

---

## 🔧 How to Use

1. Clone the repository or download notebooks.
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
