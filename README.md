# IEEE-CIS Fraud Detection using XGBoost

## 📌 Project Overview
This project implements a **fraud detection system** using the **IEEE-CIS Fraud Detection dataset**. The objective is to classify transactions as **fraudulent** or **legitimate** by leveraging advanced machine learning techniques, with **XGBoost** as the primary model.

The IEEE-CIS dataset is known for its high dimensionality and anonymized features, making it a strong real-world benchmark for tabular fraud detection problems.

---

## 🧠 Model Used
- **Algorithm:** XGBoost (Extreme Gradient Boosting)
- **Problem Type:** Binary Classification (Fraud vs Non-Fraud)
- **Evaluation Metric:** Accuracy

---

## 📊 Model Performance
- **Final Accuracy:** **98%**

> Accuracy is reported on the validation / test split after preprocessing and feature engineering.

---

## 🗂️ Dataset Information
The dataset used in this project comes from Kaggle's official IEEE-CIS competition.

- **Competition Page:**  
  https://www.kaggle.com/competitions/ieee-fraud-detection

- **Datasets Included:**
  - `train_transaction.csv`
  - `train_identity.csv`
  - `test_transaction.csv`
  - `test_identity.csv`

⚠️ **Important:** Due to size constraints, datasets are **not included in this repository**. Please download them directly from Kaggle.

---

## ⚙️ Workflow
1. Data loading and merging (transaction + identity)
2. Missing value handling
3. Feature engineering
4. Encoding categorical variables
5. Train-validation split
6. Model training using XGBoost
7. Model evaluation

---

## 🧪 Libraries & Tools
- Python
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/Naman0911/IEEE-CIS-Fraud-Pedict.git

# Navigate into the project
cd IEEE-CIS-Fraud-Pedict

# Install dependencies
pip install -r requirements.txt

# Run training script
python train.py
```

---

## 📁 Project Structure
```
├── data/               # Dataset directory (ignored in git)
├── notebooks/          # EDA and experiments
├── src/                # Source code
├── models/             # Trained models
├── requirements.txt
└── README.md
```

---

## 👤 Author
**Naman Upadhyay**

---

## ⭐ Acknowledgements
- Kaggle
- IEEE-CIS Fraud Detection Competition
- XGBoost Documentation
