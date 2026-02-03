# Stock-Price-Market-Performance-Analysis

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-brightgreen)
![EDA](https://img.shields.io/badge/EDA-Completed-orange)

## Objective
-Analyze historical stock market data to understand price movements, identify key factors influencing stock prices, and build a machine learning model to predict closing prices.

## Dataset
-Historical stock market data (OHLCV)

-Features include Date, Open, High, Low, Close, Volume, and derived technical indicators

## Approach
-Cleaned and preprocessed raw stock price data

-Handled missing values and date-time formatting

-Performed exploratory data analysis (EDA) to study trends, volatility, and correlations

-Engineered features such as moving averages and returns

-Trained a Random Forest Regression model (80–20 train–test split)

-Evaluated model performance and analyzed feature importance

## Results
-R² Score: ~0.88–0.92 (depends on stock & time range)

-Mean Squared Error (MSE): Dataset-dependent

-Volume, recent price trends, and moving averages were among the most influential features

## Key Insights
-Stock prices are strongly influenced by recent historical trends

-Volume spikes often align with sharp price movements

-Short-term technical indicators contribute more to predictions than long-term averages

-Model performs better on stable stocks than highly volatile ones

## Tools Used
-Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, SQL, Power BI

## How to Run
-Download the stock market dataset

-Open stocks.ipynb in Jupyter Notebook

-Run the cells sequentially to reproduce analysis and results
