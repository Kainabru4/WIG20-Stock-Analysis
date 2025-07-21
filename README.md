# Comparative Analysis of Machine Learning Models Effectiveness in Predicting Stock Prices

This project aims to compare SVM's and LSTM's ability to correctly predict time-series data, more precisely prices of WIG20 stock index. It does so using different datasets and time frames. The prediction is based on technical idicators reflecting movement of prices and on sentiment of financial articles related to the index. Project involves preprocessing textual and stock data, performing exploratory data analysis, calculating technical indicators, and building predictive models using deep learning techniques as well as statistical test confirming validity of prediction.

---

---

## 📂 Project Structure

```
data/
├── processed/                   # Cleaned and engineered datasets
│   ├── dataset_1y.csv
│   ├── dataset_5y.csv
│   ├── dataset_binary.csv
│   ├── dataset_neutral.csv
│   ├── dataset_so_pmi.csv
│   ├── sentiment.csv
│   └── technical_indicators.csv
├── raw/                         # Raw data including articles and stock info
│   ├── articledata.json
│   ├── articledata_2.json
│   ├── slownikWydzwieku.csv
│   ├── wig20_5d.csv
│   └── wig20_5w.csv
notebooks/                       # Jupyter notebooks for development
│   ├── datasets.ipynb
│   ├── eda.ipynb
│   ├── indicators.ipynb
│   ├── models.ipynb
│   └── nlp.ipynb
requirements.txt                 # Required packages
```

---

## ⚙️ Installation

Clone the repository:

```powershell
git clone https://github.com/your-username/sentiment-market-prediction.git](https://github.com/Kainabru4/WIG20-Stock-Analysis)
cd WIG20-stock-market prediction
```

Create a virtual environment and install dependencies:

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

---

## 🧪 Notebooks Overview

- `eda.ipynb`: Visualizes sentiment trends and stock performance.
- `indicators.ipynb`: Calculates technical indicators (e.g. RSI, MACD).
- `nlp.ipynb`: Applies NLP to extract sentiment from news articles.
- `datasets.ipynb`: Merges sentiment and financial data into apropiate dataset.
- `models.ipynb`: Trains and evaluates machine learning/LSTM models.

---

## 📊 Data Sources

- **Articles**: JSON files containing news article data.
- **Stock Data**: CSV files containing WIG20 index historical data.
- **Sentiment Dictionary**: Polish sentiment lexicon (slownikWydzwieku.csv).

---

## 🧠 Modeling Approach

The project utilizes:
- Sentiment analysis from news articles.
- Feature engineering from technical indicators.
- SVM and LSTM models for time-series forecasting.
- Evaluation metrics.

---

## 📦 Requirements

See `requirements.txt` for a full list of dependencies, including:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `tensorflow` / `keras`
- `nltk` or `spacy` for NLP

---

## 👥 Author: Filip Urbaniak

---
