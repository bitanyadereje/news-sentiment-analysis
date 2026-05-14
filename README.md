# News Sentiment Analysis – Nova Financial Solutions

**Predicting stock price movements using financial news sentiment.**  
This project builds an analytical pipeline to quantify news sentiment, compute technical indicators, and measure correlation with daily stock returns


## Tasks Overview

- **Task 1 (EDA):** Load and explore financial news dataset (1.4M headlines, 2009‑2020).  
  - Analyzed headline lengths, publisher activity, publication time patterns.  
  - Extracted top keywords and topics using TF‑IDF and LDA.  
  - Identified most covered stocks (MRK, NVDA, MU, etc.) and active publishers (Paul Quintano, Lisa Levin).  
  - Cleaned datetime column and handled missing values.

- **Task 2 (Technical Indicators):** *In progress* – compute SMA, EMA, RSI, MACD from historical price data.

- **Task 3 (Correlation):** *Planned* – align news sentiment (TextBlob/VADER) with daily returns and measure Pearson correlation.

## Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/bitanyadereje/news-sentiment-analysis.git
   cd news-sentiment-analysis

   2,Create virtual environment

python -m venv venv
source venv/bin/activate      # Linux/Mac
.\venv\Scripts\activate       # Windows

3, Install dependencies

pip install -r requirements.txt

4, Run the EDA notebook

jupyter notebook notebooks/01_eda.ipynb
