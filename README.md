# 2022 IAQF Student Competition 2022
This repository contains the solution for 2022 IAQF(International Association for Quantitative Finance) Student Competition.

The question is concerning develop a technique to predict or determine the “hidden” state of the market: bear, bull, or static. Prove the validity of your approach by comparing a trading strategy(no leverage) based on the technique against a buy-and-hold strategy for the years 2018 to 2021.

## Coding Part
This project focuses on classifying market states into bull, bear and static. We utilize traditional Set of Rules and Hidden Markov Models to create labels, and then build classical and neural networks to train our models. Finally, we build a simple trading strategy to compare our results with buy-and-hold strategy.

- **Set_of_Rules_Label.ipynb**: Use Set of Rules methods to create labels;
- **Basic HMMs with different number of regimes and ADF test.ipynb**: experiment with different number of regimes and conduct ADF test on the training set.
- **HMM_labels.ipynb**: construct HMM1 and HMM2 labels and associated duration
- **Data Consolidation.ipynb**: Data Preprocessing and Features Engineering;
- **Machine Learning Framework.ipynb**: Create a class for classical machine learning in time series data for later use;
- **Classical Machine Learning - Exploratory.ipynb**: Train classical Supervised Learning models (Random forest and Adaboost);
- **Deep Learning - Exploratory.ipynb**: Explore different deep learning models with different architecture;
- **Deep Learning - Mass Production.ipynb**: Find the optimal threshold from the trading result of different deep learning model (GRU and ESN);
- **Backtesting.ipynb**: creates a class for backtesting, including the trading strategy. 

NOTE: ALL codes are written in Google Colab.

## Final Solution
Here we also upload a final solusion(paper) named IAQF_2022_Solution.pdf.

## Team
**Team name**: Five+1 Guys

**Team member**: Vanessa Liang, Guojun Chen, Simon Chau, Jonathan Sun, Wenyi Huang, Jiarui Li


