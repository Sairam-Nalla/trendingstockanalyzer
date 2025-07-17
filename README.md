# Trending Stock Sentiment Analyzer

A Python tool that surfaces bullish or bearish signals by combining live market data with Reddit chatter:

- **Trending tickers** pulled from Yahoo Finance API  
- **Reddit scraping** (posts & comments) via PRAW  
- **Sentiment analysis** using NLTK’s VADER to compute per-­stock bullish/bearish scores  
- **Aggregated “Social Sentiment”** score to help identify up‐ or down‐trending equities

## Technologies
Python · Pandas · yfinance · PRAW · NLTK (VADER)

---

### Roadmap
- Twitter sentiment via snscrape  
- Institutional signals (SEC 13F filings)  
- Government‐contract flags (QuiverQuant)  
