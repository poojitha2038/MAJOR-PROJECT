# MAJOR-PROJECT


# AA-NBEATS-GAN: Attention-Augmented N-BEATS-GAN for Financial Time Series Forecasting

## Overview

This project presents **AA-NBEATS-GAN**, a deep learning framework for multi-series financial time-series forecasting. The model combines the forecasting capabilities of N-BEATS with the generative learning power of GANs, enhanced by Cross-Series Attention, Sentiment-Augmented Conditioning, and Adaptive TILDE-Q Weighting.

The objective is to generate accurate future forecasts while capturing uncertainty and preserving the temporal characteristics of financial market data.

---

## Problem Statement

Financial markets are highly volatile and influenced by multiple correlated factors. Traditional forecasting models often struggle to model long-term dependencies and uncertainty.

This project addresses these challenges by developing an advanced deep learning model capable of:

- Forecasting multiple financial indices simultaneously
- Learning cross-market relationships
- Generating probabilistic forecasts
- Improving prediction accuracy through adversarial learning

---

## Objectives

- Develop a hybrid N-BEATS + GAN forecasting model.
- Capture inter-market relationships using Cross-Series Attention.
- Improve sequence learning using Adaptive TILDE-Q loss weighting.
- Produce uncertainty-aware financial forecasts.
- Evaluate the model using MAE, MSE, and CRPS.

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- SciPy
- Plotly
- Matplotlib
- Jupyter Notebook
- CUDA GPU Support

---

## Project Workflow

### 1. Data Preparation

The financial time-series data is preprocessed by:

- Cleaning missing values
- Normalizing data
- Creating rolling windows
- Feature engineering

Features include:

- Returns
- Rolling Volatility
- Momentum
- RSI Indicator

---

### 2. Model Architecture

The model consists of:

- N-BEATS Generator
- Cross-Series Attention (CSA)
- Sentiment-Augmented Conditioning (SAC)
- Adaptive TILDE-Q Weighting (ATW)
- CNN-based WGAN-GP Discriminator

---

### 3. Training

Training is performed in two phases:

- Supervised Pretraining
- Progressive GAN Training

Additional techniques include:

- Gradient Clipping
- Spectral Normalization
- EMA (Exponential Moving Average)
- Cosine Annealing Scheduler

---

### 4. Evaluation

Performance metrics include:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Continuous Ranked Probability Score (CRPS)
- Country-wise Forecast Error
- Volatility Comparison

---

## Results

The prototype successfully demonstrates:

- Multi-series forecasting
- Probabilistic prediction
- Cross-market dependency learning
- Stable adversarial training

Performance achieved:

- MAE: **0.1905**
- MSE: **0.0589**
- CRPS: **0.1904**

---

## Future Improvements

- Integrate real MSCI financial data
- Add macroeconomic indicators
- Incorporate news sentiment analysis
- Deploy as a real-time forecasting web application

---

## Repository Structure

```
AA-NBEATS-GAN/
│
├── notebooks/
├── models/
├── dataset/
├── outputs/
├── images/
├── requirements.txt
├── README.md
└── AA_NBEATS_GAN.ipynb
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/poojitha2038/MAJOR-PROJECT.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## Applications

- Financial Forecasting
- Stock Market Analysis
- Risk Management
- Portfolio Analytics
- Investment Decision Support

---

## Author

**Vithanala Poojitha**

GitHub:
https://github.com/poojitha2038

---

## License

This project is developed for academic and research purposes.
