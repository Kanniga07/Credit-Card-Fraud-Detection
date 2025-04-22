# 💳 Credit Card Fraud Detection

A Machine Learning project to detect fraudulent credit card transactions using Logistic Regression. This project uses publicly available datasets: `fraudTrain.csv` and `fraudTest.csv`.

---

## 📁 Dataset

- `fraudTrain.csv` – Training data with labeled fraud transactions.
- `fraudTest.csv` – Testing data to evaluate model performance.

These files should be downloaded from [Kaggle – Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection) and placed in the project directory.

---

## 🚀 Features

- Data preprocessing and feature engineering
- One-hot encoding for categorical features
- Logistic Regression classifier
- Evaluation metrics: Accuracy, Confusion Matrix, and Classification Report
- Visualization using Seaborn and Matplotlib

---

## 📊 Model Used

**Logistic Regression** – A statistical model used for binary classification. Suitable for a baseline fraud detection system.

---

## 🛠️ Installation

Make sure you have Python 3.x installed. Then install the dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

---

▶️ How to Run:
1. Clone this repository:

git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection

2. Place fraudTrain.csv and fraudTest.csv inside the project folder.

3. Run the Python script:

python fraud_detection.py

---

📊 Output Includes:

✅ Accuracy Score

🧾 Classification Report

📉 Confusion Matrix (text + heatmap)

---

📂 Folder Structure

credit-card-fraud-detection/
│
├── fraudTrain.csv
├── fraudTest.csv
├── fraud_detection.py
└── README.md

---

📚 Future Improvements

Try other classifiers (Random Forest, XGBoost)

Balance dataset using SMOTE or other techniques

Build a frontend using Streamlit or Flask

---

🧑‍💻 Author

Kanniga Saraswathy M
Final-year B.Tech in AI & Data Science

---
