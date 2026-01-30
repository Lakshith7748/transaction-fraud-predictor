# Transaction Fraud Predictor

A machine learning-powered service designed to detect and flag fraudulent transactions in real-time. This project uses a Random Forest approach (via Scikit-Learn) and serves predictions through a high-performance FastAPI backend.

## 📂 Project Structure

```text
transaction-fraud-predictor/
├── model/
│   ├── train.py       # Script to preprocess data and train the model
│   └── model.pkl      # model which predicts
├── data/
│   └── transactions.csv 
├── api/
│   └── main.py        # FastAPI application and endpoints
├── README.md          
└── requirements.txt   
