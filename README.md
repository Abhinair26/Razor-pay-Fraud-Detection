---

## 🛡️ Razorpay Fraud Detection using Machine Learning

### 📌 Project Description

This project detects fraudulent credit card transactions using machine learning techniques. The goal is to help payment platforms like Razorpay prevent unauthorized activity and reduce financial risk. A dataset of anonymized transaction records was analyzed to build a classification model.

---

### 📁 Dataset

* **Source:** [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
* **Features:**

  * V1–V28: PCA-transformed features
  * Amount: Transaction amount
  * Class: 0 = legitimate, 1 = fraud

---

### 🔍 Exploratory Data Analysis

* Checked for missing values
* Visualized class imbalance
* Scaled the `Amount` feature
* Used correlation matrix to identify patterns

---

### ⚙️ Techniques Used

* Data Preprocessing (StandardScaler)
* Handling Imbalanced Data (Random UnderSampling)
* Model Training (Random Forest)
* Model Evaluation (Confusion Matrix, Classification Report)

---

### 📈 Model Performance

* Achieved high precision and recall on balanced test data
* Evaluated using:

  * Accuracy
  * Precision, Recall, F1-score
  * ROC Curve

---

### 🧰 Libraries Used

* `pandas`, `numpy`, `matplotlib`, `seaborn`
* `scikit-learn`
* `imblearn` for undersampling

---

### 💡 How to Run

```bash
git clone https://github.com/yourusername/razorpay-fraud-detection.git
cd razorpay-fraud-detection
pip install -r requirements.txt
python fraud_detection.py
```

---

### 📊 Output

* Confusion Matrix
* Classification Report
* Fraud detection summary

---

### ✍️ Author

Abhijith Nair
[LinkedIn](#) | [GitHub](#)

---
