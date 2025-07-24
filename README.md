# Wine Quality Prediction – ML

A machine learning project that predicts the quality of wine based on its chemical properties.

This project demonstrates a complete applied data science workflow — **ETL (Extract, Transform, Load)**, **exploratory data analysis (EDA)**, **model training**, and **evaluation**.

---

## ETL Workflow

- **Extract**: Load the Wine Quality datasets (`winequality-red.csv`, `winequality-white.csv`).
- **Transform**: Handle missing values, scale features, and split data into training and testing sets.
- **Load**: Save the trained best model (`best_model.pkl`) for later predictions.

---

## Features

- **Data Preprocessing**: Cleaning, feature scaling, and handling missing values.
- **Exploratory Data Analysis**: Visualizing distributions and correlations.
- **Machine Learning Models**:
  - Logistic Regression
  - Random Forest with hyperparameter tuning (GridSearchCV)
- **Evaluation Metrics**: Accuracy, precision, recall, F1-score, and confusion matrix.

---

## Results

- Random Forest achieved higher accuracy and F1-score compared to Logistic Regression.
- Final trained model saved as `best_model.pkl`.

---

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/TanayKumar76/WineQualityPrediction-ML.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the Jupyter notebook and run all cells:
    ```bash
    jupyter notebook WQP.ipynb
    ```

---

## Purpose

This project serves as a demonstration of applied machine learning and data visualization skills, highlighting a solid understanding of **ETL processes**, **supervised learning**, and **model evaluation**.
