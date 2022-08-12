# Project-2

Company Bankruptcy Prediction (Study Case : Taiwan)

Project Purpose
The purpose of this project is to create a model that can be used to predict whether a company will go bankrupt or not based on their finantial ratio.

Description
Source of Data : https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction

The model used in this project is Random Forest Classifier with Hyperparameter Tuning using GridSearchCV.
The Hyperparameter that is tuned are the sample leaf, sample split, max depth and n estimators.
For balancing the data set I use SMOTE.

After tuning the Hyperparameter we applied PCA process to increase the performance of the model.

Based on the classification report, the model shows 67% of accuracy and 34% of recall performance.

Finding:
![This is an image](https://github.com/anggafebrianno/Project-2/blob/main/Picture%20for%20Readme.png)

1. ROA after tax shows that the return on Assets for the company that going to bankrupt has lower number. It means that the company can not utilize their assets as good as the company which is survive.
2. The company that is predicted to go bankruptcy has a good performance to collect cash but can not handle their expense.
3. The company that is going to bankrupt has a high number of total debt compare to the total net worth.

Recommendations:
For further research it is good to know type of company industry and how the economy condition at that time.
Beside that we have to handle the imbalance data on the data set.
