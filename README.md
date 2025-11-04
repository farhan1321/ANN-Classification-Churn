# 🧠 ANN Classification – Customer Churn Prediction

### 🔗 Live Demo  
🚀 **Streamlit App:** https://your-streamlit-app-link.streamlit.app  
📂 **GitHub Repo:** https://github.com/your-username/ANN-Classification-Churn

---

## 📖 Project Overview
This project predicts **customer churn** — whether a customer will leave a company — using an **Artificial Neural Network (ANN)** built with TensorFlow and Keras.

Customer churn prediction is essential in industries like telecom, banking, and subscription-based services.  
With this model, businesses can proactively retain customers at risk of leaving.

---

## 🧩 Key Features

- ✅ Artificial Neural Network (ANN) built using **TensorFlow/Keras**
- ✅ **Streamlit Web App** for real-time predictions
- ✅ Data preprocessing (encoding, scaling, splitting)
- ✅ Shows prediction as **"Customer will stay"** or **"Customer will churn"**
- ✅ Fully deployed on Streamlit Cloud

---

## ⚙️ Tech Stack

| Category | Tools Used |
|----------|------------|
| Language | Python |
| ML Framework | TensorFlow / Keras |
| Data Processing | Pandas, NumPy, Scikit-learn |
| Visualization | Matplotlib |
| Web Deployment | Streamlit Cloud |

---

## 🧠 Model Architecture (ANN)

Input Layer (11 features)
↓
Dense Layer (units=6, activation='relu')
↓
Dense Layer (units=6, activation='relu')
↓
Output Layer (units=1, activation='sigmoid')



- **Loss Function:** Binary Crossentropy  
- **Optimizer:** Adam  
- **Evaluation Metric:** Accuracy  

---

## ✅ Data Preprocessing Steps

1. Import dataset
2. Encode categorical columns (Label Encoding & One-Hot Encoding)
3. Standardize numeric values using `StandardScaler`
4. Split dataset → Train (80%) / Test (20%)
5. Train ANN model on training data

---

## 📊 Model Performance

| Metric | Result |
|--------|--------|
| Training Accuracy | ~85% |
| Test Accuracy | ~83% |
| Loss | Stable across epochs |

---

## 🧪 Example Prediction Input

| Feature | Value |
|----------|--------|
| Credit Score | 600 |
| Geography | France |
| Gender | Male |
| Age | 40 |
| Balance | 60000 |
| Tenure | 3 |
| NumOfProducts | 2 |
| HasCrCard | Yes |
| IsActiveMember | Yes |
| EstimatedSalary | 50000 |

**Output:** ✅ Customer likely to stay  
or  
**Output:** ⚠️ Customer likely to churn

---

## 💻 How to Run Locally

```bash
# Clone repository
git clone https://github.com/your-username/ANN-Classification-Churn.git
cd ANN-Classification-Churn

# Install required packages
pip install -r requirements.txt

# Run Streamlit app
streamlit run app.py

📦 Requirements
tensorflow==2.15.0
numpy
pandas
scikit-learn
streamlit
matplotlib

🚀 Deployment (Streamlit Cloud)

✅ Push code to GitHub
✅ Streamlit auto-builds & deploys
No server needed

⭐ Future Enhancements

Add more ML models and compare performance

Use hyperparameter tuning (Keras Tuner)

Convert into a full dashboard with reports

If you like this project, don't forget to star⭐ the repository and follow for more ML/AI projects.

