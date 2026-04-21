# 🏦 Customer Churn Prediction using ANN

## 📌 Project Overview
This project predicts whether a bank customer will leave (churn) or stay using an Artificial Neural Network (ANN).

---

## 🎯 Objective
- Predict customer churn (0 = No, 1 = Yes)
- Help businesses take proactive actions

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Streamlit

---

## 📊 Dataset Features
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

**Target:** Exited (1 = Churn, 0 = No Churn)

---

## ⚙️ Steps Performed

### 1. Data Preprocessing
- Removed unnecessary columns
- Encoded categorical variables:
  - Gender → Label Encoding
  - Geography → One-Hot Encoding
- Feature scaling using StandardScaler

---

### 2. Train-Test Split
- 80% training, 20% testing

---

### 3. Model Building (ANN)
- Multiple Dense layers
- ReLU activation for hidden layers
- Sigmoid activation for output

---

### 4. Model Compilation
- Optimizer: Adam
- Loss: Binary Crossentropy
- Metric: Accuracy

---

### 5. Model Training
- Batch size: 32
- Epochs: 150

---

### 6. Model Evaluation
- Accuracy Score
- Confusion Matrix

---

### 7. Deployment
- Built using Streamlit
- Takes user input and predicts churn

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
streamlit run app.py