# Stock Market Analysis Using Linear Algebra

## What This Project Does
Downloads real stock data for 10 major companies
and analyzes them using pure linear algebra and ML
concepts — no black box libraries, math from scratch.

## Stocks Analyzed
Tech:    AAPL, GOOGL, MSFT, AMZN
Finance: JPM, BAC, GS
Energy:  XOM, CVX, BP

## Math Concepts Applied
| Concept | How Used |
|---|---|
| Vectors | Each stock as a feature vector |
| Matrices | Entire dataset as one matrix |
| Cosine Similarity | Finding similar stocks |
| Eigenvalues + PCA | Reducing 10 stocks to 2D |
| Linear Regression | Predicting daily returns |

## Results
- Identified most similar stock pairs by sector
- Compressed 10 stocks into 2D keeping 85% variance
- Built return predictor using matrix equation only

## Tools
Python · NumPy · Pandas · Matplotlib · yfinance

## How to Run
1. Open stock_market_analysis.ipynb in Google Colab
2. Runtime → Run All
3. All charts generate automatically
