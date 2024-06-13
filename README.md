
# Stock Market Analysis for Trade&Ahead

## Context
The stock market presents lucrative opportunities for investment, offering avenues for wealth creation and retirement savings. However, navigating the market and identifying profitable investment options can be challenging. Trade&Ahead, a financial consultancy firm, aims to provide personalized investment strategies to its clients. In this project, we analyze stock market data to group stocks based on their attributes and provide insights to aid in investment decision-making.

## Objective
The objective of this project is to analyze stock market data and group stocks based on various financial indicators. By employing clustering techniques, we aim to identify stocks with similar characteristics and minimize investment risk for Trade&Ahead's clients. Additionally, we provide insights into each stock cluster to aid in portfolio diversification and investment strategy development.

## Data
The dataset provided includes stock price data and financial indicators for companies listed on the New York Stock Exchange. The data dictionary contains details about each attribute, including ticker symbol, company name, sector, price, volatility, financial ratios, and earnings metrics.

## Methodology
### K-means Clustering:
- Identified four clusters of stocks based on price, volatility, price change, cash ratio, net income, P/E ratio, and outstanding shares.
- Provided insights into each cluster's characteristics, including average price change, cash ratio, net income, P/E ratio, and outstanding shares.

### Hierarchical Clustering:
- Grouped stocks into four clusters based on previous quarter performance and sector.
- Provided insights into each cluster's performance, sector composition, price, volatility, and earnings per share.

## Results
### K-means Clustering:
- Cluster 0: Moderate price, low volatility, moderate price change, low cash ratio, low net income, low P/E ratio, and low outstanding shares.
- Cluster 1: Low price, low volatility, moderate price change, low cash ratio, high net income, low P/E ratio, and high outstanding shares.
- Cluster 2: Low price, high volatility, significant price drop, low cash ratio, negative net income, high P/E ratio, and low outstanding shares.
- Cluster 3: High price, moderate volatility, significant price rise, high cash ratio, low net income, moderate P/E ratio, and moderate outstanding shares.

### Hierarchical Clustering:
- Cluster 0: Poor performing stocks, mainly from the Energy sector.
- Cluster 1: High-priced stocks with significant growth potential, primarily from Healthcare and IT sectors.
- Cluster 2: Low-priced stocks with good performance and high trading volumes.
- Cluster 3: Moderately priced stocks with good performance and moderate trading volumes.

## Recommendations
- Utilize additional financial indicators for better stock price predictions and company valuation assessments.
- Conduct cluster analysis for each economic sector to provide tailored investment recommendations.
- Continuously monitor market trends and update investment strategies accordingly.
