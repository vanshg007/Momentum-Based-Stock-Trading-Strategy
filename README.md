# Momentum-Based-Stock-Trading-Strategy

---

This project implements a robust momentum scoring and signal generation system for Nifty 50 stocks using technical indicators like RSI, MACD, and Bollinger Bands. For each stock, it computes adaptive weights based on the extremity of indicator values and adjusts the momentum score by recent price volatility. The scores are calculated at 5-day intervals using the most recent 20-day window, allowing for dynamic tracking of bullish and bearish movements over time. The top and bottom performers are ranked using standardized scores.

In addition to scoring, the system includes a rule-based signal generation mechanism using EMA crossovers combined with RSI confirmation. The notebook visualizes key indicators and highlights the top bullish stock at the latest period using Bollinger Bands. This framework serves as a flexible base for technical screening, momentum-based trading strategies, or feature generation for machine learning pipelines.
---
