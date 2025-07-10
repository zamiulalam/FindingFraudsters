# FindingFraudsters
Repo to analyze finding fraudsters dataset

Inspired by https://arxiv.org/pdf/2208.14417 and their git repo: https://github.com/amazon-science/fraud-dataset-benchmark which provides methods to prepare the datasets and reproduce results

Useful writeup of previous analysis of dataset: https://developer.nvidia.com/blog/leveraging-machine-learning-to-detect-fraud-tips-to-developing-a-winning-kaggle-solution/

# Contents
Two notebooks `EDA.ipynb` and `FE_Training.ipynb` are included in the folder named `Notebooks`. Data exploratory analysis is done in `EDA.ipynb`, while feature engineering and training are done in `FE_Training.ipynb`.

A brief description of the project:

• Developed a fraud detection model using boosted decision trees (BDT) on the IEEE-CIS Fraud Detection dataset.
• Dealt with a highly imbalanced dataset of 590,540 transactions, of which only 3.5% were fraudulent.
• Achieved 93% ROC AUC score using ensemble model of XGBoost, LightGBM and CATBoost
