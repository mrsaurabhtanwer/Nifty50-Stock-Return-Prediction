# 📊 Nifty50 Stock Return Prediction

![GitHub last commit](https://img.shields.io/github/last-commit/mrsaurabhtanwer/Nifty50-Stock-Return-Prediction)
![GitHub repo size](https://img.shields.io/github/repo-size/mrsaurabhtanwer/Nifty50-Stock-Return-Prediction)
![GitHub stars](https://img.shields.io/github/stars/mrsaurabhtanwer/Nifty50-Stock-Return-Prediction?style=social)
![GitHub forks](https://img.shields.io/github/forks/mrsaurabhtanwer/Nifty50-Stock-Return-Prediction?style=social)

An end-to-end stock return prediction project using machine learning on 20 years of historical Nifty50 data. Built as part of a Data Science & AI Capstone Project.

---

## 🚀 Problem Statement
Analyze 2 decades of Nifty 50 stock data and devise strategies to build a portfolio that maximizes future returns.

---

## 🧠 Project Highlights

- ✅ Merged & cleaned 50 individual CSVs from Nifty 50 companies
- ✅ Engineered features like returns & volatility
- ✅ Labeled target for high return (>1%) in next 7 days
- ✅ Built and tuned ML models (Random Forest, Logistic Regression)
- ✅ Evaluated via accuracy, recall, and confusion matrix
- ✅ Built Streamlit app for interactive predictions

---

## 📂 Folder Structure
```
Nifty50-Stock-Return-Prediction/
├── data/
│   └── cleaned_fintech_data.csv
├── models/
│   └── nifty50_rf_model.pkl
├── notebooks/
│   └── Exploratory & Modeling Notebook.ipynb
├── app/
│   └── streamlit_app.py
├── README.md
└── requirements.txt
```

---

## 🧪 Model Performance
| Metric     | Value  |
|------------|--------|
| Accuracy   | ~52%   |
| Recall (1) | ~63%   |
| Precision (1) | ~54% |

---

## 💻 Streamlit Dashboard
> Predicts whether a stock will give >1% return in 7 days based on recent performance.

To run locally:
```bash
pip install -r requirements.txt
streamlit run app/streamlit_app.py
```

---

## 📈 Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, Imbalanced-learn
- Streamlit
- Matplotlib / Seaborn

---

## ✍️ Author
**Saurabh Tanwer**  
[GitHub: @mrsaurabhtanwer](https://github.com/mrsaurabhtanwer)

---

## 📌 License
This project is open-source and free to use for educational or research purposes.

