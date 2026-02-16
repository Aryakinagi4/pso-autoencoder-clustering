# Dataset Description

## Dataset Used

Nifty 100 Stock Market Dataset  
(Source: Kaggle)

The dataset consists of:

- 1-minute interval stock data
- 13,561 features
- OHLCV attributes:
  - Open
  - High
  - Low
  - Close
  - Volume

---

## Data Characteristics

- High dimensional feature space
- Time-series financial structure
- Sector-based categorization

---

## Preprocessing Steps

1. Data cleaning and removal of non-numeric features
2. Normalization using Min-Max Scaling
3. Dimensionality reduction using Autoencoder
4. Optimal cluster estimation using Elbow Method

---

## Motivation for Dataset Selection

Financial datasets are:

- High-dimensional
- Non-linear
- Volatile
- Suitable for testing clustering robustness

This makes them ideal for evaluating PSO-enhanced clustering.
