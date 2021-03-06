# Machine Learning for Algorithmic Trading using Python

The book provides a comprehensive introduction to how ML can add value to the design and execution of algorithmic trading strategies. It is organized in four parts that cover different aspects of the data sourcing and strategy development process, as well as different solutions to various ML challenges.

## Part 1: How to Design a Trading Strategy

The first part provides a framework for the development of trading strategies driven by machine learning (ML). It focuses on the data that power the ML algorithms and strategies discussed in this book, outlines how ML can be used to derive trading signals, and how to deploy and evaluate strategies as part of a portfolio.

### 01 Machine Learning for Trading

This [chapter](01_machine_learning_for_trading) summarizes how and why ML became central to investment, describes the trading process and outlines how ML can add value. It covers:

- How to read this book
- The rise of ML in the Investment Industry 
- Design and execution of a trading strategy
- ML and algorithmic trading strategies: use cases

### 02: Market & Fundamental Data

This [chapter](02_market_and_fundamental_data) introduces market and fundamental data sources and the environment in which they are created. Familiarity with various types of orders and the trading infrastructure matters because they affect backtest simulations of a trading strategy. We also illustrate how to use Python to access and work with trading and financial statement data. 

In particular, this chapter will cover the following topics:
- How market microstructure shapes market data
- How to reconstruct the order book from tick data using Nasdaq ITCH 
- How to summarize tick data using various time, volume and dollar bars
- How to work with eXtensible Business Reporting Language (XBRL)-encoded electronic filings
- How to parse and combine market and fundamental data to create a P/E series
- How to access various market and fundamental data sources using Python


### 03: Alternative Data for Finance

This [chapter](02_market_and_fundamental_data) outlines categories and describes criteria to assess the exploding number of alternative data sources and providers. It also demonstrates how to create alternative data sets by scraping websites, for example to collect earnings call transcripts for use with natural language processing (NLP) and sentiment analysis algorithms in the second part of the book. More specifically, this chapter covers:

- How the alternative data revolution has unleashed new sources of information
- How individuals, business processes, and sensors generate alternative data
- How to evaluate the proliferating supply of alternative data used for algorithmic trading
- How to work with alternative data in Python, such as by scraping the internet
- Important categories and providers of alternative data

### 04: Research & Evaluation of Alpha Factors

[Chapter 4](04_alpha_factor_research) provides a framework for understanding how factors work and how to measure their performance, for example using the information coefficient (IC). It demonstrates how to engineer alpha factors from data using Python libraries offline and on the Quantopian platform. It also introduces the `zipline` library to backtest factors and the `alphalens` library to evaluate their predictive power.

We use a simple mean-reversal factor to introduce the algorithmic trading simulator `zipline` that is written in Python and facilitates the testing of alpha factors for a given investment universe. We will also use `zipline` when we backtest trading strategies in a portfolio context in the next chapter. Next, we will discuss key metrics to evaluate the predictive performance of alpha factors, including the information coefficient and the information ratio, which leads to the fundamental law of active management. In particular, this chapter will address the following topics:

- How to characterize, justify and measure key types of alpha factors
- How to create alpha factors using financial feature engineering
- How to use zipline offline to test individual alpha factors
- How to use zipline on Quantopian to combine alpha factors and identify more sophisticated signals
- How the information coefficient (IC) measures an alpha factor's predictive performance
- How to use alphalens to evaluate predictive performance and turnover
 

### 05: Strategy Evaluation & Portfolio Management

In this [chapter](05_strategy_evaluation), we cover 
- how to build, test and evaluate trading strategies using historical data with `zipline` offline and on the Quantopian platform. 
- how to compute portfolio performance and risk metrics using the `pyfolio` library. 
- how to manage methodological challenges of strategy backtests 
- how to optimize a strategy from a portfolio risk perspective.


## Part 2: Machine Learning Fundamentals

### 06: The Machine Learning Process
### 07: Linear Models for Regression & Classification
### 08: Linear Time Series Models
### 09: Bayesian Machine Learning
### 10: Decision Trees & Random Forests
### 11: Gradient Boosting Machines
### 12: Unsupervised Learning

## Part 3: Natural Language Processing

### 13:	Working with Text Data
### 14:	Topic Modeling
### 15:	Word Vector Embeddings

## Part 4: Deep & Reinforcement Learning

### 16:	Deep Learning
### 17:	Recurrent Neural Networks
### 18:	Convolutional Neural Networks
### 19:	Autoencoders & Generative Adversarial Networks
### 20:	Reinforcement Learning

## Part 5: Conclusion

### 21:	What's Next?
