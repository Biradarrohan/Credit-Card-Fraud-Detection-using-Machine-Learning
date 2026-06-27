# Credit Card Fraud Detection using Machine Learning

## Project Overview

This project detects fraudulent credit card transactions using two unsupervised machine learning algorithms:

- Isolation Forest
- Local Outlier Factor (LOF)

The objective is to identify abnormal transactions that may represent fraud. Since fraudulent transactions are very rare compared to normal transactions, anomaly detection techniques are used instead of traditional supervised classification.

---

## Dataset

Dataset: Credit Card Fraud Detection Dataset

Features:
- Time
- V1–V28 (PCA transformed features)
- Amount
- Class

Target Variable:
- 0 = Genuine Transaction
- 1 = Fraudulent Transaction

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## Machine Learning Algorithms

### 1. Isolation Forest

Isolation Forest detects anomalies by randomly partitioning the data. Fraudulent transactions are isolated faster than normal transactions.

### 2. Local Outlier Factor (LOF)

LOF compares each transaction with its neighboring data points and detects transactions with significantly lower local density as anomalies.

---

## Project Workflow

1. Load the dataset.
2. Sample 20% of the data for faster processing.
3. Perform Exploratory Data Analysis (EDA).
4. Visualize feature distributions using histograms.
5. Generate a correlation heatmap.
6. Separate fraud and genuine transactions.
7. Prepare feature matrix (X) and target labels (Y).
8. Train Isolation Forest and LOF models.
9. Predict fraudulent transactions.
10. Evaluate using Accuracy and Classification Report.

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score

---

## Project Structure

```
CreditCardFraudDetection/
│
├── creditcard.csv
├── fraud_detection.py
├── README.md
├── requirements.txt
└── images/
    ├── histogram.png
    └── heatmap.png
```

---

## Installation

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn
```

---

## Run the Project

```bash
python fraud_detection.py
```

---

## Expected Output

- Fraud case count
- Genuine transaction count
- Histograms
- Correlation heatmap
- Accuracy score
- Classification report
- Comparison of Isolation Forest and LOF performance

---

## Future Improvements

- Implement supervised models such as Random Forest, XGBoost, and LightGBM.
- Build a real-time fraud detection API using Flask or FastAPI.
- Develop a web dashboard using Streamlit.
- Perform hyperparameter tuning for improved performance.
- Deploy the model on cloud platforms such as AWS, Azure, or Google Cloud.

---

## Applications

- Banking systems
- Credit card companies
- Digital payment platforms
- Financial institutions
- Insurance fraud detection
- Online transaction monitoring

---

## Author

Rohankumar Biradar

B.E. Computer Science (AI & ML)

Machine Learning | Data Science | Python
