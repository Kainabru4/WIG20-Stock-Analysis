# Sentiment-Driven Market Prediction

This project explores the relationship between financial sentiment and stock market movements using NLP and time-series modeling. It involves preprocessing textual and stock data, performing exploratory data analysis, calculating technical indicators, and building predictive models using deep learning techniques.

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
logs/                            # Training logs
lstm_directory/                  # LSTM tuning files
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

```bash
git clone https://github.com/your-username/sentiment-market-prediction.git
cd sentiment-market-prediction
```

Create a virtual environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
```

---

## 🧪 Notebooks Overview

- `datasets.ipynb`: Loads and merges raw sentiment and financial data.
- `eda.ipynb`: Visualizes sentiment trends and stock performance.
- `indicators.ipynb`: Calculates technical indicators (e.g. RSI, MACD).
- `models.ipynb`: Trains and evaluates machine learning/LSTM models.
- `nlp.ipynb`: Applies NLP to extract sentiment from news articles.

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
- LSTM models for time-series forecasting.
- Evaluation metrics such as accuracy, precision, and AUC.

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

## 👥 Authors

- [Your Name] - NLP & Modeling
- [Collaborator] - Data Collection & EDA

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

- NBP (National Bank of Poland) for sentiment dictionary
- Warsaw Stock Exchange (GPW) for WIG20 data
