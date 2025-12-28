# 🚢 Titanic: Survival Prediction

## 📌 Project Overview

This project aims to predict the survival of passengers aboard the **Titanic** using various **classification algorithms**. The objective is to compare multiple models and identify the best-performing one after applying proper data preprocessing techniques.

An end-to-end machine learning pipeline was followed, including data cleaning, preprocessing, model training, and performance evaluation.

---

## 📊 Dataset

* **Source:** Kaggle
* **Dataset:** Titanic – Machine Learning from Disaster
* **Description:**
  The dataset contains passenger information such as age, gender, ticket class, fare, embarkation port, and survival status.

---

## 🔍 Data Preprocessing

Before training the models, several preprocessing steps were applied to ensure data quality and optimal model performance:

* **Handling missing values**
* **Label Encoding** for categorical variables
* **Standardization (Feature Scaling)** to normalize numerical features
* **Train-test split** for model evaluation

These steps were crucial, especially for distance-based and margin-based models.

---

## 🤖 Models Implemented

The following **five classification models** were trained and evaluated:

1. **Logistic Regression**
2. **Naive Bayes**
3. **Decision Tree Classifier**
4. **K-Nearest Neighbors (KNN)**
5. **Support Vector Machine (SVM)**

Each model was trained using the same preprocessed dataset to ensure a fair comparison.

---

## 📈 Model Evaluation

The models were evaluated using appropriate classification metrics such as accuracy, precision, recall, and F1-score.

### 🔎 Key Findings:

* Logistic Regression and Naive Bayes provided reasonable baseline performance
* Decision Tree showed signs of overfitting
* KNN performance was sensitive to feature scaling
* **Support Vector Machine (SVM) achieved the best overall performance**

---

## ✅ Conclusion

* Proper preprocessing significantly improved model performance
* Comparing multiple classifiers helps in selecting the most suitable model
* **SVM emerged as the best-performing model** for Titanic survival prediction

---

## 🧠 Learning Outcomes

* Practical experience with classification algorithms
* Importance of data preprocessing and standardization
* Model comparison and performance analysis
* Understanding strengths and weaknesses of different classifiers

---



## 🚀 Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Cross-validation
* Ensemble methods (Random Forest, XGBoost)
* Feature engineering

