# 🏡 House Price Classification

This project focuses on building a complete **supervised machine learning pipeline** to classify houses as **expensive or not expensive**, based on structured housing data.

The project was originally developed during my Data Science Bootcamp at **WBS Coding School** and later refined for portfolio presentation.

---

## 🎯 Problem Statement

Given a set of house features such as size, number of rooms, age, and location-related attributes,  
the goal is to predict whether a house belongs to a **high-price category**.

This is formulated as a **binary classification problem**.

---

## 🧠 Approach

The project follows a full end-to-end machine learning workflow:

1. **Exploratory Data Analysis (EDA)**
2. **Data preprocessing and feature engineering**
3. **Automated preprocessing pipelines**
4. **Model training and hyperparameter tuning**
5. **Model evaluation and comparison**

Special emphasis was placed on **clean pipeline design** and **reproducibility**.

---

## ⚙️ Machine Learning Pipeline

- Implemented **scikit-learn Pipelines** combined with **ColumnTransformer**
- Different preprocessing steps for:
  - Numerical features (scaling)
  - Categorical features (encoding)
  - Ordinal features (ordering)
- End-to-end automation from raw data to prediction

---

## 🤖 Models Trained

Multiple supervised learning models were trained and compared:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  

**GridSearchCV** was used to optimize hyperparameters for each model.

---

## 📊 Evaluation

Models were evaluated using multiple metrics to ensure balanced performance:

- Accuracy  
- Precision  
- Recall  
- F1-Score  

Additional analysis included:
- Confusion matrices
- Feature importance analysis for tree-based models

---

## 🏁 Results & Insights

- Performance varied significantly across models, highlighting the importance of proper model selection.
- Tree-based models provided better interpretability through feature importance.
- The final selected model achieved a balanced trade-off between **precision and recall**, making it suitable for real-world decision-making.

---

## 🗂 Project Structure

```
house_price_classification/
├── data/
│ ├── raw/
|   ├── housing_classification_full.csv
│ └── test/
|   ├── test_set.csv
├── notebooks/
│ └── house_price_classification.ipynb
└── README.md
```

---

## 🛠 Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📌 Key Takeaways

- Hands-on experience with end-to-end supervised learning workflows
- Strong understanding of preprocessing pipelines and model evaluation
- Ability to compare multiple models and justify final model selection
