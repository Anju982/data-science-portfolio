# 📊 Data Science & Machine Learning Portfolio

Welcome to my data science repository! Here I share my projects, analysis, and machine learning experiments, primarily using **Python** and **Jupyter Notebooks**.

## 🚀 Projects Overview

| Project / Notebook Name | Description | Tech Stack |

| :---------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------- | :----------------------------------------------- |

| **[AML Detection Case Study](<./Anti_Money_Laundering_Transaction_Data_(SAML_D).ipynb>)** | End-to-end pipeline to detect illicit transactions in imbalanced data using behavioral features and SMOTE. | `XGBoost`, `SMOTE`, `Scikit-learn`, `Pandas` |

| **[Credit Scoring & Risk Assessment](<./Credit_Scoring_&_Risk_Assessment.ipynb>)** | Develops a credit scoring model to assess creditworthiness and predict loan default risk. | `Scikit-learn`, `Pandas`, `XGBoost`, `Matplotlib` |

| **[Aviation Predictive Manpower & Delay Analysis](<./Aviation_Predictive_Manpower_&_Delay_Analysis.ipynb>)** | Analyzes aviation data to predict manpower needs and potential flight delays, optimizing operational efficiency. | `Pandas`, `Scikit-learn`, `Matplotlib`, `Seaborn` |

| **[Stock Price Forecasting](./Stock_predict_nuralprhophet.ipynb)** | Time-series forecasting using NeuralProphet to identify market trends and seasonal patterns. | `NeuralProphet`, `PyTorch`, `yfinance`, `Pandas` |

## 🛠️ Technologies & Tools

- **Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Scikit-learn, Imbalanced-learn (SMOTE), XGBoost, NeuralProphet, PyTorch, yfinance, Matplotlib, Seaborn
- **Environment:** Jupyter Lab, Google Colab

## 📂 Project Highlights: AML Detection

This project showcases a robust machine learning approach to a high-volume, highly imbalanced dataset (~0.1% fraud rate).

- **Feature Engineering:** Captured behavioral patterns through temporal rolling windows (velocity, volume).
- **Imbalance Handling:** Implemented SMOTE within a pipeline to prevent data leakage and address class imbalance.
- **Model:** XGBoost Classifier optimized for Precision-Recall (AUPRC).

## 📂 Project Highlights: Stock Price Forecasting

This project implements a time-series forecasting model to predict stock movements by leveraging a hybrid approach.

- **Hybrid Modeling:** Utilized `NeuralProphet`, which combines traditional AR-Net and deep learning (PyTorch) for robust time-series forecasting.
- **Data Integration:** Automated stock data retrieval using `yfinance` to fetch real-time and historical market data.
- **Insight Generation:** Identified seasonal trends and market momentum to provide data-driven trading insights.

## 🤝 How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Anju982/data-science-portfolio.git
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy scikit-learn imbalanced-learn xgboost matplotlib seaborn kagglehub neuralprophet yfinance
    ```
3.  **Launch Jupyter:**
    ```bash
    jupyter notebook
    ```

## 📫 Contact

Feel free to reach out if you have questions or want to collaborate!

- **Email:** anjanaurulugastenna71@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/anjana-urulugastenna-5408a9187/
- **GitHub:** https://github.com/Anju982
- **Website:** https://anjana-urulugastenna.netlify/
