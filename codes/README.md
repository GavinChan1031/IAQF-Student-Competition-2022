# Codes:

## Data Consolidation:
This part mainly focus on how we preprocess our data and generate different features using existing data.

`Data Consolidation.ipynb`: Data Preprocessing and Features Engineering;

## Labeling: 
This part is related to on how we label the market states using unsupervised learning and verify the labeling effects.

`Labeling_Set_of_Rules.ipynb`: Use Set of Rules methods to create labels;
`Labeling_HMM`: Construct HMM1 and HMM2 labels and associated duration;
`Labeling_HMM_Verification`: experiment with different number of regimes and conduct ADF test on the training set.

## Machine Learning and Deep Learning
This part concerns how we use generated labels and supervised learning to differentiate the market states.
`ML_Framework.ipynb`: Create a class for classical machine learning in time series data for later use;
`ML_Exploratory.ipynb`: Train classical Supervised Learning models (Random forest and Adaboost);
`DL_Exploratory.ipynb`: Explore different deep learning models with different architecture;
`DL_Mass_Production.ipynb`: Find the optimal threshold from the trading result of different deep learning model (GRU and ESN);

## Backtesting
Final part of the project: design simple trading strategy and backtest the data on test dataset.
`Backtesting.ipynb`: creates a class for backtesting, including the trading strategy. 

NOTE: ALL codes are written in Google Colab.
