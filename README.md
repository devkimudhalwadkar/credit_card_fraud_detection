# 💳 Credit Card Fraud Detection Dashboard 🔒  
Built with ❤️ by [devkimudhalwadkar](https://github.com/devkimudhalwadkar)

---

## 🚀 Overview

Every second, thousands of credit card transactions flow through global systems. But some of them are fraudulent—and that's where this project steps in.  
This interactive Streamlit dashboard visualizes and detects potential **fraudulent credit card transactions** using machine learning and synthetic analytics.

> Real-world defense meets data science elegance.

---

## 🧠 Key Features

- 📊 **Interactive Visualizations** (Plotly)
  - Transaction Amount Distribution
  - Time-of-Day Patterns
  - Distance vs. Amount
  - Fraud Trend Over Time

- 🛠️ **ML Pipeline**
  - Random Forest-based classification
  - Feature scaling and one-hot encoding
  - Model serialization with `joblib`

- 🔍 **Feature Engineering**
  - Velocity, frequency, night/weekend detection, and more
  - Custom synthetic data fields like `Distance_from_Home`, `Transaction_Velocity`

- 🌐 **Streamlit UI**
  - Custom CSS styling for fraud alerts 🚨
  - Clean, responsive layout with real-time interactivity

---

## 📥 Dataset Download

This project uses the **[Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)** from Kaggle.  
To use the project:

1. **Sign in to Kaggle**
2. Navigate to the dataset: [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
3. Click on **"Download"**
4. Place the `creditcard.csv` file in the root of this project directory

> 🗂️ The app expects the file to be named exactly `creditcard.csv`

---

## 📂 How to Run

```bash
# Clone the repo
git clone https://github.com/devkimudhalwadkar/credit-card-fraud-dashboard.git
cd credit-card-fraud-dashboard

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
