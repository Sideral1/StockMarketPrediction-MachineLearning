# S&P 500 Direction Prediction

### Overview
This project predicts the direction of the S&P 500 index using historical price data and machine learning. It involves collecting market data, engineering features, training a classification model, and evaluating performance with backtesting.

### Steps
- Collect S&P 500 historical data using yfinance.
- Visualize price trends and remove irrelevant columns.
- Engineer additional features to provide market context.
- Train a RandomForestClassifier to predict up/down movements.
- Backtest the model on historical data for realistic performance evaluation.
- Improve features and re-train for better accuracy.

### Tools
- Python
- Jupyter Notebook
- Pandas, NumPy
- yfinance
- Matplotlib
- Scikit-learn

### Results
- The backtested accuracy shows the model’s ability to identify market direction above (or near) random guessing.
- Feature engineering improved context but prediction remains challenging due to market complexity.
- The project demonstrates end-to-end ML workflow for financial data: from collection and preprocessing to evaluation.
