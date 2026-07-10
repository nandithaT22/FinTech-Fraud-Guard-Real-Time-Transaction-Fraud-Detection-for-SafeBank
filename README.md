# FinTech Fraud Guard: Real-Time Transaction Fraud Detection for SafeBank

## Project Overview

FinTech Fraud Guard is a Machine Learning project developed to detect fraudulent banking transactions in real time. The project uses supervised learning techniques to classify transactions as either **fraudulent** or **legitimate**, helping financial institutions reduce financial losses and improve customer security.

The complete workflow includes data preprocessing, exploratory data analysis, feature engineering, handling class imbalance, model training, evaluation, and prediction.

---

## Objective

Build an end-to-end fraud detection system that:

- Detects fraudulent transactions with high accuracy.
- Minimizes false positives while identifying fraud.
- Handles imbalanced transaction data.
- Demonstrates a complete Machine Learning pipeline.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (RandomOverSampler)

---

## Dataset

The dataset used in this project is:

**Transaction Fraud Detection for SafeBank**

It is loaded directly from GitHub:

https://raw.githubusercontent.com/YBIFoundation/ProjectDataSet/main/Transaction%20Fraud%20Detection%20for%20SafeBank.csv

---

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore and understand the data
4. Perform data visualization
5. Handle missing values
6. Encode categorical variables
7. Split features and target
8. Train-test split
9. Feature scaling using StandardScaler
10. Handle class imbalance using RandomOverSampler
11. Train Machine Learning model(s)
12. Evaluate model performance
13. Predict fraudulent transactions

---

## Data Preprocessing

The preprocessing pipeline includes:

- Handling missing values
- Encoding categorical variables
- Feature scaling
- Train-test splitting
- Balancing classes using RandomOverSampler

These steps improve model performance and reduce bias caused by class imbalance.

---

## Data Visualization

Exploratory Data Analysis (EDA) includes:

- Distribution of transaction amounts
- Fraud vs non-fraud comparison
- Correlation analysis
- Feature distributions
- Transaction pattern visualization

---

## Machine Learning

The project applies supervised Machine Learning techniques for binary classification.

The workflow includes:

- Training the model
- Predicting on unseen data
- Evaluating performance using classification metrics

---

## Evaluation Metrics

Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics provide a comprehensive understanding of the fraud detection model's effectiveness.

---

## Project Structure

```
FinTechFraud.ipynb
README.md
```

---

## How to Run

1. Clone this repository.

```bash
git clone <repository-url>
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

3. Open the notebook.

```bash
jupyter notebook FinTechFraud.ipynb
```

4. Run all cells sequentially.

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- XGBoost or LightGBM implementation
- Real-time API deployment using Flask or FastAPI
- Interactive dashboard using Streamlit
- Model explainability using SHAP or LIME

---

