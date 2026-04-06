# 💳 Credit Card Fraud Detection

## 📌 Project Overview

This project aims to detect fraudulent credit card transactions using Machine Learning. The dataset is highly imbalanced, so undersampling is used to balance the data and improve model performance.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Google Colab

---

## 📊 Dataset

* Dataset: Credit Card Fraud Detection (Kaggle)
* Features: 30 numerical features (V1–V28, Time, Amount)
* Target:

  * 0 → Legit Transaction
  * 1 → Fraud Transaction

**Note:** Dataset is not uploaded due to large size. Please download it from Kaggle.

---

## 🔍 Steps Performed

1. Data loading using Pandas
2. Handling missing values (`dropna`)
3. Exploratory Data Analysis
4. Handling imbalanced data using undersampling
5. Feature & target separation
6. Train-test split
7. Model training using Logistic Regression
8. Model evaluation using accuracy score

---

## 🤖 Model Used

* Logistic Regression (`max_iter=1000`)

---

## 📈 Results

* Training Accuracy: ~95%
* Testing Accuracy: ~90%

---

## ⚠️ Important Note

Since the dataset is imbalanced, accuracy alone is not sufficient. Metrics like precision, recall, and F1-score should also be considered for better evaluation.

---

## ▶️ How to Run This Project

### Option 1: Run on Google Colab

1. Download the dataset from Kaggle
2. Upload dataset (`creditcard.csv`) to Colab
3. Open the notebook
4. Ensure file path:

   ```python
   pd.read_csv('/content/creditcard.csv')
   ```
5. Run all cells

---

### Option 2: Run Locally

1. Install dependencies:

   ```bash
   pip install numpy pandas scikit-learn
   ```
2. Place dataset in the same folder
3. Run using Jupyter Notebook

---

## 🚀 Future Improvements

* Use SMOTE instead of undersampling
* Try advanced models (Random Forest, XGBoost)
* Add Precision, Recall, F1-score
* Deploy as a web application
