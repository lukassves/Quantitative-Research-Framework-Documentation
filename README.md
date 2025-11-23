Quantitative Research Framework Documentation



Author: Lukas Svešnikovas

November 2025

Classification: Confidential — Internal Use Only



Overview



This document outlines a unified quantitative research framework designed to transform high-frequency market data into consistent, reproducible forecasting outputs. The framework integrates statistical, machine learning, and deep learning models under a single architecture emphasizing stability, transparency, and diagnostic rigor





Core Components



Data Acquisition: Continuous integration of market and order-flow data via Bybit and ccxt APIs.



Preprocessing: Outlier cleaning, normalization, and stationarity validation.



Modeling Layer:



Statistical: FIGARCH-t (1,d,1) long-memory volatility model



Machine Learning: XGBoost regressors



Deep Learning: CNN-LSTM hybrid networks



Backtesting \& Validation: Walk-forward analysis, transaction cost modeling, and multi-test diagnostic framework.



Deployment: Real-time execution with Playwright and Selenium automation.



Methodology Highlight — FIGARCH-t (1,d,1)



Implements fractional integration for volatility persistence and Student-t innovations for heavy-tail behavior.

Validation includes standardized residual tests, volatility-realized correlation, and predictive performance benchmarks



Technical Stack



Python • R • C++ • NumPy • Pandas • PyTorch • TensorFlow • XGBoost • Docker • GitHub Actions • PostgreSQL • Redis



Confidentiality



All material is proprietary and intended solely for internal evaluation. Redistribution is strictly prohibited.



For authorized collaboration or extended technical documentation, please contact:

Lukas Svešnikovas — Quantitative Research \& Systems Automation

