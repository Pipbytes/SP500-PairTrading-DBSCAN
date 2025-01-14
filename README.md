# SP500-PairTrading-DBSCAN
Apply machine learning with DBSCAN clustering to identify tradable pairs in the S&amp;P 500 for statistical arbitrage. Includes data preprocessing, clustering, cointegration analysis, and backtesting.

## Overview
This project demonstrates the application of machine learning techniques, specifically DBSCAN clustering, for identifying tradable pairs in the S&P 500 for statistical arbitrage strategies. By leveraging unsupervised learning, the project aims to uncover market inefficiencies and construct a quantitative framework for pair trading.

## Features
- **Machine Learning Integration**: Use of DBSCAN (Density-Based Spatial Clustering of Applications with Noise) for identifying clusters of securities with similar price behaviors.
- **Statistical Arbitrage Framework**: Implementation of pair selection and validation based on historical data.
- **Quantitative Analysis**: Analysis of cointegration, spread calculation, and statistical robustness of pairs.
- **S&P 500 Focus**: Leveraging one of the most liquid and widely tracked equity indices for the analysis.

## Methodology
1. **Data Preprocessing**:
    - Extract historical price data of S&P 500 constituents.
    - Normalize and clean data for consistent analysis.

2. **Clustering with DBSCAN**:
    - Apply DBSCAN to cluster stocks based on similarity metrics.
    - Identify potential pair candidates within each cluster.

3. **Pair Selection**:
    - Conduct cointegration tests to validate statistical relationships.
    - Analyze the spread between pairs for mean-reverting properties.

4. **Backtesting** (WIP):
    - Simulate pair trading strategies using historical data.
    - Evaluate performance metrics such as Sharpe ratio, drawdowns, and profitability.
