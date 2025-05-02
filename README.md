# S&P-500-Demographic-Consequences

## Stock Market Effects on Demographics

## **List of Data Sources Used:**

| Link # | Description                                      | URL |
|--------|--------------------------------------------------|-----|
| 1      | Civilian Unemployment Rate Chart (BLS)           | [View](https://www.bls.gov/charts/employment-situation/civilian-unemployment-rate.htm) |
| 2      | S&P 500 (SPY) Dataset from Kaggle                | [View](https://www.kaggle.com/datasets/gkitchen/s-and-p-500-spy) |
| 3      | Jupyter Notebook – Final Check-In                | [View](check_in_final.ipynb) |
| 4      | Project Proposal Document (Slides)               | [View](https://iowa-my.sharepoint.com/:w:/r/personal/aaelwood_uiowa_edu/Documents/Project%20Proposal.docx?d=w980e8e4dde9f4a10bbc79be4309aa89e&csf=1&web=1&e=8wWRQx) |

## Introduction to the Dataset
This data set comprises Microsoft stock prices from April 2015 to April 2021. It provides a historical view of stock performance, including opening price, closing price, highest and lowest price of the day, and trading volume. The dataset does not include stock market activity on weekends or public holidays, leading to occasional missing dates. 
Stock market analysis is broadly classified into two approaches: fundamental analysis and technical analysis. Fundamental analysis evaluates a company’s financial standing and future profitability based on factors like earnings reports and market position. Technical analysis, on the other hand, focuses on identifying patterns in stock prices through statistical and mathematical models. In this study, the emphasis is on technical analysis, leveraging historical data to forecast future stock prices. 
## Method of Analysis 
Various statistical and machine learning techniques are applied to forecast stock price trends in this dataset. The Moving Average method is used to smooth price fluctuations and highlight trends over time. Linear Regression and k-Nearest Neighbors (kNN) are used to find potential correlations between past and future stock prices based on extracted features like dates and price movements.
Auto ARIMA is used to model stock price trends by analyzing past price values and forecast errors. Facebook Prophet helps in capturing seasonality and long-term trends without requiring extensive data preprocessing. Finally, Long Short-Term Memory (LSTM) networks, a deep learning approach, are utilized to recognize sequential dependencies in the stock price data, potentially improving the accuracy of future price predictions.
## Key Observations
Traditional statistical models like Linear Regression and kNN often struggle to capture the highly volatile nature of stock prices. Auto ARIMA performs better by identifying trends but lacks predictive power in unpredictable markets. Facebook Prophet captures seasonality well but falls short in accurately predicting price fluctuations driven by external factors.
