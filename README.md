# 🚢 Survive or Sink: Titanic ML Model

## 📖 Overview
This project aims to predict passenger survival on the Titanic using **Logistic Regression**. The model is trained on the Titanic dataset, which includes various passenger details such as age, gender, fare, and class.

---

## 🛠️ Problem Statement
The Titanic disaster resulted in significant loss of life. The objective of this project is to:
- Analyze the Titanic dataset and preprocess the data.
- Train a **Logistic Regression** model to predict survival.
- Evaluate the model’s performance using accuracy and other metrics.

---

## ✨ Solution
- **Dataset:** The dataset consists of passenger details such as age, gender, ticket class, fare, and survival status.
- **Data Preprocessing:** 
  - Handled missing values.
  - Encoded categorical variables.
  - Normalized numerical features where necessary.
- **Model Training:** 
  - Implemented **Logistic Regression** for classification.
- **Evaluation:** 
  - Assessed performance using accuracy and other relevant metrics.

---

## 📝 Features
- **Survival Prediction Model:** Predicts whether a passenger would survive based on available data.
- **Performance Metrics:** Achieved an accuracy score of **80.97%**.

---

## 📊 Libraries and Tools Used
- **Data Processing:** pandas, numpy
- **Machine Learning:** scikit-learn
- **Visualization:** matplotlib, seaborn

---

## 🚀 How It Works
1. **Input:** The model takes passenger details as input.
2. **Processing:** The data is preprocessed and passed to the trained **Logistic Regression** model.
3. **Output:** The model predicts whether the passenger survived or not.

---

## ⚙️ Output
- The trained **Logistic Regression** model predicts survival probabilities.
- **Model Accuracy:** **80.97%**.
- Performance is evaluated using classification metrics.

---

### 🔥 How to Run the Project
1. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "titanic_logistic regression.ipynb"
3. Test the model with new passenger data.
