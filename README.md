# Bankruptcy-Prediction-with-Machine-Learning #			

					ABSTRACT

Predicting corporate bankruptcy is of interest to creditors, investors, borrowing organizations, and governments. This thesis applies various business prediction models based on several machine learning algorithms to a set of 145 financial distress Greek companies between the years 2003 and 2004 and estimates their effectiveness. These models estimate the bankruptcy robability considering a variety of accounting ratios and explanatory variables. The experiments contacted have shown that Decision trees, Neural Networks, and the libraries H2O and AutoSklearn can be effective in this type of problem. Naive Bayes and Logistic Regression on the other hand did not have the same success. Furthermore, the Boosting algorithms such as XG-Boost, CatBoost and Gradient Boosting Machine, did not handle the problem effectively since the dataset is not large enough to justify their use. The experimental results are in line with previously published findings and showed that the suggested models give promising outcomes.

Overview of files

final_boosting_algorithms.ipynb: GBM, XGBOOST,CATBOOST
autosklearn_final.ipynb: the autosklearn model – it works only in Linux
final_h2oAutoMl.ipynb: the h2o model
final_ipynb_algorithms.ipynb: logistic regression, naïve bayes, decision trees
final_NN_implementation.ipynb: Neural networks implementation
