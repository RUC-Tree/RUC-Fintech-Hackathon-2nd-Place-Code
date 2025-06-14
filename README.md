## The First RUC Fintech Hackathon (2024) 2nd Place Code
### 1. Brief Introduction:
The School of Economics at Renmin University of China held a fintech hackathon (also called "quantitative modeling competition") from March to July in 2024. In this competition, contestants need to predict the prices of houses in the test set based on the data of houses and prices in the training set. The final score is determined by weighting the `MAE`, `MSE` and `Median Absolute Error` of the predictions. In this competition, I ranked second among 192 teams and also won the Best Modeling Award.
- Hackathon Link: https://datahub.ruc.edu.cn/org/RUC/workspace/competition/area
(Unfortunately, this website can only be accessed using the account of Renmin University.)

<img src="second.jpg" alt="second" width="500">
### 2. The Methods I used:
- Linear Models: `OLS`, `Lasso`, `Ridge`, `Elastic Net`
- Tree-based Models: `Random Forest`, `XGBoost`, `LightGBM`
- Neural Networks
### 3. The Packages I used:
`scikit-learn`, `xgboost`, `lightgbm`, `openfe`, `autogluon`, `keras`
### 4. Innovations:
- A possible method to solve the data imbalance problem in Machine Learning: **Data Enhancement** (not yet proven by theory)
- A possible improvement based on the **White Test**：Fit the residuals using more function forms, such as logarithms.
- An improvement of the initial neural network: **Wide ANN** (theoretically proven by Cheng, 2016)
- Application of `openfe` (for mining deep features) and `autogluon` (for Automated machine learning).
### 5. References:
> 1. Cheng, Heng-Tze, et al. "Wide & deep learning for recommender systems." Proceedings of the 1st workshop on deep learning for recommender systems. 2016.
> 2. Erickson, Nick, et al. "Autogluon-tabular: Robust and accurate automl for structured data." arXiv preprint arXiv:2003.06505 (2020).
> 3. Zhang, Tianping, et al. "Openfe: Automated feature generation with expert-level performance." International Conference on Machine Learning. PMLR, 2023.
