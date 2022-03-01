# 2022 IAQF Student Competition 2022
This repository contains the solution for 2022 IAQF(International Association for Quantitative Finance) Student Competition.

The question is concerning develop a technique to predict or determine the “hidden” state of the market: bear, bull, or static. Prove the validity of your approach by comparing a trading strategy(no leverage) based on the technique against a buy-and-hold strategy for the years 2018 to 2021.

## Code Part
This project focuses on classifying market states into bull, bear and static. We utilize traditional Set of Rules and Hidden Markov Models to create labels, and then build classical and neural networks to train our models. Finally, we build a simple trading strategy to compare our results with buy-and-hold strategy.

- Set of Rules - Label: use traditional methods to create labels;
- Basic HMMs with different number of regimes and ADF test: experiment with different number of regimes and conduct ADF test in the training set.
- HMM_labels: construct HMM1 and HMM2 labels and associated duration
- Data Consolidation: data preprocessing and features engineering;
- Machine Learning Framework: create a class for classical machine learning in time series data;
- Classical Machine Learning - Exploratory: train classical supervised learning models, namely random forest and adaboost;
- Deep Learning - Exploratory: explore different deep learning models with different architecture;
- Deep Learning - Mass Production: find the optimal threshold from the trading result of different deep learning model (GRU and ESN);
- Backtesting: creates a class for backtesting, including the trading strategy. 
